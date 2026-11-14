# Guion de la Lección 4: Imágenes y Enlaces en HTML

## Detalles de la Lección

- **Duración aproximada:** 15 minutos.
- **Público objetivo:** Estudiantes de secundaria (12 a 17 años).
- **Herramientas:** Navegador web y CodePen (100% en línea).
- **Lenguaje:** HTML.

---

## Estructura del Video

### Bloque 1: Introducción a las imágenes y los enlaces (00:00 – 00:44)

- **[En pantalla]:** Mostrar una página web que contiene únicamente texto. Después, presentar una página con imágenes y enlaces para comparar ambas.
- **[Texto de apoyo visual]:**
    - `Imágenes = Contenido visual`
    - `Enlaces = Conexión entre páginas`
    - `La web es una red de páginas conectadas`
- **[Narración (Voz en off)]:**

> "Hola. Una página que solo tiene texto se parece a un libro sin portada ni dibujos. Es aburrido de leer.
>
> Lo que hace especial a la web son dos cosas: las imágenes, que hacen que la página sea más atractiva, y los enlaces, que te permiten saltar de una página a otra con un clic.
>
> De hecho, la palabra web significa red o telaraña, justamente porque las páginas están conectadas entre sí mediante enlaces.
>
> Hoy aprenderás a usar las dos. Vamos a empezar con las imágenes. Para ello vamos a irnos a nuestro editor HTML, que en este caso es CodePen."

### Bloque 2: Conociendo la etiqueta IMG y sus atributos (00:44 – 02:17)

- **[En pantalla]:** Mostrar el panel HTML de CodePen y escribir la etiqueta `img`. Explicar que no necesita una etiqueta de cierre y señalar los atributos `src` y `alt`.
- **[Texto de apoyo visual]:**
    - `<img> → Insertar imágenes`
    - `src → Dirección de la imagen`
    - `alt → Descripción alternativa`
    - `width → Ancho de la imagen`
- **[Narración (Voz en off)]:**

> "Para mostrar una imagen vamos a utilizar la etiqueta img. Es especial porque no tiene etiqueta de cierre, no encierra ningún contenido y solo muestra una imagen.
>
> ¿Qué quiere decir? Que nosotros al hacer nuestra etiqueta img no es que se nos va a autocompletar otra etiqueta de cerrado. De hecho, si lo rellenamos nos daremos cuenta de que el editor mismo nos dice que esto está mal. En su lugar se usan atributos.
>
> El primero de todos es source o src, que significa fuente y es la dirección de donde está la imagen.
>
> Para este ejemplo utilizaré la dirección de una imagen de prueba que está en internet.
>
> Y el segundo atributo que usaremos será alt, de alternative, y es una descripción en palabras de lo que muestra la imagen."

### Bloque 3: Insertando nuestra primera imagen (02:17 – 05:09)

- **[En pantalla]:** Crear una página sobre nuestro lugar favorito. Escribir el encabezado principal y agregar la etiqueta `img` con sus atributos. Mostrar inicialmente la imagen sin una dirección válida para explicar el texto alternativo.
- **[Texto de apoyo visual]:**
    - `<h1> → Título principal`
    - `<img src="..."> → Dirección de la imagen`
    - `alt="..." → Texto alternativo`
    - `width="300" → Ancho en píxeles`
- **[Narración (Voz en off)]:**

> "Bien, vamos a empezar a escribir el código de esta página. Vamos a iniciar, como ya hemos visto en la clase pasada, con nuestro encabezado principal.
>
> En este caso vamos a tratar de escribir acerca de nuestro lugar favorito. Ya que estamos hablando del uso de imágenes en nuestra web, sería interesante ilustrar cómo luciría nuestro lugar favorito.
>
> Para ello vamos a empezar con nuestra etiqueta img. A continuación utilizamos, como habíamos mencionado anteriormente, el atributo src, que se escribe de la siguiente forma: img src igual. Y entre estas comillas es donde vamos a colocar la dirección de nuestra imagen.
>
> Luego colocamos alt, de alternative, igual a 'Paisaje de ejemplo'.
>
> Y un último atributo, width, que es el ancho que va a tener nuestra imagen. En este caso va a ser igual a 300.
>
> Ahora, ¿qué es lo que nos damos cuenta en nuestra pantalla? Que no nos aparece la imagen.
>
> Esto es porque en el atributo src, donde tiene que ir el enlace de nuestra imagen, no la hemos colocado aún.
>
> Sin embargo, igual aparece un texto y nos dice 'Paisaje de ejemplo'. ¿Por qué? Porque hemos añadido este texto alternativo para que, en caso de que no cargue nuestra imagen, se muestre este texto para que podamos mencionar de qué trata la imagen.
>
> Este atributo es muy importante. El alt primero ayuda a que las personas que no pueden ver y usan un programa que lee la pantalla en voz alta puedan escuchar la descripción de la imagen.
>
> Y, en segundo lugar, si la imagen por algún motivo no carga, el navegador va a mostrar ese texto en su lugar, como es en este caso.
>
> De hecho, miren, si yo por algún motivo reemplazo con una foto agregando el contenido en src, nos vamos a dar cuenta de que ya no carga el texto alternativo porque ahora tenemos una imagen.
>
> Sin embargo, si yo lo quito, sí que va a aparecer, pues no tenemos una imagen.
>
> Y finalmente, el width indica el ancho en píxeles. En este caso vamos a poner 300.
>
> Y como consejo de oro que yo les puedo brindar es que cada vez que vayan a colocar una imagen con su src, por más que ustedes tengan certeza de que va a funcionar el recurso, siempre por precaución se pone el alt porque nunca se sabe cuándo puede haber algún problema con la carga de las imágenes."

### Bloque 4: Conociendo los enlaces HTML (05:09 – 06:45)

- **[En pantalla]:** Mostrar un ejemplo de enlace y señalar la etiqueta `a` y el atributo `href`. Después, comenzar a escribir un párrafo en CodePen.
- **[Texto de apoyo visual]:**
    - `<a> → Crear enlaces`
    - `href → Dirección de destino`
    - `Texto del enlace → Contenido sobre el que se hace clic`
- **[Narración (Voz en off)]:**

> "Bien, ahora vamos a pasar con el segundo apartado, que son los enlaces.
>
> Los enlaces se crean con la etiqueta A. A viene de anchor, que significa ancla.
>
> Entre la etiqueta de apertura y la etiqueta de cierre va el texto sobre el que la persona hará clic y necesita un atributo importante.
>
> En este caso, el atributo href, que viene de hypertext reference y es el destino del enlace. Es decir, a qué dirección irá quien haga clic.
>
> A continuación voy a ejemplificar esto que estoy mencionando.
>
> Vamos a empezar poniendo un pequeño párrafo. En este caso vamos a poner P para escribir un párrafo, como ya hemos visto en la clase pasada.
>
> 'Para saber más, visita' y a continuación vamos a colocar nuestro enlace."

### Bloque 5: Creando nuestro primer enlace (06:45 – 09:07)

- **[En pantalla]:** Escribir la etiqueta `<a>` dentro del párrafo. Agregar el atributo `href` y colocar el texto del enlace. Después, pegar la dirección de MDN Web Docs en español.
- **[Texto de apoyo visual]:**
    - `<a href="URL">Texto del enlace</a>`
    - `href = Dirección de destino`
    - `MDN Web Docs = Recurso de aprendizaje`
- **[Narración (Voz en off)]:**

> "Vamos a poner A con el atributo href igual y entre comillas vamos a colocar dentro de estas comillas el enlace que nosotros vamos a desear visitar.
>
> Luego ponemos la etiqueta de cierre y, finalmente, luego de cerrar nuestra etiqueta de apertura, vamos a escribir el texto sobre el cual se va a hacer clic para visitar el enlace.
>
> En este caso, MDN.
>
> Y a continuación podemos notar cómo en la pantalla se muestra el texto que acabamos de programar.
>
> 'Para saber más, visita' y nos deja un enlace para poder abrir.
>
> En este caso, como nuestro enlace está en blanco, nos va a autorreferenciar la página. Sin embargo, si nosotros deseamos que nos dirija a otro enlace, vamos a pegar la dirección de la web preparada que queremos visitar.
>
> Y en este caso ya nos navega a otra web.
>
> Lo que hemos hecho en resumen ha sido escribir primero un párrafo que decía 'Para saber más'.
>
> Para ello abrimos la etiqueta P. Luego la etiqueta A con el href igual a la dirección que vamos a visitar. En este caso developer.mozilla.org en español, que es una página muy buena para aprender desarrollo web.
>
> Como texto del enlace, finalmente se coloca el texto sobre el cual se va a hacer clic, en este caso el título del recurso.
>
> En la vista previa aparece el típico azul y el subrayado que nos indica que, si hago clic, me va a llevar a esa página."

### Bloque 6: Abrir enlaces en una nueva pestaña con TARGET (09:07 – 10:35)

- **[En pantalla]:** Resaltar el atributo `target="_blank"` en el código y mostrar cómo se abre el enlace en una nueva pestaña del navegador.
- **[Texto de apoyo visual]:**
    - `target="_blank" → Abrir en una nueva pestaña`
    - `Sin target="_blank" → Abrir en la pestaña actual`
- **[Narración (Voz en off)]:**

> "Pero eso ha sido la lección en cuanto a los enlaces o los links.
>
> Algo muy importante que es necesario recalcar es que target igual, abrimos comillas, guion bajo blank, lo que nos permite es que, a la hora de nosotros hacer clic, se abra automáticamente otra pestaña con el recurso, con la página web cargada.
>
> Si prescindimos de este apartado, lo que ocurriría es que cargaría dentro de nuestra página actual.
>
> Sin embargo, no queremos eso porque ello involucraría que perderíamos todo el avance que estamos codificando.
>
> Ustedes mismos pueden probar borrando esta parte de la línea de código y notarán cómo automáticamente va a cargarse en la misma pestaña que tenían abierta."

### Bloque 7: Pausa interactiva: Agregando una imagen y un enlace (10:35 – 11:21)

- **[En pantalla]:** Mostrar el mensaje `¡PAUSA PARA PRACTICAR!` y presentar los requisitos del reto.
- **[Texto de apoyo visual]:**
    - `Reto: Mi sitio web favorito`
    - `1. Agrega una imagen.`
    - `2. Incluye un texto alternativo.`
    - `3. Agrega un enlace a tu sitio favorito.`
    - `4. Configura el enlace para abrirse en otra pestaña.`
- **[Narración (Voz en off)]:**

> "Muy bien. Ha llegado la hora de practicar.
>
> En el Pen que les he preparado agreguen una imagen con un texto alternativo y un enlace a su sitio favorito.
>
> Y lo que vamos a buscar como requisito es que se abra en una pestaña nueva.
>
> Para probar que funciona, haz clic en el enlace y, si la imagen no aparece, revisa que la dirección esté bien escrita y entre comillas.
>
> Pausa el video y hazlo por tu cuenta."

### Bloque 8: Resolución del reto: Mi sitio web favorito (11:21 – 13:55)

- **[En pantalla]:** Volver a CodePen y mostrar la solución. Agregar el encabezado, la imagen de YouTube y el enlace configurado para abrirse en una nueva pestaña.
- **[Texto de apoyo visual]:**
    - `<h1> → Mi sitio web favorito`
    - `src → Dirección de la imagen`
    - `alt → Descripción de la imagen`
    - `width="300" → Ancho de la imagen`
    - `href → Dirección del enlace`
    - `target="_blank" → Nueva pestaña`
- **[Narración (Voz en off)]:**

> "Bueno, a continuación vamos a hacer la solución acompañada de este pequeño reto que hemos visto.
>
> Lo que hemos sugerido como reto fue básicamente que ustedes añadan una imagen con su texto alternativo y un enlace a su sitio web favorito que se abra en una pestaña nueva.
>
> Entonces, para conseguir esto vamos a empezar poniendo como encabezado de título en nuestra página 'Mi sitio web favorito'.
>
> Vamos a empezar poniendo la imagen. Como hemos visto, abrimos la etiqueta imagen y le añadimos los atributos, empezando por el src, donde tiene que ir el enlace.
>
> El texto alternativo, que en este caso sería 'Foto de mi sitio web favorito'.
>
> Y vamos a limitar el tamaño del ancho de mi foto a 300 píxeles.
>
> En este caso, el sitio que he escogido va a ser YouTube.
>
> Bueno, en este caso ya tenemos lista nuestra foto de YouTube, que es mi sitio web favorito en realidad.
>
> Y a continuación vamos a poner un link.
>
> Vamos a abrir un párrafo y vamos a escribir: 'Visita la página web oficial de YouTube'.
>
> A continuación vamos a escribir nuestra etiqueta de enlace con A. Vamos a escribir A href igual y vamos a poner aquí el enlace de YouTube.
>
> Vamos a escribir target para que se abra en una nueva pestaña porque recordemos que así es como lo solicitamos en nuestro ejercicio.
>
> Y ponemos finalmente el texto que queremos que vaya en nuestro hipervínculo.
>
> En este caso vamos a escribir: 'Aquí', porque es la continuación de nuestro texto anterior.
>
> Vamos a ver cómo nos ha quedado. Tenemos mi título de la página web, mi sitio web favorito, la imagen de YouTube cargada y un apartado que dice 'Visita la página web oficial de YouTube aquí'.
>
> Si le damos clic en 'Aquí', nos abre específicamente la página web de YouTube.
>
> Entonces, con esto tendríamos conseguido nuestro pequeño reto. ¡Felicitaciones!"

### Bloque 9: Cierre del primer módulo (13:55 – 14:35)

- **[En pantalla]:** Mostrar un resumen visual de los contenidos aprendidos en las cuatro primeras lecciones. Presentar las etiquetas HTML trabajadas.
- **[Texto de apoyo visual]:**
    - `Estructura HTML`
    - `Encabezados y párrafos`
    - `Listas`
    - `Imágenes`
    - `Enlaces`
    - `¡Primer módulo completado!`
- **[Narración (Voz en off)]:**

> "Si terminaste este primer módulo, ya sabes crear la estructura básica de una página, organizar texto, hacer listas, mostrar imágenes y crear enlaces.
>
> Todo esto es HTML básico, pero todavía se ve muy simple, ¿verdad?
>
> En el siguiente módulo la vas a transformar con CSS. ¡Nos vemos en el próximo video!"

---

## Código de Referencia para la Lección

**Código de Inicio (Starter - Para el estudiante):**

```html
<h1>Mi lugar favorito</h1>

<img src="https://picsum.photos/300/200"
     alt="Paisaje de ejemplo"
     width="300">

<p>
  Para saber más, visita
  <a href="https://developer.mozilla.org/es/"
     target="_blank">MDN Web Docs</a>.
</p>
```

## Actividad de Práctica

**Reto de la Lección 4 — Mi sitio web favorito**

**Objetivo:** Insertar imágenes y crear enlaces utilizando los atributos correspondientes de HTML.

**Parte 1: Agregar una imagen**

1. Abre el enlace de CodePen que se encuentra en la descripción del video.
2. Agrega un encabezado con el texto "Mi sitio web favorito".
3. Inserta una imagen utilizando la etiqueta `<img>`.
4. Coloca la dirección de la imagen en el atributo `src`.
5. Agrega una descripción mediante el atributo `alt`.
6. Establece un ancho de 300 píxeles utilizando `width`.

**Parte 2: Crear un enlace**

1. Agrega un párrafo que invite a visitar tu sitio web favorito.
2. Utiliza la etiqueta `<a>` para crear un enlace.
3. Coloca la dirección del sitio web en el atributo `href`.
4. Agrega `target="_blank"` para abrir el enlace en una nueva pestaña.
5. Escribe el texto que aparecerá como hipervínculo.

**Resultado esperado:** El estudiante aprende a insertar imágenes utilizando `img`, comprende la importancia del texto alternativo `alt`, establece dimensiones mediante `width` y crea enlaces con `a`, `href` y `target="_blank"`. Al finalizar, tendrá una página web con contenido visual y enlaces externos.