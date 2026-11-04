# TechPoint · sistema de ventas (publicación)

Este repo **sólo publica** la página: GitHub Pages la sirve en **https://orbepy.com/techpoint/**.

- `index.html` es toda la app, y `lib/` tiene la librería de Supabase que usa (desde la v34 ya no se baja de jsdelivr). El código fuente, las guías y el SQL están en la rama `sin-servidor` del repo privado `infotechpointar-sys/sistema-ventas-techpoint` (ver `SIN-SERVIDOR.md` ahí).
- **Para publicar**: copiar el `index.html` **y la carpeta `lib/`** de esa rama acá y subirlos a `main`. En 1 o 2 minutos queda en el link.
- **Antes de publicar una versión que usa funciones nuevas de la base**, el SQL nuevo (`supabase/00N_*.sql`) tiene que estar corrido en Supabase (proyecto techpoint del dueño). Si no, la página se rompe.
- No agregar un archivo `CNAME`: el dominio sale solo de orbepy.com.
