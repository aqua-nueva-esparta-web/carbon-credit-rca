# Blueprint: AGROPOLI RDC Website (Versión 1.0)

## 1. Visión General del Proyecto

El sitio web de AGROPOLI RDC es una página web estática e informativa diseñada para presentar la misión de la iniciativa, mostrar su modelo operativo en la República Democrática del Congo y detallar el rol de los socios clave que respaldan el proyecto. Sirve como un punto de contacto digital profesional para stakeholders, potenciales inversores y el público general interesado en proyectos de desarrollo sostenible y créditos de carbono.

---

## 2. Esquema del Proyecto y Características Implementadas

Esta sección documenta la arquitectura, el diseño y las funcionalidades del sitio web en su estado actual.

### 2.1. Pila Tecnológica
- **Lenguajes:** HTML5, CSS3
- **Estilo:** CSS plano con uso de Variables CSS (`:root`) para una temática consistente.
- **Tipografía:** `Montserrat` importada desde Google Fonts.
- **Principios de Diseño:** Diseño responsivo (Mobile-First), centrado en la claridad visual y la coherencia de la marca.

### 2.2. Estructura de Archivos Final
```
/
├── index.html              # Página principal de aterrizaje (Landing Page)
├── estilos.css             # Hoja de estilos para las páginas de socios
├── socio-capitalimprese.html # Página de detalle del socio Capitalimprese
├── socio-arioli.html       # Página de detalle del socio Instituto Arioli
└── socio-blotix.html       # Página de detalle del socio Blotix Fund LLC
```

### 2.3. Diseño y Componentes

#### A. Página Principal (`index.html`)

- **Sección Hero de Portada:**
    - Usa `min-height: 100vh` para ocupar toda la pantalla y expandirse si el contenido es grande, evitando superposiciones.
    - **Fondo:** Imagen fija (`GQj3J5Q.png`) con superposición oscura para legibilidad.
    - **Contenido Centrado:** Logo, títulos y párrafo descriptivo centrados vertical y horizontalmente.
    - **Títulos Fluidos:** `clamp()` para `h1` y `h2` asegura una tipografía adaptable.
- **Sección del Modelo AGROPOLI:** Presenta el modelo de negocio con texto y un mapa del proyecto.
- **Sección de Socios:** Rejilla responsiva con los logos de los socios que enlazan a sus páginas de detalle.

#### B. Páginas de Socios (`socio-*.html`)

- **Plantilla Consistente:** Usan `estilos.css` para una apariencia unificada.
- **Navegación:** Barra superior para volver a la página principal.
- **Contenido Flotante:** Sección principal con fondo semi-transparente que destaca sobre el fondo de la página.

---

## 3. Historial de Finalización (Versión 1.0)

- **Objetivo Final:** Consolidar el diseño, corregir todos los errores visuales y establecer una versión estable del sitio web.
- **Pasos de Finalización:**
    1.  **Aislamiento de Estilos:** Se encapsularon los estilos de `index.html` para evitar conflictos.
    2.  **Ajustes de Diseño en Portada:** Se refinó el tamaño del logo, la tipografía y el espaciado de los textos.
    3.  **Eliminación de Elementos:** Se quitó el botón CTA de la portada para un diseño más limpio.
    4.  **Corrección de Superposición (Error #1):** Se ajustaron los márgenes entre el subtítulo y el párrafo de la portada.
    5.  **Corrección de Desbordamiento (Error #2 - Final):** Se cambió `height: 100vh` por `min-height: 100vh` en la sección de la portada para solucionar definitivamente el problema de superposición de contenido en diferentes tamaños de pantalla.
    6.  **Creación del Punto de Restauración:** El proyecto se ha documentado y guardado en este estado estable (v1.0).
