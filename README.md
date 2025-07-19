# Verde_Moda

Descripción General del Proyecto

VerdeModa es una plataforma web que simula un comercio electrónico (e-commerce).
Diseñada en base a productos de moda sostenible y ecológica. 
Objetivo principal -> Ofrecer <- un compromiso con la sostenibilidad a través de su diseño y funcionalidad.

Estructura de Carpetas
El proyecto está organizado de manera modular y lógica para facilitar la navegación y el mantenimiento del código. En esta rama, los archivos Sass (.scss) han sido actualizados para reflejar los nuevos requerimientos de diseño.

..//

├── assets/

│   ├── css/              # Archivos CSS compilados (generados por Sass)

│   │   └── style.css

│   ├── img/              # Imágenes del proyecto (contiene todas las imagenes)

│   ├── js/               # Archivos JavaScript (en este caso no usaremos)

│   └── scss/             # Archivos fuente de Sass (pre-procesador CSS)

│       ├── abstracts     

│       │   ├── _media.scss         # Responsividad en las imagenes y contenedores

│       │   └── _variables.scss     # Variables de configuración (colores, fuentes, etc)

│       ├── base

│       │   ├── _base.scss          # Estilos base

│       │   └── _typography.scss    # Estilos de letra

│       ├── componentes             # Estilos para componentes (botons, cards)

│       │   ├── _about.scss 

│       │   ├── _forms.scss 

│       │   ├── _gallery.scss 

│       │   ├── _hero.scss 

│       │   ├── _navbar.scss 

│       │   └── _product-card.scss 

│       ├── layouts                 # Estructura y diseño de secciones principales

│       │   └── _footer.scss

│       ├── pages                   # Estructura y diseño de paginas principales

│       │   └── _products.scss

│       ├── themes                  # Apariencia Darkmode y otros (en este caso no usaremos)

│       ├── vendors                 # Import bootstrap y otros (en este caso no usaremos)

│       └── style.scss

├── index.html       # Página principal del sitio

├── contacto.html    # Página de contacto

├── productos.html   # Página sobre los productos

└── README.md        # Este archivo de documentación

🎨 Paleta de Colores y Estilo

Verde claro     #d5f5e3     - Fondo de la pagina
Verde           #88e581     - Navbar/Footer
Verde oscuro    #0742219e   - Texto sobre Navbar y Footer
Hover           #2050f06b   - Sobre Navbar

🧰 Tecnologías utilizadas 

HTML5: Estructura del contenido.
CSS
Sass (SCSS): Preprocesador CSS para estilos modulares y mantenibles.

