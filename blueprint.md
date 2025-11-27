# Blueprint: Agropoli Republica Centro Africana

## Visión General

Este proyecto es un sitio web estático de una sola página para "Agropoli Republica Centro Africana". El sitio presenta la misión de la empresa, que se centra en la generación de créditos de carbono de alta calidad en la República Centroafricana a través de un modelo de desarrollo sostenible. También destaca a sus socios estratégicos.

## Estructura del Proyecto

*   `index.html`: La página de inicio principal.
*   `style.css`: La hoja de estilos principal para la página de inicio.
*   `estilos.css`: Una hoja de estilos compartida para las páginas de los socios y proyectos.
*   `proyecto-redd.html`: Página de detalles para el proyecto REDD+.
*   `socio-capitalimprese.html`: Página de detalles para el socio Capitalimprese.
*   `socio-arioli.html`: Página de detalles para el socio Instituto Arioli.
*   `socio-blotix.html`: Página de detalles para el socio Blotix Fund LLC.
*   `assets/`: Directorio para imágenes y otros recursos (actualmente usando imgur).

## Diseño y Estilo

*   **Tipografía:** Montserrat de Google Fonts.
*   **Colores:** Paleta de verdes y blancos, evocando naturaleza y sostenibilidad.
*   **Diseño:** Limpio y moderno, con una sección de héroe prominente, seguida de secciones para el modelo de negocio y los socios.
*   **Iconografía:** Se utilizan emojis (🌱) para dar un toque orgánico a las listas en la página del proyecto.

## Funcionalidad

*   Navegación a las páginas de los socios y proyectos desde la página principal.
*   Diseño receptivo para una buena visualización en dispositivos móviles y de escritorio.
*   Gráfico de distribución de créditos interactivo en la página del proyecto REDD+ usando Chart.js.

## Plan de Desarrollo Actual

*   **Tarea:** Añadir un diagrama circular para la distribución de créditos y cambiar las viñetas por un icono de planta en la página `proyecto-redd.html`.
*   **Pasos:**
    1.  Añadir la librería Chart.js desde un CDN a `proyecto-redd.html`.
    2.  Insertar un elemento `<canvas>` para el gráfico.
    3.  Añadir un script para crear un gráfico de tipo "doughnut" que muestre la distribución de créditos (65.1% Gobierno de la RCA, 34.9% Inversores Privados).
    4.  Añadir CSS para eliminar los estilos de lista por defecto y usar el emoji '🌱' como viñeta.
    5.  Actualizar este `blueprint.md`.
