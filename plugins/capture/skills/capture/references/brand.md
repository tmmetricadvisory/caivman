# Writing brand.md

The file every skill reads before it makes anything the person's clients will see. Keep it under a page. Facts a template builder can act on, not adjectives.

## Read first

1. Guidelines document, if there is one. Take colours, fonts, logo rules and tone from it verbatim where it gives them.
2. Logo files. Note each file, its format, whether it is the full lockup or an emblem, and whether it is for light or dark backgrounds. Measure the aspect ratio from the file; it goes in the note so nothing ever stretches it.
3. Font files. Note the family names and weights present.
4. The best work on the bench. Confirm the guidelines are what the person actually uses; where the work and the guidelines differ, the work wins and the note says so.
5. A website, only as a fallback. Read the stylesheet for colours and fonts if you can; say every value that was inferred.

## Write

```
# Brand: <Business name>

Written by capture on <date> from: <what was read>. Inferred: <what was guessed, or "nothing">.

## Colours
| Name | Hex | Use |
|---|---|---|
| <name> | #xxxxxx | Headings |
| <name> | #xxxxxx | The one accent. Never a wash. |
| <name> | #xxxxxx | Body text |
| <name> | #xxxxxx | Backgrounds, rules |

## Fonts
- Headings: <family> <weight>. If not installed: <fallback>.
- Body: <family> <weight>. If not installed: <fallback>.
- Files: <paths in context/brand/>.

## Logo
- Files: <path> (lockup, light backgrounds), <path> (lockup, dark), <path> (emblem).
- Aspect ratio: <w:h>. Minimum width: <mm>. Clear space: <rule>.
- Never: recolour, stretch, rotate, outline, add effects, place on a busy image.

## The look in a sentence
<One sentence: e.g. "Plenty of white space, one blue accent, navy headings, tables not boxes.">

## Paper
A4 (or US Letter if the business is in North America). Margins <mm>.

## Templates
- Word: context/brand/<Business>-Letterhead.dotx
- PowerPoint: context/brand/<Business>-Deck.potx
```

## If there are no guidelines

Build the palette from the logo (its colours become the accent and the heading colour), pick one neutral dark for text and one light neutral for rules, use the logo's font family if it is identifiable and a safe pair otherwise (a clean sans for headings and body), and label every line "inferred". Tell the person which three decisions they should confirm.
