# Rómulo Cardier — Portafolio

Sitio estático listo para GitHub Pages. **Todo el contenido de esta carpeta va directo a la raíz del repositorio** (no lo metas en una subcarpeta).

## Qué hay aquí
- `index.html` — la página completa, **100% autocontenida**: estilos, fuentes e imágenes de portada van embebidos dentro del propio archivo (no depende de ninguna otra carpeta para verse). Esto evita cualquier problema de rutas o de Jekyll ignorando carpetas.
- `.nojekyll` — evita que GitHub Pages procese el sitio con Jekyll (por si acaso; ya no es indispensable pero no estorba).
- `projects/` — las 4 páginas web y los 2 artefactos IA (HTML) + los 2 PDF de identidad de marca, enlazados desde las tarjetas del portafolio. Estos SÍ deben mantenerse como archivos separados.

## Cómo montarlo
1. Descomprime este zip.
2. Copia **todo su contenido** (incluido `.nojekyll`, que suele estar oculto) a la raíz del repo `cardierromulo.github.io`, reemplazando lo que haya — borra cualquier `_ds/` o `assets/` viejo que haya quedado de una subida anterior.
3. En la raíz del repo deben quedar: `index.html`, `.nojekyll`, `projects/` — al mismo nivel, no dentro de otra carpeta.
4. Haz commit y push a la rama que sirve GitHub Pages (normalmente `main`).
5. Espera 1–2 minutos y recarga la URL del sitio (o fuerza recarga sin caché: Ctrl/Cmd+Shift+R).
