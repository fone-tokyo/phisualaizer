# PHISUALAIZER v1.1.1

**PHISH-inspired lighting visualizer**
Inspired by CK5 (Chris Kuroda) / Created by FONE.TOKYO PROJECT

---

## What is PHISUALAIZER?

A browser-based lighting visualizer inspired by the legendary PHISH lighting director **Chris Kuroda (CK5)**.
Built with Three.js. No installation required. Just open in Chrome.

---

## Disclaimer

This is an **unofficial fan-made project**.
Not affiliated with, endorsed by, or connected to Phish, CK5 (Chris Kuroda), or any related organizations.

This software is provided "as is", without warranty of any kind.
The authors are not responsible for any damages, injuries, or issues arising from the use of this software.
Use at your own risk.

---

## Warning

The **BLINK** feature produces flashing lights.
Flashing lights may cause photosensitive seizures in some people.

- Use the BLINK feature with caution.
- Not recommended for public events without prior warning to attendees.
- If you experience discomfort, dizziness, or seizures, stop use immediately.

---

## Installation

**None. Zero. Zip.**

1. Download ZIP from this repository
2. Unzip
3. Open `phisualaizer_control_111.html` in **Chrome**
4. Done.

> **Works on Mac and Windows.**
> **Works offline.** -- Both files are fully self-contained. No internet required.
> **Chrome recommended** -- BroadcastChannel (TV output sync) requires Chrome.

---

## Features

- **6 Light Groups** -- CEILING / WALL-HI / FLOOR / LEFT / RIGHT / MV (26 beams total)
- **Individual Control** -- Speed, Length, Spread, Hue, Brightness, Blink per light
- **Particle Effects** -- FLURRY / SPARKS / RAIN / ORBIT / BURST / DRIFT
- **Audio Reactive** -- Load WAV/MP3 and particles react to the music
- **Camera Control** -- ORBIT / DISTANCE / HEIGHT / FOV
- **TV Output** -- Dual screen mode via BroadcastChannel API (16:9)
- **SYNC** -- Group sync, column sync, cross-light sync
- **AUTO** -- Parameters change slowly and automatically
- **SLOW / STOP** -- Fine control of motion
- **COMBO** -- 2001 performance combo triggers (new in v1.1)

---

## Files

| File | Description |
|------|-------------|
| `phisualaizer_control_111.html` | Main controller -- open this in Chrome |
| `phisualaizer_view_111.html` | TV output view -- open in second screen |

---

## Usage

### Single Screen
1. Open `phisualaizer_control_111.html` in Chrome
2. That's it. Everything works standalone.

### Dual Screen (TV Output)
1. Connect HDMI to TV
2. Set TV as extended display (not mirror)
3. Open `phisualaizer_control_111.html` in Chrome (on Mac screen)
4. Open `phisualaizer_view_111.html` in a new tab -- drag to TV -- F11 fullscreen
5. Both tabs sync automatically via BroadcastChannel

> Both files must be open in the **same Chrome browser** on the **same PC**

---

## Audio

- Supported formats: **WAV / MP3**
- M4A is not supported
- Drop audio file onto the DROP/SELECT area
- Particles react to bass frequencies

---

## COMBO -- 2001 Performance Mode

Trigger each note of the iconic 2001 build with a single key.

| Key | Button | Effect |
|-----|--------|--------|
| `a` | C1 | L2 lights up from the back |
| `s` | C2 | L2 + L1 join in |
| `d` | C3 | L2 + L1 + L3 -- full build |
| `[SPACE]` | C4 | ALL lights -- flash -> freeze -> sparkle fade |

- Hold `a` / `s` / `d` to sustain the effect. Release to return.
- `[SPACE]` triggers the full C4 sequence automatically:
  - Full blast -> 3-second freeze (the "decisive pose") -> 5-second sparkle fadeout -> back to normal

---

## How it was made

**Built in a single day -- May 31, 2026.**

This entire project was created through a conversation with **Claude (AI by Anthropic)**.

No traditional coding was done by the author.
Pure collaboration between human vision and AI execution.

- The idea, creative direction, and all design decisions -- **human**
- The code -- **AI-generated**

This is what human-AI collaboration looks like in 2026.

---

## How to customize with Claude

You don't need to know how to code.
Anyone can modify PHISUALAIZER using Claude.

1. Go to **claude.ai**
2. Upload `phisualaizer_control_111.html`
3. Ask Claude to modify anything:
   - *"Add a new light group"*
   - *"Change the default colors to red"*
   - *"Add a strobe effect"*
   - *"Make the particles react to high frequencies"*
4. Download the modified file
5. Open in Chrome

**No coding knowledge required!**

---

## Contributions Welcome!

Fork it, improve it, share it.

Ideas for future versions:
- Mobile support
- Better audio sync
- New particle types
- Preset save/load
- More light groups

If you improve it, please:
- Credit **FONE.TOKYO** as the original
- Share your version on GitHub
- Let us know -- we'd love to see it!

Pull requests welcome!

---

## License

MIT License -- Free to use, modify, and distribute.

**Commercial use:** Credit required.
Please include: `Based on PHISUALAIZER by FONE.TOKYO`

---

## Credits

- Inspired by **Chris Kuroda (CK5)** -- PHISH lighting director
- Built with [Three.js r128](https://threejs.org/)
- Created by **FONE.TOKYO PROJECT**
- Built in collaboration with **Claude by Anthropic**
- `github.com/fone-tokyo/phisualaizer`

---

## Version History

| Version | Date | Notes |
|---------|------|-------|
| v1.0 | 2026.05.31 | Initial release -- built in one day |
| v1.0.1 | 2026.06.01 | Add disclaimer and warning |
| v1.1 | 2026.06.04 | Offline support / COMBO mode (2001) / Keyboard shortcuts |
| v1.1.1 | 2026.06.04 | Full ASCII cleanup -- all comments in English / charset fix |

---

*For PHANS, by a PHAN.*
