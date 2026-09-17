# reels-cdn

Host estático (GitHub Pages) para servir vídeos **MP4 públicos** que luego se publican como **reels en Instagram** mediante la API (`ig.py` → `publish-reel`).

## Cómo funciona
- Los vídeos van en la carpeta `v/`.
- Quedan servidos públicamente en:
  `https://santiago-off.github.io/reels-cdn/v/<nombre>.mp4`
- `.nojekyll` desactiva el procesado Jekyll para que GitHub Pages sirva los MP4 tal cual.

## Reglas
- **Solo archivos públicos.** Cualquiera con la URL puede descargarlos (Instagram necesita bajarlos de forma anónima para publicarlos).
- Nombres sin espacios ni acentos (`v1_aws152.mp4`).
- Se puede borrar un vídeo del repo una vez publicado en Instagram; el reel sigue en la cuenta.
