# Compartir el dashboard desde cualquier dispositivo

El archivo HTML funciona como sitio web estatico. Para abrirlo desde telefono, tablet u otra computadora, publica juntos estos dos archivos:

- `dashboard_seguridad_patrimonial.html`
- `logo sopiha.jpg`

## Opcion sencilla: Netlify Drop

1. Abre `https://app.netlify.com/drop`.
2. Arrastra una carpeta que contenga el HTML y el JPG del logo.
3. Netlify generara una URL publica `https://...netlify.app`.
4. Comparte esa URL con el boton **Compartir** del dashboard.

## Opcion institucional: GitHub Pages

1. Crea un repositorio privado o institucional.
2. Sube `dashboard_seguridad_patrimonial.html` y `logo sopiha.jpg`.
3. En Settings > Pages, selecciona la rama principal y la carpeta raiz.
4. Comparte la URL que genere GitHub Pages.

El XLSM no es necesario para mostrar la vista inicial. Solo debe cargarse desde **Elegir bases** cuando se requiera recalcular con archivos nuevos. Por seguridad, no publiques el XLSM si contiene informacion interna; mantenlo local y cargalo desde el dispositivo autorizado.
