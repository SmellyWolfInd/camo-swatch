# Camo Swatch

Turn a landscape photo into a seamless, tileable camouflage pattern. Color extraction, pattern weaving, premade suggestions, stealth scoring, and SVG/PNG export all run in the browser. No photo leaves the device.

**Live app:** https://smellywolfind.github.io/camo-swatch/

The published site is the static bundle in [`docs/`](docs/) and on the `gh-pages` branch.

## Try it

1. Drop a JPG, PNG, or WebP, or pick Mossy forest, Desert, Urban, or Snow.
2. Pick a family: Military or Hunting. Tiger stripe and brushstroke are separate. Hunting styles have plant types, bark types, pine forest types, and a density slider. Sample photos include a pine forest. Use Optimize to search combinations for the highest stealth score. Each palette color, including one picked from the photo, shows the closest Krylon spray. Camouflage cans are Black, Brown, Khaki, Olive, Sand, and Woodland Light Green. That chip is a screen match; the can will not be exact.
3. Edit a swatch, or arm the eyedropper and click a pixel on the photo. Compare ranked premades in classic colors or recolored to the photo.
4. Check the 2×2 tile, cloth drape, and stealth score.
5. Export SVG, a stencil layer per color, a 2048 PNG tile, a field card, or hex / CSS / JSON.

Patterns are multi-scale: large breakup, mid shapes, and fine shadow grit, with ragged edges so the tile does not read as smooth vector art.

The same seed and settings always reproduce the same pattern. Vary detail shifts only the fine texture.
