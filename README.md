# La Manada — Marcador de dominó

Aplicación web estática para llevar la puntuación de partidas de dominó.

## Desarrollo local

Abre `manada_domino.html` en un navegador o sirve la carpeta raíz con un servidor HTTP local.

## Publicar en Vercel

Importa este repositorio en Vercel y configura:

- **Framework Preset:** Other
- **Root Directory:** `./`
- **Build Command:** vacío (sin comando de build)
- **Output Directory:** `.`

La regla de `vercel.json` sirve `manada_domino.html` en la ruta raíz (`/`) y deja los recursos estáticos disponibles desde la raíz del repositorio. No se necesitan dependencias ni variables de entorno.
