# DHF Estilistas · Web demo

Landing page one-page para **DHF Estilistas**, peluquería y salón de belleza en Calle del Fuego, 33, 28100 Alcobendas (Madrid).

Todo el sitio está en un solo archivo: `index.html`, con el HTML, el CSS y el JS dentro. No necesita compilación.

## Publicar en GitHub Pages
1. En el repositorio, ve a **Settings → Pages**.
2. En **Source**, elige *Deploy from a branch*.
3. Selecciona la rama `claude/clever-hopper-gfw0dp` (o `main` si se fusiona) y la carpeta `/ (root)`, y pulsa **Save**.
4. En 1–2 minutos estará en `https://takalislam9-lab.github.io/dhf2/`.

## Datos que hay que confirmar con el cliente antes de publicar
| Dato | Dónde se cambia |
|---|---|
| Teléfono y WhatsApp | objeto `CONFIG` al final de `index.html` |
| Horario de apertura | `CONFIG.hours` |
| Precios | sección `#servicios` (ahora son orientativos) |
| Testimonios | sección `#opiniones` (ahora son textos de muestra: sustituir por reseñas reales de Google) |
| Fotos | `.hero-bg` y `.about-media img` (ahora de Unsplash: sustituir por fotos del salón o de su Instagram) |

Datos verificados en fuentes públicas: la dirección, la valoración de 4,9★ con 27 reseñas en Google y el Instagram [@dhf.estilistas](https://www.instagram.com/dhf.estilistas/).
