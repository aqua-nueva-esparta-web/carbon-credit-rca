# Blueprint: República Centroafricana - Créditos de Carbono

## Visión General

Este proyecto es un sitio web estático para una iniciativa centrada en la generación de créditos de carbono a través de un modelo de desarrollo sostenible en la República Centroafricana. El sitio web tiene como objetivo proporcionar información sobre el proyecto, sus socios y el impacto que busca generar.

## Estilo y Diseño

El diseño es moderno y limpio, con un enfoque en la legibilidad y el impacto visual.

*   **Paleta de Colores:** Primario: `#2c3e50`, Secundario: `#ffffff`, Acento: `#2ECC71`.
*   **Tipografía:** 'Montserrat', sans-serif.
*   **Animaciones:** Sutiles efectos de `fadeIn` para la carga de contenido.
*   **Imágenes:** Se utiliza `loading="lazy"` para optimización.
*   **Favicon:** Presente en todas las páginas.

## Plan de Desarrollo

### Tareas Completadas

*   **Consolidación de Estilos:** Unificado todos los estilos en `style.css`.
*   **Ajustes de Diseño:**
    *   Centrado y dimensionado del mapa en la página principal.
    *   Añadido favicon y animaciones.
    *   Optimización de carga de imágenes.
*   **Actualización de Contenido:** Actualizado el enlace al registro de Pepitee.
*   **Despliegue Continuo:** Configurado el despliegue automático en Firebase Hosting después de cada cambio.

### Próximos Pasos

El plan actual es enriquecer el contenido y la estructura del sitio para mejorar la navegación y la interacción del usuario.

1.  **Crear Página Central de Socios (`socios.html`):**
    *   Diseñar una página que liste a todos los socios del proyecto.
    *   Cada socio tendrá una "tarjeta" con su logo, una breve descripción y un enlace a su página de detalle.
    *   Esto mejorará la navegación y dará una visión general de las alianzas.
2.  **Añadir Página de Contacto (`contacto.html`):**
    *   Crear una página con información de contacto.
    *   Implementar un formulario de contacto funcional (esto puede requerir un backend simple o un servicio de terceros como Formspree).
3.  **Actualizar la Navegación:**
    *   Añadir enlaces a las nuevas páginas (`Socios` y `Contacto`) en la barra de navegación de todo el sitio.

## Estructura del Proyecto

*   `index.html`: La página de inicio.
*   `socio-arioli.html`: Detalle del socio Instituto de Investigación Arioli.
*   `socio-blotix.html`: Detalle del socio Blotix Fund LLC.
*   `socio-capitalimprese.html`: Detalle del socio CAPITALIMPRESE.
*   `proyecto-redd.html`: Detalle del Proyecto REDD+.
*   `style.css`: Hoja de estilos principal.
*   `404.html`: Página de error 404.
*   `blueprint.md`: Este archivo.
