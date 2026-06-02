# HUD Studio

Procedural sci-fi **HUD compositor** — a single-file, zero-dependency browser tool for building animated heads-up-display overlays and exporting them as layered, alpha-channel PNG sequences for After Effects.

Built for the Ben · REBA 2026 project.

![version](https://img.shields.io/badge/version-3.0-29ebed)

## Features

- **Footage** — drop a photo *or* video as the background plate. Video seeks per-frame on export for frame-accurate sync.
- **Tracking box** — 4 shapes (cut-corner / notched / stepped / brackets), full position & size control, drift, breathe, rotate, double-line, marching dashes, corner brackets, label tab, per-element glow.
- **HP / vitals animation** — keyframe editor (time in seconds → value %) with smooth / linear / step easing and mode presets (critical / recovering / sorted).
- **Supporting geometry** — outer frame brackets, background grid, ruler edge-ticks, procedural circuit traces with pulsing nodes, rotating reticle ring.
- **Splines** — draw smooth (Catmull-Rom) splines directly on the canvas with animated flow-dash, node dots, and per-spline color.
- **Data tags** — add/remove tags with header strip, big value, status dot, animated connector lines (float / pulse / drift).
- **Typography** — global HUD font scale, mono / Rajdhani typefaces. *(Canvas ignores CSS vars — fixed in v3.)*
- **Export** — composited PNG, HUD-only alpha PNG, and per-layer PNG sequences (box / geometry / splines / bars / tags / scan) with transparent background.

## Usage

It's a single HTML file. Open it in any modern browser:

```bash
open ben_hud_studio_v3.html
```

No build step, no server, no install.

## Files

| File | Notes |
|------|-------|
| `ben_hud_studio_v3.html` | Current version |
| `ben_hud_studio_v2.html` | Previous version (kept for reference) |
