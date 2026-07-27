# Aerodrome Apex 🏎️

A Micro Machines–style top-down racer: tiny vehicles tearing around big circuits with arcade drift physics, AI opponents, time trials, hazards, jumps, and weather.

**▶ Play it here: `https://github.freaxnx01.ch/game-aerodrome-apex/`**

![Top-down arcade racer](https://img.shields.io/badge/style-top--down%20arcade-ff6a2b) ![Single file](https://img.shields.io/badge/build-none%20needed-8fd8e8) ![License](https://img.shields.io/badge/license-MIT-bfe3b2)

## Features

- **8 vehicle types** — from the balanced Slick Rod to the 52-tonne Tank, each with distinct speed/accel/grip stats and unique rendering (van light bar, bus windows, rally stripes, tank turret)
- **4 tracks** — an airfield GP, a fast flowing ex-RAF circuit, a short alpine power track, and a dirt rallycross course with jump ramps
- **Race or Time Trial** modes — 6-car grid vs. AI, or solo laps chasing a locally-saved best time
- **Arcade drift physics** — surface-aware grip (tarmac/grass/dirt), oil slicks, boost strips, jumps, and rain that changes handling
- **AI opponents** — pure-pursuit steering with rubber-banding and stuck-car recovery
- **Two camera modes** — top-down and isometric, toggle with `C`
- **Synthesized audio** — engine note, skid/grass/rain noise beds, and one-shot SFX, all Web Audio, no audio files
- Best lap times saved locally per track

## Controls

| Input | Action |
|---|---|
| ↑ / ↓ | Accelerate / brake & reverse |
| ← / → | Steer |
| C | Toggle camera (top-down / isometric) |
| R | Reset / restart |
| Esc | Back to menu |
| Enter | Confirm / start |

## Running locally

Open `index.html` in any modern browser — that's it.

## Tech

Single-file HTML5 canvas game built on a small custom `sc-if`/`sc-for` template runtime (`support.js`) driving one `Component` class: Catmull-Rom track generation, dt-scaled arcade physics, pure-pursuit AI, and fully canvas-drawn visuals (no external art assets). Fonts (Russo One, Chakra Petch) load from Google Fonts.

## License

MIT — see [LICENSE](LICENSE). Track names and liveries are original, not references to real circuits or brands.
