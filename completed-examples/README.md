# Ejemplos resueltos y código terminado de cada lección

Esta carpeta contiene los ejercicios completamente desarrollados y las soluciones de referencia de cada lección del curso de desarrollo web.

---

## Lección 1: ¿Qué es el desarrollo web?

Se incluye la página del video vestida con tres estilos diferentes, para demostrar que una página web es contenido (HTML) más estilo (CSS).

### Contenido desarrollado
- Una página con contenido en HTML: título, párrafo, imagen, enlace y botón.
- Tres hojas de estilo CSS que cambian su aspecto sin tocar el contenido: `estilo-claro.css`, `estilo-oscuro.css` y `estilo-naturaleza.css`.
- El botón «Suscribirse» del video: HTML dice qué es; CSS lo vuelve rojo, redondeado y con letras blancas.
- Herencia de estilos («en cascada»): el color del `body` lo heredan los elementos de adentro.

### Resultado esperado
Al cambiar el archivo CSS enlazado en `index.html`, la misma página se ve de tres formas distintas.

---

## Lección 2: Introducción a HTML

Se incluye una página web personal desarrollada utilizando las etiquetas básicas de HTML.

### Contenido desarrollado
- Estructura básica de un documento HTML.
- Uso de las etiquetas HTML, HEAD y BODY.
- Definición del título con TITLE.
- Creación de encabezados con H1 y H2.
- Creación de párrafos con P.
- Inserción de imágenes con IMG.
- Uso de los atributos SRC y ALT.
- Creación de enlaces con A y HREF.

### Resultado esperado
Una página web personal que contiene una presentación, descripción de pasatiempos, una imagen y un enlace externo.

---

## Lección 3: Añadir más elementos HTML

### Contenido desarrollado
Esta lección contiene un ejercicio resuelto sobre la creación de listas, imágenes y enlaces en HTML.

### Elementos implementados
- UL: creación de listas desordenadas.
- LI: definición de elementos de una lista.
- IMG: inserción de imágenes.
- SRC: especificación de la dirección de una imagen.
- ALT: descripción alternativa de imágenes.
- WIDTH: modificación del ancho de una imagen.
- A: creación de enlaces.
- HREF: especificación de la dirección de un enlace.

### Resultado esperado
Una página web que presenta una lista de videojuegos favoritos, una imagen y un enlace externo.

### Archivo principal
`leccion-3-elementos-html/index.html`

---

## Lección 4: Introducción a CSS

### Contenido desarrollado
Solución completa que transforma una página HTML plana en una tarjeta de perfil visualmente profesional y moderna en CodePen.

### Elementos implementados
- Selector de etiqueta (`body`): tipografía limpia sin serifa y fondo suave.
- Selector de clase (`.tarjeta-perfil`): contenedor con `max-width`, centrado con `margin: 0 auto`, sombras (`box-shadow`) y bordes redondeados.
- Recorte circular (`.imagen-avatar`): avatar circular mediante `border-radius: 50%` y borde decorativo.
- Jerarquía tipográfica: títulos oscuros, rol destacado y espaciado de lectura cómodo (`line-height`).
- Botón interactivo: microanimaciones con pseudo-clase `:hover`.

### Archivos
- `lesson-4/index.html` y `lesson-4/styles.css`: código fuente ejecutable.
- `lesson-4-completed.md`: guía paso a paso con explicación pedagógica del resultado visual.

---

## Lección 5: Página de perfil personal

El ejemplo incluye:
- Fotografía de muestra.
- Nombre y presentación ficticios.
- Lista de pasatiempos.
- Enlaces educativos.
- Pie de página.
- Estilos de colores, espacios y fotografía circular.

### Cómo utilizarlo

Abre el editor en línea de la práctica y coloca el contenido de `index.html` y `style.css` en sus archivos correspondientes.

Compara este resultado con tu práctica para revisar diferencias y corregir errores.

Los archivos de partida están en la carpeta `starter-files`.

---

## Lección 6: Consejos y Próximos Pasos

Solución completa de la actividad «Encuentra y corrige el error», donde se resuelven los errores más habituales de principiantes en HTML y CSS.

### Errores corregidos y explicados:
1. **Etiqueta HTML no cerrada (`<strong>`):** Se cerró adecuadamente con `</strong>` para evitar que todo el párrafo continúe en negrita.
2. **Selector de clase CSS sin punto (`.titulo-perfil`):** Se antepuso el punto (`.`) para vincular la regla de estilo con la clase de HTML.
3. **Nombre de propiedad erróneo (`colr` -> `color`):** Corrección ortográfica para que el navegador interprete la propiedad.
4. **Falta de punto y coma (`;`):** Se añadió el delimitador para garantizar que las declaraciones siguientes se procesen sin fallas.

### Archivos:
- `leccion-6-consejos-proximos-pasos/index.html`: documento HTML validado y corregido.
- `leccion-6-consejos-proximos-pasos/encuentra-el-error-solucion.css`: hoja de estilos comentada con la justificación de cada solución.
