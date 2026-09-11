# PDF Fusion Studio

Aplicación web progresiva (PWA) para:
- Imágenes → PDF (varias imágenes en un único PDF)
- PDF → PNG (una imagen por página)
- Combinar varios PDF en uno
- Instalación desde el navegador
- Procesamiento local, sin subir archivos a un servidor

## Despliegue en GitHub Pages
1. Sube todos los archivos a un repositorio.
2. En Settings → Pages, selecciona `Deploy from a branch`.
3. Selecciona la rama principal y `/root`.
4. Abre la URL HTTPS generada.
5. En Chrome/Edge aparecerá el botón "Instalar aplicación" cuando el navegador considere la PWA instalable.

## Nota
La aplicación usa PDF-Lib, jsPDF y PDF.js desde CDN. Para una versión completamente offline, descarga esas librerías y cambia las referencias de CDN por archivos locales; después inclúyelos en el caché del service worker.
