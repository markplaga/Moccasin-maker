# Moccasin Maker

A single web page for designing and making a soft-sole, puckered-toe **ankle-boot moccasin** from your own foot.

1. **Size from a photo.** Print the measuring mat (1 cm grid, corner targets A to D), stand on it or trace your foot, photograph it from above, and tap the corners and a few points on the foot. A 4-point perspective correction turns taps into millimetres. A ruler-only mode and an optional traced outline are included.
2. **Design.** Live side and top views: leather colour, cuff style (wrap-and-tie, fold-down, fringe), beadwork and an optional hard outsole.
3. **Pattern.** Wrap (sole + walls with heel dart), vamp + tongue, cuff and outsole, full size with gather notches and punch marks. Download a tiled Letter/A4 PDF or a full-size SVG.
4. **Make it.** Step-by-step instructions that use your numbers.

## Install on a phone

The app is a Progressive Web App: it installs from the browser and works offline after the first visit.

- **Live site:** https://markplaga.github.io/Moccasin-maker/ (served by GitHub Pages from `main`).
- **Android (Chrome, Edge, Samsung Internet):** tap **Install app** in the banner, or open the browser menu and choose **Install app** / **Add to Home screen**.
- **iPhone / iPad (Safari):** tap **Share**, then **Add to Home Screen**. The page shows these steps on iOS.

To publish your own copy: in the repo go to **Settings → Pages**, set **Source** to *Deploy from a branch*, and pick `main` and `/ (root)`.

## Use it

Open `index.html` in a browser. There is no build step. It loads fonts from Google Fonts and [jsPDF](https://github.com/parallax/jsPDF) 2.5.1 from cdnjs.

See [docs/PLAN.md](docs/PLAN.md) for the design plan and the pattern geometry.
