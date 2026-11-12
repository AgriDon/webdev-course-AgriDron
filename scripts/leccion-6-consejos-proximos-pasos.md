# Lección 6: Consejos y Próximos Pasos (10 minutos)

* **Video:** https://youtu.be/VNTNi3iZ8Sg
* **Duración planificada:** 10:00 minutos.
* **Duración de la versión grabada:** 09:25 minutos.
* **Público objetivo:** Estudiantes de secundaria de 12 a 17 años que han seguido el curso básico de HTML y CSS.
* **Herramienta demostrada:** Editor en línea CodePen ([codepen.io](https://codepen.io)) sin descargas ni instalaciones.
* **Proyecto práctico:** Actividad «Encuentra y corrige el error» en una tarjeta de perfil personal.
* **Regla de estilo:** Contenido 100% anónimo, sin nombres de autores, integrantes ni marcas de equipo o instituciones. Ana es un personaje ficticio de ejemplo (14 años). Lenguaje claro, cercano y motivador.

---

## ⏱️ Estructura y Cronograma del Video Grabado

| Minuto | Sección | Acción visual / En pantalla |
|---|---|---|
| 00:00 - 01:15 | Introducción y felicitaciones | Carátula «Lección 6: Consejos y Próximos Pasos». Recapitulación del viaje de aprendizaje: HTML (estructura y contenido) y CSS (diseño y estilo). Presentación de los objetivos de la lección. |
| 01:15 - 03:00 | Buenas prácticas de código limpio | Visualización comparativa de código desordenado vs. código limpio con sangría adecuada, nombres de clase semánticos (`.titulo-perfil`), uso de comentarios útiles y orden lógico de etiquetas. |
| 03:00 - 05:30 | Actividad: «Encuentra y corrige el error» | Demostración en vivo en CodePen: identificación y solución de los 4 errores típicos: etiqueta `<strong>` sin cerrar en HTML, selector de clase sin punto en CSS, propiedad mal escrita y falta de punto y coma `;`. |
| 05:30 - 07:15 | Herramientas esenciales para seguir aprendiendo | Demostración de las herramientas de desarrollo del navegador (DevTools / Inspeccionar elemento), el validador oficial del W3C y la documentación de referencia MDN Web Docs. |
| 07:15 - 08:30 | Próximos pasos en el desarrollo web | Explicación conceptual del siguiente nivel: JavaScript (comportamiento e interactividad), maquetación moderna (Flexbox y Grid) y la importancia de crear proyectos propios. |
| 08:30 - 09:25 | Mensaje final y cierre del curso | Palabras de motivación para seguir practicando, invitación a compartir proyectos con la etiqueta `#WebDevBeginners` y despedida oficial del curso. |

---

## 🎙️ Guion y Locución del Video

### [00:00 - 01:15] Introducción y felicitaciones por el camino recorrido
**[En pantalla: Carátula animada con el título «Lección 6: Consejos y Próximos Pasos» y subtítulo «Mejores prácticas, errores comunes y cómo seguir aprendiendo». Luego, transición a la vista del navegador].**

**Locución:**
> "¡Hola a todos y bienvenidos a la sexta y última lección de nuestro curso de Fundamentos de Desarrollo Web!
>
> Primero que nada: ¡muchísimas felicitaciones por haber llegado hasta aquí! A lo largo de las lecciones anteriores aprendiste qué es una página web, cómo construir su estructura con HTML utilizando encabezados, párrafos, listas, imágenes y enlaces, y cómo transformarla visualmente con CSS aplicando colores, tipografías y el modelo de caja.
>
> En esta lección de cierre no aprenderemos una etiqueta nueva, sino algo igual de valioso: los mejores consejos de los profesionales para escribir código limpio, cómo encontrar y resolver los errores más comunes sin frustrarte, qué herramientas gratuitas te ayudarán todos los días y cuáles son los siguientes pasos para que continúes tu camino en la programación. ¡Acompáñame!"

---

### [01:15 - 03:00] Buenas prácticas para escribir código limpio
**[En pantalla: Se abre el editor mostrando un fragmento de código sin sangría todo pegado a la izquierda, y luego se aplica sangría de dos espacios paso a paso].**

**Locución:**
> "Cuando empezamos a programar, es muy común concentrarnos solo en que la página se vea bien, olvidando cómo luce nuestro código por dentro. Pero los programadores pasan más tiempo leyendo código que escribiéndolo. Por eso, seguir buenas prácticas te ahorrará horas de confusión:
>
> 1. **La sangría o indentación:** Cada vez que abras una etiqueta dentro de otra, como los elementos `<li>` dentro de un `<ul>`, agrega dos espacios hacia la derecha. De esta forma, tus ojos sabrán al instante qué elemento pertenece a qué contenedor.
> 2. **Nombres de clases claros y en minúsculas:** Usa nombres descriptivos que expliquen qué es el elemento, no cómo se ve. Por ejemplo, es mucho mejor usar `class=\"titulo-perfil\"` que `class=\"letras-rojas\"`. Si en el futuro decides cambiar el color a azul, tu clase seguirá teniendo sentido. Además, usa siempre minúsculas separadas por guiones.
> 3. **Comentarios como notas personales:** En HTML usamos `<!-- comentario -->` y en CSS `/* comentario */`. Úsalos para recordar por qué hiciste un cambio importante o para organizar tu hoja de estilos en secciones."

---

### [03:00 - 05:30] Actividad práctica: «Encuentra y corrige el error»
**[En pantalla: Se abre la plantilla de práctica en CodePen con la tarjeta de perfil de Ana. Se observa que el texto se ve desordenado y en negrita completa, y que el título no tiene color].**

**Locución:**
> "Ahora pongamos a prueba tus habilidades de detective con nuestra actividad: «Encuentra y corrige el error». En la descripción del video tienes el enlace directo a CodePen para que abras esta plantilla y la resuelvas conmigo.
>
> Aquí tenemos la tarjeta de perfil de Ana, de 14 años. Pero algo no anda bien: el título principal se ve en negro sin estilos y todo el párrafo inferior aparece en negrita. ¡Vamos a investigar por qué!
>
> **Error 1 en HTML: La etiqueta sin cerrar.**
> Revisemos la línea del párrafo: dice `<p>Hola, soy <strong>Ana y tengo 14 años.</p>`. Observa con atención: abrimos `<strong>` para resaltar el nombre Ana, ¡pero nunca la cerramos con `</strong>`! Como el navegador no sabe dónde termina la negrita, pone en negrita todo el resto del texto. Coloquemos `</strong>` justo después de Ana... y listo, el párrafo vuelve a la normalidad.
>
> **Error 2 en CSS: El punto olvidado en la clase.**
> Ahora miremos nuestra hoja de estilos. En el HTML tenemos `<h1 class=\"titulo-perfil\">`, pero en CSS escribieron `titulo-perfil` sin nada adelante. ¿Recuerdas la regla de oro de CSS? Para seleccionar una clase, siempre debemos anteponer un punto: `.titulo-perfil`. Agregamos el punto... ¡y mira la magia! El título ahora luce su color morado y su tamaño correcto.
>
> **Errores 3 y 4 en CSS: Ortografía y punto y coma.**
> Finalmente, en la regla `.frase-favorita` notamos dos detalles: la propiedad está escrita como `colr` en vez de `color`, y falta el punto y coma final. CSS es muy estricto: si olvidas el punto y coma (`;`), el navegador se confunde y suele ignorar las reglas siguientes. Corregimos `color` y añadimos el punto y coma. ¡Nuestra tarjeta de perfil ha quedado perfecta!"

---

### [05:30 - 07:15] Herramientas profesionales para depurar y aprender
**[En pantalla: Se hace clic derecho en la página web y se selecciona «Inspeccionar». Se recorre la pestaña Elementos y la pestaña Estilos de las DevTools del navegador].**

**Locución:**
> "Una gran ventaja del desarrollo web es que tu propio navegador ya incluye las mismas herramientas que usan los ingenieros en las empresas de tecnología:
>
> 1. **Herramientas del Desarrollador (DevTools):** En cualquier página web en Google Chrome, Edge o Firefox, puedes hacer clic derecho y presionar «Inspeccionar» (o presionar la tecla F12). En la pestaña 'Elementos' puedes ver el HTML exacto de la página, y en 'Estilos' puedes probar colores y tamaños en tiempo real sin romper nada. ¡Es el mejor laboratorio para experimentar!
> 2. **Validadores oficiales del W3C:** La organización internacional que define los estándares de la web ofrece herramientas gratuitas como el W3C Markup Validator. Solo pegas tu código y te señala con precisión si olvidaste cerrar una etiqueta o si cometiste un error de sintaxis.
> 3. **MDN Web Docs (Mozilla Developer Network):** Nadie memoriza todas las etiquetas ni todas las propiedades de CSS. MDN es la enciclopedia oficial y gratuita más confiable del mundo para consultar cómo funciona cualquier elemento de HTML o CSS con ejemplos interactivos."

---

### [07:15 - 08:30] ¿Hacia dónde continuar? Próximos pasos
**[En pantalla: Diapositiva ilustrativa con los tres pilares de la web: HTML (estructura), CSS (estilo) y JavaScript (interactividad)].**

**Locución:**
> "Has dominado los dos primeros pilares de la web: HTML para el contenido y CSS para la presentación. ¿Qué sigue ahora en tu camino?
>
> * **Aprender JavaScript:** Es el tercer pilar fundamental. Con JavaScript puedes agregar interactividad real a tus páginas: botones que abren ventanas modales, contadores, juegos interactivos o modo oscuro con un solo clic.
> * **Diseño responsivo con Flexbox y CSS Grid:** Para que tus sitios web se adapten de forma automática y fluida tanto a pantallas de computadoras como a teléfonos celulares y tabletas.
> * **Construir tus propios proyectos:** El mejor consejo que te puedo dar es: ¡crea cosas que te apasionen! Diseña una página para tu videojuego preferido, un catálogo para las recetas de tu familia o un portafolio para mostrar tus dibujos. La práctica constante es el verdadero secreto."

---

### [08:30 - 09:25] Cierre del curso y despedida
**[En pantalla: Vista general del sitio web completado en CodePen y pantalla de créditos finales].**

**Locución:**
> "Con esto llegamos al final de nuestro curso de Fundamentos de Desarrollo Web. En solo una hora demostraste que no necesitas instalar programas complicados ni tener experiencia previa para crear tus propios sitios web desde cero.
>
> Comparte tus proyectos con tus amigos y en redes sociales usando la etiqueta `#WebDevBeginners`. Guarda tus enlaces en CodePen para que siempre puedas consultarlos y seguir mejorándolos.
>
> ¡Muchas gracias por acompañarnos en este viaje y mucho éxito en tus futuros proyectos web! ¡Hasta la próxima!"

---

## 📝 Descripción del video (YouTube, no listado)

```text
Lección 6: Consejos y Próximos Pasos (Fundamentos de Desarrollo Web)
Aprende las mejores prácticas para escribir código limpio, descubre cómo encontrar y corregir los errores más comunes en HTML y CSS mediante la actividad «Encuentra el error», conoce las herramientas de desarrollo del navegador (DevTools) y explora los próximos pasos para continuar tu aprendizaje en desarrollo web.

⏱️ Marcas de tiempo:
00:00 Introducción y felicitaciones por completar el curso
01:15 Buenas prácticas: sangría, nombres de clases semánticos y comentarios
03:00 Actividad práctica en vivo: «Encuentra y corrige el error»
05:30 Herramientas profesionales: DevTools del navegador, Validador W3C y MDN
07:15 Próximos pasos: JavaScript, diseño responsivo y proyectos propios
08:30 Mensaje final y cierre del curso

💻 Práctica en CodePen (Actividad «Encuentra el error»): https://codepen.io/editor/Miguel-Jara-the-scripter/pen/01a1cd1a-e5e4-7bf5-a1ff-8959a8f22d73
📂 Repositorio con todo el código fuente del curso: https://github.com/AgriDon/webdev-course-AgriDron
```

---
