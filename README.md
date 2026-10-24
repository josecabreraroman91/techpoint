# TechPoint · sistema de ventas (publicación)

Este repo **sólo publica** la página: GitHub Pages la sirve en **https://orbepy.com/techpoint/**.

- `index.html` es toda la app. El código fuente, las guías y el SQL están en la rama `sin-servidor` del repo privado `infotechpointar-sys/sistema-ventas-techpoint` (ver `SIN-SERVIDOR.md` ahí).
- **Para publicar**: copiar el `index.html` de esa rama acá y subirlo a `main`. En 1 o 2 minutos queda en el link.
- **Antes de publicar una versión que usa funciones nuevas de la base**, el SQL nuevo (`supabase/00N_*.sql`) tiene que estar corrido en Supabase. Lo corre José. Si no, la página se rompe.
- No agregar un archivo `CNAME`: el dominio sale solo de orbepy.com.
