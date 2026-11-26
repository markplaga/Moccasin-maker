# Moccasin Maker: plan

A single web page for designing and making a soft-sole, puckered-toe ankle-boot moccasin from your own foot measurements.

## What it does

1. **Size from a photo.** Print the measuring mat (a 1 cm grid inside a 170 × 250 mm frame with corner targets). Stand on it or trace your foot on it, take a photo from above, then tap the four frame corners and a few points on the foot. A 4-point perspective correction turns the taps into real millimetres, so the camera does not have to be perfectly square. A ruler-only mode works too (tap two ruler marks and type the distance). You can also tap around the outline to use your own foot shape instead of the built-in one.
2. **Measurements.** Foot length, ball and heel width, ball and instep girth, leg circumference and cuff height, in inches or centimetres. Presets cover common sizes.
3. **Design preview.** Side and top views redraw live: leather colour, cuff style (wrap-and-tie, fold-down, fringe), beadwork (rosette, beaded edge, none) and an optional hard outsole.
4. **Pattern.** Four pieces are generated to scale:
   - **Wrap**: the sole and side walls in one piece, with a heel dart.
   - **Vamp and tongue**: the U-shaped top piece, gathered into the wrap.
   - **Cuff**: a curved band cut as a flattened cone so it follows the leg.
   - **Outsole** (optional).
   The pieces include numbered gather notches, punch-hole marks and grain arrows. The page reports the gather ratio and other fit checks.
5. **Print.** Download a tiled PDF for Letter, Legal, Tabloid or A4 with a cover page, test squares and a tile map, or download a full-size SVG for a plotter or a copy shop.
6. **Instructions.** Step-by-step making directions that use your numbers, such as hole spacing, stitch counts, lace length and leather area.

## How the geometry works

- The foot outline is a smooth spline sized to your length and widths, or your traced outline.
- The wrap is the outline offset outward by the side-wall height. The heel excess, about 0.75 × the heel turning angle × the wall height, is removed as a dart.
- The vamp width comes from girth minus sole width minus both walls. Its length is the slope distance from the instep to the toe.
- The gather ratio is the wrap toe-edge length divided by the vamp U length. Matching hole counts on both edges spread the puckers evenly.
- The cuff's bottom length matches the opening around the heel and its top length matches the leg circumference plus overlap. It is cut as an annular sector.

## Next steps (if this moves into a repo)

- Split the page into modules for geometry, rendering and photo calibration, and add unit tests for the geometry.
- Add a two-page mat for feet longer than 25 cm on one sheet.
- Add other styles: a one-piece Woodland moccasin and a two-piece Plains hard-sole moccasin.
