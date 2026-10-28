# Carpeta para publicar

Contiene solo lo que necesita la web: `index.html` (minificado), `og-image.png` (vista previa al compartir) y `LICENCIA.txt`.
Los scripts, los datos crudos y el LEEME del proyecto quedan fuera: no los subas al repo público.

Regenerar: `python scripts/armar_web.py` y después `node scripts/exportar_web.mjs` (necesita Node y
`npm i terser html-minifier-terser` una vez).

Al tener la dirección definitiva, cambiar en index.html `content="og-image.png"` por la URL completa
(p. ej. `https://tu-sitio/og-image.png`) para que la vista previa funcione en WhatsApp y redes.
