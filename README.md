# 🛍️ Hering — Tienda de Indumentaria
 
Proyecto desarrollado como **entrega final** del curso de **Desarrollo Web** en [CoderHouse](https://www.coderhouse.com/).
 
> ⚠️ **Proyecto semi-terminado** — algunas secciones están pendientes de completar y muestran una página 404 de forma temporal.
 
---
 
## 📋 Descripción
 
**Hering** es un sitio web estático que simula la experiencia de una tienda online de indumentaria para toda la familia. Cuenta con una propuesta visual orientada al ecommerce, navegación responsive y secciones para explorar productos, sucursales y contacto.
 
---
 
## 🗂️ Secciones
 
| Sección    | Estado         | Descripción                                                             |
|------------|----------------|-------------------------------------------------------------------------|
| 🏠 Inicio   | ✅ Completa     | Portada con carousel promocional, categorías destacadas y ofertas       |
| 🛒 Catálogo | 🚧 En proceso  | Grilla de productos con buscador y filtros por categoría, precio y talle |
| 🏪 Tiendas  | 🚧 En proceso  | Sucursales físicas con tarjetas informativas y mapa embebido            |
| 📩 Contacto | 🚧 En proceso  | Formulario con campos validados y datos de atención                     |
| ❌ 404      | ✅ Completa     | Página auxiliar para rutas o secciones no disponibles                   |
 
---
 
## ✨ Características
 
- 📱 Diseño **responsive** con breakpoints definidos en SCSS
- 🧭 Navbar adaptable para escritorio y mobile
- 🖼️ Carousel de promociones en la página principal
- 🃏 Tarjetas de productos y categorías destacadas
- 🔍 Buscador visual en desktop y mobile
- 📬 Formulario de contacto con campos obligatorios y checkbox de aceptación
- 🗺️ Integración de Google Maps en la sección de tiendas
- 🗂️ Estilos organizados de forma modular con SCSS (`base`, `components`, `utilities`)
 
---
 
## 🛠️ Tecnologías utilizadas
 
- **HTML5** — estructura semántica
- **CSS3 / SCSS** — estilos con preprocesador y parciales reutilizables
- **Bootstrap 5.3** — componentes y comportamiento responsive (CDN)
- **Bootstrap Icons** — íconos (CDN)
- **Google Fonts** — tipografías
 
---
 
## 📁 Estructura del proyecto
 
```
Proyecto-CoderHouse/
├── index.html
├── css/
│   └── styles.css
├── images/
│   ├── categorias/
│   ├── Destacados/
│   ├── tarjetas/
│   └── tiendas/
├── pages/
│   ├── 404.html
│   ├── catalogo.html
│   ├── contacto.html
│   └── tiendas.html
└── scss/
    ├── styles.scss
    ├── base/
    ├── components/
    └── utilities/
```
 
---
 
## 🚀 Cómo visualizar el proyecto
 
El proyecto es completamente estático, no requiere instalación de dependencias ni servidor backend.
 
1. Cloná el repositorio:
   ```bash
   git clone https://github.com/agusbrave52/Proyecto-CoderHouse.git
   ```
2. Abrí la carpeta en **Visual Studio Code**.
3. Ejecutá `index.html` en el navegador, o usá la extensión **Live Server** para desarrollo local.
 
---
 
## 🎨 Trabajo con SCSS
 
El proyecto incluye los estilos ya compilados en `css/styles.css`. Si querés editar y recompilar el SCSS:
 
```bash
sass --watch scss/styles.scss css/styles.css
```
 
---
 
## 📌 Estado del proyecto
 
🟠 **Semi-terminado** — entrega académica en curso. Las secciones de Catálogo, Tiendas y Contacto están en desarrollo; por el momento redirigen a una página 404.
 
Próximos pasos:
- [ ] Completar sección Catálogo
- [ ] Completar sección Tiendas
- [ ] Completar sección Contacto
 
---
 
## 👤 Autor
 
**Agustín Brave**
- GitHub: [@agusbrave52](https://github.com/agusbrave52)