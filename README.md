# bichonlabs.cl

Landing de Bichon Labs: páginas web y tiendas online para emprendimientos.

Sitio estático (HTML + CSS, sin build) publicado en Vercel. Cada push a `main` se publica solo.

## Archivos
- `index.html`: contenido, metadatos SEO y datos estructurados (JSON-LD).
- `styles.css`: estilos con los tokens del sistema de diseño Bichon Labs.
- `assets/`: isotipos SVG.
- `robots.txt`, `sitemap.xml`, `llms.txt`: rastreo para buscadores y asistentes de IA.
- `vercel.json`: redirección de www, URLs limpias y caché.

## Cambios frecuentes
- **Contacto:** los botones "Cotiza tu web" apuntan a `https://ig.me/m/bichonlabs`. Para usar WhatsApp, reemplázalo por `https://wa.me/569XXXXXXXX` en todo `index.html`.
- **Precios:** están en `index.html` (tarjetas, FAQ y JSON-LD) y en `llms.txt`. Cámbialos en los tres lugares.
- Al cambiar contenido, actualiza `lastmod` en `sitemap.xml`.
