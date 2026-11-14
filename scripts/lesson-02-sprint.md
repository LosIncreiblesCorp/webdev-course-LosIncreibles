# Guion de la Lección 2: Estructura Básica de un Documento HTML

## Detalles de la Lección

- **Duración aproximada:** 9 minutos y 30 segundos.
- **Público objetivo:** Estudiantes de secundaria (12 a 17 años).
- **Herramientas:** Navegador web y CodePen (100% en línea).
- **Lenguaje:** HTML.

---

## Estructura del Video

### Bloque 1: Introducción y conexión con la lección anterior (00:02 – 00:41)

- **[En pantalla]:** Mostrar el título de la segunda lección y recordar brevemente el resultado obtenido en el video anterior.
- **[Texto de apoyo visual]:**
    - `Lección 2: Estructura básica de HTML`
    - `HTML = Estructura y contenido`
    - `CSS = Estilos visuales`
- **[Narración (Voz en off)]:**

> "Hola nuevamente. Bienvenido a nuestra segunda lección de fundamentos de desarrollo web. En el video anterior conocimos dos tecnologías fundamentales, HTML y CSS. También utilizamos CodePen para crear un título, escribir un párrafo y modificar su color.
>
> Sin embargo, hasta ahora hemos trabajado con algunas etiquetas individuales. En esta oportunidad aprenderemos cómo se estructura un documento HTML completo y conoceremos sus principales componentes. Comencemos."

### Bloque 2: Preparación del entorno de trabajo en CodePen (00:41 – 01:17)

- **[En pantalla]:** Mostrar el proyecto de CodePen y señalar los archivos `index.html`, `style.css` y la vista previa.
- **[Texto de apoyo visual]:**
    - `index.html → Estructura y contenido`
    - `style.css → Estilos visuales`
    - `Preview → Resultado de nuestro código`
- **[Narración (Voz en off)]:**

> "Para esta lección continuaremos usando CodePen, nuestro editor de código en línea, pero para esta ocasión habremos creado una cuenta para usar esta función.
>
> Como pueden observar, tenemos diferentes archivos dentro de nuestro proyecto.
>
> El primero es index.html, que utilizaremos para definir la estructura y el contenido de nuestra página web.
>
> También encontramos a style.css, que nos permite trabajar con los estilos visuales de nuestra página. En esta ocasión nos concentraremos en HTML, por lo que no necesitaremos modificar los estilos.
>
> Finalmente, tenemos una vista previa donde podemos observar cómo el navegador interpreta nuestro código y muestra el resultado."

### Bloque 3: Construcción de la estructura principal del documento HTML (01:17 – 02:05)

- **[En pantalla]:** Acercar el panel HTML y comenzar a escribir el código. Mostrar primero la declaración DOCTYPE y posteriormente la etiqueta HTML.
- **[Texto de apoyo visual]:**
    - `<!DOCTYPE html> → Declara HTML moderno`
    - `<html> → Elemento principal`
    - `lang="es" → Idioma español`
- **[Narración (Voz en off)]:**

> "Ahora vamos a comenzar a escribir nuestro documento HTML. Bien, he hecho un pequeño zoom para que se vea mejor la sección de HTML.
>
> A continuación avanzaremos primero escribiendo la declaración DOCTYPE HTML. Esta declaración le indica al navegador que nuestro documento utiliza HTML moderno.
>
> Después agregamos la etiqueta que representa el elemento principal de nuestra página. Le damos un atributo. Este atributo es lang, que es el idioma de la página, que indica al documento que el idioma es español."

### Bloque 4: Las secciones HEAD y BODY (02:05 – 04:10)

- **[En pantalla]:** Mostrar cómo se agregan progresivamente las etiquetas `<head>` y `<body>`. Destacar las configuraciones dentro de HEAD.
- **[Texto de apoyo visual]:**
    - `<head> → Información y configuración`
    - `<meta charset="UTF-8"> → Caracteres especiales`
    - `<meta name="viewport"> → Adaptación a dispositivos`
    - `<title> → Título de la pestaña`
    - `<link> → Conexión con CSS`
    - `<body> → Contenido visible`
- **[Narración (Voz en off)]:**

> "Ahora vamos a definir las dos secciones principales de nuestro documento, el head y el body.
>
> Comenzamos escribiendo la etiqueta head. Esta sección contiene información y configuración del documento que el navegador utiliza para interpretar nuestra página.
>
> Dentro de ella agregamos meta charset igual entre comillas UTF-8. Esta configuración permite representar correctamente caracteres como las tildes y la letra ñ.
>
> Después agregamos una configuración llamada viewport, que ayuda a visualizar correctamente el contenido en dispositivos móviles.
>
> A continuación escribo la etiqueta title y colocamos 'Mi primera página'. Este será el título que aparecerá en la pestaña de nuestro navegador.
>
> También agregamos una etiqueta link para conectar nuestro archivo HTML con la hoja de estilo CSS, aunque en esta sección no lo utilizaremos.
>
> Y cerramos. Ahora cerramos la sección y comenzamos con la siguiente sección principal, body."

### Bloque 5: Agregando contenido visible a nuestra página (04:10 – 04:58)

- **[En pantalla]:** Mostrar la sección BODY y escribir progresivamente las etiquetas `<h1>` y `<p>`. Mantener visible la vista previa.
- **[Texto de apoyo visual]:**
    - `<body> → Contenido visible`
    - `<h1> → Encabezado principal`
    - `<p> → Párrafo`
- **[Narración (Voz en off)]:**

> "La etiqueta body representa el cuerpo de nuestro documento. Dentro de esta sección colocaremos el contenido que los usuarios podrán visualizar en nuestra página.
>
> Primero agregamos un encabezado utilizando la etiqueta H1, como enseñé anteriormente. Escribimos un clásico, 'Hola mundo'. Bien, ya se muestra en nuestro preview.
>
> Después agregamos un párrafo mediante la etiqueta P con el siguiente texto: 'Me llamo Ana y estoy aprendiendo HTML'.
>
> Finalmente, cerramos las etiquetas de body y HTML. Ahora observaremos nuestra vista previa.
>
> Hola mundo, me llamo Ana y estoy aprendiendo HTML. Perfecto. Podemos ver que nuestro documento muestra el título principal y el párrafo que acabamos de escribir."

### Bloque 6: Etiquetas, elementos y atributos (04:58 – 06:32)

- **[En pantalla]:** Mostrar el código HTML completo y resaltar las partes correspondientes a las etiquetas, elementos y atributos.
- **[Texto de apoyo visual]:**
    - `Etiqueta → <p>`
    - `Elemento → <p>Contenido</p>`
    - `Atributo → lang="es"`
- **[Narración (Voz en off)]:**

> "Bien. Anteriormente dije que iba a enseñar un poco a futuro sobre lo que son estas partes, las etiquetas.
>
> Ahora que ya tenemos la estructura de la página HTML, vamos a aprender tres conceptos: etiquetas, elementos y atributos.
>
> Primero tenemos las etiquetas. Estas se escriben entre signos menor y mayor que y permiten definir diferentes partes de nuestro documento.
>
> Por ejemplo, la etiqueta H1 representa un encabezado principal o un título, mientras que la etiqueta P representa un párrafo, un contenido.
>
> Estos elementos utilizan una etiqueta de apertura y otra de cierre. La etiqueta de cierre se diferencia porque contiene una barra antes de su nombre.
>
> El segundo concepto es el elemento HTML. Un elemento está formado por su etiqueta de apertura, su contenido y, cuando corresponde, su etiqueta de cierre. Por ejemplo, nuestro párrafo completo representa un elemento HTML.
>
> Finalmente, tenemos los atributos. Los atributos proporcionan información adicional sobre el elemento. Un ejemplo es lang igual a es, que escribimos anteriormente para indicar el idioma de nuestro documento.
>
> Estos conceptos nos ayudarán a comprender cómo funcionan las instrucciones HTML."

### Bloque 7: Modificando nuestra página HTML (06:32 – 08:15)

- **[En pantalla]:** Volver al código de CodePen y realizar los cambios en las etiquetas `title`, `h1` y `p`. Mostrar cómo se actualiza la vista previa.
- **[Texto de apoyo visual]:**
    - `title → Título de la pestaña`
    - `h1 → Encabezado visible`
    - `p → Contenido del párrafo`
- **[Narración (Voz en off)]:**

> "Ahora, vamos a realizar algunos cambios para comprobar cómo funciona este documento.
>
> Primero vamos a buscar la etiqueta title y lo cambiaremos por 'Mi primera página'.
>
> Antes que nada tengo que explicar lo siguiente. En CodePen no podemos ver esta función, pero cuando ustedes quieran publicar una página web este apartado se mostrará en la parte de arriba, donde dice el título de la página.
>
> Si lo cambian, por ejemplo, de Twitter a X, dirá X arriba.
>
> Después nos dirigiremos al H1 y cambiaremos ese texto por algo como 'Hola, soy yo'. Observa la vista previa y se nota el cambio. Hola, soy yo."

### Bloque 8: Diferencias entre HEAD y BODY (08:15 – 09:03)

- **[En pantalla]:** Mostrar nuevamente el documento HTML y señalar las secciones HEAD y BODY. Diferenciar visualmente la información de configuración y el contenido visible.
- **[Texto de apoyo visual]:**
    - `HEAD = Información que no se muestra directamente`
    - `BODY = Contenido que ve el usuario`
- **[Narración (Voz en off)]:**

> "También podemos observar que el título de la pestaña corresponde al contenido que hemos cambiado. Por ejemplo, 'Me llamo José'. Y también cambia el párrafo.
>
> De esta manera podemos identificar cómo cada etiqueta cumple una función diferente dentro del HTML.
>
> La etiqueta head es la información que no vemos, la información que indica el tipo de lenguaje y el título de tu página. Mientras que el body es la que ve el usuario, como un título o un párrafo.
>
> Bueno, ahora ya conoces la estructura básica de una página HTML."

### Bloque 9: Pausa interactiva y cierre (09:03 – 09:30)

- **[En pantalla]:** Mostrar el código HTML final y resaltar el nombre Ana y el contenido del párrafo. Después, presentar el mensaje `¡PAUSA PARA PRACTICAR!`.
- **[Texto de apoyo visual]:**
    - `Reto 1: Cambia el nombre Ana por el tuyo.`
    - `Reto 2: Escribe un pequeño párrafo sobre ti.`
- **[Narración (Voz en off)]:**

> "Para poner en práctica lo aprendido, te propongo una actividad.
>
> Ingresa al enlace que encontrarás en la descripción de este video. Una vez dentro, cámbiale el nombre de Ana por el tuyo y escribe un pequeño párrafo sobre ti.
>
> Después, observa cómo se visualiza el resultado de tu página.
>
> Recuerda que practicar es fundamental para aprender programación.
>
> En la siguiente lección conocerás más etiquetas HTML para organizar textos, encabezados y listas. ¡Nos vemos en el próximo video!"

---

## Código de Referencia para la Lección

**Código de Inicio (Starter - Para el estudiante):**

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi primera página</title>
</head>
<body>
  <h1>¡Hola, mundo!</h1>
  <p>Me llamo Ana y estoy aprendiendo HTML.</p>
</body>
</html>
```

## Actividad de Práctica

**Reto de la Lección 2 — Mi primera página personal**

**Objetivo:** Personalizar un documento HTML modificando su título, encabezado y párrafo.

1. Abre el enlace de CodePen que se encuentra en la descripción del video.
2. Busca la etiqueta `<title>` y cambia el título de tu página.
3. Modifica el contenido de `<h1>` para escribir un saludo personalizado.
4. Cambia el nombre Ana por el tuyo.
5. Escribe un pequeño párrafo contando algo sobre ti.
6. Observa el resultado en la vista previa.

**Resultado esperado:** El estudiante reconoce la estructura básica de un documento HTML, identifica la función de las etiquetas `head` y `body`, diferencia etiquetas, elementos y atributos, y personaliza su primera página web utilizando HTML.