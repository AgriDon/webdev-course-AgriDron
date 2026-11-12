# Lección 2: Introducción a HTML (10 minutos)

* **Video:** https://youtu.be/Vl414u2bYE4
* **Práctica en CodePen:** https://codepen.io/editor/Miguel-Jara-the-scripter/pen/01a1b17b-43bf-70b4-abd1-16316e229606
* **Público objetivo:** Estudiantes de secundaria (12 a 17 años) sin conocimientos previos de programación.
* **Herramienta demostrada:** Editor en línea CodePen ([codepen.io](https://codepen.io)) sin descargas ni instalaciones.
* **Regla de estilo:** Cero mención a nombres propios, integrantes o marcas de equipo. Lenguaje accesible, estructurado y explicaciones visuales paso a paso.

---

## Estructura y Cronograma del Video Grabado

| Minuto | Sección | Acción visual / En pantalla |
|---|---|---|
| 00:00 - 01:15 | Bienvenida y concepto de HTML | Introducción a las etiquetas HTML, analogía de la casa (estructura, puertas, ventanas) y esqueleto web. |
| 01:15 - 02:45 | Etiquetas de apertura y cierre | Diferencia entre `<title>` (pestaña del navegador) y `<h1>` (encabezado visual en el documento). |
| 02:45 - 04:30 | Jerarquía de encabezados (`<h1>` a `<h6>`) | Demostración visual de los 6 niveles de encabezado y su importancia en tamaño y jerarquía. |
| 04:30 - 06:15 | Estructura base: `<head>` y `<body>` | Organización del documento: elementos invisibles en `<head>` y contenido visible en `<body>`. Párrafos con `<p>`. |
| 06:15 - 08:30 | Imágenes y Enlaces (`<img>`, `<a>`) | Uso de etiquetas de autocierre `<img>` con atributos `src` y `alt`. Creación de hipervínculos con `<a>` y `href`. |
| 08:30 - 14:50 | Creación de la primera página y Cierre | Construcción en vivo de una página personal con encabezado, presentación, pasatiempos, imagen y enlace. |

---

## 🎙️ Guion y Locución del Video

### [00:00 - 01:15] Bienvenida y concepto de HTML
**[En pantalla: Portada de la lección «Lección 2: Introducción a HTML» y apertura del editor en línea CodePen].**

**Locución:**
> "¡Hola chicos, bienvenidos! Hoy vamos a aprender a crear nuestra primera página web utilizando HTML.
>
> ¿Alguna vez han visitado YouTube, un videojuego en línea o una página para ver dibujos? Todas esas páginas utilizan tecnologías que permiten mostrar textos, imágenes y muchas otras cosas más. Hoy aprenderemos a crear nuestra propia página web desde cero.
>
> ¿Qué es HTML? HTML es un lenguaje, pero no es un lenguaje de programación. Lo utilizamos para estructurar y organizar el contenido de una página web; en pocas palabras, es el esqueleto de nuestro sitio. Imaginen que una página web es como una casa: HTML sería la estructura, que nos ayuda a decidir dónde van las habitaciones, las puertas y las ventanas."

---

### [01:15 - 02:45] Etiquetas de apertura y cierre: `<title>` vs `<h1>`
**[En pantalla: Zoom en el editor mostrando la sintaxis `<etiqueta>contenido</etiqueta>`].**

**Locución:**
> "Para crear una página web utilizamos etiquetas. Las etiquetas son palabras especiales que escribimos entre los símbolos menor que `<` y mayor que `>`.
>
> Se componen de una etiqueta de apertura y una etiqueta de cierre, que lleva una barra diagonal. Entre esas dos etiquetas se escribe el contenido que queremos mostrar.
>
> Por ejemplo, tenemos la etiqueta `<title>`, que define el título de la página, y la etiqueta `<h1>`, que sirve para el encabezado principal.
>
> ¿Cuál es la diferencia entre `<title>` y `<h1>`? `<title>` es el nombre que se muestra en la pestaña del navegador y en los resultados del buscador. En cambio, `<h1>` es el encabezado visible dentro del cuerpo de la página web."

---

### [02:45 - 04:30] Jerarquía de encabezados (`<h1>` a `<h6>`)
**[En pantalla: El editor escribe sucesivamente `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>` y `<h6>` y se observa la vista previa].**

**Locución:**
> "El `<h1>` no es el único encabezado. Tenemos seis niveles: `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>` y `<h6>`.
>
> Cada etiqueta `h` tiene un tamaño y una importancia diferente. Mientras mayor sea el número del encabezado, menor será su tamaño visual.
>
> `<h1>` representa el título de mayor jerarquía y se recomienda tener solo uno principal por página, mientras que `<h2>`, `<h3>` y los demás sirven para subtítulos y secciones secundarias."

---

### [04:30 - 06:15] Estructura base: `<head>`, `<body>` y párrafos `<p>`
**[En pantalla: Organización de la estructura HTML con los bloques `<head>` y `<body>` claramente indentados].**

**Locución:**
> "Es fundamental organizar el código: dentro de `<head>` colocamos la información de configuración, como `<title>` y metadatos. El contenido visual que el usuario ve debe ir obligatoriamente dentro de la etiqueta `<body>`.
>
> Para escribir texto normal, descripciones o párrafos, utilizamos la etiqueta `<p>`, que significa párrafo. Al igual que los encabezados, abrimos con `<p>`, escribimos nuestro texto y cerramos con `</p>`."

---

### [06:15 - 08:30] Elementos multimedia y enlaces (`<img>`, `<a>`)
**[En pantalla: Inserción de la etiqueta `<img>` con `src` y `alt`, y luego el hipervínculo `<a>` con `href`].**

**Locución:**
> "Para mostrar una fotografía o ilustración utilizamos la etiqueta `<img>`. A diferencia de los párrafos, esta etiqueta no necesita etiqueta de cierre.
>
> En su lugar, utiliza **atributos**:
> * `src`: indica la dirección o enlace de la imagen que deseamos mostrar.
> * `alt`: es el texto alternativo que describe la imagen si no se pudiera cargar o para personas con lectores de pantalla.
>
> Para conectar nuestra página con otros sitios web usamos la etiqueta `<a>`, que significa enlace o ancla. Mediante el atributo `href` escribimos la dirección web de destino, como por ejemplo `https://www.google.com`, y entre las etiquetas colocamos el texto sobre el que se puede hacer clic."

---

### [08:30 - 14:50] Práctica en vivo: Creando nuestra primera página personal
**[En pantalla: Construcción paso a paso de la página en CodePen: título principal, presentación personal, pasatiempos, logo y enlace externo].**

**Locución:**
> "Llegó el momento de ponerlo en práctica. Vamos a crear una página web personal sencilla:
>
> 1. En el `<head>`, definimos el `<title>`: 'Mi primera página web'.
> 2. En el `<body>`, creamos un `<h1>` con '¡Hola mundo!'.
> 3. Agregamos un párrafo `<p>` presentándonos: 'Hola, soy un estudiante apasionado por la tecnología y estoy aprendiendo HTML'.
> 4. Con un `<h2>`, colocamos 'Mis pasatiempos' y detallamos en otro párrafo nuestras actividades favoritas.
> 5. Insertamos una imagen con `<img>` usando una dirección válida en `src` y un texto descriptivo en `alt`.
> 6. Por último, agregamos un enlace con `<a>` para visitar nuestro sitio web favorito.
>
> ¡Y listo! Con estas etiquetas básicas ya tienes la estructura completa de tu primera página web en HTML. En la siguiente lección continuaremos profundizando en más elementos y listas para enriquecer tus sitios. ¡Nos vemos en el próximo video!"

---

## Descripción del video (YouTube, no listado)

```text
Lección 2: Introducción a HTML
Aprende las etiquetas fundamentales de HTML: estructura básica, encabezados, párrafos, imágenes y enlaces.

💻 Práctica en CodePen: https://codepen.io/editor/Miguel-Jara-the-scripter/pen/01a1b17b-43bf-70b4-abd1-16316e229606
📂 Repositorio del curso: https://github.com/AgriDon/webdev-course-AgriDron
```
