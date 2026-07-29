# Rómulo Cardier — Portafolio

Sitio estático listo para GitHub Pages. **Todo el contenido de esta carpeta va directo a la raíz del repositorio** (no lo metas en una subcarpeta).

## Qué hay aquí
- `index.html` — la página (auto-contenida, sin dependencias de build).
- `.nojekyll` — **archivo obligatorio**: le dice a GitHub Pages que no procese el sitio con Jekyll. Sin él, Jekyll ignora por defecto cualquier carpeta que empiece con "_" (como `_ds/`), y por eso los estilos, colores y tipografía no cargaban.
- `_ds/` — hojas de estilo y fuentes del sistema de diseño. No renombrar ni mover.
- `assets/` — imágenes de los proyectos.
- `projects/` — páginas web y artefactos IA (HTML) + PDFs de identidad de marca, enlazados desde las tarjetas.

## Cómo montarlo
1. Descomprime este zip.
2. Copia **todo su contenido** (incluido `.nojekyll`, que suele estar oculto) a la raíz del repo `cardierromulo.github.io`, reemplazando lo que haya.
3. Confirma que en la raíz del repo queden: `index.html`, `.nojekyll`, `_ds/`, `assets/`, `projects/` — todos al mismo nivel, no dentro de otra carpeta.
4. Haz commit y push a la rama que sirve GitHub Pages (normalmente `main`).
5. Espera 1–2 minutos y recarga la URL del sitio.
