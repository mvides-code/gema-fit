# GEMA · Tabata ⏱️🔴🔵

Cronómetro de Tabata para las clases virtuales del equipo **GEMA** (Martin, Daniela y el profe Emanuel) por Google Meet.

App web de **un solo archivo**, sin servidor ni login. Se adapta sola al dispositivo:

- 💻 **Notebook / escritorio** → vista "control": cronómetro gigante para compartir pantalla en Meet, atajos de teclado, editor cómodo.
- 📱 **iPhone / celular** → vista "táctil": todo en vertical, botones grandes para el dedo. Se puede **"Agregar a inicio"** y abre en pantalla completa como una app.

Botón 💻/📱 en la barra para forzar una vista u otra.

## Uso

1. Elegí la rutina del día (Lunes / Martes / Jueves) arriba.
2. **Compartí pantalla** en Meet y usá la barra de abajo (o el teclado) para correr el timer.
3. Verde = trabajo · Naranja = descanso · Azul = descanso entre sets.

### Atajos de teclado (escritorio)
- `Espacio` → play / pausa
- `←` / `→` → fase anterior / siguiente
- `R` → reiniciar slot
- `C` → ocultar / mostrar controles

### Editor y catálogo
- **Editor**: armá cada rutina con sets y ejercicios; tiempos por slot, "aplicar a todo el set", reordenar. Se guarda solo.
- **Catálogo**: lista de ejercicios que autocompletan en el editor.

## Técnico

- HTML/CSS/JS puro, sin dependencias ni build.
- Persistencia en `localStorage` (JSON versionado).
- Sonido con la Web Audio API. Timer con corrección de deriva.
- PWA (manifest + íconos) para instalar en el celular.

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | La app completa |
| `icon.svg` | Logo / favicon (emblema) |
| `logo.svg` | Logo completo con cartel "GEMA" |
| `manifest.webmanifest` + `icon-*.png` | PWA |

Publicado con Cloudflare Pages.
