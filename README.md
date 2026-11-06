# La Santa Snack · Web

Web estática (HTML + datos en `data.json`). Hecho por AgencyBlue.es · Autor: José Antonio Romero.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub y sube **todos** los archivos de esta carpeta (incluido `.nojekyll`).
2. Ve a **Settings → Pages**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`, y guarda.
3. En 1-2 minutos la web estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Panel de administrador
- Abre la web con `#admin` al final: `https://…/#admin` e introduce el PIN.
- **Cambia el PIN antes de publicar:** abre `generar-pin.html`, genera el código de tu PIN nuevo y pégalo en `index.html`, en la línea `const PIN_SHA256="…"`.
- En GitHub Pages no hay servidor: los cambios del panel se guardan **solo en tu navegador** como borrador.
- **Para que los vean todos los clientes:** en el panel, pestaña **Copia de seguridad → Descargar copia (JSON)**, renombra el archivo a `data.json` y súbelo al repositorio reemplazando el anterior. Se publica en 1-2 minutos.
- Las fotos que subes se guardan dentro de `data.json` (comprimidas). GIF y vídeos: máximo 1,5 MB cada uno.
- El PIN es solo una comodidad: no protege nada sensible, porque los cambios no se publican hasta que subes `data.json`.

## Archivos
- `index.html`: la web.
- `data.json`: carta, slider y reels que ve el público.
- `LICENSE`, `robots.txt`, `.nojekyll`, `generar-pin.html`: apoyo.
