# Lección 3: Añadir más elementos HTML (8 minutos)

* **Video:** https://youtu.be/vub2qG4cP8s
* **Práctica en CodePen:** https://codepen.io/editor/Miguel-Jara-the-scripter/pen/01a1b19a-9e0d-70c2-a71e-e373bdc6c24a
* **Público objetivo:** Estudiantes de secundaria (12 a 17 años) sin conocimientos previos de programación.
* **Herramienta demostrada:** Editor en línea CodePen ([codepen.io](https://codepen.io)) sin descargas ni instalaciones.
* **Regla de estilo:** Cero mención a nombres propios, integrantes o marcas de equipo. Lenguaje accesible, estructurado y explicaciones visuales paso a paso.

---

## ⏱️ Estructura y Cronograma del Video Grabado

| Minuto | Sección | Acción visual / En pantalla |
|---|---|---|
| 00:00 - 01:10 | Introducción y repaso | Breve bienvenida, recapitulación de títulos y párrafos, y presentación de los nuevos elementos: listas, imágenes y enlaces. |
| 01:10 - 03:00 | Creación de listas desordenadas | Uso de la etiqueta contenedora `<ul>` y los elementos de lista `<li>` usando videojuegos favoritos (Mario Kart, Roblox, Minecraft). |
| 03:00 - 05:00 | Inserción de imágenes con `<img>` | Inserción de imagen con etiquetas de autocierre, uso de atributos `src`, texto alternativo `alt` y control de tamaño con `width`. |
| 05:00 - 06:45 | Creación de hipervínculos con `<a>` | Explicación del atributo `href` y cómo enlazar hacia páginas web externas (ej. Google). |
| 06:45 - 08:00 | Actividad práctica y Cierre | Resumen de los 5 elementos de la página integradora y despedida hacia la lección de CSS. |

---

## 🎙️ Guion y Locución del Video

### [00:00 - 01:10] Introducción y repaso
**[En pantalla: Portada de la lección «Lección 3: Añadir más elementos HTML» y apertura de la plantilla de trabajo en CodePen].**

**Locución:**
> "¡Hola chicos, bienvenidos a una nueva lección de nuestro curso de desarrollo web!
>
> En la clase anterior aprendimos a crear títulos y párrafos para estructurar nuestra página web. Hoy vamos a dar un paso más allá aprendiendo a agregar listas, imágenes y enlaces. De esta manera, podremos crear una página mucho más divertida, dinámica e interactiva. ¡Comencemos!"

---

### [01:10 - 03:00] 1. ¿Cómo crear listas en HTML?
**[En pantalla: Zoom en el editor mientras se escribe el encabezado `<h2>` y las etiquetas `<ul>` y `<li>`].**

**Locución:**
> "Imaginen que quieren hacer una lista de sus videojuegos favoritos, sus pasatiempos o sus comidas preferidas. En HTML podemos organizar esta información fácilmente.
>
> Para hacer una lista utilizamos la etiqueta `<ul>`, que crea una lista desordenada con viñetas o puntos, y la etiqueta `<li>`, que representa cada elemento dentro de esa lista.
>
> Por ejemplo, agreguemos un encabezado `<h2>` con el título 'Mis videojuegos favoritos'. Luego abrimos `<ul>` y dentro agregamos nuestros juegos favoritos con `<li>`:
> * `<li>Mario Kart</li>`
> * `<li>Roblox</li>`
> * `<li>Minecraft</li>`
>
> Cerramos nuestra lista con `</ul>`. Como pueden observar en la vista previa, estas etiquetas organizan la información de manera limpia y ordenada."

---

### [03:00 - 05:00] 2. ¿Cómo agregar imágenes?
**[En pantalla: Inserción de la etiqueta `<img src="..." alt="..." width="...">` y demostración del atributo alt].**

**Locución:**
> "También podemos agregar fotografías de nuestras mascotas, dibujos o personajes favoritos utilizando la etiqueta `<img>`.
>
> Recuerden que esta etiqueta no necesita etiqueta de cierre, pero sí requiere atributos fundamentales:
> * `src`: indica la dirección web o ruta donde se encuentra la imagen.
> * `alt`: describe la imagen con un texto alternativo si la imagen no logra cargar o para personas que utilizan lectores de pantalla por accesibilidad.
>
> Agregamos un encabezado `<h2>` llamado 'Mi mascota favorita'. Ahora usamos `<img>` con el atributo `src` con la dirección de nuestra imagen de prueba y el atributo `alt`. Además, podemos controlar qué tan grande se muestra en pantalla modificando su ancho con el atributo `width`, por ejemplo a 300 píxeles."

---

### [03:00 - 06:45] 3. ¿Cómo crear enlaces?
**[En pantalla: Demostración de la etiqueta `<a>` con `href` y cómo el cursor cambia a puntero interactivo].**

**Locución:**
> "¿Alguna vez han hecho clic en una palabra o botón y han viajado a otra página web? Eso es un enlace o hipervínculo.
>
> Para crear enlaces utilizamos la etiqueta `<a>` y el atributo `href`, que le indica al navegador a qué dirección de internet queremos ir.
>
> Por ejemplo, podemos crear un enlace hacia Google. Dentro del atributo `href` escribimos la dirección completa `https://www.google.com` y entre la etiqueta de apertura y cierre colocamos el texto visible: 'Visitar Google'.
>
> De esta manera, cuando cualquier persona haga clic sobre ese texto, el navegador lo llevará a la página indicada."

---

### [06:45 - 08:00] 4. Actividad práctica y Cierre
**[En pantalla: Vista previa final con la página completa: título, lista de videojuegos, imagen y enlace].**

**Locución:**
> "Ahora es momento de poner en práctica lo aprendido en tu propio navegador. En la descripción del video tienes el enlace directo a CodePen con la plantilla lista.
>
> El reto de hoy es crear una página que contenga:
> 1. Un título principal `<h1>`.
> 2. Una lista desordenada `<ul>` con al menos tres de tus videojuegos o actividades favoritas en `<li>`.
> 3. Una imagen con `<img>` utilizando correctamente sus atributos `src` y `alt`.
> 4. Un enlace externo hacia tu sitio web favorito con `<a>` y `href`.
>
> ¡Excelente trabajo! Hoy aprendiste a enriquecer tu página con listas, imágenes y enlaces. Con estos elementos ya dominas la estructura esencial de HTML.
>
> En la próxima lección descubriremos CSS para darle color, estilo y diseño visual a todo lo que hemos construido. ¡Nos vemos en el próximo video!"

---

## 📝 Descripción del video (YouTube, no listado)

```text
Lección 3: Añadir más elementos HTML
Aprende a enriquecer tu página web con listas (ul, li), imágenes (img con src y alt) y enlaces interactivos (a con href).

💻 Práctica en CodePen: https://codepen.io/editor/Miguel-Jara-the-scripter/pen/01a1b19a-9e0d-70c2-a71e-e373bdc6c24a
📂 Repositorio del curso: https://github.com/AgriDon/webdev-course-AgriDron
```
