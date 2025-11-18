# Frontend Mentor - Order Summary Card Solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-card-QlWdhrk7_). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size.
- See hover states for all interactive elements (buttons and link).

### Screenshot

![Screenshot of the completed Order Summary Card](design/Diseño%20sin%20título.png)

### Links

- **URL del Repositorio:**  [GitHub]
- **URL del Sitio en Vivo:** [GitHub Pages]

## My process

### Built with

- **Maquetado semántico:** Uso de las etiquetas `<main>` y `<footer>` (Landmarks).
- **CSS Custom Properties (Variables):** Para manejar la paleta de colores.
- **Flexbox:** Para el centrado del `body` (`flex-direction: column`) y la alineación horizontal de la caja del plan (`.plan-container`).
- **Unidades:** Uso de **`rem`** para asegurar la escalabilidad.
- **Flujo de trabajo Mobile-First:** Uso de media queries para el fondo (`@media (max-width: 500px)`).

### What I learned

Mi mayor aprendizaje en este proyecto fue depurar problemas de estructura y **especificidad de CSS**.

1.  **Dominio de la Especificidad:** La lección más crítica fue que mis reglas CSS no se aplicaban (o no se veían) porque su **especificidad era demasiado baja**. Corregí esto usando selectores encadenados (`.card-content .card-title`) para asegurar que mis estilos personalizados anularan los estilos predeterminados del navegador.
2.  **Solución del Layout (Flexbox vs. Bloqueo):** Descubrí que el `body` requiere **`flex-direction: column`** para apilar la tarjeta (`<main>`) y la atribución (`<footer>`), ya que un simple `display: flex` los pone en una fila horizontal.
3.  **Depuración Estructural:** Solucioné el problema de que el layout del plan estuviera roto (vertical) al confirmar la implementación de **`display: flex`** y **`justify-content: space-between`** en el `.plan-container`.
4.  **Rutas y Activos:** Reforcé la importancia de enlazar correctamente la fuente de Google Fonts (`<link>`) y de mantener las rutas de imágenes correctas (`images/...`) para que el fondo de ondas y las ilustraciones se carguen.

### Continued development

Quiero seguir enfocándome en:

1.  **Maquetación Avanzada:** Explorar **CSS Grid** para el siguiente proyecto, para crear estructuras bidimensionales complejas.
2.  **JavaScript:** Empezar a integrar JavaScript para añadir interactividad real y lógica a mis soluciones.
3.  **Accesibilidad Proactiva:** Continuar implementando las mejores prácticas de accesibilidad (`aria-label`, `prefers-reduced-motion`) como configuración por defecto.

### Useful resources

- [MDN Web Docs - Especificidad CSS](https://developer.mozilla.org/es/docs/Web/CSS/Specificity)
- [Google Fonts](https://fonts.google.com/)

## Author

- **Frontend Mentor** - [@jesussantos210](https://www.frontendmentor.io/profile/jesussantos210)