# La Vinilería 

## Integrantes
* Álvaro Muñoz
* Raúl Canto
* Juan Diego Borrego

---

## Descripción del Proyecto
**La Vinilería** es una tienda web de discos de vinilo desarrollada como trabajo grupal para la asignatura de **Diseño de Interfaces Web (2º DAW)**. 

La web está construida exclusivamente con **HTML5 semántico** y **CSS compilado desde SCSS**, con diseño adaptativo (**responsive**) y **sin utilizar JavaScript** (el menú móvil y las animaciones funcionan al 100% con CSS puro).

Consta de las siguientes páginas:
* `index.html`: Página principal con presentación de la tienda, ventajas y animación de un vinilo girando.
* `catalogo.html`: Catálogo con 9 vinilos ordenados en cuadrícula con filtros por género y paginación.
* `producto.html` (y fichas individuales `producto-*.html`): Páginas de detalle de cada disco con portada, precio, botón de compra, tracklist y ficha técnica.
* `contacto.html`: Información de la tienda física en Córdoba, horarios, mapa ilustrado, formulario de contacto y sección de preguntas frecuentes (FAQ).

---

## Cómo Compilar el SCSS

Para compilar los estilos hemos utilizado la extensión de Visual Studio Code **Live Sass Compiler** en modo escucha:

1. Abrir la carpeta del proyecto en Visual Studio Code con la extensión **Live Sass Compiler** instalada.
2. Hacer clic en el botón **"Watch Sass"** ubicado en la barra de estado inferior de VS Code.
3. Al activar el modo escucha, cualquier cambio guardado en los archivos dentro de la carpeta `scss/` se compila automáticamente en `css/main.css`.

El archivo `css/main.css` ya se encuentra generado y actualizado en el repositorio, por lo que la web funciona directamente abriendo los archivos `.html` en el navegador.

---

## Reparto de Tareas

El trabajo se ha dividido de forma equitativa entre los tres integrantes:

### Álvaro
* Inicialización del repositorio Git y documentación base.
* Arquitectura SCSS: variables de color y tipografía (`_variables.scss`), funciones de rem y mixins (`_functions.scss`, `_mixins.scss`).
* Maquetación de la página de inicio `index.html` y sección Hero (`_hero.scss`).
* Fichas de producto de Rock: Fleetwood Mac y The Beatles.
* Solución técnica al aspecto cuadrado de las portadas (`aspect-ratio: 1/1`).
* Compilación final de producción de `css/main.css`.

### Raúl
* Recursos gráficos iniciales (logotipo y mapa en SVG) e importación de portadas reales de vinilos (`img/`).
* Reseteo de estilos (`_reset.scss`) y archivo central `scss/main.scss`.
* Maquetación de cabecera con menú responsive sin JS (`_header.scss`), pie de página (`_footer.scss`) y cuadrícula (`_grid.scss`).
* Estilos de tarjetas, etiquetas y filtros (`_card.scss`, `_badge.scss`, `_filters.scss`).
* Maquetación de la página completa `catalogo.html`.
* Fichas de producto: Miles Davis, Daft Punk y Rosalía.

### Juan Diego
* Estilos de botones (`_button.scss`) y formularios (`_form.scss`).
* Maquetación de la página `contacto.html` y preguntas frecuentes (`_contact.scss`).
* Plantilla y estilos de detalle de vinilo (`_product-detail.scss`) y ficha de Pink Floyd (`producto.html`).
* Fichas de producto: Amy Winehouse, Michael Jackson y el musical Hamilton.
* Simplificación y homogeneización de los comentarios del código para facilitar la lectura del equipo.
* Revisión de accesibilidad y adaptación en pantallas móviles.


