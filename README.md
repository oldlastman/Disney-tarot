# Disney-tarot

Un tarot con personajes Disney

## 🎴 Galería de Cartas de Tarot

Esta web muestra una galería interactiva de cartas de tarot con personajes Disney.

### Características

- ✨ **Vista de Miniaturas**: Las cartas se muestran en una cuadrícula responsive
- 🔍 **Zoom al Hacer Clic**: Haz clic en cualquier carta para verla en tamaño completo
- 📱 **Diseño Responsive**: Funciona perfectamente en desktop, tablet y móvil
- 🎨 **Interfaz Elegante**: Fondo degradado, animaciones suaves y efectos hover
- ⌨️ **Múltiples Controles**: Cierra el zoom con el botón X, tecla Escape o clic fuera del modal

### Cómo Usar

1. Abre `index.html` en tu navegador web
2. Las cartas en la carpeta `cartas` se mostrarán automáticamente
3. Haz clic en cualquier carta para verla ampliada
4. Para cerrar el zoom:
   - Haz clic en el botón × (esquina superior derecha)
   - Presiona la tecla Escape
   - Haz clic fuera de la imagen

### Añadir Cartas

1. Añade tus imágenes de cartas en la carpeta `cartas/`
2. Formatos soportados: JPG, JPEG, PNG, GIF, WEBP, SVG
3. Nombra las cartas de forma descriptiva:
   - `el-loco.jpg`
   - `el-mago.png`
   - `la-sacerdotisa.jpg`
   - etc.

Las cartas soportadas incluyen todos los Arcanos Mayores del Tarot tradicional.

### Tecnologías

- HTML5
- CSS3 (Grid Layout, Flexbox, Animaciones)
- JavaScript Vanilla (ES6+)
- Sin dependencias externas

### Demo

Incluye una carta de ejemplo (`placeholder.svg`) para demostrar la funcionalidad de la galería.

## 🌐 GitHub Pages

Este proyecto está configurado para funcionar con GitHub Pages.

### Activar GitHub Pages

1. Ve a la configuración del repositorio en GitHub
2. Navega a **Settings** → **Pages**
3. En la sección **Source**, selecciona:
   - **Branch**: `main` (o la rama que desees publicar)
   - **Folder**: `/ (root)`
4. Haz clic en **Save**
5. GitHub Pages generará una URL como: `https://oldlastman.github.io/Disney-tarot/`

La galería estará disponible públicamente en esa URL una vez que GitHub Pages termine de construir el sitio (generalmente tarda 1-2 minutos).

### Nota Técnica

El archivo `.nojekyll` está incluido para evitar el procesamiento de Jekyll y garantizar que todos los archivos se sirvan correctamente.

