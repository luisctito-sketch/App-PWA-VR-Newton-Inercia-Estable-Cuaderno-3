# App PWA VR Newton: Inercia Estable — versión corregida

Esta versión corrige el problema de botones que no funcionaban en GitHub Pages.

Causa probable del fallo anterior:
el archivo index.html usaba importaciones externas de módulos JavaScript. Si una importación falla, todo el script deja de ejecutarse y los botones quedan visibles, pero sin respuesta.

Esta versión no usa Three.js ni dependencias externas. Todo está hecho con Canvas y JavaScript interno.

Archivos:
- index.html
- manifest.json
- service-worker.js
- icon-192.png
- icon-512.png
- assets/Educcartito.png
- preview_App_PWA_VR_Newton_CORREGIDA.jpg
- guia_reemplazo_github.txt
