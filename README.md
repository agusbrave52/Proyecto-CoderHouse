# Hering | Entrega Final Desarrollo Web

Proyecto académico desarrollado como entrega final del curso de Desarrollo Web en Coderhouse. El sitio representa una tienda online de indumentaria para toda la familia, con una propuesta visual orientada a ecommerce, navegación responsive y secciones informativas para explorar productos, sucursales y contacto.

## Descripción

Hering es un sitio web estático construido con HTML, CSS y SCSS, pensado para simular la experiencia de una marca de ropa con catálogo, promociones destacadas y acceso a tiendas físicas. La interfaz fue trabajada con una estructura modular de estilos y apoyo de Bootstrap para algunos componentes y comportamientos responsivos.

## Objetivos del proyecto

- Aplicar estructura semántica con HTML5.
- Desarrollar un sitio responsive adaptable a distintos dispositivos.
- Organizar los estilos con SCSS en archivos parciales reutilizables.
- Integrar componentes visuales y de navegación propios de un ecommerce.
- Presentar una maqueta funcional como entrega final del curso.

## Secciones principales

- Inicio: portada con carousel promocional, categorías destacadas y productos en oferta.
- Catálogo: grilla de productos con buscador y filtros visuales por categoría, precio y talle.
- Tiendas: sucursales físicas con tarjetas informativas y mapa embebido.
- Contacto: formulario de contacto con campos validados y datos de atención.
- 404: página auxiliar para rutas o secciones no disponibles.

## Tecnologías utilizadas

- HTML5
- CSS3
- SCSS
- Bootstrap 5.3.8 vía CDN
- Bootstrap Icons vía CDN
- Google Fonts

## Características destacadas

- Diseño responsive con breakpoints definidos en SCSS.
- Navbar adaptable para escritorio y mobile.
- Carousel de promociones en la página principal.
- Organización modular de estilos en `base`, `components` y `utilities`.
- Buscador visual en desktop y mobile.
- Tarjetas de productos y categorías destacadas.
- Formulario de contacto con campos obligatorios y checkbox de aceptación.
- Integración de mapa de Google Maps en la sección de tiendas.

## Estructura del proyecto

```text
Proyecto-CoderHouse/
|-- index.html
|-- css/
|   `-- styles.css
|-- images/
|   |-- categorias/
|   |-- Destacados/
|   |-- tarjetas/
|   `-- tiendas/
|-- pages/
|   |-- 404.html
|   |-- catalogo.html
|   |-- contacto.html
|   `-- tiendas.html
`-- scss/
    |-- styles.scss
    |-- base/
    |-- components/
    `-- utilities/
```

## Cómo visualizar el proyecto

Al ser un proyecto estático, no requiere instalación de dependencias ni un servidor backend.

1. Clonar o descargar este repositorio.
2. Abrir la carpeta del proyecto en Visual Studio Code.
3. Ejecutar `index.html` en el navegador.

Como alternativa, se puede usar una extensión como Live Server para mejorar la visualización local durante el desarrollo.

## Trabajo con SCSS

El proyecto incluye una versión compilada en `css/styles.css` y la fuente editable en `scss/`.

Si querés recompilar los estilos manualmente con Sass:

```bash
sass --watch scss/styles.scss css/styles.css
```

## Aprendizajes aplicados

- Maquetado semántico y organización de contenido.
- Responsive design.
- Modularización de estilos con SCSS.
- Uso de librerías externas por CDN.
- Construcción de una interfaz orientada a experiencia de usuario.

## Estado del proyecto

Proyecto finalizado con fines académicos como entrega final de Coderhouse. Puede seguir ampliándose con funcionalidades dinámicas como carrito real, filtrado con JavaScript, validaciones avanzadas o integración con backend.