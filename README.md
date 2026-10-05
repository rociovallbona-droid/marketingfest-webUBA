# Marketing Fest · 2ª edición — Pre-inscripción

Landing de pre-inscripción para Marketing Fest (FCE-UBA), 27 y 28 de octubre, de 14 a 21 hs.

## Archivos
- `index.html`: la landing completa (HTML, CSS y JS en un solo archivo; el logo de UBA Económicas va embebido).
- `logo-uba-economicas.png`: el logo en blanco y naranja por si lo necesitás aparte.

## Publicar con GitHub Pages
1. Subí estos archivos a la raíz del repo.
2. En Settings → Pages, elegí la rama `main` y la carpeta `/ (root)`.
3. La landing queda en `https://<usuario>.github.io/<repo>/`.

## Envío del formulario
Por ahora el envío solo hace `console.log` de los datos. Para guardarlos, reemplazá esa línea en el `<script>` de `index.html` por un `fetch` a tu webhook (n8n, Google Apps Script, etc.).

Campos: nombre, apellido, email, telefono, dni, perfil, carrera (solo Estudiante/Graduado), compartir_perfil (true por defecto).
