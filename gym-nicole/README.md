# NICOLEGYM

PWA personal de gimnasio (antes app APK "JOSEGYM"), publicada como página estática dentro de `plataformas`.

- 100% offline, sin servidor ni build: 1 solo `index.html` autocontenido (HTML+CSS+JS+fuente embebida).
- Datos en `localStorage` (clave `nicolegym-v1`), aislados de cualquier otra app del mismo origen.
- Export/import JSON de los datos disponible dentro de la propia app (Historial → "Tus datos").
- Instalable como app ("Añadir a pantalla de inicio") gracias al `manifest.webmanifest` + `sw.js`.

Reemplaza al contenido anterior de `gym-nicole/` (la PWA de plan de 12 semanas con IndexedDB), que fue retirada a petición del usuario.
