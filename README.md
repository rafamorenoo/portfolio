# Portfolio de Rafa Moreno

Web estática: no necesita build. Todo el contenido está en `content.json`.

## Editar sin tocar código
1. Abre `content.json` en tu repo de GitHub y pulsa el lápiz.
2. Cambia el texto, o copia un bloque de `research` o `projects` para añadir otro.
3. Guarda (Commit). Vercel republica solo en ~1 minuto.

Campos de un hallazgo: `title`, `program`, `year`, `sev` (Critical, Medium o Info) y `status` (es/en).
Para actualizar el CV, sustituye `CV_Rafa_Moreno.pdf` por el nuevo con el mismo nombre.

## Publicar
Sube la carpeta a un repo de GitHub e impórtalo en Vercel (Framework: Other, sin build).

## Probar en local
`python3 -m http.server` dentro de la carpeta y abre http://localhost:8000
