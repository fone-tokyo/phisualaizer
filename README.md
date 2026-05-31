# phisualaizer
PHISH-inspired lighting visualizer / CK5 omage / by FONE.TOKYO
# PHISUALAIZER v1.0

**PHISH-inspired lighting visualizer**
Inspired by CK5 (Chris Kuroda) / Created by FONE.TOKYO PROJECT

---

## What is PHISUALAIZER?

A browser-based lighting visualizer inspired by the legendary PHISH lighting designer **Chris Kuroda (CK5)**.
Built with Three.js. No installation required. Just open in Chrome.

---

## Features

- **6 Light Groups** — CEILING / WALL-HI / FLOOR / LEFT / RIGHT / MV (26 beams total)
- **Individual Control** — Speed, Length, Spread, Hue, Brightness, Blink per light
- **Particle Effects** — FLURRY / SPARKS / RAIN / ORBIT / BURST / DRIFT
- **Audio Reactive** — Load WAV/MP3 and particles react to the music
- **Camera Control** — ORBIT / DISTANCE / HEIGHT / FOV
- **TV Output** — Dual screen mode via BroadcastChannel API (16:9)
- **SYNC** — Group sync, column sync, cross-light sync
- **AUTO** — Parameters change slowly and automatically
- **SLOW / STOP** — Fine control of motion

---

## Files

| File | Description |
|------|-------------|
| `phisualaizer_control.html` | Main controller — open this in Chrome |
| `phisualaizer_view.html` | TV output view — open in second screen |

---

## Usage

### Single Screen
1. Open `phisualaizer_control.html` in Chrome
2. That's it. Everything works standalone.

### Dual Screen (TV Output)
1. Connect HDMI to TV
2. Set TV as extended display (not mirror)
3. Open `phisualaizer_control.html` in Chrome (on Mac screen)
4. Open `phisualaizer_view.html` in a new tab → drag to TV → F11 fullscreen
5. Both tabs sync automatically via BroadcastChannel

> ⚠️ Both files must be open in the **same Chrome browser** on the **same PC**

---

## Audio

- Supported formats: **WAV / MP3**
- M4A is not supported
- Drop audio file onto the DROP/SELECT area
- Particles react to bass frequencies

---

## License

MIT License — Free to use, modify, and distribute.

**Commercial use:** Credit required.
Please include: `Based on PHISUALAIZER by FONE.TOKYO`

---

## Credits

- Inspired by **Chris Kuroda (CK5)** — PHISH lighting designer
- Built with [Three.js r128](https://threejs.org/)
- Created by **FONE.TOKYO PROJECT**
- `github.com/fone-tokyo/phisualaizer`

---

## Version History

| Version | Date | Notes |
|---------|------|-------|
| v1.0 | 2026.05.31 | Initial release |

---

*For PHANS, by a PHAN. 🌟*
