# ZETA LABS — labs.hg-vl.com

La app de captación y venta de Human Glitche: auditoría de leads, embudo,
propuesta autogenerada, catálogo de pipelines y guía de venta — todo alrededor
del lead.

- **Fuente canónica**: `web/zeta-labs/` en el repo `hg-cerebro` (el vault).
  Este repo es solo el artefacto publicado; los cambios se hacen allá y se
  copian acá.
- 100% client-side: lee los leads del Firebase público de la Auditoría
  (solo lectura) y guarda embudo/propuestas/escaneos en localStorage.
  No cobra, no escribe ningún backend.
- Escaneo de redes vía el Worker `hg-redes-scan` (Cloudflare).

Publicado con GitHub Pages en https://labs.hg-vl.com
