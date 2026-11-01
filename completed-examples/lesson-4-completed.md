# Clase 4 - Introducción a CSS: Colores, Fuentes y Diseño (Completed)

Este documento contiene la solución completa, explicada y lista para producción de la lección 4.

---

## 💻 Código Completo Resuelto

A continuación se presenta el código final que transforma una estructura HTML plana en una tarjeta de perfil visualmente profesional y moderna en **CodePen**:

### Estructura HTML (`index.html`)
```html
<div class="contenedor-principal">
  <div class="tarjeta-perfil">
    <img 
      src="https://images.unsplash.com/photo-1535713875002-d1d0cf377fde?w=150&auto=format&fit=crop&q=80" 
      alt="Avatar de usuario" 
      class="imagen-avatar"
    >
    
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

### Reglas de Estilo CSS (`styles.css`)
```css
/* ==========================================================
   CLASE 4: INTRODUCCIÓN A CSS - CÓDIGO COMPLETO RESUELTO
   ========================================================== */

/* 1. CONFIGURACIÓN GENERAL Y SELECTOR DE ETIQUETA */
body {
  font-family: 'Segoe UI', Arial, sans-serif;
  background-color: #eef2f7;
  color: #334155;
  margin: 0;
  padding: 40px 20px;
}

/* 2. CONTENEDOR DE TARJETA CON CENTRADO Y SOMBRA */
.tarjeta-perfil {
  background-color: #ffffff;
  max-width: 380px;
  margin: 0 auto;
  padding: 30px 24px;
  border-radius: 20px;
  text-align: center;
  box-shadow: 0 12px 30px rgba(0, 0, 0, 0.08);
  border: 1px solid #e2e8f0;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.tarjeta-perfil:hover {
  transform: translateY(-4px);
  box-shadow: 0 16px 36px rgba(0, 0, 0, 0.12);
}

/* 3. AVATAR CIRCULAR CON BORDE */
.imagen-avatar {
  width: 110px;
  height: 110px;
  border-radius: 50%;
  border: 4px solid #3b82f6;
  object-fit: cover;
  box-shadow: 0 4px 10px rgba(59, 130, 246, 0.25);
}

/* 4. TIPOGRAFÍA Y JERARQUÍA VISUAL */
#titulo-nombre {
  color: #0f172a;
  font-size: 24px;
  margin-top: 16px;
  margin-bottom: 4px;
  font-weight: 700;
}

.etiqueta-rol {
  color: #2563eb;
  font-size: 14px;
  font-weight: 600;
  margin-top: 0;
  margin-bottom: 16px;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.descripcion {
  color: #64748b;
  font-size: 15px;
  line-height: 1.6;
  margin-bottom: 20px;
}

/* 5. SECCIÓN DE INTERESES (INSIGNIAS / CHIPS) */
.seccion-intereses {
  margin-bottom: 24px;
}

.insignia {
  display: inline-block;
  background-color: #f1f5f9;
  color: #475569;
  padding: 6px 14px;
  border-radius: 999px;
  font-size: 12px;
  font-weight: 600;
  margin: 3px;
  border: 1px solid #e2e8f0;
}

/* 6. BOTÓN INTERACTIVO */
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

.boton-conectar:hover {
  background-color: #1d4ed8;
  transform: scale(1.02);
}

.boton-conectar:active {
  transform: scale(0.98);
}
```

---

## 🖥️ Resultado Visual Esperado en el Navegador

Al visualizar la página web resultante:
1. **Fondo suave:** La pantalla completa luce un tono gris azulado claro (`#eef2f7`), que descansa la vista y destaca el contenido central.
2. **Tarjeta centrada:** Una caja blanca flotante de 380 píxeles de ancho máximo, perfectamente centrada horizontalmente mediante `margin: 0 auto`, con bordes redondeados y una sutil sombra tridimensional (`box-shadow`).
3. **Avatar circular:** La foto del usuario se recorta en un círculo impecable mediante `border-radius: 50%` y tiene un borde azul decorativo.
4. **Jerarquía de textos:** El título resalta en tono oscuro (`#0f172a`), el subtítulo de rol en azul informativo (`#2563eb`), y la descripción en un gris equilibrado para una lectura cómoda.
5. **Insignias estilizadas:** Tres etiquetas en forma de píldora redondeada para las habilidades del estudiante.
6. **Interactividad:** Cuando el usuario pasa el puntero del mouse sobre el botón "Conectar", este cambia a un azul más intenso y realiza una microanimación de pulsación.

---

## 🔍 Explicación Paso a Paso de las Propiedades y Selectores

### 1. El Selector de Etiqueta (`body`)
* Se encarga de aplicar los estilos base a todo el documento.
* Al declarar `font-family: 'Segoe UI', Arial, sans-serif;`, garantizamos que toda la página use una tipografía moderna y sin serifa (*sans-serif*), eliminando la fuente predeterminada del navegador (*Times New Roman*).

### 2. Centrado y Modelo de Caja (`.tarjeta-perfil`)
* `max-width: 380px;`: Evita que la tarjeta se extienda ocupando todo el ancho de pantallas de computadoras o tabletas.
* `margin: 0 auto;`: Es el truco clásico y más confiable para centrar un elemento de bloque: indica 0 píxeles arriba y abajo, y calcula automáticamente (`auto`) márgenes idénticos a la izquierda y derecha.
* `padding: 30px 24px;`: Crea un respiro interno para que los textos y elementos no queden pegados al borde de la tarjeta blanca.

### 3. Recorte Circular (`.imagen-avatar`)
* Una imagen cuadrada adquiere forma circular al asignarle `border-radius: 50%`.
* La propiedad `object-fit: cover;` asegura que la fotografía conserve sus proporciones y no se deforme al adaptarse a los 110 píxeles de ancho y alto.

### 4. La Pseudo-clase de Interacción (`:hover`)
* Las pseudo-clases en CSS se escriben con dos puntos (`:`) y definen el estilo de un elemento cuando se encuentra en un estado específico.
* `.boton-conectar:hover`: Solo se activa cuando el puntero del cursor se sitúa encima del botón, brindando retroalimentación visual al usuario antes de hacer clic.
