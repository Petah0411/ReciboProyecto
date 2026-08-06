# Generador de recibos

Aplicación web local para crear recibos de pedido y descargarlos en PDF. No requiere instalación, servidor ni conexión a una base de datos: funciona directamente en el navegador.

## Cómo usarla

1. Descarga o copia la carpeta del proyecto.
2. Abre `index.html` con Chrome, Safari, Edge o Firefox.
3. Completa los campos del panel izquierdo.
4. Revisa la vista previa, que se actualiza automáticamente mientras escribes.
5. Presiona **Generar y Descargar PDF**.

Los renglones de artículos vacíos se conservan en el formato. Para usar un artículo, completa su **Descripción**, **Cantidad** y **Precio**. El total se calcula automáticamente.

## Compartir la aplicación

### Compartir como archivo

Envía `index.html` por correo, WhatsApp, Google Drive, Dropbox o una memoria USB. La persona que lo reciba debe descargarlo y abrirlo en su navegador; no necesita instalar programas adicionales.

### Compartir con un enlace web

Puedes publicar este archivo en un hosting estático, por ejemplo GitHub Pages, Netlify, Vercel o Cloudflare Pages. Al ser una aplicación de un solo archivo, basta con subir `index.html`.

## Privacidad y funcionamiento

- Los datos se procesan en el navegador de quien usa la aplicación.
- No se envían datos a un servidor ni se almacenan automáticamente.
- El PDF se genera desde la misma vista previa que aparece en pantalla.
- Para evitar bloqueos de descarga, permite las descargas cuando el navegador lo solicite.

## Archivos

- `index.html`: aplicación completa, estilos, lógica de actualización y generación de PDF.
- `README.md`: esta guía de uso y distribución.
