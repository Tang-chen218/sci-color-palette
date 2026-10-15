# Scientific figure colour palettes

47 colour schemes collected from published journal figures, kept as a reference when choosing
colours for a new figure. Each is recorded as the hex values printed on its source card.

## What's here

| File | Contents |
|---|---|
| `SKILL.md` | A Claude Code skill that reads this library and picks a palette for a figure |
| `palettes.md` | The 47 palettes: hex values, source journal, and what each is useful for |

Source images are **not** included — they are figures published by Cell, Nature, Elsevier and
others, and redistributing them is not ours to do. Only the extracted colour values are here.

## Using it as a skill

Copy this directory to `~/.claude/skills/sci-color-palette/`. The skill then triggers on a
request for a colour scheme and reads `palettes.md` directly.

## How the values were extracted

By reading the hex labels **printed on each card**, not by sampling pixels from the image.
That choice matters: sampling would have produced four plausible-looking colours and hidden
the fact that four cards print a hex which disagrees with the RGB beside it, and two cards
print the same hex for two different swatches. Both defects are recorded in `palettes.md`
rather than quietly smoothed over.

## Contributing

Add an entry to `palettes.md` in the same shape and add its row to the index. Copy the hex
as printed. If the card disagrees with itself, record both values and say so.
