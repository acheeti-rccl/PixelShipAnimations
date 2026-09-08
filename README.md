# PixelShipAnimations

Open-source pixel-art character sprites and animations of shipboard crew, generated with [PixelLab](https://pixellab.ai) (v3 characters, low top-down view).

## Contents

- `sprites/<character>/<animation>/frame_NNN.png` — 12 shipboard characters (navigator, marine engineer, safety officer, HVAC technician, and more), each with:
  - `idle` (4 frames), `walkEast` / `walkWest` (6), `type` (9), `thumbsUp` (7–9), `celebrate` (9)
- `backgrounds/` — 400×224 pixel-art scene backgrounds (ship engine room, ops lounge) and props

All frames are transparent-background PNGs, cropped to a per-character square with feet anchored to the bottom edge, so they drop straight into a sprite engine.

## Usage

Frames are plain PNG sequences — loop them at ~8–10 FPS. `walkWest` is a real generation, not a mirrored `walkEast`.

## License

Released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) — free to use for any purpose, no attribution required.
