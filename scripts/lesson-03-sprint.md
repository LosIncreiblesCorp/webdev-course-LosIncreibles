# Guion de la Lección 3: Organización de Textos, Encabezados y Listas en HTML

## Detalles de la Lección

- **Duración aproximada:** 16 minutos.
- **Público objetivo:** Estudiantes de secundaria (12 a 17 años).
- **Herramientas:** Navegador web y CodePen (100% en línea).
- **Lenguaje:** HTML.

---

## Estructura del Video

### Bloque 1: Introducción a la organización del contenido (00:00 – 00:39)

- **[En pantalla]:** Mostrar unos apuntes organizados con títulos, subtítulos, párrafos y listas. Después, realizar una transición hacia una página web.
- **[Texto de apoyo visual]:**
    - `Contenido organizado = Fácil de leer`
    - `Encabezados + Párrafos + Listas`
- **[Narración (Voz en off)]:**

> "Mira, estos apuntes de clase. Tienen un título grande, subtítulos más pequeños, párrafos de texto e incluso una lista. Gracias a esta organización es fácil encontrar lo que uno busca.
>
> Con las páginas web pasa exactamente lo mismo. El contenido tiene que estar completamente ordenado, tanto para quien lo lee como para los buscadores.
>
> Hoy aprenderás las etiquetas HTML para organizar un texto con encabezados, párrafos y listas."

### Bloque 2: Los seis niveles de encabezados HTML (00:39 – 01:26)

- **[En pantalla]:** Mostrar los seis niveles de encabezados HTML, desde H1 hasta H6, utilizando ejemplos de diferentes tamaños.
- **[Texto de apoyo visual]:**
    - `H1 → Título principal`
    - `H2 → Subtítulos`
    - `H3 → Subtítulos secundarios`
    - `H4, H5 y H6 → Niveles adicionales`
- **[Narración (Voz en off)]:**

> "Antes de ir a nuestro apartado HTML, quiero hacer un pequeño énfasis en los encabezados, ya que puede ser un poco confuso, pues notamos que tenemos del H1 a H6.
>
> En total tenemos seis niveles de encabezados, como hemos visto: H1, H2, H3, H4, H5 y H6.
>
> Son los títulos y subtítulos. Y como vemos, hay seis niveles del H1 al H6.
>
> El H1 es el título principal y es el más importante y más grande. Como regla general, se usa solo un H1 por página.
>
> ¿Qué será el título principal? Los H2 son subtítulos. Los H3 son subtítulos de los subtítulos y así sucesivamente.
>
> Vamos a continuación, ahora sí, a pasar a nuestro HTML escribiendo una página sobre nuestra mascota."

### Bloque 3: Creando una página sobre nuestra mascota (01:26 – 02:45)

- **[En pantalla]:** Mostrar el panel HTML de CodePen y comenzar a escribir el encabezado principal y el primer subtítulo. Mantener visible la vista previa.
- **[Texto de apoyo visual]:**
    - `<h1> → Título principal`
    - `<h2> → Subtítulo`
    - `Una página debe tener una estructura organizada`
- **[Narración (Voz en off)]:**

> "Bien, nos encontramos en nuestro HTML. A continuación vamos a escribir el código de nuestra página web.
>
> Vamos a empezar abriendo nuestra etiqueta de H1 para ingresar nuestro encabezado.
>
> Como he dicho, nuestra página web va a hablar acerca de nuestra mascota. Por ende, vamos a escribir como título 'Mi mascota'. Nosotros podemos escribirlo de la forma que deseamos. En este caso puede ser, por ejemplo, con mayúsculas para que se note o en minúsculas.
>
> A continuación, como estamos hablando de nuestra mascota, yo creo que sería pertinente que demos algunos datos básicos de nuestra mascota.
>
> En este caso, por ejemplo, podemos entregar el nombre, pero ojo, como los datos básicos son un subtema de nuestro tema principal, que es mi mascota, lo estamos considerando como un H2, con un nivel de encabezado de H2.
>
> Además, recordemos que el H1 solo se puede usar una única vez por página.
>
> Y miremos el lado derecho de nuestra pantalla. Se ha escrito correctamente 'Mi mascota' y un poco más abajo 'Datos básicos'."

### Bloque 4: Creando párrafos y resaltando palabras importantes (02:45 – 06:07)

- **[En pantalla]:** Escribir la etiqueta `<p>` para agregar una descripción de Rocky. Después, seleccionar su nombre y envolverlo con `<strong>`. Finalmente, mostrar un ejemplo de la etiqueta `<em>`.
- **[Texto de apoyo visual]:**
    - `<p> → Párrafo`
    - `<strong> → Importancia o relevancia`
    - `<em> → Énfasis`
    - `HTML permite organizar y destacar información`
- **[Narración (Voz en off)]:**

> "Vamos a ver qué ocurre si damos ahora, no vamos a ingresar un H3, sino una nueva etiqueta, que es la letra P.
>
> P va a ser la etiqueta para nuestros párrafos y la vamos a usar cuando necesitemos dar una descripción un poco larga acerca del contenido.
>
> En este caso, como son unos datos básicos, vamos a dar algunas características de nuestra mascota.
>
> En mi caso, yo tengo un perro el cual se llama Rocky y le gusta correr. Entonces, ello puede ser un buen contenido para considerar dentro de nuestro párrafo.
>
> Vamos a escribir a continuación: 'Mi perro se llama Rocky y le gusta correr'.
>
> Vamos a esperar un momento a que carguen los resultados en la pantalla. Y como se puede apreciar, ya están disponibles. Aparece de manera exitosa un texto que indica: 'Mi perro se llama Rocky y le gusta correr'.
>
> Además, se denota que tiene un tamaño de letra un poco más bajo que el anterior encabezado. Este tamaño de letra es uniforme en todos los párrafos, a menos que se edite posteriormente en un CSS que ya se verá más adelante en el curso.
>
> Como ya podemos apreciar en la vista previa, el título es grande, el subtítulo es un poco más pequeño y el párrafo es de texto normal.
>
> Un detalle importante es que no uses los encabezados solo para hacer el texto más grande. Se usan por su significado para indicar la importancia de cada parte.
>
> A continuación vamos a aprender cómo resaltar el texto.
>
> En nuestra última línea hemos escrito: 'Mi perro se llama Rocky y le gusta correr'. Si yo quisiera resaltar que mi perro se llama Rocky, podemos resaltar la palabra Rocky.
>
> Si quieres resaltar una palabra importante dentro de un párrafo, es muy sencillo. Se tiene que utilizar la etiqueta strong, que significa fuerte.
>
> Encierro la palabra que quiero resaltar, en este caso Rocky, entre una etiqueta de apertura y cierre strong.
>
> Al escribir strong automáticamente me dan la etiqueta abierta y cerrada, pero nosotros queremos dentro de esta etiqueta escribir el nombre de nuestra mascota para resaltarla, que era Rocky.
>
> Entonces vamos a pegarlo y nos damos cuenta de que en el párrafo se ha editado correctamente. Rocky ahora aparece con negrita. Mira la vista previa.
>
> También existe la etiqueta em, que da énfasis y normalmente muestra el texto en cursiva. Puedes utilizarla también dentro de cualquier párrafo, igual que subrayas con un marcador lo más importante en tus apuntes."

### Bloque 5: Conociendo los tipos de listas en HTML (06:07 – 07:38)

- **[En pantalla]:** Mostrar dos ejemplos de listas: una con viñetas y otra numerada. Señalar las etiquetas `ul`, `ol` y `li`.
- **[Texto de apoyo visual]:**
    - `UL → Lista sin orden`
    - `OL → Lista ordenada`
    - `LI → Elemento de una lista`
- **[Narración (Voz en off)]:**

> "Ahora, hasta este punto ya hemos aprendido un poco de norma general sobre los encabezados, los párrafos y cómo resaltar algunas palabras que nosotros consideremos importantes dentro de nuestra página.
>
> Ahora vamos a hablar de las listas. Existen dos tipos.
>
> La primera es la lista con viñetas, que se realiza de la siguiente forma, abriendo la etiqueta UL.
>
> Se llama UL, ya que viene del inglés unordered list, es decir, lista sin orden. Se usa cuando el orden no importa, como una lista de juegos favoritos o algún otro elemento que no tenga jerarquía.
>
> Y por otro lado tenemos OL, que también viene del inglés ordered list, que se traduce como lista ordenada y se usa cuando el orden sí importa.
>
> Cada elemento va en una etiqueta LI, que significa list item."

### Bloque 6: Creando una lista con viñetas: Juegos favoritos (07:38 – 09:38)

- **[En pantalla]:** Agregar un nuevo encabezado H2 llamado "Sus juegos favoritos". Después, abrir la etiqueta `ul` y escribir progresivamente cada elemento con `li`. Mostrar el resultado en la vista previa.
- **[Texto de apoyo visual]:**
    - `<h2> → Sus juegos favoritos`
    - `<ul> → Lista con viñetas`
    - `<li> → Cada elemento de la lista`
- **[Narración (Voz en off)]:**

> "Vamos a aplicar esta teoría que les estoy brindando a través de código.
>
> Vamos a seguir con la idea de nuestro perrito. En este caso vamos a escribir sus juegos favoritos.
>
> Vamos a abrir un nuevo encabezado de H2 y vamos a escribir 'Sus juegos favoritos'.
>
> Vamos a usar la etiqueta unordered list porque realmente no tiene una jerarquía o no queremos enumerar los juegos favoritos de nuestra mascota. Simplemente son actividades que podemos enumerar sin una jerarquía como tal.
>
> Y aquí viene lo importante. Dentro de una lista es importante enlistar cada uno de los apartados que vamos a colocar.
>
> Por ende, una vez abierta nuestra etiqueta unordered list, vamos a abrir otra que es list item, que mencioné anteriormente.
>
> Dentro del list item podemos escribir nuestro item, en este caso, el juego favorito que tiene nuestra mascota Rocky.
>
> A Rocky, en mi caso, le gusta, por ejemplo, buscar la pelota.
>
> Vamos a escribirla como un item dentro de sus juegos favoritos: 'Buscar la pelota'.
>
> Y vemos cómo se ha añadido automáticamente en nuestra pantalla.
>
> Vamos a seguir con el resto de actividades que le gustan a nuestra mascota, en este caso correr en el parque.
>
> Y también le gusta dormir bajo el sol.
>
> Entonces, como vemos en la pantalla, ya tenemos en nuestra página web acerca de nuestra mascota sus datos básicos, una descripción de Rocky y sus juegos favoritos, que están ordenados con viñetas.
>
> En este caso son tres apartados o items: buscar la pelota, correr en el parque y dormir bajo el sol."

### Bloque 7: Creando una lista ordenada: La rutina de nuestra mascota (09:38 – 11:59)

- **[En pantalla]:** Mostrar la explicación de las listas ordenadas. Después, agregar el encabezado H2 "Su rutina" y crear una lista utilizando las etiquetas `ol` y `li`.
- **[Texto de apoyo visual]:**
    - `OL → Lista numerada`
    - `LI → Elementos de la lista`
    - `1. Desayuno`
    - `2. Paseo`
    - `3. Siesta`
- **[Narración (Voz en off)]:**

> "Ahora vamos a seguir. Tenemos además otro tipo de listas.
>
> El segundo tipo de lista es la lista numerada, que se llama OL o que proviene del inglés ordered list, que se traduce como lista ordenada y se usa cuando el orden sí importa, como los pasos de una receta o la rutina de un día.
>
> Y aquí los elementos también van con list item, pero ahora va a haber una gran diferencia a la hora de escribirlos, pues nos vamos a dar cuenta de que, cuando aparezcan en nuestra página web, van a estar numerados automáticamente, empezando por el uno y así sucesivamente.
>
> Voy a continuación a mostrar cómo luciría esto en nuestro código.
>
> Ahora vamos a hablar, por ejemplo, de su rutina. Vamos a poner un H2 para hablar de su rutina.
>
> Nos damos cuenta de que también aparece en nuestra página como el encabezado respectivo.
>
> Vamos a abrir una ordered list. Una vez tenemos la ordered list, vamos a poner nuestros items con la etiqueta list item.
>
> Vamos a poner que su rutina consiste en primero, el desayuno. Como segunda actividad tenemos su paseo y como tercera actividad dentro de su rutina tenemos que hace su siesta.
>
> Si nos damos cuenta, ahora en nuestra pantalla aparecen enumerados automáticamente y esa es la magia de ordered list.
>
> Nos permite, además de enlistar, darles un orden enumerado, lo cual nos puede servir para dar una jerarquía o determinar cuándo tienen una secuencia ordenada los pasos que se van a manejar."

### Bloque 8: Pausa interactiva: Mis tres comidas favoritas (11:59 – 13:42)

- **[En pantalla]:** Mostrar el mensaje `¡PAUSA PARA PRACTICAR!`. Después, presentar el reto con dos apartados: lista con viñetas y lista ordenada.
- **[Texto de apoyo visual]:**
    - `Reto: Mis tres comidas favoritas`
    - `Parte 1: Lista con viñetas`
    - `Parte 2: Lista ordenada de mayor a menor preferencia`
- **[Narración (Voz en off)]:**

> "A continuación, listo, llegó la hora de su práctica.
>
> Los reto a hacer una lista con sus tres comidas favoritas.
>
> Los voy a ayudar un poco. Vamos a iniciar, como ya hemos aprendido, dentro del body, escribiendo 'Mis comidas favoritas'.
>
> Ahora es su turno de ustedes. Por favor, enlístenme una lista con viñetas de sus tres comidas favoritas.
>
> Y abajo quiero que esas mismas tres comidas favoritas las cambien con una lista ordenada, indicando cuál les gusta más hasta cuál les gusta menos.
>
> Pausa el video y prueba por tu cuenta resolver este apartado, este reto que les estamos dejando."

### Bloque 9: Resolución del reto y ejemplo práctico (13:42 – 15:59)

- **[En pantalla]:** Volver al editor HTML y resolver el reto. Primero crear la lista con viñetas y después la lista ordenada. Mostrar el resultado final en la vista previa.
- **[Texto de apoyo visual]:**
    - `Lista con viñetas: UL`
    - `Lista ordenada: OL`
    - `Elementos: LI`
- **[Narración (Voz en off)]:**

> "Listo, ¿lo consiguieron? Bueno, de ser el caso, espero que su solución sea muy similar a la mía y si no, ya veremos, estaremos juntos en el proceso para poder realizar nuestra actividad.
>
> Recordemos que lo que dijimos fue escribir una lista con viñetas de sus tres comidas.
>
> En este caso, con viñetas era la palabra clave, porque eso significa una unordered list. Y dentro de ella, los list items.
>
> En mi caso, a mí me gusta, por ejemplo, el arroz verde, me gusta el ají de gallina y, por último, también me gusta el lomo saltado.
>
> Esas son mis comidas favoritas y se pueden ver en nuestra pantalla.
>
> Y la segunda parte del reto consistía básicamente en que estas tres comidas favoritas que hemos enumerado vamos a tener que ordenarlas de nuestra favorita a nuestra menos favorita.
>
> Vamos a empezar especificando que vamos a trabajar con una ordered list y luego vamos a enlistar nuestros items, en este caso mis comidas.
>
> De estas tres antes mencionadas, mi favorita definitivamente es el lomo saltado. Mi segunda comida favorita de esta lista es el ají de gallina. Y mi tercera comida favorita es el arroz verde.
>
> Entonces, así quedó nuestro reto finalizado.
>
> Mis tres comidas favoritas son el arroz verde, el ají de gallina y el lomo saltado. Y mis comidas favoritas ordenadas son el lomo saltado en primer lugar, el ají de gallina en segundo lugar y en tercer lugar el arroz verde.
>
> Muy bien. En este punto ya sabes organizar un texto con encabezados, párrafos, resaltados y listas.
>
> Recuerda que las etiquetas se abren y se cierran.
>
> En el próximo video agregarás imágenes y enlaces para que tu página se vea mucho más interesante."

---

## Código de Referencia para la Lección

**Código de Inicio (Starter - Para el estudiante):**

```html
<h1>Mi mascota</h1>

<h2>Datos básicos</h2>
<p>Mi perro se llama <strong>Rocky</strong> y le gusta correr.</p>

<h2>Sus juegos favoritos</h2>
<ul>
  <li>Buscar la pelota</li>
  <li>Correr en el parque</li>
  <li>Dormir al sol</li>
</ul>

<h2>Su rutina</h2>
<ol>
  <li>Desayuno</li>
  <li>Paseo</li>
  <li>Siesta</li>
</ol>
```

## Actividad de Práctica

**Reto de la Lección 3 — Mis tres comidas favoritas**

**Objetivo:** Organizar información utilizando encabezados, párrafos y listas con viñetas y numeradas.

**Parte 1: Lista con viñetas**

1. Crea un encabezado con el texto "Mis comidas favoritas".
2. Utiliza la etiqueta `<ul>` para crear una lista con viñetas.
3. Agrega tres de tus comidas favoritas utilizando la etiqueta `<li>`.

**Parte 2: Lista ordenada**

1. Debajo de la primera lista, crea otro encabezado llamado "Mi ranking de comidas".
2. Utiliza la etiqueta `<ol>` para crear una lista ordenada.
3. Agrega las mismas tres comidas utilizando `<li>`.
4. Organízalas desde tu comida favorita hasta la que menos te gusta.

**Resultado esperado:** El estudiante identifica los seis niveles de encabezados HTML, utiliza párrafos para organizar información, reconoce las etiquetas `strong` y `em` para destacar contenido y construye listas con viñetas y listas numeradas mediante `ul`, `ol` y `li`.