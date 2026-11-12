# Lección 1: ¿Qué es el desarrollo web? (4:16)

**Video:** https://youtu.be/Xlk6Rtb2RMw

**Práctica en CodePen:** https://codepen.io/editor/Italo-Damacen/pen/01a1ae4a-b04f-7fad-8584-e02d43dade4a

Objetivo: entender qué es una página web, cómo llega a tu pantalla y qué hacen HTML y CSS. **Toda la lección es teoría y contexto**: no aparece código ni se explican etiquetas (eso empieza en la lección 2).

## Cómo cumple la rúbrica

| Requisito o criterio | Dónde se cumple en este guion |
|---|---|
| Tema «Introducción al desarrollo web (¿qué es un sitio web?)» | Toda la lección, con la fórmula del plan de curso: Sitios web = Contenido (HTML) + Estilo (CSS). |
| Sin instalar nada, 100 % en línea | Se dice en la narración (bloque «¿Qué necesitas?»). |
| Texto en pantalla, anotaciones y narración en off | Cada bloque tiene **Narración** (voz en off) y **Edición** (texto y animaciones en pantalla). |
| Pausas de práctica | Bloque «¡Tu turno!»: quiz «¿HTML o CSS?». |
| Sin branding ni referencia a autores | Páginas de ejemplo genéricas, sin logos ni nombres reales. |
| C01 Estructura y flujo | Va de lo conocido (las páginas que usas) a cómo funcionan, y termina presentando la lección 2. |
| C02 Precisión técnica | Datos verificables: HTML (Tim Berners-Lee, inicios de los 90), CSS (propuesto en 1994, primera versión en 1996), HTML no es lenguaje de programación. |
| C03 Público objetivo | Sin jerga: cada término se explica en el momento; analogías del delivery, la casa y la ropa; quiz para pausar. |
| C04 Calidad de video | Checklist de grabación al final. |
| Anexo C (términos) | No se usan «librería», «requerimiento», «aplicativo» ni «elicitar». |

---

### 0:00–0:04 · Carátula

- **Edición:** «Lección 1», título «¿Qué es el desarrollo web?» y subtítulo «De qué están hechas las páginas que usas todos los días».

### 0:04–0:22 · Las páginas web están en todas partes

- **Narración:** "Hoy seguramente ya entraste a alguna página web: viste un video, buscaste una tarea o revisaste tus notas del colegio. Cada una de esas páginas la construyó una persona. A ese trabajo se le llama desarrollo web, y en este curso vas a dar tus primeros pasos."
- **Edición:** ventanas de navegador genéricas (videos, buscador, notas del colegio), sin logos; aparece el rótulo «Desarrollo web = construir páginas web».

### 0:22–0:58 · ¿Cómo llega una página a tu pantalla?

- **Narración:** "¿Qué pasa cuando entras a una página? Usas un navegador, que es el programa para entrar a internet, como Chrome, Edge o Firefox. Ahí escribes una dirección, que se llama URL. Al presionar Enter, el navegador le pide la página a un servidor: una computadora siempre encendida que guarda los archivos de esa página. El servidor se los envía, y el navegador los lee y los dibuja en tu pantalla. Es como pedir comida por delivery: haces el pedido, la cocina lo prepara y te lo traen."
- **Edición:** barra de direcciones con `www.mipagina.com` y la etiqueta «URL = dirección»; flecha «pedido» hacia una torre con la etiqueta «servidor»; vuelven los archivos y el navegador arma la página. Debajo: 🧑 pedido → 🍳 cocina → 🛵 entrega.

### 0:58–1:35 · Las tres capas de una página

- **Narración:** "Esos archivos están escritos en tres lenguajes, y cada uno tiene un trabajo distinto. Imagina que una página web es una casa. HTML es la estructura: las paredes, las puertas y las ventanas. CSS es la decoración: la pintura, los muebles, las luces de colores. Y JavaScript es la electricidad: hace que las cosas reaccionen cuando las tocas. En este curso nos enfocamos en las dos primeras, porque son la base de todo."
- **Edición:** casa que se arma por capas: estructura gris (HTML), pintura y muebles (CSS), luces (JavaScript, más pequeña y en gris porque no es parte del curso).

### 1:35–2:15 · ¿Qué es HTML?

- **Narración:** "HTML significa lenguaje de marcado de hipertexto. Hipertexto es texto con enlaces que te llevan a otras páginas. Y marcado quiere decir que HTML le pone nombre a cada parte del contenido: esto es un título, esto es un párrafo, esto es una imagen, esto es un enlace. Ojo: HTML no es un lenguaje de programación. No hace cuentas ni toma decisiones. Su trabajo es decir qué hay en la página y en qué orden."
- **Edición:** «HyperText Markup Language» → «lenguaje de marcado de hipertexto»; un texto subrayado que salta a otra página («hipertexto»). Una página genérica donde aparecen rótulos sobre cada parte: «título», «párrafo», «imagen», «enlace». Tarjeta «No es un lenguaje de programación: es de marcado».

### 2:15–2:40 · Un poco de historia

- **Narración:** "HTML lo creó Tim Berners-Lee, un científico que trabajaba en el CERN, en Suiza, a inicios de los años 90. Quería que los investigadores compartieran documentos enlazados entre sí, y así nació la web. Hoy usamos su versión moderna, HTML5."
- **Edición:** línea de tiempo: «inicios de los 90: nace la web y HTML» → «hoy: HTML5». Ilustración genérica de un laboratorio con documentos unidos por flechas.

### 2:40–3:20 · ¿Qué es CSS?

- **Narración:** "Con solo HTML, una página se ve bastante aburrida: letras negras sobre fondo blanco. Ahí entra CSS, que significa hojas de estilo en cascada. CSS decide cómo se ve cada parte: los colores, el tipo y el tamaño de letra, los bordes y dónde va cada cosa. Si HTML es tu cuerpo, CSS es tu ropa: puedes cambiarte de ropa sin dejar de ser tú. Por eso la misma página puede verse completamente distinta solo cambiando su CSS."
- **Edición:** la página genérica en blanco y negro; luego se "viste" con colores, fuentes y bordes; al final se cambia dos veces de "ropa" (tres diseños distintos con el mismo contenido). Rótulo «Cascading Style Sheets = hojas de estilo en cascada».

### 3:20–3:45 · ¿Por qué «en cascada»?

- **Narración:** "¿Y por qué en cascada? Porque los estilos caen de arriba hacia abajo, como el agua. Si le das un color a toda la página, todo lo que está dentro lo hereda. Y si dos estilos chocan, CSS tiene reglas para decidir cuál gana. CSS nació en 1996, para que HTML se ocupara del contenido y CSS del diseño."
- **Edición:** cascada de agua de color que baja por la página y tiñe todo lo que toca; dos pinceles que chocan y un ✓ sobre el que gana. Línea de tiempo: «1996: primera versión de CSS».

### 3:45–4:15 · Juntos: contenido + estilo

- **Narración:** "Así trabajan juntos: el navegador lee el HTML para saber qué mostrar, y lee el CSS para saber cómo mostrarlo. Mira un botón de suscribirse: HTML dice que hay un botón con el texto «Suscribirse»; CSS dice que es rojo, redondeado y con letras blancas. Recuerda la fórmula de hoy: página web es igual a contenido, con HTML, más estilo, con CSS."
- **Edición:** botón genérico dividido en dos: a la izquierda «HTML: qué es» (un botón gris con el texto), a la derecha «CSS: cómo se ve» (el mismo botón rojo y redondeado). Cierre con la fórmula en grande: **Página web = Contenido (HTML) + Estilo (CSS)**.

### 4:15–4:30 · ¿Qué necesitas?

- **Narración:** "¿Y qué necesitas para crear páginas? Solo tu navegador. En este curso vamos a usar editores en línea, gratis y sin instalar nada, donde escribes a un lado y ves tu página al otro."
- **Edición:** tarjetas «Solo tu navegador ✓» · «Gratis ✓» · «Sin instalar nada ✓»; pantalla dividida genérica: editor a la izquierda, página a la derecha.

### 4:30–4:45 · ¡Tu turno! (pausa)

- **Narración:** "Pausa el video y decide: ¿esto es trabajo de HTML o de CSS? Uno: el texto de un título. Dos: el color de fondo. Tres: que haya una imagen. Cuatro: el tamaño de la letra. Cuando termines, dale play."
- **Edición:** «¡Tu turno!», ícono de pausa y cuatro tarjetas numeradas. Al darle play se revelan: 1 HTML · 2 CSS · 3 HTML · 4 CSS.

### 4:45–5:00 · Resumen y lo que viene

- **Narración:** "Hoy aprendiste que el navegador le pide las páginas a un servidor, que HTML pone el contenido y que CSS le da el estilo. En la próxima lección vas a escribir tu primera página en HTML."
- **Edición:** tres tarjetas de resumen (navegador ↔ servidor · HTML = contenido · CSS = estilo) y tarjeta final «Siguiente: Lección 2, Introducción a HTML».

---

## Descripción del video (YouTube, no listado)

```text
Lección 1: ¿Qué es el desarrollo web?
Descubre de qué están hechas las páginas web: contenido (HTML) + estilo (CSS).

💻 Práctica en CodePen: https://codepen.io/editor/Italo-Damacen/pen/01a1ae4a-b04f-7fad-8584-e02d43dade4a
▶ Siguiente: Lección 2, Introducción a HTML: https://youtu.be/Vl414u2bYE4
📂 Repositorio del curso: https://github.com/AgriDon/webdev-course-AgriDron
```

## Checklist de grabación

- [ ] Solo voz: toda la lección es teoría; las animaciones se hacen en la edición.
- [ ] Grabar cada bloque del guion como un clip aparte, nombrado con su orden (leccion1-1, leccion1-2…).
- [ ] Micrófono cerca y en un cuarto sin eco; grabar 10 segundos de silencio al inicio para limpiar el ruido.
- [ ] No mostrar logos ni páginas reales con marca; todo genérico.

## Código de la lección

- `completed-examples/leccion-1-intro-desarrollo-web/`: la página del video con tres «ropas» de CSS (`estilo-claro.css`, `estilo-oscuro.css`, `estilo-naturaleza.css`) y el botón «Suscribirse».
- `starter-files/leccion-1-intro-desarrollo-web/`: la misma página sin estilo, con ejercicios en `estilo.css` para comprobar que el CSS cambia cómo se ve, pero no el contenido.
