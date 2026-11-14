# Guion de la Lección 5: Introducción a CSS y Selectores Básicos

## Detalles de la Lección

- **Duración aproximada:** 26 minutos
- **Público objetivo:** Estudiantes de secundaria (12 a 17 años)
- **Herramientas:** CodePen (100% en línea)
- **Lenguajes:** HTML y CSS

---

## Estructura del Video

### 1. ¿Qué es CSS y para qué sirve? (00:00 – 02:47)

- **[En pantalla]** Mostrar dos páginas web: una con un diseño organizado y atractivo, como Interbank, y otra con una presentación visual menos organizada.

- **[Texto de apoyo visual]**
    - HTML: estructura y contenido.
    - CSS: apariencia y diseño.
    - Colores, tamaños, fuentes y distribución.

- **[Narración (Voz en off)]**

  Para comenzar esta lección, vamos a conocer CSS, un lenguaje que nos ayudará a complementar lo que ya aprendimos de HTML.

  Primero, observemos dos páginas web. La primera tiene una presentación visual ordenada: sus textos están bien ubicados, los colores combinan y los tamaños de las letras permiten distinguir cada sección.

  En cambio, la segunda página tiene una apariencia menos organizada, con imágenes y elementos que no siguen una distribución visual clara.

  ¿Cuál es la diferencia? Principalmente, el estilo.

  Hasta ahora hemos utilizado HTML para definir qué contenido tiene una página. Con CSS aprenderemos a decidir cómo se ve ese contenido: sus colores, tipos de letra, tamaños y posiciones.

  Por ejemplo, con HTML podemos escribir un texto que diga «Contacto». Con CSS podemos cambiar su fuente, su tamaño, su color y la manera en que se presenta en la página.

  CSS significa *Cascading Style Sheets*, que en español se traduce como hojas de estilo en cascada. No necesitamos memorizar el nombre completo por ahora; lo importante es comprender lo que podemos lograr con este lenguaje.

### 2. ¿Cómo se conecta CSS con HTML? (02:47 – 04:45)

- **[En pantalla]** Mostrar los paneles HTML y CSS de CodePen.

- **[Texto de apoyo visual]**
    - HTML: define el contenido.
    - CSS: define la apariencia.
    - Los estilos se aplican al contenido HTML.

- **[Narración (Voz en off)]**

  Antes de escribir CSS, debemos entender cómo se conecta con HTML.

  En un proyecto normal, el código CSS suele guardarse en un archivo separado, que puede llamarse `style.css` o `styles.css`. Desde el archivo HTML indicamos que queremos utilizar esa hoja de estilos mediante una etiqueta llamada `link`.

  En esta ocasión trabajaremos directamente con los paneles de CodePen. Lo que escribamos en el panel CSS se aplicará automáticamente al HTML y podremos observar el resultado en la vista previa.

  La idea es la misma: HTML indica qué elementos existen y CSS determina cómo se muestran.

  Mantener ambos lenguajes separados tiene una ventaja importante. Si queremos cambiar el color de todos los títulos, podemos hacerlo desde CSS sin tener que modificar cada elemento HTML.

### 3. ¿Cómo se escribe una regla CSS? (04:45 – 05:24)

- **[En pantalla]** Mostrar la estructura básica de una regla CSS.

- **[Texto de apoyo visual]**

  Una regla CSS tiene tres partes:

    1. Selector: indica a qué elemento se aplica el estilo.
    2. Propiedad: indica qué característica queremos modificar.
    3. Valor: indica cómo queremos modificarla.

- **[Narración (Voz en off)]**

  En CSS, los estilos se escriben mediante reglas. Cada regla tiene tres partes principales.

  La primera es el selector, que indica a qué elemento queremos aplicar un estilo.

  La segunda es la propiedad, que señala qué característica queremos cambiar.

  Finalmente, tenemos el valor, que indica cómo queremos que sea esa característica.

  Por ejemplo, podemos seleccionar un párrafo, cambiar el tamaño de su letra y establecerlo en 18 píxeles.

### 4. Preparando la estructura HTML y conectando CSS (05:24 – 10:24)

- **[En pantalla]** Escribir la estructura básica de HTML en el panel correspondiente.

- **[Texto de apoyo visual]**
    - `<!DOCTYPE html>`: indica que utilizamos HTML5.
    - `<html lang="en">`: establece el idioma del documento.
    - `<head>`: contiene información del documento.
    - `<meta charset="UTF-8">`: permite reconocer caracteres especiales.
    - `<link>`: conecta la hoja de estilos.
    - `<title>`: establece el título de la página.
    - `<body>`: contiene el contenido visible.

- **[Narración (Voz en off)]**

  Ahora vamos a preparar nuestra estructura HTML para comenzar a trabajar.

  Primero escribimos `<!DOCTYPE html>` y abrimos la etiqueta `html`. En este ejemplo, el atributo `lang` está establecido en inglés.

  Después abrimos `head`, que es la sección donde colocamos información sobre nuestro documento.

  Dentro de esta sección agregamos la etiqueta `meta` con la codificación UTF-8. Esto permite que caracteres como las tildes y otros símbolos se muestren correctamente.

  Ahora vamos a utilizar la etiqueta `link`, que nos permitirá conectar nuestro archivo HTML con la hoja de estilos.

  Para hacerlo, escribimos el atributo `rel` con el valor `stylesheet`. Esto indica que el archivo relacionado es una hoja de estilos.

  Luego utilizamos `href` para indicar la ubicación del archivo CSS. En este caso, escribimos `./style.css`, porque el archivo se encuentra en la misma carpeta que nuestro HTML.

  Es importante recordar que la ruta debe coincidir con la ubicación y el nombre real del archivo. Si estuviera dentro de otra carpeta, tendríamos que indicar esa ubicación.

  Finalmente, agregamos la etiqueta `title` para colocar el nombre de nuestra página y cerramos la sección `head`.

  Ahora abrimos `body`, que es donde escribiremos el contenido que aparecerá en nuestra página.

### 5. Nuestro primer estilo con CSS (10:24 – 13:31)

- **[En pantalla]** Escribir un párrafo en HTML y modificar su apariencia desde CSS.

- **[Texto de apoyo visual]**
    - Selector: `p`
    - Propiedad: `font-size`
    - Valor: `18px`
    - `px`: píxeles.
    - Las declaraciones CSS terminan con punto y coma.

- **[Narración (Voz en off)]**

  Para comenzar, vamos a escribir un párrafo sencillo en nuestro HTML.

  Utilizaremos la etiqueta `p` y colocaremos el texto: «Este párrafo es normal».

  Como pueden observar, el texto aparece con el estilo predeterminado del navegador.

  Ahora vamos al panel CSS y escribimos `p`. Esto significa que vamos a seleccionar todos los elementos de tipo párrafo.

  Abrimos las llaves y escribimos la propiedad `font-size`, que significa tamaño de fuente.

  Como valor colocamos `18px` y terminamos la declaración con punto y coma.

  Automáticamente podemos observar que el tamaño del párrafo ha cambiado.

  ¿Qué pasa si colocamos un valor mucho más pequeño? La letra también se verá más pequeña.

  Recuerden que `px` significa píxeles, una unidad que podemos utilizar para definir tamaños en CSS.

### 6. Primer tipo de selector: por etiqueta (13:31 – 15:28)

- **[En pantalla]** Modificar los estilos de `h1` y `body` desde CSS.

- **[Texto de apoyo visual]**
    - `p`: selecciona todos los párrafos.
    - `h1`: selecciona todos los títulos principales.
    - `body`: selecciona el cuerpo de la página.
    - `background-color`: modifica el color de fondo.

- **[Narración (Voz en off)]**

  Ahora vamos a conocer los tres tipos principales de selectores.

  El primero es el selector por etiqueta. Es el que acabamos de utilizar con `p`.

  Podemos hacer lo mismo con otras etiquetas HTML. Por ejemplo, si escribimos `h1` en CSS, podremos modificar todos los títulos principales de nuestra página.

  También podemos seleccionar `body`, que representa el cuerpo del documento.

  Vamos a probarlo escribiendo `background-color`, que permite cambiar el color de fondo.

  Como valor utilizaremos `lightyellow`. De esta manera, el fondo de toda nuestra página cambiará a un amarillo claro.

  Como pueden observar, CSS nos permite personalizar incluso elementos que contienen gran parte del contenido de nuestra página.

### 7. Segundo tipo de selector: por clase (15:28 – 18:03)

- **[En pantalla]** Agregar el atributo `class="destacado"` a un párrafo y seleccionarlo desde CSS.

- **[Texto de apoyo visual]**
    - HTML: `class="destacado"`
    - CSS: `.destacado`
    - Una clase puede utilizarse en varios elementos.

- **[Narración (Voz en off)]**

  El segundo tipo de selector es el selector por clase.

  Una clase es un nombre que nosotros inventamos para identificar un grupo de elementos que queremos personalizar.

  Para crearla, vamos al HTML y agregamos el atributo `class` a nuestro párrafo.

  En este ejemplo, escribiremos `class="destacado"` y cambiaremos el contenido para que diga: «Este párrafo es importante».

  Ahora vamos al panel CSS. Para seleccionar una clase, debemos escribir un punto seguido del nombre que le asignamos.

  Entonces escribimos `.destacado` y abrimos las llaves.

  De esta manera, podemos aplicar estilos únicamente a los elementos que tengan esa clase.

### 8. Personalizando una clase: color, negrita y fuente (18:03 – 20:14)

- **[En pantalla]** Agregar diferentes propiedades CSS a `.destacado`.

- **[Texto de apoyo visual]**
    - `color`: cambia el color del texto.
    - `font-weight`: modifica el grosor de la letra.
    - `font-family`: cambia el tipo de fuente.

- **[Narración (Voz en off)]**

  Ahora vamos a personalizar nuestro párrafo destacado.

  Primero utilizaremos la propiedad `color` y colocaremos el valor `crimson`, para que el texto tenga un tono rojizo.

  Después agregaremos `font-weight`, que nos permite modificar el grosor de las letras. En este caso, utilizaremos `bold` para mostrar el texto en negrita.

  También podemos cambiar el tipo de letra mediante la propiedad `font-family`.

  Por ejemplo, podemos utilizar Arial. Existen muchas fuentes disponibles y no es necesario memorizar todos sus nombres. Cuando desarrollamos un proyecto, podemos investigar y elegir la fuente que mejor se adapte a nuestro diseño.

  Algunas fuentes ya están disponibles en el sistema, mientras que otras pueden necesitar una configuración adicional.

### 9. Tercer tipo de selector: por ID (20:14 – 23:12)

- **[En pantalla]** Agregar un título `h1` con el atributo `id="titulo"` y seleccionarlo desde CSS.

- **[Texto de apoyo visual]**
    - HTML: `id="titulo"`
    - CSS: `#titulo`
    - Un ID identifica un elemento específico.
    - Se utiliza `#` para seleccionarlo.

- **[Narración (Voz en off)]**

  Finalmente, tenemos el tercer tipo de selector: el selector por ID.

  Un ID funciona como un identificador para un elemento específico. A diferencia de una clase, que puede utilizarse en varios elementos, debemos procurar que cada ID sea único dentro de una página.

  Vamos a agregar un título en nuestro HTML utilizando `h1`.

  Dentro de la etiqueta escribimos `id="titulo"` y como contenido colocamos «Mi blog».

  Ahora vamos al panel CSS. Para seleccionar un ID, utilizamos el símbolo numeral o almohadilla, seguido del nombre que le asignamos.

  En este caso, escribimos `#titulo` y podemos agregarle las propiedades que queramos.

  Por ejemplo, podemos utilizar `text-decoration: underline` para subrayar nuestro título.

  Así podemos modificar un elemento específico sin afectar necesariamente a los demás.

### 10. Diferencias entre los tres selectores y práctica (23:12 – 25:28)

- **[En pantalla]** Mostrar el resultado completo de la página y repasar los selectores utilizados.

- **[Texto de apoyo visual]**

  | Selector | Sintaxis | ¿Para qué sirve? |
    |---|---|---|
  | Etiqueta | `p` | Selecciona todos los elementos de esa etiqueta. |
  | Clase | `.destacado` | Selecciona los elementos que comparten una clase. |
  | ID | `#titulo` | Selecciona un elemento identificado con ese ID. |

- **[Narración (Voz en off)]**

  Como pueden observar, cada párrafo puede tener estilos diferentes sin afectar a los demás.

  Sin embargo, si modificamos una propiedad directamente en `body`, como `font-family`, el cambio puede afectar al contenido que se encuentra dentro de él.

  También podemos establecer un tamaño de fuente general para los párrafos y otros elementos mediante sus selectores correspondientes.

  Vamos a recordar lo aprendido:

  El selector por etiqueta sirve para modificar todos los elementos de un mismo tipo.

  El selector por clase sirve para modificar un grupo de elementos que nosotros elegimos.

  Y el selector por ID sirve para identificar y modificar un elemento específico.

  Ahora les toca practicar. Pueden crear sus propias clases, utilizar diferentes títulos como `h1`, `h2` y `h3`, y probar distintos tipos de fuentes desde `style.css`.

### 11. Cierre de la lección (25:28 – 25:50)

- **[En pantalla]** Mostrar el resultado final y el código HTML y CSS.

- **[Texto de apoyo visual]**
    - Ya conoces las reglas CSS.
    - Ya puedes utilizar selectores por etiqueta, clase e ID.
    - Próxima lección: colores, fuentes, bordes y tarjetas.

- **[Narración (Voz en off)]**

  ¡Excelente! Ya escribieron sus primeras reglas CSS y aprendieron a seleccionar los elementos que desean modificar.

  En el próximo video aprenderemos a trabajar con colores, tipos de letra y bordes. Además, utilizaremos lo aprendido para crear una tarjeta de presentación con mucho más estilo.

  ¡Hasta pronto!

---

## Código de Referencia

### Panel HTML

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="./style.css">
    <title>Pen</title>
  </head>
  <body>

    <h1 id="titulo">Mi blog</h1>
    <p class="destacado">Este párrafo es importante.</p>
    <p>Este párrafo es normal.</p>

  </body>
</html>
```

### Panel CSS

```css
body {
  background-color: lightyellow;
  font-family: Arial, sans-serif;
}

h1 {
  color: darkblue;
}

p {
  font-size: 18px;
}

.destacado {
  color: crimson;
  font-weight: bold;
}

#titulo {
  text-decoration: underline;
}
```

### Forma de una regla CSS

```css
selector {
  propiedad: valor;
}
```

---

## Actividad de Práctica — Personaliza tu Blog

**Objetivo:** aplicar los tres tipos de selectores CSS para personalizar una página HTML.

**Instrucciones:**

1. Crea un título principal utilizando `h1` con el texto «Mi blog».
2. Agrega dos párrafos con información sobre tus intereses.
3. Asigna una clase llamada `destacado` a uno de los párrafos.
4. Asigna un ID llamado `titulo` al título principal.
5. En CSS, cambia el color del título utilizando un selector por etiqueta o por ID.
6. Cambia el color y el grosor del párrafo destacado utilizando su clase.
7. Modifica el color de fondo de toda la página.
8. Prueba una fuente diferente utilizando `font-family`.

**Resultado esperado:** una pequeña página personal con un título, dos párrafos y diferentes estilos aplicados mediante selectores CSS.

**Reto adicional:** crea una segunda clase llamada `subtitulo` y utilízala para personalizar un subtítulo `h2` con un color y tamaño diferentes.