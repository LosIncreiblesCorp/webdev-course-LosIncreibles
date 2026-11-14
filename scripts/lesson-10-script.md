# Guion de la Lección 10: Errores Comunes en HTML y CSS

## Detalles de la Lección

- **Duración aproximada:** 7 minutos y 30 segundos
- **Público objetivo:** Estudiantes de secundaria (12 a 17 años)
- **Herramientas:** CodePen (editor en línea)
- **Lenguajes:** HTML y CSS
- **Tema:** Identificación y corrección de errores comunes.

---

## Objetivo de la Lección

Identificar y corregir cinco errores frecuentes al escribir código HTML y CSS. Aprenderemos a reconocer etiquetas sin cerrar, errores de sintaxis, imágenes sin texto alternativo, confusiones entre clases e identificadores y problemas al conectar archivos CSS.

Al finalizar, podremos revisar nuestro código de manera más ordenada y aplicar buenas prácticas para encontrar y solucionar errores.

---

## Estructura del Video

### 1. Introducción a los errores comunes (00:04 – 00:48)

**[En pantalla]**
- Mostrar la página de perfil personal de la lección anterior.
- Presentar el título: Cinco errores comunes en HTML y CSS.
- Mostrar brevemente los cinco errores que se revisarán.

**[Texto de apoyo visual]**
- Error 1: Etiqueta sin cerrar.
- Error 2: Falta de punto y coma.
- Error 3: Imagen sin `alt`.
- Error 4: Confundir `class` con `id`.
- Error 5: Nombre incorrecto del archivo CSS.

**[Narración (Voz en off)]**

¡Hola! En la lección anterior le dimos estilo a nuestra página de perfil y hoy vamos a aprender a identificar cinco errores comunes al escribir HTML y CSS.

En cada ejemplo veremos qué sucede en el navegador, buscaremos la causa en el código y corregiremos el problema.

De esta manera aprenderemos que equivocarse al programar es normal y que lo importante es saber cómo encontrar y solucionar esos errores.

¡Empecemos con el primero!

### 2. Error 1: Olvidar cerrar una etiqueta (00:48 – 01:44)

**[En pantalla]**
- Mostrar una frase donde aparece más texto en negrita del esperado.
- Abrir el código HTML.
- Identificar la etiqueta `strong` sin cerrar.
- Agregar `</strong>` después del nombre Ana.
- Actualizar la vista previa.

**[Texto de apoyo visual]**
- Etiqueta de apertura: `<strong>`
- Etiqueta de cierre: `</strong>`
- Recuerda cerrar las etiquetas.

**[Narración (Voz en off)]**

Primero, mira esta frase. Yo quería resaltar solamente el nombre de Ana, pero también aparece en negrita el texto Me gusta programar.

Si revisamos el código HTML, podemos ver que abrí la etiqueta `strong` antes del nombre Ana, pero olvidé indicar dónde termina.

Para corregirlo, vamos a escribir la etiqueta de cierre justo después del nombre.

Recuerda que para cerrar una etiqueta colocamos una barra antes de su nombre.

Ahora actualizamos la vista previa y podemos observar que Ana sigue en negrita, mientras que el resto de la frase volvió a tener su formato normal.

La etiqueta de cierre le indica al navegador hasta dónde llega el texto que queremos destacar.

### 3. Error 2: Olvidar el punto y coma en CSS (01:44 – 02:35)

**[En pantalla]**
- Mostrar un aviso que debería aparecer en rojo y con letra más grande.
- Abrir el archivo `style.css`.
- Identificar la falta del punto y coma después de `color: red`.
- Agregar el punto y coma.
- Actualizar la página.

**[Texto de apoyo visual]**
- `color: red;`
- `font-size: 18px;`
- No olvides el punto y coma al finalizar cada declaración.

**[Narración (Voz en off)]**

Para el segundo error vamos a nuestro archivo de estilos CSS.

Aquí tenemos un aviso que debería aparecer en rojo y con un tamaño de letra más grande, pero no se está mostrando como esperamos.

Si revisamos el código, encontramos dos propiedades: una para el color y otra para el tamaño de fuente.

El problema es que después de `red` falta colocar el punto y coma.

Este separador permite distinguir una declaración CSS de la siguiente. Si lo olvidamos, el navegador puede interpretar incorrectamente las propiedades.

Vamos a agregar el punto y coma y actualizar la página.

¡Ahora sí! El aviso aparece en rojo y con una letra más grande.

Recuerda que, si un estilo no se aplica, también conviene revisar la línea anterior.

### 4. Error 3: Olvidar el texto alternativo de una imagen (02:35 – 04:30)

**[En pantalla]**
- Mostrar una imagen que aparece correctamente.
- Revisar el código HTML y señalar que falta `alt`.
- Agregar una descripción breve.
- Mostrar qué sucede cuando se utiliza una dirección incorrecta para la imagen.
- Restaurar la dirección original.

**[Texto de apoyo visual]**
- `src`: dirección de la imagen.
- `alt`: descripción alternativa.
- Ayuda a comprender el contenido de una imagen cuando no puede visualizarse.

**[Narración (Voz en off)]**

El tercer error es olvidar el texto alternativo de una imagen.

En este ejemplo podemos observar que la imagen aparece correctamente porque tenemos la dirección indicada en el atributo `src`.

Sin embargo, falta el atributo `alt`.

Este atributo permite proporcionar una descripción de la imagen para las personas que utilizan lectores de pantalla. También puede mostrar un texto alternativo cuando la imagen no carga correctamente.

Vamos a agregar una descripción breve de lo que aparece en la fotografía. En este caso escribiremos Imagen de unas montañas nevadas.

Fíjate que la imagen conserva prácticamente el mismo aspecto. La mejora está en que ahora tenemos una descripción en texto.

Para comprobarlo, vamos a cambiar temporalmente la dirección de la imagen por una que no sea válida.

Guardamos y recargamos. Ahora podemos observar que aparece el texto alternativo, que nos ayuda a entender qué mostraba la imagen.

Finalmente, restauramos la dirección original para dejar nuestro ejemplo como estaba.

### 5. Error 4: Confundir una clase con un ID (04:30 – 05:17)

**[En pantalla]**
- Mostrar un párrafo que debería tener un fondo amarillo.
- Revisar el HTML y encontrar `class="destacado"`.
- Abrir el CSS y señalar el selector `#destacado`.
- Cambiar `#` por `.`.
- Actualizar la página.

**[Texto de apoyo visual]**
- `.destacado`: selector de clase.
- `#titulo`: selector de ID.
- Clase: puede utilizarse en varios elementos.
- ID: identifica un elemento de la página.

**[Narración (Voz en off)]**

Para el cuarto error, vamos a revisar un problema que ocurre cuando confundimos una clase con un ID.

Este párrafo debería tener un fondo amarillo, pero no está recibiendo el estilo.

En el HTML podemos observar que le asignamos la clase `destacado`.

Ahora vamos al CSS y buscamos el selector correspondiente. Aquí encontramos el problema: escribimos `#destacado`, pero el símbolo numeral se utiliza para seleccionar elementos por su ID.

Como nuestro elemento tiene una clase, debemos cambiar el numeral por un punto.

Guardamos y actualizamos la página. ¡Ahora sí! El fondo amarillo aparece correctamente.

Recuerda que una clase puede utilizarse en varios elementos, mientras que un mismo ID debe identificar a un solo elemento de la página.

### 6. Error 5: Escribir incorrectamente el nombre del archivo CSS (05:17 – 05:59)

**[En pantalla]**
- Mostrar la página con todos sus estilos.
- Abrir `index.html`.
- Localizar la etiqueta `link`.
- Cambiar temporalmente `style.css` por `estilos.css`.
- Actualizar y mostrar cómo desaparecen los estilos.
- Restaurar el nombre correcto.

**[Texto de apoyo visual]**
- `href="style.css"`
- El nombre y la ruta deben coincidir con el archivo real.

**[Narración (Voz en off)]**

Y ahora vamos con el quinto y último error.

Imagina que de pronto desaparecen todos los estilos de tu página.

En el encabezado del HTML tenemos la etiqueta `link`, que le indica al navegador qué archivo CSS debe cargar.

Vamos a cambiar temporalmente el nombre `style.css` por `estilos.css` y recargar la página.

Como podemos observar, desaparecieron el fondo celeste y los demás estilos que habíamos agregado.

¿Qué sucedió? El navegador buscó un archivo llamado `estilos.css`, pero nuestro archivo real se llama `style.css`.

Para solucionarlo, restauramos el nombre anterior y actualizamos nuevamente.

¡Listo! Los estilos vuelven a aparecer.

Si te sucede algo parecido, recuerda comprobar que el nombre y la ruta del archivo coincidan exactamente.

### 7. Buenas prácticas para evitar errores (05:59 – 06:46)

**[En pantalla]**
- Mostrar una lista de recomendaciones.
- Señalar la importancia de cambiar una cosa a la vez.
- Mostrar ejemplos de código con sangría.
- Resaltar nombres descriptivos para las clases.

**[Texto de apoyo visual]**
- Cambia una cosa a la vez.
- Revisa el código y la vista previa.
- Utiliza sangría.
- Elige nombres descriptivos.
- Comprueba las conexiones entre archivos.

**[Narración (Voz en off)]**

Antes de terminar, vamos a recordar algunas buenas prácticas.

Cuando algo no se ve como esperabas, cambia una cosa a la vez y revisa el resultado.

Si el problema está en un texto, revisa primero la etiqueta HTML y el selector CSS que aplica el estilo.

Si desapareció el diseño de toda la página, empieza revisando el enlace al archivo CSS.

También es importante utilizar sangría para identificar qué etiquetas están dentro de otras y elegir nombres de clases que expliquen para qué sirven.

Estas pequeñas prácticas nos ayudarán a escribir código más ordenado y encontrar errores con mayor facilidad.

### 8. Actividad final y cierre del curso (06:46 – 07:24)

**[En pantalla]**
- Mostrar nuevamente los cinco errores.
- Elegir uno de los ejemplos.
- Introducir un error intencionalmente.
- Pedir al estudiante que prediga el resultado y después lo corrija.
- Mostrar posibles temas para seguir aprendiendo.

**[Texto de apoyo visual]**
- ¡Pon a prueba lo aprendido!
- Introduce un error.
- Predice qué sucederá.
- Encuentra la causa y corrígelo.

**[Narración (Voz en off)]**

Ahora te toca practicar.

Elige uno de estos ejemplos, introduce un error intencionalmente e intenta predecir qué sucederá en el navegador.

Después, revisa el código y trata de encontrar la causa para corregirlo.

Si quieres seguir aprendiendo, puedes explorar el diseño adaptable para que tus páginas se vean bien en celulares, aprender JavaScript para añadir interacciones o publicar tu primera página para compartirla.

¡Gracias por acompañarme en esta última lección!

---

## Ejemplos de Código

### Error 1: Olvidar cerrar una etiqueta

**Incorrecto:**

```html
<p>Hola, soy <strong>Ana y me gusta programar.</p>
```

**Correcto:**

```html
<p>Hola, soy <strong>Ana</strong> y me gusta programar.</p>
```

### Error 2: Olvidar el punto y coma en CSS

**Incorrecto:**

```css
p {
  color: red
  font-size: 18px;
}
```

**Correcto:**

```css
p {
  color: red;
  font-size: 18px;
}
```

### Error 3: Imagen sin atributo `alt`

**Incorrecto:**

```html
<img src="foto.jpg">
```

**Correcto:**

```html
<img src="foto.jpg" alt="Foto de mi mascota">
```

### Error 4: Confundir `class` con `id`

**HTML:**

```html
<p class="destacado">Este texto es importante.</p>
```

**Incorrecto en CSS:**

```css
#destacado {
  background-color: yellow;
}
```

**Correcto en CSS:**

```css
.destacado {
  background-color: yellow;
}
```

### Error 5: Escribir mal el nombre del archivo CSS

**Incorrecto:**

```html
<link rel="stylesheet" href="estilos.css">
```

**Correcto:**

```html
<link rel="stylesheet" href="style.css">
```

---

## Cheatsheet de HTML y CSS

Esta tabla reúne algunas de las etiquetas y propiedades que utilizamos durante el curso. Puedes consultarla cuando necesites recordar cómo escribirlas.

### Etiquetas HTML

| Etiqueta | Uso |
|---|---|
| `h1` a `h6` | Encabezados. |
| `p` | Párrafos. |
| `strong` | Resalta texto importante. |
| `em` | Da énfasis al texto. |
| `ul`, `ol`, `li` | Creación de listas. |
| `img` | Inserta imágenes. |
| `a` | Crea enlaces. |
| `div` | Agrupa contenido en un contenedor genérico. |
| `header` | Encabezado de la página. |
| `main` | Contenido principal. |
| `section` | Sección de contenido. |
| `footer` | Pie de página. |

### Atributos HTML

| Atributo | Uso |
|---|---|
| `src` | Indica la dirección de una imagen. |
| `alt` | Proporciona una descripción alternativa. |
| `href` | Indica el destino de un enlace. |
| `target` | Define dónde se abre un enlace. |
| `class` | Asigna una clase a uno o varios elementos. |
| `id` | Identifica un elemento de la página. |
| `width` | Establece el ancho de un elemento. |

### Propiedades CSS

| Propiedad | Uso |
|---|---|
| `color` | Cambia el color del texto. |
| `background-color` | Cambia el color de fondo. |
| `font-family` | Define el tipo de letra. |
| `font-size` | Cambia el tamaño del texto. |
| `font-weight` | Controla el grosor de la letra. |
| `text-decoration` | Modifica la decoración del texto. |
| `border` | Agrega un borde. |
| `border-radius` | Redondea las esquinas. |
| `margin` | Controla el espacio exterior. |
| `padding` | Controla el espacio interior. |
| `text-align` | Alinea el texto. |
| `max-width` | Establece un ancho máximo. |
| `display: flex` | Organiza elementos mediante Flexbox. |
| `justify-content` | Distribuye elementos en el eje principal de Flexbox. |
| `align-items` | Alinea elementos en el eje transversal de Flexbox. |
| `gap` | Define el espacio entre elementos. |

---

## Actividad Práctica — Encuentra y corrige el error

**Objetivo:** Aplicar lo aprendido identificando errores en fragmentos de HTML y CSS.

**Instrucciones:**

1. Selecciona uno de los cinco errores de la lección.
2. Escribe una versión incorrecta del código.
3. Antes de ejecutarlo, intenta predecir qué sucederá.
4. Comprueba el resultado en CodePen.
5. Identifica qué parte del código provoca el problema.
6. Corrige el error y verifica que funcione correctamente.

**Reto adicional:**

Crea un pequeño documento HTML que contenga un título, una imagen, un párrafo y un enlace. Después, introduce intencionalmente dos errores diferentes e intenta encontrarlos sin consultar la solución.

**Resultado esperado:** Un documento HTML y CSS funcional, con los errores identificados y corregidos.

---

## ¡Felicidades por completar el curso!

Has llegado al final de este curso de Fundamentos de Desarrollo Web para Principiantes.

Durante las diez lecciones aprendiste a construir páginas web utilizando HTML y CSS, desde la estructura básica de un documento hasta la creación y personalización de una página de perfil personal.

Ahora tienes una base para continuar explorando el desarrollo web y construir tus propios proyectos.

¡Sigue practicando y creando!