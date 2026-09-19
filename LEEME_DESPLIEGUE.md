# aetasnostra.es · despliegue en GitHub Pages · v0.1 · 19.09.2026

## Antes de publicar

- `estado/index.html` · Financiación: los importes están escritos (5 €/año dominio · 0 alojamiento ·
  5 €/mes GitHub · 200 €/mes Claude · 200 €/mes Gemini, los tres últimos compartidos). Si alguna
  cifra o periodo no es exacto, corrígela antes de subir: la página es un registro público.
- `sobre/index.html` · el retrato está comentado en el HTML y NO va en la carpeta. Entra solo
  cuando la ficha tenga autoría y fecha de la fotografía (R1): se copia `AN_retrato_autor.png`
  a `assets/img/` y se descomenta el bloque.

## Pasos

1. Repositorio en GitHub. Sube TODO el contenido de esta carpeta a la raíz, incluidos `.nojekyll` y `CNAME`.
2. Settings → Pages → Source: «Deploy from a branch» → `main`, carpeta `/ (root)`.
3. DonDominio → DNS: cuatro registros A para `@` (185.199.108.153 · 185.199.109.153 ·
   185.199.110.153 · 185.199.111.153) y un CNAME para `www` → `<tu-usuario>.github.io`.
4. Settings → Pages → Custom domain: `aetasnostra.es` → «Enforce HTTPS» cuando aparezca.
5. Comprueba https://aetasnostra.es/AN-2026-001/ — esa URL no cambia nunca.

## Versionar

Cada cambio es un commit con motivo. Cuando el expediente pase a v2: carpeta `/AN-2026-001/v2/`,
la raíz `/AN-2026-001/` muestra v2, y `/v1/` se conserva legible.
