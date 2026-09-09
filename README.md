# Carnaval de Barranquilla — Página Web

Proyecto de página web básica sobre el Carnaval de Barranquilla, desarrollado con HTML5 y CSS3.

## Contenido del proyecto
- `index.html` — estructura y contenido de la página.
- `styles.css` — estilos (colores, tipografía, botones, tablas, animaciones).
- `media/` — carpeta donde debes colocar tu propio archivo de video (por ejemplo `carnaval-barranquilla.mp4`) para que se reproduzca en la etiqueta `<video>`. Mientras no agregues un archivo allí, el reproductor mostrará el mensaje de navegador no compatible; el video de YouTube incrustado seguirá funcionando de todas formas.

## Cómo publicar el sitio gratis

### Opción 1: Netlify Drop (la más rápida, sin cuenta de GitHub)
1. Entra a https://app.netlify.com/drop
2. Arrastra la carpeta completa `carnaval-barranquilla` (con `index.html`, `styles.css` y `media/`) a la zona de arrastre.
3. Netlify generará un enlace público en segundos (ej. `nombre-aleatorio.netlify.app`).
4. Opcional: crea una cuenta gratuita para poder editar el sitio después y personalizar el subdominio.

### Opción 2: GitHub Pages
1. Crea una cuenta en https://github.com si no tienes una.
2. Crea un repositorio nuevo, por ejemplo `carnaval-barranquilla`.
3. Sube los archivos `index.html`, `styles.css` y la carpeta `media/` al repositorio (botón "Add file" → "Upload files").
4. Ve a **Settings → Pages**.
5. En "Branch", selecciona `main` y la carpeta `/root`, luego guarda.
6. Espera uno o dos minutos; GitHub te dará la URL pública (ej. `tuusuario.github.io/carnaval-barranquilla`).

### Opción 3: Vercel
1. Entra a https://vercel.com y crea una cuenta gratuita.
2. Sube el proyecto como carpeta o conéctalo a un repositorio de GitHub.
3. Vercel detecta que es un sitio estático y lo publica automáticamente.

Cualquiera de las tres opciones cumple con el requisito de "Publicación del sitio en un hosting gratuito".
