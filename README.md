# Camo Swatch

Turn a landscape photo into a seamless, tileable camouflage pattern. Color extraction, pattern weaving, premade suggestions, stealth scoring, and SVG/PNG export all run in the browser. No photo leaves the device.

The static app is in [`docs/`](docs/) and on the [`gh-pages`](https://github.com/SmellyWolfInd/camo-swatch/tree/gh-pages) branch. Open `docs/index.html` with any static host. There is no backend.

## Try it

1. Drop a JPG, PNG, or WebP, or pick Mossy forest, Desert, Urban, or Snow.
2. Edit or lock the extracted swatches, then switch style: organic, digital, contour, cellular, tiger, or fleck.
3. Compare ranked premades (Woodland, Desert, MultiCam-style, MARPAT, Tiger stripe, Flecktarn, Urban, Snow, hunting foliage, blaze) in classic colors or recolored to the photo.
4. Check the 2×2 tile, cloth drape, and stealth score.
5. Export SVG, a 2048 PNG tile, a field card, or copy hex / CSS / JSON.

The same seed and settings always reproduce the same pattern.

## GitHub Pages

Publishing source is ready. This token cannot flip the Pages switch (`pages=write` is not granted), so the site is not live until that one setting is saved:

1. Open [Settings → Pages](https://github.com/SmellyWolfInd/camo-swatch/settings/pages).
2. **Build and deployment** → Source: **Deploy from a branch**.
3. Branch: **gh-pages**, folder **/(root)**, then Save.

The site will be [https://smellywolfind.github.io/camo-swatch/](https://smellywolfind.github.io/camo-swatch/).

To use Actions instead: set Source to **GitHub Actions**, then re-run [Deploy GitHub Pages](https://github.com/SmellyWolfInd/camo-swatch/actions).

## Privacy

Processing uses canvas, FileReader, and object URLs only. SVG export is paths and fills — no scripts or event handlers. The camera is requested only when you open it.
