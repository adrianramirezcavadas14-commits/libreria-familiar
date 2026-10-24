# Librería familiar - primera versión

## Subida a GitHub
1. Abre el repositorio `libreria-familiar`.
2. Pulsa **Add file > Upload files**.
3. Sube todos los archivos de esta carpeta, no la carpeta contenedora ni el ZIP.
4. Escribe un mensaje, por ejemplo `Primera versión`, y pulsa **Commit changes**.
5. Entra en **Settings > Pages**.
6. En **Source**, elige **Deploy from a branch**.
7. Selecciona `main`, carpeta `/(root)`, y pulsa **Save**.

## Supabase
La web funciona visualmente sin configurar Supabase. Cuando vayamos a conectar las tablas, abre `supabase-config.js` y añade la URL y la clave pública anon/publishable. Nunca añadas la clave `service_role`.

## Archivos
- `index.html`: estructura y pantallas.
- `styles.css`: estética.
- `app.js`: menú y navegación.
- `supabase-config.js`: configuración pública de Supabase.
- `manifest.webmanifest`: instalación como PWA.
- `service-worker.js`: caché básica.
- `icon.svg`: icono provisional.
