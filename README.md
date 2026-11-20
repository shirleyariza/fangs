# Fangs — Portafolio de Maggie Rodríguez

Sitio estático (HTML + CSS + JS, sin build). Listo para GitHub Pages.

## Estructura
```
index.html
css/styles.css      ← colores, fuentes y TIEMPOS de animación (bloque :root)
js/main.js          ← dispara las animaciones al hacer scroll
assets/img/         ← imágenes
assets/video/       ← videos de UX/UI (GOAL)
.nojekyll  .gitignore
```

## Publicar en GitHub Pages
1. Crea un repositorio y sube **todo el contenido de esta carpeta** (que `index.html` quede en la raíz).
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)` → Save.
3. Tu sitio quedará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Animaciones (tomadas del timeline de Figma)
| Elemento | Qué anima | Tiempo |
|---|---|---|
| Dientes del hero | abrir y cerrar en bucle | 0.8 s (`--t-dientes`) |
| Branding | opacidad 0 → 1 | 1 s (`--t-branding`) |
| Ilustración | desenfoque | 1 s (`--t-ilustracion`) |
| Hablemos | textura, 6 keyframes | 0 / .21 / .39 / .58 / .77 / 1.02 s (`--t-hablemos`) |

## Fuentes
Se cargan desde Google Fonts (Pinyon Script, Italianno, Montserrat). Si usas otras, agrega los archivos en `assets/fonts/` y declara `@font-face` en `css/styles.css`.

## Local
Abre `index.html` o usa `python3 -m http.server`.
