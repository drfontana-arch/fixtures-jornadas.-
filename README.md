# Fixtures de las Jornadas

Sitio estático para que los delegados consulten los fixtures que sube la organización.

- Página: `public/index.html` (sin build).
- Datos: Supabase, proyecto `jornadas-necochea-2026` — tabla `fixture_files` y bucket público `fixtures`.
- Quién puede subir: los emails de la tabla `fixture_admins` que además tengan usuario en Supabase Auth.

## Render
Static Site → Build command: `echo ok` → Publish directory: `public`.
