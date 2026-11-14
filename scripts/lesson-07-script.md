# Guion de la Lección 7: Modelo de Caja, Centrado y Flexbox con CSS

## Detalles de la Lección

- **Duración aproximada:** 9 minutos
- **Público objetivo:** Estudiantes de secundaria (12 a 17 años)
- **Herramientas:** CodePen (100% en línea)
- **Lenguajes:** HTML y CSS

---

## Estructura del Video

### 1. Introducción al modelo de caja (00:00 – 01:26)

- **[En pantalla]** Mostrar un dibujo del modelo de caja CSS con sus diferentes capas: contenido, padding, border y margin.

- **[Texto de apoyo visual]**
    - Cada elemento HTML es una caja rectangular.
    - Content: contenido.
    - Padding: espacio interior.
    - Border: borde.
    - Margin: espacio exterior.

- **[Narración (Voz en off)]**

  ¡Hola! Existe una pregunta muy conocida entre quienes están aprendiendo CSS: ¿cómo centro esto?

  Aunque parezca sencillo, incluso los programadores con experiencia suelen buscar diferentes formas de centrar elementos.

  En esta lección aprenderemos algunas de las formas más útiles para organizar y centrar el contenido de una página web.

  Primero, debemos comprender un concepto fundamental: cada elemento de una página puede entenderse como una caja rectangular.

  Esta caja tiene diferentes capas.

  En el centro encontramos el contenido, que puede ser un texto o una imagen.

  Alrededor tenemos el `padding`, que representa el espacio interior entre el contenido y el borde.

  Después encontramos el `border`, que es el borde de la caja.

  Finalmente, tenemos el `margin`, que representa el espacio exterior y permite separar una caja de los demás elementos.

  Para recordarlo fácilmente, el padding es como el acolchado que se encuentra dentro de una caja de regalo, mientras que el margin es la distancia que existe entre dos cajas colocadas una al lado de la otra.

  Ambas propiedades pueden medirse en píxeles y utilizarse con una o dos medidas.

  Por ejemplo, `margin: 20px` aplica el mismo espacio en los cuatro lados, mientras que `margin: 20px auto` establece 20 píxeles arriba y abajo y deja que el navegador distribuya automáticamente el espacio horizontal.

### 2. Creando un contenedor HTML (01:26 – 02:48)

- **[En pantalla]** Abrir CodePen y crear un `div` con la clase `contenedor`. Dentro agregar un título `h1` y un párrafo `p`.

- **[Texto de apoyo visual]**
    - `<div>`: crea un contenedor.
    - `class="contenedor"`: identifica el contenedor.
    - `<h1>`: título principal.
    - `<p>`: párrafo.

- **[Narración (Voz en off)]**

  Ahora vamos a nuestro editor CodePen para poner en práctica estos conceptos.

  En el panel HTML, dentro del `body`, vamos a crear una caja utilizando la etiqueta `div`.

  Le asignaremos la clase `contenedor`, para poder identificarla y personalizarla desde CSS.

  Dentro de esta caja agregaremos un título utilizando `h1` y un párrafo utilizando `p`.

  De esta manera tendremos un contenedor con dos elementos que podremos organizar y centrar.

### 3. Centrar texto y una caja completa (02:48 – 03:37)

- **[En pantalla]** Agregar las propiedades `text-align`, `max-width` y `margin` al selector `.contenedor`.

- **[Texto de apoyo visual]**
    - `text-align: center;` centra el texto.
    - `max-width: 400px;` establece un ancho máximo.
    - `margin: 20px auto;` centra horizontalmente el bloque.

- **[Narración (Voz en off)]**

  Primero vamos a aprender a centrar el texto dentro de una caja.

  Para hacerlo, utilizamos la propiedad `text-align` con el valor `center`.

  Así, todo el texto que se encuentre dentro del contenedor quedará centrado.

  Pero ¿qué pasa si queremos centrar la caja completa?

  Para conseguirlo necesitamos dos cosas.

  Primero, debemos establecer un ancho máximo utilizando `max-width`. En nuestro ejemplo colocaremos `400px`, para que la caja no ocupe todo el ancho disponible de la pantalla.

  Después utilizaremos `margin: 20px auto`.

  Esto significa que tendremos 20 píxeles de espacio arriba y abajo, mientras que el navegador distribuirá automáticamente el espacio sobrante a la izquierda y a la derecha.

  De esta manera, nuestra caja quedará centrada horizontalmente.

  Para visualizar mejor el resultado, podemos agregar un color de fondo utilizando `background-color`.

### 4. Organizando varias cajas con Flexbox (03:37 – 04:48)

- **[En pantalla]** Crear un nuevo contenedor con la clase `fila` y agregar tres elementos `div` con la clase `caja`.

- **[Texto de apoyo visual]**
    - `display: flex;`
    - Organiza los elementos en una fila.
    - Permite distribuir varias cajas dentro de un contenedor.

- **[Narración (Voz en off)]**

  Ahora vamos a aprender cómo colocar varias cajas una al lado de la otra.

  Normalmente, los elementos de tipo bloque se colocan uno debajo del otro.

  Sin embargo, CSS tiene una herramienta llamada Flexbox que nos permite organizar los elementos de una manera más flexible.

  Para comenzar, vamos a crear un nuevo `div` con la clase `fila`.

  Dentro de este contenedor agregaremos tres cajas, cada una con la clase `caja`.

  Ahora nos dirigimos al panel CSS y seleccionamos `.fila`.

  Dentro de sus llaves escribimos `display: flex`.

  Con esta propiedad, los elementos que están dentro del contenedor pasarán a organizarse en una fila.

### 5. Centrando y separando las cajas con Flexbox (04:48 – 06:18)

- **[En pantalla]** Agregar `justify-content: center` y `gap: 12px` al selector `.fila`.

- **[Texto de apoyo visual]**
    - `display: flex;`: activa Flexbox.
    - `justify-content: center;`: centra los elementos en el eje principal.
    - `gap: 12px;`: establece una separación entre las cajas.

- **[Narración (Voz en off)]**

  Ahora que nuestras tres cajas están en una fila, podemos controlar cómo se distribuyen.

  Para centrarlas horizontalmente utilizaremos `justify-content` con el valor `center`.

  De esta manera, las cajas quedarán agrupadas en el centro del contenedor.

  También podemos establecer una separación entre ellas utilizando la propiedad `gap`.

  Vamos a colocar `gap: 12px`, para dejar doce píxeles de espacio entre cada caja.

  Como pueden observar, ahora tenemos tres cajas organizadas en una fila, centradas y con una separación uniforme.

  También podemos probar otros valores de `justify-content`, como `space-between`, que distribuye el espacio disponible entre los elementos.

### 6. Centrando el contenido dentro de cada caja (06:18 – 07:00)

- **[En pantalla]** Seleccionar `.caja` y mostrar las propiedades `display: flex`, `align-items` y `justify-content`.

- **[Texto de apoyo visual]**
    - `align-items: center;`: centra en el eje transversal.
    - `justify-content: center;`: centra en el eje principal.
    - Flexbox también puede utilizarse dentro de cada caja.

- **[Narración (Voz en off)]**

  Ahora vamos a centrar el contenido que se encuentra dentro de cada caja.

  Para ello, también podemos utilizar Flexbox directamente en el selector `.caja`.

  Primero escribimos `display: flex`.

  Después agregamos `align-items: center` y `justify-content: center`.

  De esta manera, el número que se encuentra dentro de cada caja quedará centrado tanto vertical como horizontalmente.

  Como pueden observar, Flexbox no solamente sirve para organizar varias cajas, sino también para alinear el contenido que se encuentra dentro de ellas.

### 7. Actividad de práctica (07:00 – 08:45)

- **[En pantalla]** Mostrar el resultado de los contenedores y dejar visible el código HTML y CSS.

- **[Texto de apoyo visual]**
    - Agrega una cuarta caja.
    - Prueba diferentes valores de `justify-content`.
    - Modifica `margin`.
    - Modifica `padding`.
    - Observa las diferencias entre el espacio interior y exterior.

- **[Narración (Voz en off)]**

  Ahora te toca practicar.

  Primero, agrega una cuarta caja a la fila y observa cómo cambia la distribución.

  Después, prueba diferentes valores de `justify-content` y observa cómo se organizan los elementos.

  Por último, modifica el `margin` y el `padding` del contenedor y fíjate en la diferencia entre el espacio interior y el espacio exterior.

  Puedes pausar el video y experimentar con diferentes valores hasta encontrar la distribución que más te guste.

  ¡Excelente! Ahora ya conoces las herramientas necesarias para organizar los elementos de tu página.

### 8. Cierre de la lección (08:45 – 09:00)

- **[En pantalla]** Mostrar el resultado final de los contenedores y las cajas organizadas.

- **[Texto de apoyo visual]**
    - Modelo de caja.
    - Margin y padding.
    - Centrado con `text-align`.
    - Centrado de bloques con `margin: auto`.
    - Organización con Flexbox.

- **[Narración (Voz en off)]**

  En el siguiente video comenzaremos a desarrollar nuestro proyecto y lo construiremos paso a paso.

  ¡Hasta pronto!

---

## Código de Referencia

### Panel HTML

```html
<div class="contenedor">
  <h1>Mi página centrada</h1>
  <p>Este texto está centrado.</p>
</div>

<div class="fila">
  <div class="caja">1</div>
  <div class="caja">2</div>
  <div class="caja">3</div>
</div>
```

### Panel CSS

```css
.contenedor {
  max-width: 400px;
  margin: 20px auto;
  padding: 16px;
  text-align: center;
  background-color: #eef3f8;
}

.fila {
  display: flex;
  justify-content: center;
  gap: 12px;
}

.caja {
  width: 80px;
  height: 80px;
  background-color: #f89820;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
}
```

---

## Conceptos Clave

| Propiedad | Función |
|---|---|
| `margin` | Establece el espacio exterior de una caja. |
| `padding` | Establece el espacio interior entre el contenido y el borde. |
| `text-align` | Alinea el texto dentro de un elemento. |
| `max-width` | Establece el ancho máximo de un elemento. |
| `display: flex` | Activa Flexbox para organizar los elementos. |
| `justify-content` | Distribuye los elementos en el eje principal. |
| `align-items` | Alinea los elementos en el eje transversal. |
| `gap` | Establece la separación entre elementos. |

**Idea clave:** `margin` es el espacio de afuera de una caja y `padding` es el espacio de adentro.

---

## Actividad de Práctica — Organiza tus Cajas

**Objetivo:** utilizar el modelo de caja y Flexbox para organizar y centrar elementos en una página web.

**Instrucciones:**

1. Crea un contenedor con la clase `contenedor`.
2. Agrega un título y un párrafo dentro de él.
3. Centra el texto utilizando `text-align`.
4. Establece un ancho máximo de `400px`.
5. Utiliza `margin: 20px auto` para centrar el contenedor.
6. Agrega un `padding` de `16px`.
7. Crea otro contenedor con la clase `fila`.
8. Agrega cuatro cajas con la clase `caja`.
9. Utiliza `display: flex` para organizarlas horizontalmente.
10. Prueba diferentes valores de `justify-content` y `gap`.
11. Centra los números dentro de cada caja utilizando `align-items` y `justify-content`.

**Resultado esperado:** una página con un contenedor de texto centrado y una fila de cuatro cajas organizadas mediante Flexbox.

**Reto adicional:** modifica los colores, tamaños y espacios de las cajas para crear una distribución visual diferente.