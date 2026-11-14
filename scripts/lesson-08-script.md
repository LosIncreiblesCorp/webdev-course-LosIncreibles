# Guion de la Lección 8: Proyecto Final — Página de Perfil Personal (Parte 1: HTML)

## Detalles de la Lección

- **Duración aproximada:** 7 minutos
- **Público objetivo:** Estudiantes de secundaria (12 a 17 años)
- **Herramientas:** Replit (editor en línea)
- **Lenguajes:** HTML
- **Archivo principal:** `index.html`
- **Proyecto:** Página de perfil personal

---

## Objetivo de la Lección

Construir la estructura HTML de una página de perfil personal utilizando etiquetas semánticas como `header`, `main`, `section` y `footer`. La página incluirá una foto de perfil, una presentación, una lista de pasatiempos y un enlace externo.

Al finalizar, tendremos el contenido organizado y preparado para agregarle estilos con CSS en la siguiente lección.

---

## Estructura del Video

### 1. Presentación del proyecto final (00:00 – 00:40)

**[En pantalla]**
- Mostrar el resultado final de la página de perfil personal.
- Presentar el proyecto dividido en dos partes:
    - Parte 1: estructura HTML.
    - Parte 2: diseño con CSS.
- Abrir el proyecto en Replit.

**[Texto de apoyo visual]**
- Proyecto final: Mi perfil personal.
- Parte 1: HTML — Estructura.
- Parte 2: CSS — Diseño.

**[Narración (Voz en off)]**

¡Llegó el momento del proyecto final! En esta ocasión vamos a crear una página de perfil personal que tendrá nuestra foto, una presentación, una lista de pasatiempos y algunos enlaces.

Fíjate en cómo se verá cuando esté terminada. Lo construiremos en dos videos. En este primero crearemos la estructura con HTML, que será como el esqueleto de nuestra página. En el siguiente video le daremos estilo utilizando CSS.

Abre el proyecto de Replit que encontrarás en la descripción y vamos a comenzar.

Antes de escribir código, siempre es buena idea hacer un pequeño boceto, aunque sea a mano, para organizar cómo queremos que se vea nuestra página.

### 2. Organización de la página con etiquetas semánticas (00:40 – 01:23)

**[En pantalla]**
- Mostrar el boceto de la página.
- Señalar el encabezado, el contenido principal y el pie de página.
- Mostrar las etiquetas `header`, `main`, `section` y `footer`.

**[Texto de apoyo visual]**
- `header`: encabezado.
- `main`: contenido principal.
- `section`: sección de contenido.
- `footer`: pie de página.

**[Narración (Voz en off)]**

Mira mi boceto. En la parte superior tendremos un encabezado con una foto, nuestro nombre y una frase corta.

En el centro estará el contenido principal, dividido en tres secciones: sobre mí, mis pasatiempos y mis enlaces.

Finalmente, en la parte inferior tendremos el pie de página.

HTML tiene etiquetas que nos ayudan a organizar estas partes. Por ejemplo, `header` representa el encabezado, `main` contiene el contenido principal, `section` representa cada sección y `footer` corresponde al pie de página.

Estas etiquetas nos permiten organizar mejor el código y comunicar al navegador y a otras personas qué función cumple cada parte de nuestra página.

### 3. Crear la estructura base del documento (01:23 – 02:10)

**[En pantalla]**
- Abrir `index.html`.
- Escribir la estructura básica de HTML.
- Cambiar el título a `Mi perfil`.
- Agregar la etiqueta `link` para conectar la futura hoja de estilos.

**[Texto de apoyo visual]**
- `<!DOCTYPE html>`: indica que usamos HTML5.
- `<head>`: contiene información del documento.
- `<title>`: establece el título de la página.
- `<link>`: conecta el archivo CSS.

**[Narración (Voz en off)]**

Empezamos con la estructura base que ya conocemos.

Primero colocamos `DOCTYPE html`, después la etiqueta `html` indicando que el idioma será español. Dentro agregamos `head`, donde colocaremos la configuración del documento.

Incluimos `meta charset` para permitir que se muestren correctamente los caracteres y cambiamos el título de la página por Mi perfil.

También agregaremos algo nuevo: la etiqueta `link`, que nos permitirá conectar nuestra hoja de estilos llamada `style.css`.

Este archivo todavía no tiene los estilos, pero lo tendremos preparado para trabajar con él en el siguiente video.

Ahora pasamos al `body`, donde construiremos todo el contenido que aparecerá en nuestra página.

### 4. Crear el encabezado del perfil (02:10 – 02:50)

**[En pantalla]**
- Crear la etiqueta `header`.
- Agregar una imagen con `img`.
- Colocar un título con el nombre y un párrafo con una frase de presentación.

**[Texto de apoyo visual]**
- `header`: encabezado.
- `img`: insertar una imagen.
- `alt`: descripción de la imagen.
- `width`: ancho de la imagen.
- `h1`: título principal.

**[Narración (Voz en off)]**

Dentro del `body` comenzaremos creando nuestro `header`.

Aquí colocaremos una imagen utilizando la etiqueta `img`. Para este ejemplo usaremos una foto de prueba y agregaremos el texto alternativo Mi foto de perfil. También estableceremos un ancho de 150 píxeles.

Debajo de la imagen colocaremos un título `h1` con nuestro nombre y un párrafo con una frase corta, como estudiante y futura programadora.

¡Listo! Ya tenemos el encabezado de nuestro perfil.

### 5. Crear el contenido principal y sus secciones (02:50 – 03:49)

**[En pantalla]**
- Crear la etiqueta `main`.
- Dentro, crear la primera etiqueta `section`.
- Agregar el título `Sobre mí` con `h2`.
- Escribir un párrafo de presentación.

**[Texto de apoyo visual]**
- `main`: contenido principal.
- `section`: agrupa contenido relacionado.
- `h2`: título de una sección.
- `p`: párrafo.

**[Narración (Voz en off)]**

Ahora vamos con el contenido principal de nuestra página. Para eso utilizaremos la etiqueta `main`.

Dentro de `main` crearemos nuestras secciones utilizando `section`.

La primera sección tendrá un título `h2` que diga Sobre mí. Debajo agregaremos un párrafo con algunos detalles personales, como nuestra edad, lo que nos gusta y otras cosas que queramos compartir.

Recuerda que podemos escribir nuestra propia presentación para que el perfil sea más personal.

### 6. Agregar la lista de pasatiempos (03:49 – 04:40)

**[En pantalla]**
- Crear una segunda etiqueta `section`.
- Agregar el título `Mis pasatiempos`.
- Crear una lista con `ul` y tres elementos `li`.

**[Texto de apoyo visual]**
- `ul`: lista desordenada o con viñetas.
- `li`: elemento de una lista.

**[Narración (Voz en off)]**

Para la segunda sección escribiremos Mis pasatiempos.

En esta ocasión colocaremos nuestros pasatiempos dentro de una lista con viñetas. Para crearla utilizaremos la etiqueta `ul`.

Cada elemento de la lista se escribirá utilizando `li`.

Por ejemplo, podemos agregar tocar la guitarra, dibujar y programar.

De esta manera tendremos nuestros pasatiempos organizados y fáciles de leer.

### 7. Agregar nuestros enlaces (04:40 – 05:30)

**[En pantalla]**
- Crear una tercera etiqueta `section`.
- Agregar el título `Mis enlaces`.
- Crear un párrafo con un enlace a MDN.

**[Texto de apoyo visual]**
- `a`: crea un enlace.
- `href`: indica la dirección de destino.
- `target="_blank"`: abre el enlace en otra pestaña.

**[Narración (Voz en off)]**

Para nuestra tercera sección colocaremos el título Mis enlaces.

Debajo agregaremos un párrafo que contenga un enlace utilizando la etiqueta `a`.

En `href` escribiremos la dirección de MDN, que es un sitio donde podemos aprender más sobre desarrollo web.

También agregaremos `target="_blank"` para que el enlace se abra en una nueva pestaña.

Como texto del enlace escribiremos Aprender más sobre la web.

¡Perfecto! Ya tenemos nuestras tres secciones dentro de `main`.

### 8. Crear el pie de página y visualizar el resultado (05:30 – 06:07)

**[En pantalla]**
- Crear la etiqueta `footer`.
- Agregar el texto `Hecho con HTML y CSS`.
- Cerrar las etiquetas restantes.
- Ejecutar el proyecto para visualizar la página.

**[Texto de apoyo visual]**
- `footer`: pie de página.
- Recuerda cerrar todas las etiquetas.

**[Narración (Voz en off)]**

Ahora vamos con la última parte: el pie de página.

Para eso utilizaremos `footer` y dentro colocaremos un párrafo que diga Hecho con HTML y CSS.

Finalmente, cerramos las etiquetas `body` y `html`.

¡Y listo! Al ejecutar nuestro proyecto ya podemos observar la página con todo su contenido. Por ahora se ve bastante sencilla, porque todavía no tiene estilos, pero eso es justamente lo que trabajaremos en el siguiente video.

### 9. Personalizar el perfil y cierre (06:07 – 06:55)

**[En pantalla]**
- Mostrar nuevamente el resultado de la página.
- Cambiar el nombre de ejemplo.
- Editar la presentación y los pasatiempos.
- Mostrar cómo agregar una cuarta sección.

**[Texto de apoyo visual]**
- Personaliza tu perfil:
    - Coloca tu nombre.
    - Escribe sobre ti.
    - Agrega tus pasatiempos.
    - Incluye otra sección si deseas.

**[Narración (Voz en off)]**

Ahora es tu turno de personalizar la página.

Cambia el nombre por el tuyo, escribe algunas líneas sobre ti y agrega más pasatiempos que realmente te gusten.

Si quieres, puedes agregar una cuarta sección con otro tema, como tu comida favorita o tu música preferida.

Recuerda que cada sección debe tener su propio título `h2` y que todas las etiquetas que abras deben estar correctamente cerradas.

Pausa el video y personaliza tu página.

¡Muy bien! Ya tienes el esqueleto completo de tu perfil personal. Por ahora se ve sin colores ni estilos, pero eso cambiará en el siguiente video.

Guarda tu proyecto y nos vemos en la siguiente lección.

---

## Código de la Lección

### Archivo: `index.html`

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi perfil</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <img src="https://picsum.photos/150" alt="Mi foto de perfil" width="150">
    <h1>Ana Pérez</h1>
    <p>Estudiante y futura programadora</p>
  </header>

  <main>
    <section>
      <h2>Sobre mí</h2>
      <p>Tengo 15 años. Me gusta la música, los videojuegos y aprender cosas nuevas.</p>
    </section>

    <section>
      <h2>Mis pasatiempos</h2>
      <ul>
        <li>Tocar la guitarra</li>
        <li>Dibujar</li>
        <li>Programar</li>
      </ul>
    </section>

    <section>
      <h2>Mis enlaces</h2>
      <p><a href="https://developer.mozilla.org/es/" target="_blank">Aprender más sobre la web</a></p>
    </section>
  </main>

  <footer>
    <p>Hecho con HTML y CSS</p>
  </footer>
</body>
</html>
```

---

## Conceptos Aprendidos

| Etiqueta o atributo | Función |
|---|---|
| `header` | Define el encabezado de la página. |
| `main` | Agrupa el contenido principal. |
| `section` | Organiza el contenido en secciones. |
| `footer` | Define el pie de página. |
| `img` | Inserta una imagen. |
| `alt` | Describe la imagen. |
| `width` | Establece el ancho de la imagen. |
| `h1` | Define el título principal. |
| `h2` | Define el título de una sección. |
| `ul` | Crea una lista con viñetas. |
| `li` | Representa un elemento de una lista. |
| `a` | Crea un enlace. |
| `href` | Indica la dirección del enlace. |
| `target="_blank"` | Abre el enlace en otra pestaña. |
| `link` | Conecta el documento HTML con una hoja de estilos. |

---

## Actividad Práctica — Personaliza tu perfil

**Objetivo:** Crear una página de perfil personal utilizando las etiquetas HTML aprendidas durante la lección.

**Instrucciones:**

1. Cambia el nombre de ejemplo por tu nombre.
2. Reemplaza la imagen de prueba por una imagen que quieras utilizar.
3. Escribe una presentación breve sobre ti.
4. Agrega al menos tres pasatiempos en tu lista.
5. Incluye un enlace a una página que te resulte interesante.
6. Cambia el texto del pie de página si lo deseas.

**Reto adicional:**

Agrega una cuarta sección llamada Mi música favorita o Mi comida favorita. Recuerda utilizar `section` y colocar un título `h2`.

**Resultado esperado:** Una página de perfil personal con encabezado, presentación, pasatiempos, enlaces y pie de página. En esta primera parte solo trabajaremos la estructura HTML; el diseño visual se realizará en la siguiente lección.