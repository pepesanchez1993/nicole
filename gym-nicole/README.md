# NICOLEGYM

PWA personal de gimnasio (antes app APK "JOSEGYM"), publicada como página estática dentro de `plataformas`.

- 100% offline, sin servidor ni build: 1 solo `index.html` autocontenido (HTML+CSS+JS+fuente embebida).
- Datos en `localStorage` (clave `nicolegym-v1`), aislados de cualquier otra app del mismo origen.
- Export/import JSON de los datos disponible dentro de la propia app (Historial → "Tus datos").
- Instalable como app ("Añadir a pantalla de inicio") gracias al `manifest.webmanifest` + `sw.js`.

Reemplaza al contenido anterior de `gym-nicole/` (la PWA de plan de 12 semanas con IndexedDB), que fue retirada a petición del usuario.

## Cómo funciona el registro (v2)

- Cada día eliges qué has entrenado: **Pilates** (martes y jueves ya vienen marcados; modalidad silla/suelo/reformer, multiselección, también como recuperación en otros días), **espalda y bíceps**, **pecho, hombro y tríceps**, **pierna y glúteo** o **libre**.
- Cada sesión de gimnasio: calentamiento articular (10 min), ejercicios, core (15 min), cardio y estiramiento.
- Cada ejercicio: 3 series de trabajo + una fila **PR** (mejor peso y repeticiones del día, se rellena con el botón «PR»).
- Racha semanal (≥ 3 sesiones por semana) y avance visibles arriba en Entreno. Las rutinas antiguas (lun–vie) siguen disponibles en «Rutinas antiguas» y sus registros se conservan.
