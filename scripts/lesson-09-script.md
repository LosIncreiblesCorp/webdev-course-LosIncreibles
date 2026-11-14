# Guion de la Lección 9: Proyecto Final — Página de Perfil Personal (Parte 2: CSS)

## Detalles de la Lección

- **Duración aproximada:** 7 minutos
- **Público objetivo:** Estudiantes de secundaria (12 a 17 años)
- **Herramientas:** Replit (editor en línea)
- **Lenguajes:** HTML y CSS
- **Archivo principal:** `style.css`
- **Proyecto:** Página de perfil personal

---

## Objetivo de la Lección

Aplicar estilos CSS a la página de perfil personal creada en la lección anterior. Aprenderemos a modificar colores, fuentes, márgenes, espacios, bordes y alineaciones para mejorar la presentación de nuestra página.

Al finalizar, tendremos nuestro proyecto completo: una página de perfil personal estructurada con HTML y diseñada con CSS.

---

## Estructura del Video

### 1. Presentación y conexión del archivo CSS (00:06 – 00:50)

**[En pantalla]**
- Mostrar la página de perfil creada en la lección anterior.
- Abrir el archivo `index.html`.
- Señalar la etiqueta `link` que conecta con `style.css`.
- Abrir el archivo `style.css`.
- Crear el selector `body` y cambiar el color de fondo.

**[Texto de apoyo visual]**
- HTML: estructura de la página.
- CSS: apariencia de la página.
- `link`: conecta HTML con CSS.
- `background-color`: cambia el color de fondo.

**[Narración (Voz en off)]**

Bueno, en la lección anterior construimos la estructura de nuestra página de perfil utilizando HTML. Ahora vamos a darle estilo con CSS y veremos cómo cambia después de cada bloque de código que agreguemos.

En nuestro archivo `index.html` tenemos la etiqueta `link`, que conecta nuestra página con el archivo de estilos.

Para comprobar que funciona, vamos a abrir `style.css`.

Primero crearemos el selector `body` y cambiaremos el color de fondo por un tono azul o celeste.

Ahora recargamos la página y podemos observar el cambio.

Si el color de fondo cambió, significa que el navegador encontró y cargó correctamente nuestro archivo CSS.

### 2. Personalizar el fondo, la fuente y el texto (00:50 – 01:35)

**[En pantalla]**
- Continuar trabajando dentro del selector `body`.
- Agregar `margin: 0`.
- Establecer la fuente Arial.
- Mantener el color de fondo.
- Cambiar el color del texto.

**[Texto de apoyo visual]**
- `margin`: controla el margen exterior.
- `font-family`: establece la fuente.
- `background-color`: define el fondo.
- `color`: cambia el color del texto.

**[Narración (Voz en off)]**

Ahora vamos a ajustar el fondo y la fuente de toda nuestra página.

Dentro del mismo selector `body` agregaremos `margin: 0` para eliminar el margen predeterminado del navegador.

Después cambiaremos la fuente utilizando Arial y como alternativa colocaremos sans-serif.

También mantendremos el color de fondo que ya habíamos elegido y cambiaremos el color del texto por un tono azul oscuro.

Con estos cambios estamos definiendo una apariencia general para toda la página.

### 3. Diseñar el encabezado (01:35 – 02:15)

**[En pantalla]**
- Recargar la página para observar los cambios del `body`.
- Crear el selector `header`.
- Establecer un fondo oscuro.
- Cambiar el texto a blanco.
- Centrar el contenido y agregar espacio interior.

**[Texto de apoyo visual]**
- `background-color`: color de fondo.
- `color`: color del texto.
- `text-align: center`: centra el texto.
- `padding`: agrega espacio interior.

**[Narración (Voz en off)]**

Ahora que hemos actualizado el `body`, vamos a recargar la página para observar los cambios.

Podemos notar que desapareció el margen predeterminado y que el texto ahora tiene un tono azul oscuro.

Ahora vamos a trabajar con el encabezado.

Crearemos el selector `header` y le daremos un fondo oscuro, parecido al color que utilizamos anteriormente.

Para que el texto se vea correctamente, cambiaremos su color a blanco.

También vamos a centrar el contenido utilizando `text-align: center`.

Finalmente, agregaremos un `padding` de 24 píxeles en la parte superior e inferior y 16 píxeles a los costados.

Actualizamos la página y podemos observar cómo todo el encabezado tiene una apariencia más organizada.

### 4. Dar forma a la imagen de perfil (02:15 – 03:03)

**[En pantalla]**
- Crear el selector `header img`.
- Agregar `border-radius: 50%`.
- Agregar un borde de 4 píxeles de color naranja claro.
- Actualizar la página para observar el resultado.

**[Texto de apoyo visual]**
- `header img`: selecciona la imagen dentro del encabezado.
- `border-radius`: redondea las esquinas.
- `border`: agrega un borde.

**[Narración (Voz en off)]**

Ahora vamos a personalizar nuestra imagen de perfil.

Para seleccionar únicamente la imagen que está dentro del encabezado, utilizaremos `header img`.

Primero agregaremos `border-radius` con un valor de 50 por ciento. Esto hará que nuestra imagen tenga una forma circular.

Después agregaremos un borde de 4 píxeles, de tipo solid y de color naranja claro.

Actualizamos la página y podemos observar que nuestra imagen ahora es circular y tiene un borde que la hace destacar.

### 5. Ajustar el contenido principal y crear tarjetas (03:03 – 04:02)

**[En pantalla]**
- Crear el selector `main`.
- Establecer `max-width: 600px`.
- Agregar `margin: 24px auto`.
- Agregar `padding: 0 16px`.
- Mostrar cómo cambia la distribución del contenido.

**[Texto de apoyo visual]**
- `max-width`: establece el ancho máximo.
- `margin: 24px auto`: agrega margen vertical y centra horizontalmente.
- `padding`: agrega espacio interior.

**[Narración (Voz en off)]**

Ahora vamos a trabajar con el contenido principal de nuestra página.

Para eso utilizaremos el selector `main`.

Primero limitaremos su ancho máximo a 600 píxeles utilizando `max-width`.

Después agregaremos un margen de 24 píxeles en la parte superior e inferior y automático a los costados. Esto permitirá centrar el contenido horizontalmente.

También agregaremos un `padding` de cero píxeles verticales y 16 píxeles horizontales.

Actualizamos la página y podemos observar cómo el contenido ahora ocupa un espacio más limitado y organizado.

Ahora vamos a hacer que cada sección se vea como una tarjeta blanca, con espacio interior y esquinas redondeadas.

### 6. Convertir las secciones en tarjetas (04:02 – 05:01)

**[En pantalla]**
- Crear el selector `section`.
- Establecer el fondo blanco.
- Agregar esquinas redondeadas.
- Añadir espacio interior y margen inferior.
- Mostrar las tres tarjetas resultantes.

**[Texto de apoyo visual]**
- `background-color: white`: fondo blanco.
- `border-radius: 12px`: esquinas redondeadas.
- `padding: 16px`: espacio interior.
- `margin-bottom: 16px`: separación inferior.

**[Narración (Voz en off)]**

Para conseguir este efecto vamos a utilizar el selector `section`.

Primero cambiaremos el fondo a blanco.

Después agregaremos un `border-radius` de 12 píxeles para redondear las esquinas.

También colocaremos un `padding` de 16 píxeles para que el contenido no quede pegado a los bordes.

Finalmente, agregaremos un `margin-bottom` de 16 píxeles para separar cada tarjeta de la siguiente.

Actualizamos la página y podemos observar cómo nuestras secciones ahora están separadas y tienen una apariencia similar a tarjetas.

### 7. Personalizar títulos, enlaces y pie de página (05:01 – 06:18)

**[En pantalla]**
- Crear el selector `h2`.
- Cambiar el color de los títulos.
- Crear el selector `a` para personalizar los enlaces.
- Crear el selector `footer`.
- Centrar el texto y modificar el espacio y el color.

**[Texto de apoyo visual]**
- `h2`: selecciona los títulos de segundo nivel.
- `a`: selecciona los enlaces.
- `text-align: center`: centra el texto.
- `padding`: agrega espacio interior.
- `color`: cambia el color del texto.

**[Narración (Voz en off)]**

Para terminar, vamos a ajustar los colores de los títulos, los enlaces y el pie de página.

Primero crearemos el selector `h2` y le daremos un color diferente para que los títulos de nuestras secciones destaquen.

Después crearemos el selector `a` para cambiar el color de los enlaces. En este caso utilizaremos el mismo tono que elegimos para los títulos.

Finalmente, vamos a trabajar con el `footer`.

Centraremos su contenido utilizando `text-align: center`, agregaremos un `padding` de 16 píxeles y cambiaremos el color del texto por un tono azul parecido a los anteriores.

Ahora podemos observar todos los cambios aplicados. Nuestra página tiene una apariencia mucho más organizada y agradable.

### 8. Personalización y cierre del proyecto (06:18 – 07:06)

**[En pantalla]**
- Mostrar el resultado completo de la página.
- Cambiar el color del encabezado o el borde de la imagen.
- Comparar el resultado antes y después.
- Mostrar la página finalizada.

**[Texto de apoyo visual]**
- ¡Personaliza tu página!
- Prueba otros colores.
- Cambia un valor a la vez.
- HTML = estructura.
- CSS = apariencia.

**[Narración (Voz en off)]**

Ahora es tu turno.

Puedes probar con otro color para el encabezado o para el borde de tu foto.

Recuerda cambiar solamente un valor a la vez. Por ejemplo, podemos elegir un color diferente y observar cómo cambia el resultado.

Cada vez que modifiques un valor, fíjate qué parte de la página se modifica.

¡Y listo! Ya tenemos nuestra página de perfil completa.

Recuerda que HTML le da la estructura a nuestra página, mientras que CSS define cómo se ve.

En la última lección veremos algunos errores comunes y cómo podemos corregirlos.

¡Nos vemos en la siguiente lección!

---

## Código de la Lección

### Archivo: `style.css`

```css
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #eef3f8;
  color: #0b1f33;
}

header {
  background-color: #0b1f33;
  color: white;
  text-align: center;
  padding: 24px 16px;
}

header img {
  border-radius: 50%;
  border: 4px solid #f89820;
}

main {
  max-width: 600px;
  margin: 24px auto;
  padding: 0 16px;
}

section {
  background-color: white;
  border-radius: 12px;
  padding: 16px;
  margin-bottom: 16px;
}

h2 {
  color: #1c7293;
}

a {
  color: #1c7293;
}

footer {
  text-align: center;
  padding: 16px;
  color: #2b4a66;
}
```

---

## Conceptos Aprendidos

| Propiedad o selector | Función |
|---|---|
| `body` | Permite aplicar estilos generales a la página. |
| `header` | Selecciona el encabezado. |
| `header img` | Selecciona la imagen dentro del encabezado. |
| `main` | Selecciona el contenido principal. |
| `section` | Selecciona las secciones de contenido. |
| `h2` | Selecciona los títulos de segundo nivel. |
| `a` | Selecciona los enlaces. |
| `footer` | Selecciona el pie de página. |
| `margin` | Controla el espacio exterior. |
| `padding` | Controla el espacio interior. |
| `font-family` | Define el tipo de letra. |
| `background-color` | Cambia el color de fondo. |
| `color` | Cambia el color del texto. |
| `text-align` | Controla la alineación del texto. |
| `max-width` | Establece el ancho máximo de un elemento. |
| `border-radius` | Redondea las esquinas. |
| `border` | Agrega un borde. |
| `margin-bottom` | Establece el margen inferior. |

---

## Actividad Práctica — Personaliza el diseño de tu perfil

**Objetivo:** Modificar los estilos de la página de perfil personal para crear un diseño propio utilizando las propiedades CSS aprendidas.

**Instrucciones:**

1. Cambia el color de fondo general de la página.
2. Prueba un color diferente para el encabezado.
3. Modifica el color del borde de la imagen de perfil.
4. Cambia el color de los títulos y enlaces.
5. Experimenta con el valor de `border-radius` de las tarjetas.
6. Observa cómo cambia la página cada vez que modificas una propiedad.

**Reto adicional:**

Crea una combinación de colores propia para tu perfil. Intenta utilizar colores que combinen entre sí y mantengan el texto fácil de leer.

**Resultado esperado:** Una página de perfil personal completamente diseñada con CSS, con un encabezado personalizado, una imagen circular, secciones en forma de tarjetas y un pie de página centrado.