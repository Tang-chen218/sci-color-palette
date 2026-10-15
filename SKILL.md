---
name: sci-color-palette
description: >
  Pick colours for a scientific figure from a library of 47 palettes taken from published
  journal figures (Cell, Nature, Gut, JEM, STTT and others). Use when choosing a colour
  scheme for a plot or diagram, when asked for 配色 / 配色方案 / 科研配色 / a palette for a
  figure, or when an existing figure's colours need replacing. Not for brand or UI design.
---

# Scientific figure colour palettes

Read `palettes.md` and pick from it. Do not invent a scheme when the library has one that fits.

## Choosing

Match on **how many distinct things the figure must distinguish**, then on the stated use:

| Need | Look for |
|---|---|
| 2–5 groups (boxplot, Kaplan-Meier, forest) | 5–6 colours |
| 6–10 groups, or group x time | 8–10 colours |
| Many components in one schematic | 14–16 colours |
| A schematic whose parts carry meaning | the entries with a `Use` note saying what the colours encode |

The index table lists colours / journal / use for every entry, so filter there and read only
the candidates.

## Before using a palette

Six source cards are imperfect and are flagged in the index:

- `08` `11` `12` `16` — the card's printed hex disagrees with its printed RGB. The recorded
  value is the hex. Open the original figure if an exact match matters.
- `41` `44` — two different swatches carry the same printed hex. Check the original first.

## Using the colours

Copy the hex values straight out of the library. For matplotlib, pass them as a list to
`color=` / `palette=`; `sns.set_palette()` and `matplotlib.colors.to_rgb()` both accept them
directly. **Keep the printed order** — the source cards order colours deliberately
(light to dark, or by group), and reordering silently changes which group reads as which.

For a figure that will also be printed in greyscale, check that the chosen colours separate
by luminance, not only by hue. `colorsys.rgb_to_hsv` plus a relative-luminance calculation
is enough; aim for a luminance ratio above ~1.9 between adjacent groups.

## Adding palettes

Append an entry to `palettes.md` in the same shape and add its row to the index table.
**Copy the hex as printed on the card; do not sample pixel colours.** Sampling picks up
JPEG artefacts and anti-aliased swatch edges, and it hides card errors instead of recording
them. If a card's hex and RGB disagree, record both and note it — do not silently pick one.
