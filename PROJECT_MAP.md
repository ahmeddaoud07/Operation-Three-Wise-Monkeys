# PROJECT MAP — Operation: Three Wise Monkeys

## Overview
Physical 3-player + 1 Game Master cooperative bomb defusal game inspired by *Keep Talking and Nobody Explodes*, featuring sensory handicaps (**Mute**, **Deaf**, **Blind**) and a 5-minute countdown console.

## Key Files & Roles
- [`index.html`](file:///D:/melle/antigrav/bomb%20game%20L/index.html): Standalone offline Game Master countdown timer & soundboard console. Loads authentic vanilla *Keep Talking and Nobody Explodes* audio assets from `audio/` and manages the 5:00 timer, strike speed multipliers (`1.0x`, `1.25x`, `1.5x`), and 12 Seed configurations (`#01 ALPHA` – `#12 LIMA`).
- [`bomb_3d_schematic.html`](file:///D:/melle/antigrav/bomb%20game%20L/bomb_3d_schematic.html): Full interactive 3D WebGL hardware schematic and CAD guide with 360° orbit, exploded assembly slider, X-ray/wireframe modes, 3D dimension lines, clickable components (cut wires, flip switches, rotate shape dials), mystery chamber swapper, and real-time seed syncing.
- `lib/`: Offline standalone 3D engine libraries (`three.min.js`, `OrbitControls.js`).
- [`BOMB_DEFUSAL_MANUAL_PRINTABLE.html`](file:///D:/melle/antigrav/bomb%20game%20L/BOMB_DEFUSAL_MANUAL_PRINTABLE.html): 5-page printable HTML manual (Pages 1–4 for the Mute player; Page 5 detachable GM Answer Key).
- [`BOMB_DEFUSAL_MANUAL.pdf`](file:///D:/melle/antigrav/bomb%20game%20L/BOMB_DEFUSAL_MANUAL.pdf) / [`BOMB_DEFUSAL_MANUAL.docx`](file:///D:/melle/antigrav/bomb%20game%20L/BOMB_DEFUSAL_MANUAL.docx): Print-ready PDF and editable Word versions of the Bomb Defusal Manual.
- [`README_CLUB_GUIDE.md`](file:///D:/melle/antigrav/bomb%20game%20L/README_CLUB_GUIDE.md) / [`README_CLUB_GUIDE.docx`](file:///D:/melle/antigrav/bomb%20game%20L/README_CLUB_GUIDE.docx): Complete DIY box build guide (<\$15 budget), room layout, anti-cheat referee rules, and hotkey reference.
- [`Operation_Three_Wise_Monkeys_Simulation.mp4`](file:///D:/melle/antigrav/bomb%20game%20L/Operation_Three_Wise_Monkeys_Simulation.mp4): 5-minute animated gameplay simulation video with full audio.
- `audio/`: Extracted original `.wav` sound effects (`doublebeep.wav`, `doublebeep_1.25.wav`, `singlebeep.wav`, `Strike.wav`, `BombExploded.wav`, `BombDefused.wav`, `GameOverFanfare.wav`, `EmergencyAlarm.wav`, `CorrectChime.wav`, `WireSnip.wav`, `LightSwitch.wav`, `ButtonPress.wav`).
- [`vercel.json`](file:///D:/melle/antigrav/bomb%20game%20L/vercel.json): Vercel cloud deployment config with clean URL rewrites (`/schematic`, `/manual`, `/pdf`), audio caching, and security headers.
- [`package.json`](file:///D:/melle/antigrav/bomb%20game%20L/package.json): Package metadata and deployment scripts.
