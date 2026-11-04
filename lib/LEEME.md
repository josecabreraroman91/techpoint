# Librerías guardadas junto a la página

Para que la app no dependa de que otro sitio (cdn.jsdelivr.net) esté andando, la librería de Supabase se publica junto a `index.html`.

- `supabase-js-2.45.4/supabase.js` y `591.supabase.js`: copia exacta de `dist/umd/` del paquete npm `@supabase/supabase-js@2.45.4` (la misma versión que usaba la página desde jsdelivr). `591.supabase.js` es un pedazo que el navegador no usa, pero la librería lo busca en la misma carpeta si alguna vez lo necesita.
- Para cambiar de versión: `npm pack @supabase/supabase-js@X.Y.Z`, copiar `package/dist/umd/*` a `lib/supabase-js-X.Y.Z/`, cambiar el `<script>` de `index.html` y probar en el sandbox.
- **Al publicar** hay que copiar también la carpeta `lib/` al repo de publicación (no sólo `index.html`).
