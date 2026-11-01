# Guion de Video - Lección 4: Introducción a CSS (Colores, Fuentes y Diseño)

* **Duración planificada / grabada:** 12:00 minutos.
* **Público objetivo:** Estudiantes de secundaria (12 a 17 años) sin conocimientos previos de programación.
* **Herramienta demostrada:** Editor en línea CodePen ([codepen.io](https://codepen.io)) sin descargas ni instalaciones.
* **Regla de estilo:** Cero mención a nombres propios, integrantes o marcas de equipo. Lenguaje accesible, visual y entusiasta, con demostración práctica en vivo y pausas activas.

---

## ⏱️ Estructura y Cronograma del Video Grabado

| Minuto | Sección | Acción visual / En pantalla |
|---|---|---|
| 00:00 - 01:15 | Introducción y analogía visual | Presentación del objetivo. Comparativa visual entre una página sin CSS (solo texto plano) y una página con CSS moderno. |
| 01:15 - 03:00 | Anatomía de una regla CSS | Explicación en CodePen de la sintaxis: selector, propiedad, valor y punto y coma. Primera regla en vivo con `body`. |
| 03:00 - 05:15 | Selectores esenciales (Etiqueta, Clase e ID) | Demostración de selectores de tipo (`h1`), clases (`.tarjeta-perfil`) e identificadores (`#titulo-nombre`). |
| 05:15 - 07:30 | Tipografía, colores y jerarquía | Cambio de tipografía predeterminada a fuente sin serifa (*sans-serif*), uso de nombres y códigos hexadecimales para colores. |
| 07:30 - 09:30 | Espaciado y Modelo de Caja (Padding, Margin, Bordes) | Transformación del contenedor plano en una tarjeta flotante. Centrado con `margin: 0 auto` y recorte circular con `border-radius: 50%`. **Pausa activa para practicar**. |
| 09:30 - 11:00 | Interactividad con `:hover` | Añadir interactividad al botón y a la tarjeta cuando el cursor pasa por encima. |
| 11:00 - 12:00 | Errores comunes de principiantes y Cierre | Consejos para no olvidar el `;` ni el punto de las clases. Invitación a la siguiente lección. |

---

## 🎙️ Guion y Locución del Video

### [00:00 - 01:15] Introducción: De un documento aburrido a una experiencia visual
**[En pantalla: Título del tema "Lección 4: Introducción a CSS" y dos ventanas comparativas lado a lado: a la izquierda, una página HTML en blanco y negro sin estilo; a la derecha, la misma página convertida en una tarjeta de perfil moderna con colores, sombras y bordes redondeados].**

**Locución:**
> "¡Hola a todos y bienvenidos a la lección número 4 de nuestro curso de desarrollo web para principiantes!
>
> En las lecciones anteriores aprendiste a construir la estructura de una página utilizando HTML: encabezados, párrafos, listas e imágenes. Pero seamos sinceros: una página web con solo HTML parece un documento de texto antiguo en blanco y negro.
>
> Hoy entra en acción la verdadera magia visual: **CSS**, que significa *Hojas de Estilo en Cascada*.
>
> Si HTML es el esqueleto de un personaje o los ladrillos de una casa, CSS es la ropa, los colores, los peinados, la pintura y toda la personalidad visual.
>
> En los próximos 12 minutos aprenderás a transformar por completo una página web: cambiaremos colores, fuentes tipográficas, organizaremos el espacio y crearemos una tarjeta de presentación interactiva directamente en nuestro navegador. ¡Empecemos!"

---

### [01:15 - 03:00] Parte 1: El editor CodePen y la anatomía de una regla CSS
**[En pantalla: Navegador web ingresando a CodePen.io en una plantilla nueva. Se observan los paneles de HTML y CSS. En la parte inferior, la vista previa en vivo].**

**Locución:**
> "Para esta práctica no necesitas instalar absolutamente nada en tu computadora. Solo abriremos nuestro navegador y usaremos **CodePen**, un editor en línea gratuito.
>
> En la descripción del video tienes el enlace directo a nuestra plantilla inicial para que puedas programar a la par conmigo.
>
> Como puedes ver en pantalla, a la izquierda tenemos la ventana de HTML y al centro la ventana de CSS. Todo lo que escribamos en CSS se aplicará automáticamente en la vista previa inferior.
>
> Veamos cómo se escribe una regla en CSS. La fórmula es muy sencilla y siempre sigue tres elementos:
>
> 1. Primero, el **selector**: a quién queremos modificar.
> 2. Abrimos llaves `{}`.
> 3. Dentro escribimos la **propiedad**, dos puntos, el **valor** que deseamos y cerramos siempre con **punto y coma** (`;`)."

**[Acción en pantalla: Se escribe en vivo en el panel CSS mientras se resalta con zoom]:**
```css
body {
  background-color: #eef2f7;
}
```

**Locución:**
> "Observa lo que acaba de pasar: seleccionamos `body`, que representa a toda nuestra página web, y con la propiedad `background-color` le asignamos `#eef2f7`, un tono gris azulado suave. Al instante, el fondo blanco desapareció y la página adquirió un aspecto mucho más moderno y relajante a la vista."

---

### [03:00 - 05:15] Parte 2: Tipos de Selectores (Etiqueta, Clase e ID)
**[En pantalla: Se hace zoom sobre el código HTML para mostrar las clases y el id, luego se regresa al panel CSS].**

**Locución:**
> "Ahora bien: ¿cómo le decimos a CSS a qué elemento específico queremos darle estilo?
>
> Para eso existen tres tipos principales de selectores:
>
> * **Selector de etiqueta:** Como el `body` que acabamos de escribir. Si escribes `p`, afectará a todos los párrafos de tu página.
> * **Selector de clase:** En HTML podemos asignar nombres de clase a los elementos con el atributo `class`. En CSS las llamamos escribiendo un **punto** antes del nombre. Por ejemplo, `.tarjeta-perfil`. Las clases son geniales porque puedes aplicarlas a varios elementos que compartan el mismo estilo.
> * **Selector de ID:** Si un elemento tiene un identificador único con `id`, en CSS lo seleccionamos con el símbolo de almohadilla o numeral (`#`), como `#titulo-nombre`.
>
> Demos estilo ahora al contenedor principal de nuestra tarjeta usando su clase."

**[Acción en pantalla: Se escribe la regla de la tarjeta]:**
```css
.tarjeta-perfil {
  background-color: #ffffff;
  max-width: 380px;
  border-radius: 20px;
}
```

**Locución:**
> "Fíjate qué ocurrió: al escribir `.tarjeta-perfil` con un punto al inicio, le dimos fondo blanco puro (`#ffffff`), un ancho máximo de 380 píxeles para que no se estire por toda la pantalla, y con `border-radius: 20px` redondeamos suavemente sus esquinas."

---

### [05:15 - 07:30] Parte 3: Tipografía, Colores y Jerarquía Visual
**[En pantalla: Vista previa mostrando los textos que todavía tienen la tipografía predeterminada Times New Roman. Se aplica font-family y colores a los textos].**

**Locución:**
> "Por defecto, los navegadores muestran el texto con una fuente clásica llamada *Times New Roman*. Para que nuestra página luzca contemporánea, cambiaremos la familia tipográfica.
>
> Regresemos al selector `body` y agreguemos:"

**[Acción en pantalla: Añadir propiedades tipográficas en body]:**
```css
body {
  font-family: 'Segoe UI', Arial, sans-serif;
  color: #334155;
}
```

**Locución:**
> "Con `font-family` le decimos al navegador que use tipografías limpias y legibles, sin serifa (*sans-serif*). Al colocarla en el `body`, todos los textos internos heredan esta fuente automáticamente.
>
> Ahora creemos una jerarquía visual: el nombre de la persona debe destacar sobre todo lo demás, mientras que el subtítulo y la descripción deben acompañar de forma ordenada."

**[Acción en pantalla: Reglas para título, subtítulo e insignias]:**
```css
#titulo-nombre {
  color: #0f172a;
  font-size: 24px;
  margin-top: 16px;
  margin-bottom: 4px;
}

.etiqueta-rol {
  color: #2563eb;
  font-size: 14px;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.descripcion {
  color: #64748b;
  font-size: 15px;
  line-height: 1.6;
}
```

**Locución:**
> "Mira cómo cobra vida: usamos un tono azul profesional `#2563eb` para el rol, letras mayúsculas con `text-transform: uppercase` y aumentamos el espacio entre líneas con `line-height: 1.6` para que el párrafo se lea con total comodidad."

---

### [07:30 - 09:30] Parte 4: Espaciado y Modelo de Caja (Padding, Margin, Bordes)
**[En pantalla: Se ilustra el concepto del modelo de caja. Se añade padding a la tarjeta y margin: 0 auto].**

**Locución:**
> "Si miras la tarjeta en este momento, notarás dos problemas: los textos están pegados a los bordes blancos de la tarjeta, y la tarjeta está recargada a la izquierda de la pantalla.
>
> Aquí es donde entra en juego el **Modelo de Caja de CSS**:
>
> * **Padding (Relleno interno):** Es el espacio que hay desde el contenido hacia el borde interior. Es como el colchón protector dentro de una caja de regalo.
> * **Margin (Margen externo):** Es el espacio exterior que separa a nuestra caja de los demás elementos de la página."

**[Acción en pantalla: Se añade padding y margin auto a la tarjeta]:**
```css
.tarjeta-perfil {
  background-color: #ffffff;
  max-width: 380px;
  margin: 0 auto;
  padding: 30px 24px;
  text-align: center;
  box-shadow: 0 12px 30px rgba(0, 0, 0, 0.08);
}
```

**Locución:**
> "Con `padding: 30px 24px` le dimos aire y elegancia a todo el contenido interno. Con `text-align: center`, centramos los textos.
>
> Y atención a este secreto de diseño: `margin: 0 auto`. Al indicarle al navegador un margen superior de 0 y márgenes laterales automáticos, el navegador divide el espacio sobrante por igual y nuestra tarjeta queda perfectamente centrada en la pantalla.
>
> Por último, transformemos la foto cuadrada en un avatar circular perfecto:"

**[Acción en pantalla: Estilo de la imagen de avatar]:**
```css
.imagen-avatar {
  width: 110px;
  height: 110px;
  border-radius: 50%;
  border: 4px solid #3b82f6;
  object-fit: cover;
}
```

**Locución:**
> "Al aplicar `border-radius: 50%` sobre una imagen con el mismo ancho y alto, la convertimos instantáneamente en un círculo, y le agregamos un borde azul de 4 píxeles que la enmarca de forma impecable.
>
> **[Pausa activa para la práctica]:**
> En este momento, ponle pausa al video durante un par de minutos. Abre tu CodePen, ingresa a la regla `.imagen-avatar` o al `body`, e intenta cambiar el color del borde o del fondo por tu color favorito. ¡Prueba sin miedo y dale tu propio estilo!"

---

### [09:30 - 11:00] Parte 5: Botón Interactivo y Pseudo-clases (`:hover`)
**[En pantalla: Se reanuda el video. Se muestra el botón en la parte inferior de la tarjeta y se escribe su regla].**

**Locución:**
> "¿Pausaste el video y lograste cambiar tus colores? ¡Excelente! Continuemos.
>
> Toda buena tarjeta digital necesita un llamado a la acción. En nuestro HTML tenemos un `<button>` con la clase `.boton-conectar`. Por defecto, los botones del navegador se ven grises y anticuados.
>
> Vamos a diseñar un botón moderno:"

**[Acción en pantalla: Se escriben los estilos base del botón]:**
```css
.boton-conectar {
  background-color: #2563eb;
  color: #ffffff;
  border: none;
  padding: 12px 28px;
  border-radius: 10px;
  font-size: 15px;
  font-weight: 600;
  cursor: pointer;
  transition: background-color 0.2s ease, transform 0.1s ease;
}
```

**Locución:**
> "Con `cursor: pointer`, el mouse muestra la clásica manito interactiva al pasar por encima.
>
> Pero queremos que el usuario sienta que la página está viva cuando interactúa con ella. Para eso utilizamos una **pseudo-clase** llamada `:hover`. Se activa exclusivamente cuando el puntero del mouse se coloca sobre el elemento:"

**[Acción en pantalla: Se agrega la pseudo-clase hover y se pasa el puntero sobre el botón]:**
```css
.boton-conectar:hover {
  background-color: #1d4ed8;
  transform: scale(1.02);
}
```

**Locución:**
> "Observa la magia en la vista previa: al pasar el mouse sobre el botón, este cambia sutilmente a un tono azul más profundo y crece ligeramente. ¡Se siente como una aplicación profesional!"

---

### [11:00 - 12:00] Parte 6: Errores comunes de principiantes y Cierre
**[En pantalla: Diapositiva o panel de resumen visual con los tres errores más frecuentes y lista de verificación].**

**Locución:**
> "Antes de terminar, quiero compartirte tres recomendaciones de oro para evitar los errores más comunes cuando estás empezando con CSS:
>
> 1. **El punto y coma olvidado:** Cada vez que una propiedad no funcione como esperas, revisa la línea anterior. Si olvidaste el punto y coma (`;`), CSS no podrá interpretar la siguiente regla.
> 2. **El punto en las clases:** Recuerda que en el HTML escribes `class="tarjeta"`, pero en tu archivo CSS debes anteponer un punto: `.tarjeta`.
> 3. **Escribe nombres exactos:** CSS distingue mayúsculas y minúsculas en nombres de clases e identificadores. Si en HTML escribiste `tarjetaPerfil` y en CSS `.tarjetaperfil`, no se aplicará.
>
> ¡Felicidades! En esta lección aprendiste qué es CSS, cómo estructurar reglas con selectores, propiedades y valores, cómo manipular colores y tipografías, y cómo aplicar el modelo de caja con rellenos, bordes y centrado.
>
> En la siguiente lección, combinaremos todo lo aprendido en HTML y CSS para construir un proyecto completo paso a paso.
>
> No olvides guardar tu trabajo en CodePen. ¡Nos vemos en el próximo video!"
