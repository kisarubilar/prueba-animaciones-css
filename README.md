# Bake Today - Landing Page & Galería Interactiva 🥞✨

Bienvenido a **Bake Today**, una interfaz web comercial y responsiva inspirada en un concepto estético retro y minimalista para una marca boutique de repostería y mezclas orgánicas de pancakes. 

Este proyecto fue desarrollado utilizando metodologías avanzadas de maquetación web, priorizando la fluidez de los contenedores, la adaptabilidad de la pantalla y la implementación de microinteracciones fluidas mediante transiciones y transformaciones en CSS puro.

---

## 🚀 Demostración en Vivo

Puedes explorar la interfaz completa, interactuar con los componentes y evaluar el comportamiento responsivo en tiempo real a través del despliegue en **GitHub Pages**:

👉 **[Ver el Sitio Web en Vivo Aquí](https://kisarubilar.github.io/prueba-animaciones-css/)**

---

## 🛠️ Arquitectura Técnica y Contenidos Aplicados

La construcción de este sitio web se divide en los siguientes pilares técnicos:

### 1. Maquetación Híbrida Adaptativa (Grid macro + Flexbox interno)
* **Estructura Macro (CSS Grid):** Se definió un sistema de rejilla bidimensional que distribuye las áreas principales (`nav`, `main`, `footer`). El comportamiento muta drásticamente según el dispositivo: en pantallas móviles el menú se consolida en la cabecera superior horizontal, mientras que en pantallas de escritorio se convierte en una barra lateral (*sidebar*) fija a la izquierda.
* **Componentes Flexibles (Flexbox):** Utilizado para la alineación precisa de elementos internos como los enlaces de navegación, la simetría de las tarjetas de productos y la distribución de redes sociales en el pie de página.

### 2. Animaciones, Transiciones y Transformaciones en CSS3
* **Filtros Dinámicos de Imagen:** La galería de productos implementa un estado inicial pasivo en escala de grises (`grayscale(100%)`). Al posicionar el cursor (`:hover`), se aplica una transición suavizada mediante curvas Bézier para recuperar el color real del producto.
* **Profundidad Espacial (Transform):** Las tarjetas y las imágenes reaccionan al movimiento del cursor aplicando efectos de escalado óptico (`scale`) y desplazamientos en el eje vertical (`translateY`), generando una sensación de relieve.
* **Animaciones Continuas (`@keyframes`):** El isotipo principal de la marca incluye una rotación infinita, sutil y automatizada que añade dinamismo visual a la identidad corporativa.

### 3. Diseño de Marca y Coherencia Visual
* **Paleta de Colores:** Uso estricto de colores de marca basados en la referencia de diseño (tonos terracota profundos y fondos crema retro) para asegurar una alta legibilidad, estética orgánica y contraste óptimo.
* **Tipografía:** Integración estratégica de fuentes a través de Google Fonts, combinando estilos *Serif* expresivos para títulos con tipografías de alta lectura para textos descriptivos y precios.

---
_Desarrollado por Kisa Rubilar Leal_
