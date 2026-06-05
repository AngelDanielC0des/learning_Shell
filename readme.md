# LearningShell_LegacyLayout

¡Bienvenido a **LearningShell_LegacyLayout**! Este proyecto está pensado para practicar HTML, CSS y JavaScript con una base clásica de maquetación, antes de apoyarse en herramientas de layout más modernas.

## 🚀 El objetivo del proyecto
Este portal no es solo una página web; funciona como una colección de ejemplos para estudiar cómo se construye la interfaz con HTML semántico, CSS y JavaScript vanilla.

### 🧠 ¿Por qué no se ha usado Flexbox o Grid?
A diferencia de muchos cursos modernos, este proyecto se ha construido sin usar Flexbox ni CSS Grid en su estructura principal (salvo en una lección final avanzada).

La idea es practicar el flujo normal del documento, el modelo de caja, el posicionamiento absoluto/relativo y técnicas clásicas de alineación como `display: table` e `inline-block`. Entender ese comportamiento ayuda a leer mejor cómo funciona la web por debajo de las capas de abstracción.

---

## 🗺️ Índice de contenidos y aprendizajes

Este proyecto está organizado como una guía de estudio. Aquí tienes el mapa general de lo que incluye y dónde encontrarlo:

### 📄 CAPÍTULO 1: Anatomía y estructura HTML
- **Anatomía de una etiqueta** (apertura, elemento, atributo, valor) -> [index.html](./index.html)
- **Configuración del `<head>`**:
  - `<!DOCTYPE html>`: preparación del motor de renderizado -> [index.html](./index.html)
  - `<meta charset="utf-8">`: codificación de caracteres -> [index.html](./index.html)
  - `<meta name="viewport">`: configuración base para mobile first -> [index.html](./index.html)
  - `<meta name="description">`: meta descripción y SEO básico -> [index.html](./index.html)
  - `<link rel="preconnect">`: optimización de conexión y carga -> [index.html](./index.html)

- **Estructura semántica de contenido**:
  - `<header>` vs `<head>`: cabecera visible frente a metadatos -> [index.html](./index.html)
  - `<main>`: contenido principal de la página -> [index.html](./index.html)
  - `<section>` vs `<article>`: bloques temáticos frente a contenido autónomo -> [index.html](./index.html)
  - `<figure>` y `<figcaption>`: imágenes y leyendas -> [index.html](./index.html)
  - `<template>`: creación de moldes de DOM inerte para JavaScript -> [index.html](./index.html)
  - `<footer>`: información final y créditos -> [index.html](./index.html)
  - **Listas anidadas**: jerarquías de datos -> [index.html](./index.html)

- **Elementos y atributos especiales**:
  - `<marquee>`: ejemplo de etiqueta deprecada y advertencia de accesibilidad -> [index.html](./index.html)
  - `<kbd>`: marcado semántico de teclado -> [index.html](./index.html)
  - `<button>` vs `<a>`: acción frente a navegación -> [index.html](./index.html)
  - `&copy;` y entidades HTML: uso de símbolos especiales -> [index.html](./index.html)
  - `target="_blank"` y `rel="noopener noreferrer"`: seguridad en enlaces externos -> [index.html](./index.html)
  - `data-attributes`: atributos de datos personalizados (`data-title`) -> [index.html](./index.html)
  - **Emoji-Favicon (SVG Data URI)**: iconografía dinámica sin archivos externos -> [index.html](./index.html)
  - **URL Encoding**: limpieza de sintaxis sin perder legibilidad -> [index.html](./index.html)
  - **Geometría de favicon**: centrado absoluto y escalas de seguridad para evitar recortes -> [index.html](./index.html)

### ♿ CAPÍTULO 2: Accesibilidad universal (A11y)
- `lang="es-ES"`: útil para síntesis de voz -> [index.html](./index.html)
- `aria-hidden`: ocultar adornos visuales a lectores de pantalla -> [index.html](./index.html)
- `aria-live` (polite): actualizaciones dinámicas sin interrumpir al usuario -> [index.html](./index.html)
- `aria-haspopup`: aviso de menús emergentes -> [index.html](./index.html)
- Landmarks y roles: identificación de regiones de navegación -> [index.html](./index.html)
- `tabindex` y WAI-ARIA: elementos estructurales hechos interactivos (`role="button"`) -> [index.html](./index.html)

### ⚡ CAPÍTULO 3: Interactividad y lógica (JavaScript vanilla)
- **Arquitectura del DOM**:
  - `document` y `addEventListener`: manejo de eventos -> [index.html](./index.html)
  - `Event Bubbling`: recorrido del evento hacia arriba -> [index.html](./index.html)
  - `Event Delegation`: un único listener para varios elementos -> [index.html](./index.html)

- **Manipulación de nodos y datos**:
  - `closest()`: búsqueda de ancestros -> [index.html](./index.html)
  - `classList.toggle()`: alternancia de estados visuales -> [index.html](./index.html)
  - `cloneNode(true)`: clonación profunda de plantillas -> [index.html](./index.html)
  - `textContent` vs `innerHTML`: inserción segura de contenido -> [index.html](./index.html)
  - **TagName filtering**: lógica selectiva según el tipo de etiqueta -> [index.html](./index.html)

- **Animación y control en JS**:
  - `requestAnimationFrame()`: sincronización con el refresco del monitor -> [index.html](./index.html)
  - `Double requestAnimationFrame`: forzar el pintado de estados iniciales -> [index.html](./index.html)
  - `Operador % (módulo)`: creación de bucles en arrays -> [index.html](./index.html)
  - `setTimeout()`: persistencia y latencia visual -> [index.html](./index.html)
  - **Fetch API**: carga dinámica de recursos externos (`.json`) -> [index.html](./index.html)
  - **Async / Await**: gestión de flujos asíncronos -> [index.html](./index.html)
  - **CORS**: seguridad y protocolos (`file://` vs `http://`) -> [index.html](./index.html)
  - **Try/Catch**: resiliencia ante fallos -> [index.html](./index.html)
  - **JSON**: formato de intercambio de datos -> [index.html](./index.html)
  - **Objeto Event**: datos asociados a la interacción del usuario -> [index.html](./index.html)
  - **Estados HTTP (`.ok`)**: comunicación básica entre cliente y servidor -> [index.html](./index.html)

### 🎨 CAPÍTULO 4: CSS, diseño y composición
- **Fundamentos de arquitectura**:
  - **Variables globales (`:root`)**: sistema de design tokens -> [styles/style.css](./styles/style.css)
  - **Reseteo universal (`*`)**: estandarización del renderizado -> [styles/style.css](./styles/style.css)
  - **Modelo de caja**: uso de `box-sizing: border-box` -> [styles/style.css](./styles/style.css)
  - **Propiedades shorthand**: optimización de declaraciones -> [styles/style.css](./styles/style.css)

- **Layout y posicionamiento**:
  - **Arquitectura Flex-Mirror (Footer)**: introducción práctica a Flexbox y ejes espaciales -> [styles/style.css](./styles/style.css)
  - **Display table/cell**: centrado vertical clásico -> [styles/style.css](./styles/style.css)
  - **Inline-block & font-size: 0**: eliminación de espacios residuales -> [styles/style.css](./styles/style.css)
  - **Posicionamiento (relative/absolute)**: capas y anclajes -> [styles/style.css](./styles/style.css)
  - **Z-index**: gestión del eje Z en pantallas 2D -> [styles/style.css](./styles/style.css)
  - **Overflow: hidden**: ocultación de paneles o contenido sobrante -> [styles/style.css](./styles/style.css)

- **Ingeniería visual y UX**:
  - **Texturas avanzadas**: `background-clip: text` y gradientes -> [styles/style.css](./styles/style.css)
  - **Efecto neón y 3D**: superposición de `text-shadow` múltiples -> [styles/style.css](./styles/style.css)
  - **Lentes fotográficas**: `filter` (`blur`, `contrast`, `brightness`, `saturate`) -> [styles/style.css](./styles/style.css)
  - **Skeuomorfismo & glow inset**: volumen físico y luz interna -> [styles/style.css](./styles/style.css)
  - **UI cursor logic**: punteros contextuales (`cursor: help/pointer`) -> [styles/style.css](./styles/style.css)
  - **Pointer-events**: interactividad en capas superpuestas -> [styles/style.css](./styles/style.css)
  - **Focus-visible**: accesibilidad por teclado -> [styles/style.css](./styles/style.css)

- **Lógica de especificidad**:
  - `!important`: prioridad absoluta -> [styles/style.css](./styles/style.css)
  - **Opacity vs visibility**: técnicas para ocultar elementos de la UI -> [styles/style.css](./styles/style.css)

---

## 🛠️ Tecnologías utilizadas
- **HTML5 puro**: estructura semántica sin abuso de `div`.
- **Vanilla CSS**: sin frameworks (Tailwind, Bootstrap) para mantener control sobre el layout.
- **JavaScript vanilla**: lógica para gestión de estados y eventos de teclado.

---

> [!TIP]
> **Nota para el estudiante**: no tengas miedo de romper el código. La web se aprende inspeccionando, probando y entendiendo por qué una caja está donde está.

---
**Hecho con 💙 por Ángel Daniel & Antigravity AI**
