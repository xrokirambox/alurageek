
# AluraGeek

Este proyecto es una aplicación web para **AluraGeek**, diseñada para brindar una experiencia de usuario optimizada en una tienda en línea.

## Características

- **Encabezado**:
  - Contiene el logotipo, una barra de búsqueda y un botón de inicio de sesión.
- **Banner principal**:
  - Muestra ofertas promocionales destacadas.
- **Secciones principales**:
  - Contenedor para los productos destacados.
- **Pie de página**:
  - Incluye un menú de navegación adicional, un formulario de contacto y un apartado para el desarrollador.

## Estructura del Proyecto

### HTML

- **`index.html`**:
  - Archivo principal con la estructura del sitio.

### CSS

- Ubicado en `./sources/css/`:
  - `reset.css`: Normalización de estilos.
  - Estilos específicos para secciones como encabezado, banner, pie de página, y componentes como el formulario.

### JavaScript

- Ubicado en `./sources/controllers/` y `./sources/js/`:
  - `sectionProducts.js`: Controlador para manejar las secciones de productos.
  - `footerForm.js`: Lógica para la interacción con el formulario del pie de página.
  - `loginClick.js` y `logoClick.js`: Scripts para manejar clics en el botón de inicio de sesión y el logotipo.

## Dependencias

- **Font Awesome**:
  - Proporciona iconos en diversas partes del sitio.
- **UUID.js**:
  - Generación de identificadores únicos.

## Cómo Ejecutar el Proyecto

1. **Clonar el repositorio**:
   ```bash
   git clone <URL_del_repositorio>
   ```
2. **Abrir el archivo principal**:
   - Navegar al directorio del proyecto y abrir `index.html` en un navegador.

## Configuración del Repositorio

El archivo `.gitignore` incluye las siguientes exclusiones:
- Archivos específicos de IntelliJ IDEA y otros IDEs.
- Archivos relacionados con las configuraciones locales del entorno.

## Autor

Desarrollado por **Julián Guardiola** © 2022.
