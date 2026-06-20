# 🦖 T-Rex: Escape from Chicxulub ☄️

A hand-built, single-file HTML5 canvas endless runner. Play as a terrified T-Rex
sprinting away from the asteroid impact that ended the age of dinosaurs — leap
meteors, duck flaming debris, grab grass-shields, and survive long enough to
reach safety.

> Developed by **Gabriel and Liam Rosales** to commemorate Liam's **T-Rex "Freed" plush**. 🦖💚

## Play

No build step, no dependencies, no assets to download. Just open the game in a browser:

```bash
open index.html      # macOS
# or simply double-click index.html
```

Or play it live once published via GitHub Pages.

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Jump (hold to jump higher) | `Space` / `↑` | Tap |
| Duck | `↓` | Swipe down |
| Pause / Resume | `P` or `Esc` | Pause button |
| Music on/off | `M` | — |

## Features

- **Three escalating scenarios** — *The Badlands*, *The Coast*, and *The Long Night* — each with its own apocalyptic backdrop.
- **Rising difficulty** that ramps up speed, spawn rate, meteor showers, lightning storms, and debris pairs the longer you survive.
- **Grass-shield power-ups** — every 15th rock drops a glowing patch of grass; eat it to soak up 3 hits.
- **Near-miss scoring** — graze a meteor and live to earn bonus points.
- **A complete cinematic apocalypse** rendered entirely in canvas: a looming asteroid, burning horizons, fleeing pterosaurs and stampeding herds, falling ash and embers, parallax palms, and screen shake.
- **An original, generative soundtrack** synthesised live in the browser (no audio files) — an anthemic, royalty-free "epic adventure" theme.
- **Works on desktop and mobile** with full touch support, plus high-score saving via `localStorage`.

## Tech

Pure vanilla HTML, CSS, and JavaScript in a single `index.html` — Canvas 2D for
graphics and the Web Audio API for the soundtrack and sound effects. No
frameworks, no bundler, nothing to install.

---

Made with love by Gabriel & Liam Rosales 🦖
