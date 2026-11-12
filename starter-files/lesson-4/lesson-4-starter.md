# Clase 4 - Introducción a CSS: Colores, Fuentes y Diseño (Starter)

Este documento sirve como guía para la lección práctica y contiene las plantillas de código inicial que los estudiantes utilizarán durante la clase 4 en el editor en línea **CodePen**.

---

## Objetivo de la Lección
Aprender los fundamentos del diseño web visual utilizando **CSS** (*Cascading Style Sheets*):
1. **Comprender qué es CSS y su rol:** Transformar la estructura básica de HTML en una experiencia visual atractiva.
2. **Sintaxis y reglas de CSS:** Selectores, propiedades y valores.
3. **Tipos de selectores esenciales:** Por etiqueta (`body`, `h1`), por clase (`.tarjeta`, `.boton`) y por identificador (`#titulo-principal`).
4. **Propiedades de estilo fundamentales:** Colores de texto y fondo, familias tipográficas, alineación de texto, bordes y espaciado inicial (*padding* y *margin*).

---

## Conceptos Clave

### 1. ¿Qué es CSS?
Si **HTML** representa los cimientos y el esqueleto de una casa (las paredes, puertas y habitaciones), **CSS** es la pintura, la decoración, el estilo y los acabados que hacen que luzca moderna y agradable.

### 2. Anatomía de una Regla CSS
Cada instrucción en CSS sigue una estructura precisa:

```css
selector {
    propiedad: valor;
}
```

* **Selector:** Indica a qué elemento o elementos de la página deseamos dar estilo (ej. `h1`, `.tarjeta`).
* **Propiedad:** La característica visual que queremos modificar (ej. `color`, `background-color`, `font-size`).
* **Valor:** El nuevo ajuste que le asignamos a la propiedad (ej. `blue`, `#3498db`, `24px`).
* **Punto y coma (`;`):** Es obligatorio al final de cada declaración para separar una propiedad de otra.

### 3. Tipos de Selectores Básicos
* **Selector de etiqueta / tipo:** Aplica el estilo a todas las etiquetas de ese nombre en la página (ej. `p { font-size: 16px; }`).
* **Selector de clase (`.`):** Aplica a cualquier elemento que tenga el atributo `class="..."` (ej. `.destacado { color: orange; }`). Es ideal para reutilizar estilos en varios elementos.
* **Selector de ID (`#`):** Aplica a un elemento único con el atributo `id="..."` (ej. `#perfil-usuario { border: 2px solid black; }`).

### 4. Propiedades Principales a Practicar
* `color`: Cambia el color del texto.
* `background-color`: Establece el color de fondo.
* `font-family`: Define la tipografía (ej. `Arial, sans-serif`).
* `text-align`: Alinea el texto al centro, izquierda o derecha (`center`, `left`, `right`).
* `padding`: Espacio o relleno interno entre el contenido y el borde.
* `margin`: Margen exterior que separa el elemento de otros componentes.
* `border`: Línea de borde alrededor del elemento (grosor, tipo y color).
* `border-radius`: Curvatura en las esquinas para crear bordes redondeados modernos.

---

## Código Inicial (Starter)

Abre [CodePen.io](https://codepen.io/editor/Miguel-Jara-the-scripter/pen/01a198fd-c3e1-79eb-b8a1-015dcb40f0c0) y copia el código correspondiente en cada panel:

### Panel HTML
```html
<div class="contenedor-principal">
  <div class="tarjeta-perfil">
    <img src="https://images.unsplash.com/photo-1535713875002-d1d0cf377fde?w=150&auto=format&fit=crop&q=80" alt="Avatar de usuario" class="imagen-avatar">
    
    <h1 id="titulo-nombre">Alex Rivera</h1>
    <p class="etiqueta-rol">Estudiante & Futuro Desarrollador Web</p>
    
    <p class="descripcion">
      ¡Hola! Me apasiona la tecnología, los videojuegos de estrategia y crear páginas web interactivas. Bienvenido a mi espacio digital.
    </p>

    <div class="seccion-intereses">
      <span class="insignia">HTML5</span>
      <span class="insignia">CSS3</span>
      <span class="insignia">Gaming</span>
    </div>

    <button class="boton-conectar">Conectar</button>
  </div>
</div>
```

### Panel CSS (Plantilla con instrucciones guía)
```css
/* ==========================================================
   CLASE 4: INTRODUCCIÓN A CSS - CÓDIGO INICIAL (STARTER)
   ========================================================== */

/* 1. ESTILO GENERAL DE LA PÁGINA (Selector de etiqueta) */
body {
  /* TODO 1: Cambia la tipografía a una fuente limpia como Arial, sans-serif */
  font-family: Arial, sans-serif;
  
  /* TODO 2: Agrega un color de fondo agradable a la página (ej. #eef2f7 o lightcyan) */
  background-color: #eef2f7;

  margin: 0;
  padding: 40px 20px;
}

/* 2. CONTENEDOR DE LA TARJETA (Selector de clase) */
.tarjeta-perfil {
  /* TODO 3: Asigna un fondo blanco puro a la tarjeta */
  /* background-color: white; */

  /* TODO 4: Define un ancho máximo de 360px y céntralo con margin: 0 auto */
  /* max-width: 360px; */
  /* margin: 0 auto; */

  /* TODO 5: Agrega relleno interno (padding) de 25px */
  /* padding: 25px; */

  /* TODO 6: Redondea las esquinas con border-radius de 16px */
  /* border-radius: 16px; */

  /* TODO 7: Centra todo el texto dentro de la tarjeta con text-align */
  /* text-align: center; */
}

/* 3. IMAGEN DE AVATAR */
.imagen-avatar {
  width: 110px;
  height: 110px;
  
  /* TODO 8: Convierte la imagen en un círculo perfecto usando border-radius: 50% */
  /* border-radius: 50%; */
  
  /* TODO 9: Agrega un borde decorativo (ej. 4px solid #3b82f6) */
  /* border: 4px solid #3b82f6; */
}

/* 4. TÍTULOS Y TEXTOS */
#titulo-nombre {
  /* TODO 10: Dale un color azul marino oscuro al nombre (ej. #1e293b) */
  /* color: #1e293b; */
  margin-top: 15px;
  margin-bottom: 5px;
}

.etiqueta-rol {
  /* TODO 11: Dale un color vibrante al rol y peso de fuente negrita */
  /* color: #3b82f6; */
  /* font-weight: bold; */
  margin-top: 0;
}

.descripcion {
  /* TODO 12: Ajusta el color del texto descriptivo a un gris legible (#64748b) */
  /* color: #64748b; */
  line-height: 1.5;
}

/* 5. INSIGNIAS DE INTERÉS */
.insignia {
  display: inline-block;
  background-color: #e2e8f0;
  color: #334155;
  padding: 5px 12px;
  border-radius: 20px;
  font-size: 13px;
  margin: 3px;
}

/* 6. BOTÓN DE ACCIÓN */
.boton-conectar {
  /* TODO 13: Dale estilo al botón */
  /* background-color: #3b82f6; */
  /* color: white; */
  /* border: none; */
  /* padding: 10px 24px; */
  /* border-radius: 8px; */
  /* font-size: 15px; */
  /* cursor: pointer; */
  /* margin-top: 20px; */
}
```

---

## Retos Prácticos para el Estudiante
1. **Personaliza los colores:** Cambia el color de fondo general de la página por tu color favorito utilizando un código hexadecimal (por ejemplo, `#fdf2e9` para tono durazno o `#ecfdf5` para tono menta).
2. **Sombra moderna a la tarjeta:** Investiga y agrega la propiedad `box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);` dentro de `.tarjeta-perfil` para que la tarjeta parezca flotar sobre el fondo.
3. **Efecto interactivo con pseudo-clase `:hover`:** Añade la regla `.boton-conectar:hover { background-color: #1d4ed8; }` para que el botón cambie de tono cuando pases el cursor sobre él.
