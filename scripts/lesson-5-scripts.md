# Guion de Video - Lección 5: Crear una página web personal con HTML y CSS

* **Duración planificada:** 15:00 minutos.
* **Duración de la versión grabada y editada:** 19:09 minutos, incluida una introducción de 5 segundos.
* **Público objetivo:** Estudiantes de secundaria de 12 a 17 años que han seguido las lecciones anteriores de HTML y CSS.
* **Herramienta demostrada:** Editor en línea CodePen ([codepen.io](https://codepen.io)) sin descargas ni instalaciones para realizar la práctica.
* **Proyecto:** Tarjeta de perfil con fotografía de muestra, presentación, pasatiempos, enlaces educativos y pie de página.
* **Regla de estilo:** Contenido anónimo, sin nombres de autores, integrantes ni marcas de equipo. Alex es un personaje de ejemplo. Se utiliza lenguaje sencillo y demostración visual paso a paso.
* **Ubicación de este documento:** `scripts/lesson-5-scripts.md`.

> **Nota sobre los tiempos:** El cronograma documenta la versión montada de 19:09, con marcas redondeadas al segundo. La locución está organizada y corregida para su lectura. No es una transcripción completa del video.

---

## Objetivo de la lección

Combinar los conceptos de las lecciones anteriores para construir una página de perfil personal: estructura HTML, encabezados, párrafos, imágenes, listas, enlaces, selectores CSS, colores, tipografía y espacios. Al finalizar, el estudiante podrá reconocer y corregir errores sencillos en los selectores y en la conexión de la hoja de estilos.

## Preparación antes de grabar

* Abrir un proyecto en CodePen con los archivos `index.html` y `style.css`.
* Colocar los editores a la izquierda y la vista previa a la derecha.
* Tener `index.html` con la estructura inicial y `style.css` vacío.
* Preparar la dirección de una fotografía de muestra y comprobar que cargue.
* Preparar la imagen del resultado final para mostrarla al comienzo.
* Ocultar nombres de cuenta, notificaciones u otros datos personales que puedan aparecer durante la grabación.

**Código inicial de `index.html`:**

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lección 5 - Página de perfil personal</title>
  <link rel="stylesheet" href="./style.css">
</head>
<body>

</body>
</html>
```

---

## Estructura y cronograma del video grabado

| Minuto | Sección | Acción visual / En pantalla |
|---|---|---|
| 00:00 - 00:05 | Carátula animada | Fondo crema, barra naranja con “LECCIÓN 05”, título “Página web personal” y subtítulo “Crea tu perfil con HTML y CSS”. |
| 00:05 - 00:34 | Presentación del proyecto | Mostrar la imagen del perfil terminado y recorrer sus componentes. |
| 00:34 - 01:51 | Entorno y archivos iniciales | Mostrar la distribución del editor, el título HTML y la conexión con `style.css`. |
| 01:51 - 02:24 | Contenedor y contenido principal | Crear `div.tarjeta` y `main`. |
| 02:24 - 03:38 | Encabezado y fotografía | Crear `header` e insertar una imagen con `src`, `alt`, `width` y `height`. |
| 03:38 - 04:07 | Nombre y subtítulo | Agregar `h1` y el párrafo con la clase `subtitulo`. |
| 04:07 - 05:00 | Presentación personal | Crear la sección “Sobre mí” con `h2` y `p`. |
| 05:00 - 05:57 | Pasatiempos | Crear una lista con `ul` y `li`. |
| 05:57 - 07:19 | Enlaces educativos | Agregar enlaces con `a` y `href`. |
| 07:19 - 07:46 | Pie de página | Insertar `footer` después de `main`, dentro de la tarjeta. |
| 07:46 - 08:05 | Transición a CSS | Revisar la estructura terminada y abrir `style.css`. |
| 08:05 - 09:24 | Estilos generales | Aplicar fuente, fondo, color de texto y separación entre líneas a `body`. |
| 09:24 - 09:53 | Espacio exterior de la tarjeta | Quitar el margen predeterminado de `body` y agregar `padding`. |
| 09:53 - 11:33 | Diseño de la tarjeta | Aplicar ancho máximo, centrado, espacio interior y fondo blanco. |
| 11:33 - 12:35 | Esquinas y sombra | Agregar `border-radius` y `box-shadow`. |
| 12:35 - 13:31 | Presentación y foto circular | Añadir las clases `presentacion` y `foto`; centrar el encabezado y redondear la fotografía. |
| 13:31 - 14:17 | Títulos | Dar color a `h1` y `h2` y ajustar el tamaño y margen de `h1`. |
| 14:17 - 15:02 | Subtítulo | Aplicar color, negrita y margen superior a `.subtitulo`. |
| 15:02 - 16:39 | Secciones, enlaces y pie | Separar las secciones, destacar enlaces y diseñar `footer`. |
| 16:39 - 19:09 | Resultado, revisión y cierre | Comparar el resultado y demostrar errores en la conexión CSS, puntos, nombres de clases y llaves. |

---

## Guion y locución del video

### [00:00 - 00:05] Carátula animada

**[En pantalla: Introducción de fondo crema con símbolos de código en las esquinas y una barra naranja.]**

**Texto en pantalla:**

> LECCIÓN 05  
> Página web personal  
> Crea tu perfil con HTML y CSS

**Locución:** Sin narración durante la carátula.

---

### [00:05 - 00:34] Introducción y resultado final

**[En pantalla: Mostrar el proyecto terminado. Señalar la fotografía, el nombre, la presentación, los pasatiempos y los enlaces.]**

**Locución:**

> “Bienvenidos a la lección número cinco. Hoy vamos a crear una página de perfil personal como esta. Tendrá una fotografía, un nombre, una breve presentación, una lista de pasatiempos y enlaces a otras páginas.
>
> Usaremos un perfil de ejemplo llamado Alex. Al practicar, puedes personalizar el contenido o crear otro personaje ficticio. Vamos a reunir lo que aprendimos sobre HTML y CSS para construir la página paso a paso.”

---

### [00:34 - 01:51] Entorno y estructura inicial

**[En pantalla: Mostrar los archivos HTML y CSS y la vista previa. Señalar los controles de distribución del editor y regresar a la disposición usada en la lección.]**

**Locución:**

> “Trabajaremos directamente en CodePen. Tenemos un archivo HTML para el contenido y otro CSS para su apariencia. A la derecha veremos el resultado.
>
> Puedes acomodar los paneles como te resulte más cómodo. Para esta explicación dejaremos el código a la izquierda y la vista previa a la derecha.
>
> En la estructura inicial escribimos el título de la página y verificamos la conexión con la hoja de estilos.”

**[Acción en pantalla: Señalar estas líneas dentro de `head`.]**

```html
<title>Lección 5 - Página de perfil personal</title>
<link rel="stylesheet" href="./style.css">
```

**Locución:**

> “La etiqueta link conecta ambos archivos. Rel indica que estamos enlazando una hoja de estilos y href contiene su ruta. Como style.css está en la misma carpeta que index.html, escribimos punto, barra y el nombre del archivo.”

---

### [01:51 - 02:24] Contenedor de la tarjeta

**[Acción en pantalla: Escribir dentro de `body`.]**

```html
<div class="tarjeta">
  <main>

  </main>
</div>
```

**Locución:**

> “Empezamos creando un contenedor con div. Este agrupará toda la tarjeta del perfil. Le asignamos la clase tarjeta para poder darle estilos más adelante.
>
> Dentro colocamos main, que identifica el contenido principal de la página. Aquí escribiremos la presentación, los pasatiempos y los enlaces.”

---

### [02:24 - 03:38] Encabezado y fotografía

**[Acción en pantalla: Dentro de `main`, crear el encabezado e insertar una imagen de muestra.]**

```html
<header>
  <img
    src="https://i.pinimg.com/736x/fd/7e/ac/fd7eac51d4a09870d23e33ff95fa6418.jpg"
    alt="Retrato de prueba"
    width="120"
    height="120"
  >
</header>
```

**Locución:**

> “Para organizar la presentación agregamos un encabezado con header. Dentro insertamos una fotografía usando img.
>
> Src contiene la dirección de la imagen. Alt es un texto alternativo que describe su contenido: ayuda a quienes utilizan lectores de pantalla y puede mostrarse si la imagen no carga.
>
> Con width y height establecemos un ancho y un alto de 120 píxeles. Después, con CSS, ajustaremos el recorte y le daremos una forma circular.”

**Edición:** Resaltar cada atributo al mencionarlo. Escribir correctamente `width`.

---

### [03:38 - 04:07] Nombre y subtítulo

**[Acción en pantalla: Agregar debajo de la imagen, antes de cerrar `header`.]**

```html
<h1>Hola, soy Alex</h1>
<p class="subtitulo">Aprendiendo desarrollo web</p>
```

**Locución:**

> “Debajo de la fotografía escribimos el título principal con h1. Usamos Alex como nombre ficticio.
>
> Después agregamos un párrafo con una frase corta sobre el perfil. Le asignamos la clase subtitulo para darle una apariencia diferente sin modificar todos los demás párrafos.”

---

### [04:07 - 05:00] Sección “Sobre mí”

**[Acción en pantalla: Agregar después de `header`, dentro de `main`.]**

```html
<section>
  <h2>Sobre mí</h2>
  <p>
    Me gusta aprender cosas nuevas.
    Esta es mi primera página con HTML y CSS.
  </p>
</section>
```

**Locución:**

> “Ahora creamos una sección con section para agrupar la presentación. Le damos el título Sobre mí utilizando h2.
>
> Usamos h1 para el título principal y h2 para las secciones. Debajo colocamos un párrafo con una descripción breve.
>
> Ya tenemos fotografía, nombre y presentación. La página todavía se ve básica porque primero estamos organizando el contenido con HTML. Más adelante cambiaremos su apariencia con CSS.”

---

### [05:00 - 05:57] Lista de pasatiempos

**[Acción en pantalla: Agregar otra sección debajo de “Sobre mí”.]**

```html
<section>
  <h2>Mis pasatiempos</h2>
  <ul>
    <li>Escuchar música</li>
    <li>Leer libros</li>
    <li>Salir a caminar</li>
  </ul>
</section>
```

**Locución:**

> “Creamos una nueva sección con el título Mis pasatiempos. Para organizarlos usamos ul, que representa una lista sin orden, y cada elemento se escribe dentro de li.
>
> Como estos pasatiempos no representan pasos ni posiciones, utilizamos viñetas. Si necesitáramos una lista numerada, podríamos utilizar ol. Para agregar otro pasatiempo, basta con escribir otro li dentro de la lista.”

**Edición:** Relacionar cada `li` con su viñeta en la vista previa.

---

### [05:57 - 07:19] Enlaces educativos

**[Acción en pantalla: Agregar la siguiente sección dentro de `main`.]**

```html
<section class="enlaces">
  <h2>Mis enlaces</h2>
  <p>
    <a href="https://developer.mozilla.org/es/docs/Web/HTML">
      Aprender HTML
    </a>
  </p>
  <p>
    <a href="https://developer.mozilla.org/es/docs/Web/CSS">
      Aprender CSS
    </a>
  </p>
</section>
```

**Locución:**

> “Después creamos la sección Mis enlaces. Para cada enlace usamos la etiqueta a. El atributo href contiene la dirección de destino y entre las etiquetas escribimos el texto que verá la persona.
>
> En el primer enlace colocamos un recurso para aprender HTML. El texto visible será Aprender HTML. Repetimos el procedimiento para un recurso sobre CSS.
>
> Cada enlace está dentro de un párrafo, por lo que aparecerán en líneas separadas. En una página de perfil también podrías enlazar otros recursos públicos que quieras compartir.”

**Edición:** Diferenciar visualmente la dirección de destino y el texto del enlace.

---

### [07:19 - 07:46] Pie de página

**[Acción en pantalla: Insertar después de `</main>` y antes del `</div>` de la tarjeta.]**

```html
<footer>
  <p>Mi primera página web · HTML + CSS</p>
</footer>
```

**Locución:**

> “Para terminar el contenido agregamos el pie de página con footer. Lo colocamos después de main, pero dentro del contenedor tarjeta. Así queda separado del contenido principal y compartirá la misma tarjeta cuando apliquemos los estilos.”

---

### [07:46 - 08:05] Transición a la hoja de estilos

**[En pantalla: Recorrer el contenido terminado y abrir `style.css`, todavía vacío.]**

**Locución:**

> “Ya tenemos la fotografía, la presentación, los pasatiempos, los enlaces y el pie de página. Ahora vamos a trabajar en style.css para transformar esta estructura en la tarjeta que mostramos al comienzo.”

---

### [08:05 - 09:24] Estilos generales de la página

**[Acción en pantalla: Escribir en `style.css`.]**

```css
body {
  font-family: Arial, sans-serif;
  background-color: #eef2ff;
  color: #1f2937;
  line-height: 1.6;
}
```

**Locución:**

> “Empezamos con el selector body para establecer los estilos generales. Dentro de las llaves escribimos propiedades y valores.
>
> Font-family define la fuente. Elegimos Arial y dejamos sans-serif como alternativa si Arial no está disponible.
>
> Background-color establece el color del fondo y color define el color del texto. Podemos utilizar nombres, como red o blue, o códigos hexadecimales para indicar un tono concreto.
>
> Finalmente, line-height establece la altura de cada línea. Con 1.6 dejamos una separación cómoda para leer.”

**[Demostración temporal: Cambiar el fondo a `red`, observar el resultado y restaurar `#eef2ff`. Probar otro valor de `line-height` y restaurar `1.6`.]**

**Nota técnica:** No presentar los nombres de colores como incorrectos. Los nombres y los códigos son formas válidas de expresar colores en CSS.

---

### [09:24 - 09:53] Márgenes del documento

**[Acción en pantalla: Agregar dentro de la regla existente de `body`.]**

```css
margin: 0;
padding: 24px;
```

**Locución:**

> “Quitamos el margen que el navegador agrega al body por defecto usando margin cero. Después agregamos padding de 24 píxeles para que el contenido no quede pegado a los bordes de la ventana.”

---

### [09:53 - 11:33] Diseño y centrado de la tarjeta

**[Acción en pantalla: Agregar debajo del bloque `body`.]**

```css
.tarjeta {
  max-width: 560px;
  margin: 24px auto;
  padding: 32px;
  background-color: white;
}
```

**Locución:**

> “Seleccionamos el contenedor usando punto tarjeta. El punto indica que buscamos una clase, y su nombre debe coincidir con el que escribimos en HTML.
>
> Max-width limita el ancho del contenido a 560 píxeles, pero permite que se reduzca si hay menos espacio.
>
> En margin, el primer valor deja 24 píxeles arriba y abajo. Auto reparte el espacio horizontal disponible entre ambos lados para centrar la tarjeta.
>
> Padding agrega espacio interior entre el contenido y el borde. Por último, le damos un fondo blanco a la tarjeta.”

**Edición:** Señalar el margen exterior y el espacio interior. Mantener visible la relación entre `class="tarjeta"` y `.tarjeta`.

---

### [11:33 - 12:35] Esquinas redondeadas y sombra

**[Acción en pantalla: Agregar dentro de la regla existente de `.tarjeta`.]**

```css
border-radius: 16px;
box-shadow: 0 8px 24px rgba(0, 0, 0, 0.5);
```

**Locución:**

> “Con border-radius redondeamos las esquinas. Podemos probar distintos valores, pero para el ejemplo dejamos 16 píxeles.
>
> Box-shadow agrega una sombra. Sus valores indican el desplazamiento horizontal, el vertical, el desenfoque y el color.
>
> En rgba, los primeros tres números representan el color. El último indica su opacidad: cero es transparente y uno es opaco. Podemos probar una sombra más suave con 0.1 y una más marcada con 0.5.”

**Nota de continuidad:** La toma grabada termina usando `0.5` para la opacidad de la sombra. Mantener el mismo valor en el ejemplo terminado que acompaña al video.

---

### [12:35 - 13:31] Presentación centrada y fotografía circular

**[Acción en pantalla: Agregar la clase `presentacion` al `header` existente y la clase `foto` al `img` existente. Conservar los otros atributos de la imagen.]**

```html
<header class="presentacion">
  <img
    class="foto"
    src="https://i.pinimg.com/736x/fd/7e/ac/fd7eac51d4a09870d23e33ff95fa6418.jpg"
    alt="Retrato de prueba"
    width="120"
    height="120"
  >
```

**[El fragmento anterior muestra únicamente la apertura del encabezado: conservar el nombre, el subtítulo y el `</header>` que ya existen.]**

**[Acción en pantalla: Agregar en CSS.]**

```css
.presentacion {
  text-align: center;
}

.foto {
  width: 120px;
  height: 120px;
  object-fit: cover;
  border-radius: 50%;
}
```

**Locución:**

> “Para centrar la presentación, agregamos la clase presentacion al encabezado y usamos text-align center. Así centramos la fotografía, el nombre y el subtítulo.
>
> Después trabajamos con la clase foto. Le damos el mismo ancho y alto: 120 píxeles. Object-fit cover permite llenar ese espacio conservando las proporciones de la fotografía.
>
> Con border-radius al cincuenta por ciento convertimos el recorte cuadrado en un círculo.”

**Edición:** Mostrar primero el centrado y después el cambio de la fotografía a forma circular.

---

### [13:31 - 14:17] Color y tamaño de los títulos

**[Acción en pantalla: Agregar al final del CSS.]**

```css
h1, h2 {
  color: #4338ca;
}

h1 {
  font-size: 32px;
  margin-bottom: 8px;
}
```

**Locución:**

> “Queremos dar el mismo color a los títulos. Escribimos h1 y h2 separados por una coma para aplicarles una misma regla.
>
> Después seleccionamos solamente h1 y le damos un tamaño de 32 píxeles. Con margin-bottom dejamos ocho píxeles de separación por debajo.”

---

### [14:17 - 15:02] Estilo del subtítulo

**[Acción en pantalla: Señalar el párrafo con `class="subtitulo"` y agregar esta regla.]**

```css
.subtitulo {
  color: #4338ca;
  font-weight: bold;
  margin-top: 0;
}
```

**Locución:**

> “Ahora seleccionamos la clase subtitulo usando un punto antes del nombre. Le damos el mismo color morado y usamos font-weight bold para ponerlo en negrita.
>
> Con margin-top cero quitamos el margen superior y acercamos el subtítulo al nombre.”

---

### [15:02 - 16:39] Separación de secciones, enlaces y pie de página

**[Acción en pantalla: Agregar las reglas de las secciones y los enlaces.]**

```css
section {
  margin-top: 24px;
}

a {
  color: #ff0000;
}
```

**Locución:**

> “Para separar los grupos de contenido, seleccionamos section y agregamos un margen superior de 24 píxeles.
>
> Después seleccionamos los enlaces con a. En este ejemplo elegimos rojo para destacarlos. Conservamos el subrayado para que sigan siendo fáciles de reconocer.”

**[Acción en pantalla: Agregar el estilo del pie de página.]**

```css
footer {
  margin-top: 32px;
  text-align: center;
  color: #6b7280;
  font-size: 14px;
}
```

**Locución:**

> “Terminamos con footer. Agregamos un margen superior de 32 píxeles y centramos su contenido. Le damos un color gris y un tamaño de catorce píxeles para diferenciarlo del resto del texto.”

**Nota de continuidad:** Los enlaces de la versión grabada se muestran en rojo, aunque el diseño de referencia inicial los mostraba morados.

---

### [16:39 - 19:09] Resultado final, revisión de errores y cierre

**[En pantalla: Comparar la página terminada con la imagen de referencia. Después regresar al código y demostrar los errores por separado, restaurando el resultado correcto entre cada prueba.]**

**Locución:**

> “Este es el resultado final de la lección. Combinamos HTML y CSS para construir nuestra tarjeta de perfil. Antes de terminar, revisemos algunos errores comunes.”

#### Revisión 1: conexión entre HTML y CSS

**[Acción en pantalla: Señalar la ruta de la hoja de estilos y el archivo correspondiente.]**

```html
<link rel="stylesheet" href="./style.css">
```

**Locución:**

> “Si la página no muestra los estilos, comprobamos la etiqueta link. El nombre y la ruta deben corresponder con la ubicación real del archivo. En este proyecto, index.html y style.css están en la misma carpeta.”

#### Revisión 2: punto de los selectores de clase

**[Acción en pantalla: Quitar temporalmente el punto de `.tarjeta`, observar la pérdida de estilos y volver a colocarlo.]**

```css
/* Incorrecto para seleccionar class="tarjeta" */
tarjeta {
  background-color: white;
}

/* Correcto */
.tarjeta {
  background-color: white;
}
```

**Locución:**

> “En CSS necesitamos un punto para seleccionar una clase. Si lo quitamos, el selector ya no coincide con nuestro contenedor. Al restaurarlo, los estilos vuelven a aplicarse.”

**[Los bloques anteriores ilustran el cambio de selector; no reemplazar la regla completa de la tarjeta ni pegar ambas versiones en el archivo final.]**

#### Revisión 3: nombres exactos de clases

**[Acción en pantalla: Cambiar temporalmente `.subtitulo` por `.subtitlo`, mostrar el efecto y corregir el nombre.]**

**Locución:**

> “También debemos escribir exactamente el nombre de la clase. Si en HTML escribimos subtitulo, en CSS usamos punto subtitulo. Una letra diferente basta para que esa regla no coincida.”

#### Revisión 4: llaves de apertura y cierre

**[Acción en pantalla: Quitar temporalmente las llaves de una regla, observar el resultado y restaurarlas.]**

```css
.subtitulo {
  color: #4338ca;
  font-weight: bold;
  margin-top: 0;
}
```

**Locución:**

> “Por último, revisamos las llaves. Estas delimitan las propiedades de cada regla. Si las quitamos, el navegador puede dejar de interpretar los estilos como esperamos.
>
> Restauramos las llaves y comprobamos que el perfil vuelva a verse correctamente. Eso sería todo por la lección número cinco. ¡Hasta la próxima!”

---

## Descripción del video (YouTube, no listado)

```text
Lección 5: Crear una página web sencilla (Página de perfil personal)
Combina HTML y CSS para construir una tarjeta de perfil personal completa paso a paso con fotografía, presentación, pasatiempos, enlaces externos, estilos modernos y depuración de errores frecuentes.

Marcas de tiempo:
00:00 Carátula e Introducción
00:05 Presentación del proyecto final
00:34 Entorno de trabajo y archivos iniciales en CodePen
01:51 Estructura HTML: Contenedor y contenido principal
02:24 Encabezado y fotografía
03:38 Nombre y subtítulo
04:07 Sección "Sobre mí"
05:00 Lista de pasatiempos
05:57 Enlaces educativos
07:19 Pie de página
07:46 Transición a CSS y estilos generales del body
09:24 Márgenes y espacios de la página
09:53 Diseño de la tarjeta (ancho, centrado, fondo)
11:33 Bordes redondeados y sombra
12:35 Foto circular y encabezado centrado
13:31 Estilos de títulos (h1, h2)
14:17 Estilo del subtítulo
15:02 Separación de secciones, enlaces y pie de página
16:39 Resultado final y revisión de errores comunes

💻 Práctica inicial en CodePen: https://codepen.io/editor/Edwin-Nicho/pen/01a1ad56-4676-7325-b518-33e942d3ce57
✨ Proyecto terminado en CodePen: https://codepen.io/editor/Edwin-Nicho/pen/01a1ac65-806a-72e8-b174-5d5276c0dd72
📂 Repositorio del curso: https://github.com/AgriDon/webdev-course-AgriDron
```

---
