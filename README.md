# Chromatic Induction Generator

Interactive tool for exploring chromatic induction — the perceptual phenomenon where a surround color shifts the apparent hue, chroma, and lightness of an adjacent key color.

## What it does

Generate color pairs (surround + key) and preview how simultaneous chromatic contrast, the Hunt effect, and related mechanisms interact. Controls let you tune hue offset angle, lightness, chroma, and surround pattern to isolate or stack perceptual effects.

## Perceptual mechanisms modeled

- **Simultaneous chromatic contrast** — surround displaces key color along the opponent-color axis
- **Hunt effect** — perceived colorfulness increases with luminance
- **Lateral inhibition** — uniform surrounds amplify target saturation beyond variegated ones
- **Chromatic adaptation / hyperbolic colors** — prolonged surround viewing pushes perceived color past physical gamut limits

## Key hue offset angles

| Angle | Effect |
|-------|--------|
| 60°, 90° | Peak hue-shift induction |
| 120° | Strong induction (near-triadic) |
| 150° | Fading induction |
| 180° | Max chroma boost (radial displacement) |

## Output

Export generated pairs as CSS custom properties (`--cig-bg`, `--cig-key`) for use in production.

## Stack

Single self-contained HTML file. No build step, no dependencies beyond a Google Fonts import.
