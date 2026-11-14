# Guion de la Lección 6: Colores, Fuentes, Bordes y Tarjetas de Presentación con CSS

## Detalles de la Lección

- **Duración aproximada:** 20 minutos
- **Público objetivo:** Estudiantes de secundaria (12 a 17 años)
- **Herramientas:** CodePen (100% en línea)
- **Lenguajes:** HTML y CSS

---

## Estructura del Video

### 1. Introducción y objetivo de la lección (00:00 – 02:01)

- **[En pantalla]** Mostrar el proyecto en CodePen y repasar brevemente la estructura HTML y CSS utilizada anteriormente.

- **[Texto de apoyo visual]**
    - Lección 6: Personalizando una tarjeta de presentación.
    - Aprenderemos:
        - Colores.
        - Fuentes.
        - Bordes.
        - Espaciado interior (padding).

- **[Narración (Voz en off)]**

  ¡Hola! En esta ocasión vamos a continuar con nuestro curso de introducción a CSS.

  Hoy vamos a crear una tarjeta de presentación, tal como lo prometimos en la lección anterior. Buscaremos que tenga un diseño más atractivo y personalizado.

  Para conseguirlo, necesitamos dominar cuatro aspectos importantes: los colores, los tipos de letra, los bordes y el espacio interior de una caja.

  Primero, repasemos rápidamente nuestro código. Tenemos una estructura HTML y un archivo CSS donde escribiremos los estilos.

  Dentro del `body` utilizaremos un `div` que contendrá un título `h2` y un párrafo `p`. Estos serán los elementos que iremos personalizando durante la lección.

### 2. Trabajando con colores en CSS (02:01 – 05:59)

- **[En pantalla]** Seleccionar el `body` en CSS y probar diferentes colores de fondo.

- **[Texto de apoyo visual]**
    - `color`: cambia el color del texto.
    - `background-color`: cambia el color de fondo.
    - Nombres de colores: `red`, `blue`, `green`, `tomato`.
    - Código hexadecimal: `#EEF3F8`.

- **[Narración (Voz en off)]**

  Comencemos con los colores.

  En CSS tenemos dos propiedades principales para trabajar con ellos. La primera es `color`, que modifica el color del texto. La segunda es `background-color`, que permite cambiar el color del fondo.

  Podemos indicar un color escribiendo su nombre en inglés, por ejemplo, `red`, `blue`, `green` o `tomato`. También existen nombres más específicos, como `lightgreen` o `darkgreen`.

  Otra forma de elegir colores es mediante códigos hexadecimales. Estos comienzan con el símbolo numeral y normalmente contienen seis caracteres.

  Vamos a probarlo. En nuestro `body` escribimos `background-color` y colocamos el código `#EEF3F8`.

  Como pueden observar, el fondo cambia a un tono celeste muy suave.

  Aunque estos códigos puedan parecer difíciles de recordar, no necesitamos memorizarlos. Podemos utilizar herramientas disponibles en internet, como selectores de colores, para elegir el tono que queremos y copiar su código hexadecimal.

  De esta manera podemos encontrar prácticamente cualquier color que necesitemos para nuestro diseño.

### 3. Introducción a las fuentes y tipos de letra (05:59 – 08:09)

- **[En pantalla]** Modificar la propiedad `font-family` del `body` y mostrar el cambio en la vista previa.

- **[Texto de apoyo visual]**
    - `font-family`: cambia el tipo de letra.
    - `Verdana, sans-serif`
    - `serif`: fuentes con pequeños adornos.
    - `sans-serif`: fuentes sin esos adornos.

- **[Narración (Voz en off)]**

  Ahora vamos a trabajar con las fuentes.

  Las fuentes son los diferentes tipos de letra que podemos utilizar en nuestros textos. Seguramente ya las han utilizado en programas como Word, Excel o Google Docs.

  En CSS utilizamos la propiedad `font-family` para elegir una fuente.

  Por ejemplo, podemos escribir `Verdana, sans-serif`.

  Como pueden observar, el tipo de letra cambia para todo el contenido que se encuentra dentro del `body`.

  Pero ¿por qué estamos colocando dos valores?

  La primera fuente es la que queremos utilizar. Sin embargo, no todas las computadoras tienen instaladas las mismas fuentes.

  Por eso agregamos una segunda opción como respaldo. Si el navegador no encuentra Verdana, utilizará una fuente de tipo `sans-serif`.

  Las fuentes `serif` tienen pequeños adornos en los extremos de las letras, mientras que las `sans-serif` no tienen esos adornos y suelen presentar una apariencia más sencilla.

### 4. Aplicando fuentes a elementos dentro de una clase (08:09 – 11:32)

- **[En pantalla]** Crear el selector `.tarjeta h2` y modificar la fuente del título.

- **[Texto de apoyo visual]**
    - `.tarjeta`: selecciona la tarjeta.
    - `.tarjeta h2`: selecciona los títulos `h2` dentro de la tarjeta.
    - `font-family: Georgia, serif;`
    - Utilizar fuentes de respaldo.

- **[Narración (Voz en off)]**

  Ahora vamos a personalizar el título de nuestra tarjeta.

  Supongamos que queremos cambiar únicamente el título y no todos los elementos que están dentro de la tarjeta.

  Si utilizamos solamente `.tarjeta`, los estilos se aplicarían a todo el contenido de ese elemento.

  Pero podemos ser más específicos escribiendo `.tarjeta h2`.

  Esto significa que estamos seleccionando los elementos `h2` que se encuentran dentro de la clase `tarjeta`.

  Ahora vamos a utilizar `font-family` y colocaremos `Georgia, serif`.

  Como pueden observar, únicamente cambia la fuente del título.

  Recuerden nuestra regla: siempre es recomendable colocar una fuente de respaldo al final de la lista, por si la primera no está disponible.

### 5. Creando el diseño de la tarjeta: fondo y texto (11:32 – 14:04)

- **[En pantalla]** Seleccionar `.tarjeta` y agregar las propiedades `background-color` y `color`.

- **[Texto de apoyo visual]**
    - `background-color: white;`
    - `color: #0B1F33;`
    - El fondo y el texto pueden tener colores diferentes.

- **[Narración (Voz en off)]**

  Ahora vamos a darle forma a nuestra tarjeta.

  Como ya sabemos, nuestra tarjeta es una caja creada con un `div` que tiene la clase `tarjeta`.

  Por eso, para modificarla utilizaremos el selector `.tarjeta`.

  Primero vamos a cambiar el fondo de la tarjeta utilizando `background-color`. En este caso, elegiremos el color blanco.

  Después modificaremos el color del texto con la propiedad `color`.

  Vamos a utilizar el código hexadecimal `#0B1F33`, que representa un azul muy oscuro.

  De esta manera, tendremos un fondo blanco y un texto azul oscuro que permitirá distinguir mejor el contenido.

### 6. Agregando bordes y redondeando las esquinas (14:04 – 15:47)

- **[En pantalla]** Agregar la propiedad `border` y después `border-radius` al selector `.tarjeta`.

- **[Texto de apoyo visual]**
    - `border`: grosor, estilo y color.
    - `3px`: grosor del borde.
    - `solid`: estilo de línea continua.
    - `#F89820`: color naranja.
    - `border-radius: 12px`: redondea las esquinas.

- **[Narración (Voz en off)]**

  Ahora vamos a agregar un borde a nuestra tarjeta.

  Para hacerlo utilizamos la propiedad `border`.

  Esta propiedad nos permite indicar tres valores en una sola línea: el grosor, el estilo y el color del borde.

  Primero colocamos `3px`, que indica el grosor.

  Después escribimos `solid`, que establece un borde de línea continua.

  Finalmente, agregamos el código hexadecimal `#F89820`, que representa un tono naranja.

  Como pueden observar, ahora nuestra tarjeta tiene un marco alrededor.

  Pero también podemos modificar sus esquinas utilizando `border-radius`.

  Esta propiedad nos permite redondear las esquinas de un elemento. Vamos a colocar `12px` para conseguir un borde ligeramente redondeado.

### 7. Comprendiendo el espacio interior con padding (15:47 – 17:34)

- **[En pantalla]** Agregar `padding: 16px` a `.tarjeta` y comparar el resultado con y sin esta propiedad.

- **[Texto de apoyo visual]**
    - `padding`: espacio entre el contenido y el borde.
    - Más padding = mayor espacio interior.
    - Menos padding = contenido más cerca del borde.

- **[Narración (Voz en off)]**

  Finalmente, vamos a utilizar una propiedad muy importante: `padding`.

  El padding representa el espacio que existe entre el contenido de una caja y su borde.

  Si no utilizamos esta propiedad, el texto quedará mucho más pegado al marco y nuestra tarjeta no tendrá una apariencia tan ordenada.

  Por eso vamos a colocar `padding: 16px`.

  Como pueden observar, ahora el contenido tiene un poco más de espacio alrededor y la tarjeta se ve más organizada.

  También podemos seguir personalizando el título desde el selector `.tarjeta h2`, cambiando su fuente y su color.

  En este caso utilizaremos Georgia y un tono azul verdoso para diferenciarlo del resto del contenido.

### 8. Cómo seleccionar elementos dentro de otros elementos (17:34 – 18:48)

- **[En pantalla]** Mostrar la estructura HTML y los selectores `.tarjeta` y `.tarjeta h2`.

- **[Texto de apoyo visual]**
    - `.tarjeta`: selecciona el elemento con esa clase.
    - `.tarjeta h2`: selecciona los títulos dentro de esa clase.
    - Podemos combinar selectores para aplicar estilos más específicos.

- **[Narración (Voz en off)]**

  Como hemos visto, podemos seguir personalizando los elementos aunque estén dentro de otros elementos.

  No estamos limitados a modificar únicamente una clase completa.

  Podemos seleccionar primero la clase y después indicar qué etiqueta queremos modificar dentro de ella.

  Por ejemplo, `.tarjeta h2` nos permite modificar solamente el título que se encuentra dentro de nuestra tarjeta.

  Esta forma de seleccionar elementos nos ayuda a organizar mejor nuestros estilos y aplicar cambios específicos sin modificar innecesariamente el resto de la página.

### 9. Actividad: personaliza tu propia tarjeta (18:48 – 19:21)

- **[En pantalla]** Mostrar la tarjeta terminada y dejar visible el código HTML y CSS.

- **[Texto de apoyo visual]**
    - Cambia los colores.
    - Prueba otros códigos hexadecimales.
    - Modifica las fuentes.
    - Redondea las esquinas.
    - Experimenta con el padding.

- **[Narración (Voz en off)]**

  Ahora es tu turno de crear y personalizar tu propia tarjeta.

  Puedes cambiar el contenido del `div`, agregar tu nombre, tus intereses o alguna actividad que te guste.

  Prueba diferentes colores para el fondo y el texto. También puedes modificar el borde, hacer las esquinas más redondeadas o más cuadradas y utilizar otras fuentes.

  Experimenta con diferentes códigos hexadecimales y observa cómo cambia el resultado.

  Recuerda que puedes pausar el video y probar todas las combinaciones que quieras.

### 10. Cierre de la lección (19:21 – 19:40)

- **[En pantalla]** Mostrar el resultado final de la tarjeta de presentación.

- **[Texto de apoyo visual]**
    - Colores.
    - Fuentes.
    - Bordes.
    - Border radius.
    - Padding.
    - Próxima lección: organización y centrado de elementos.

- **[Narración (Voz en off)]**

  ¡Excelente! Ahora nuestra tarjeta ya tiene colores, bordes y esquinas redondeadas.

  El siguiente paso será aprender a ordenar y centrar los elementos de nuestra página para conseguir una presentación todavía mejor.

  Muchas gracias y nos vemos en la próxima lección.

---

## Código de Referencia

### Panel HTML

```html
<div class="tarjeta">
  <h2>Tarjeta de presentación</h2>
  <p>Me gusta programar y dibujar.</p>
</div>
```

### Panel CSS

```css
body {
  background-color: #eef3f8;
  font-family: Verdana, sans-serif;
}

.tarjeta {
  background-color: white;
  color: #0b1f33;
  border: 3px solid #f89820;
  border-radius: 12px;
  padding: 16px;
}

.tarjeta h2 {
  font-family: Georgia, serif;
  color: #1c7293;
}
```

---

## Actividad de Práctica — Mi Tarjeta de Presentación

**Objetivo:** aplicar las propiedades de colores, fuentes, bordes y espaciado interior para crear una tarjeta personalizada.

**Instrucciones:**

1. Crea un `div` con la clase `tarjeta`.
2. Agrega un título `h2` con tu nombre.
3. Agrega un párrafo con una breve descripción de tus intereses.
4. Cambia el color de fondo de toda la página utilizando `background-color`.
5. Elige una fuente para el contenido utilizando `font-family`.
6. Personaliza el fondo y el color del texto de tu tarjeta.
7. Agrega un borde utilizando `border`.
8. Redondea las esquinas con `border-radius`.
9. Utiliza `padding` para separar el contenido del borde.
10. Crea un selector `.tarjeta h2` para personalizar únicamente el título.

**Resultado esperado:** una tarjeta de presentación con información personal, colores personalizados, una fuente diferente, bordes visibles y espacio interior.

**Reto adicional:** crea una segunda tarjeta con otra clase y utiliza colores, fuentes y bordes diferentes para distinguirla de la primera.