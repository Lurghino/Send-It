# Player mat specification

Physical spec for the four climber mats. Written to be handed to an image or layout AI.
All measurements in millimetres. Origin is the top-left corner of the TRIM edge.

---

## 1. Format and print

| Property | Value |
|---|---|
| Trim size | 260 x 180 mm, landscape |
| Bleed | 3 mm all round, so full artwork is 266 x 186 mm |
| Safe margin | 6 mm inside trim. No text or icon closer than this to the edge |
| Resolution | 300 dpi minimum, 600 dpi for line work |
| Colour | CMYK for print, sRGB for screen proofs |
| Corners | Square for chipboard. 5 mm radius if produced as a neoprene mat |
| Material | 2 mm chipboard, matt finish. Prototype version prints on A4 with bleed |
| Quantity | 4 mats, identical layout, differing in colour, portrait, name and stat numbers |

Keep the layout identical across all four mats. Only the accent colour, the portrait, the
climber name, the tagline and the three stat numbers change. Players need to read each
other's mats across the table at a glance.

---

## 2. Zone map

Nine zones. Coordinates are x-start, y-start, width, height.

| # | Zone | x | y | w | h |
|---|---|---|---|---|---|
| 1 | Name banner | 0 | 0 | 260 | 22 |
| 2 | Portrait | 8 | 28 | 78 | 66 |
| 3 | Stat line | 8 | 100 | 78 | 26 |
| 4 | Tagline | 8 | 130 | 78 | 12 |
| 5 | Ability card slot | 96 | 28 | 70 | 95 |
| 6 | Drop tracker | 178 | 28 | 24 | 122 |
| 7 | First ascents | 208 | 28 | 44 | 46 |
| 8 | Pump-out track | 208 | 80 | 44 | 30 |
| 9 | Head start box | 208 | 116 | 44 | 34 |
| 10 | Rules reminder strip | 0 | 156 | 260 | 24 |

Background: dark slate rock texture, subtle, no strong pattern behind text. All zone
panels sit on top of it as slightly lighter plates with a 1 pt hairline border.

---

## 3. Zone detail

### Zone 1, name banner
Full-bleed horizontal band in the climber's accent colour, 22 mm tall.

- Climber type name, left-aligned, x = 12, vertically centred. Condensed sans, all caps,
  22 pt, near-black on the accent colour.
- Small circular colour token, 12 mm diameter, at x = 236, centred vertically. This is the
  same colour as that player's pawn so mat and pawn are unmistakably paired.

### Zone 2, portrait
78 x 66 mm framed illustration. Comic-book style, half-body, climber mid-move on rock.
Each character in a distinct pose that reads their type:

- Boulderer: compressed on a steep block, both hands crimping, feet high, explosive.
- Sport climber: clipping a bolt on an overhang, relaxed but pumped forearms.
- Alpinist: hooded, snow on the shoulders, high on a ridge, calm and methodical.
- Trad climber: delicate slab move, weight on the toes, hand fiddling a nut.

Frame: 1.5 mm inner border in the accent colour, square corners.

### Zone 3, stat line
Three equal boxes, 24 x 26 mm, 3 mm gutters, side by side.

Each box, top to bottom:
- Category icon, 8 mm tall, centred.
- Signed number, 20 pt bold, tabular figures, in the category colour.
- Category label, 6 pt, all caps, letter-spaced, in muted grey. STR, END, TEC.

Icons:
- Strength: a clenched fist gripping a crimp edge.
- Endurance: a coiled rope loop.
- Technique: a climbing shoe toe on a small edge.

Category colours: strength `#C3452F`, endurance `#3E8E8C`, technique `#D9A227`.

Stat numbers per mat:

| Climber | STR | END | TEC | Accent |
|---|---|---|---|---|
| Boulderer | +2 | -1 | 0 | `#C3452F` |
| Sport climber | 0 | +2 | -1 | `#3E8E8C` |
| Alpinist | -1 | +1 | +1 | `#8C7BB0` |
| Trad climber | -1 | 0 | +2 | `#D9A227` |

### Zone 4, tagline
One line, italic serif, 9 pt, muted grey, centred under the stat line.

- Boulderer: all power, no patience
- Sport climber: trained for the redpoint
- Alpinist: moves all day, cannot pull hard
- Trad climber: precise feet, careful head

### Zone 5, ability card slot
A recessed rectangle sized for a **sleeved standard card, 63.5 x 88 mm**. Outer slot
70 x 95 mm gives 3 mm clearance on each side.

- Draw as an inset well: 2 mm inner shadow along the top and left edges so it reads as a
  place to put a card, not a printed panel.
- Dashed 0.5 mm outline, accent colour at 40% opacity.
- Centred placeholder text, 8 pt, all caps, letter-spaced, 30% opacity: ABILITY CARD.
- A small icon of a card corner in the bottom-right of the well.
- Label above the well, 7 pt caps: YOUR ABILITY, THIS ROUTE.

### Zone 6, drop tracker
Vertical water gauge. This is the most-used part of the mat, so make it the clearest.

- 8 drop-shaped cubbies in a single column, each 20 mm wide x 12 mm tall, 2 mm gaps.
  Total 110 mm, starting at y = 32.
- Fill order is **bottom to top**, so the column reads like a water level.
- Cubbies 1 to 5 counted from the bottom: standard, outlined in endurance teal.
- Cubbies 6, 7, 8: head start only. Outlined in green `#9CB04E`, hatched at 15% so they
  read as different from the recoverable five.
- **Ceiling line: a solid 1.5 mm bar in strength red across the full width of the tracker,
  sitting between cubby 5 and cubby 6.** To its right, rotated 90 degrees, 6 pt caps:
  RECOVER TO HERE.
- Header above the column, 7 pt caps: DROPS.

The rule must be legible from the mat alone: you can hold up to 8, you can never recover
above the red line.

### Zone 7, first ascents
44 x 46 mm panel.

- Header, 7 pt caps: FIRST ASCENTS.
- 10 small hexagons, 9 mm across, in two rows of five, 2 mm gaps. Hexagons because they
  are the hold tiles.
- Empty hexagons are outlined only. Mark with a token or pencil tick as you claim them.
- Small note, 6 pt: first to turn a hold face up.

### Zone 8, pump-out track
44 x 30 mm panel.

- Header, 7 pt caps: PUMP-OUTS.
- 5 circles, 8 mm diameter, in a row.
- To the left of the first circle, a small lightning or snapped-rope glyph.
- Note, 6 pt: no marks means the flash is still alive.

### Zone 9, head start box
44 x 34 mm panel.

- Header, 7 pt caps: TURN ORDER.
- Four small squares, 8 x 8 mm, labelled 1st, 2nd, 3rd, 4th.
- Under them, 6 pt: 2nd, 3rd and 4th start with +1, +2, +3 drops above the line.

### Zone 10, rules reminder strip
Full-width footer band, 24 mm tall, darker than the mat body. Three columns separated by
thin vertical rules, 7 pt text, generous leading.

**Column A, TO CLIMB A HOLD**
1. Rows 3 to 5 cost 1 drop before you roll
2. Roll three dice, one per category
3. Turn the hold face up, one point of shortfall forgiven

**Column B, THEN CHOOSE**
- Matched everything: climb it free
- Short: pay 1 drop per point to force it
- Or back off for 1 drop and stay put

**Column C, WATER**
- Water symbol returns 1 drop
- Rest ledge returns 2, chalking up returns 1, or 2 if blocked
- At zero you drop 2 rows and refill to the red line

---

## 4. Visual direction

- **Mood**: a climbing guidebook page, not a fantasy game board. Restrained, technical,
  a little worn. Ink on stone rather than glossy fantasy art.
- **Background**: dark basalt grey `#181F22` with a faint granite grain and one subtle
  diagonal chalk smear. Nothing that competes with text.
- **Panel plates**: `#232E33` at 90% opacity, hairline borders `#EFEAE0` at 14%.
- **Text**: chalk white `#EFEAE0` for values, `#A7AFAC` for labels.
- **Typography**: one condensed sans for all structural text, labels in caps with wide
  letter-spacing. One serif italic used ONLY for the tagline. Nothing else.
- **Icons**: single-weight line icons, 1.5 pt strokes, no gradients, no drop shadows.
- Avoid: bevels, glows, gradient buttons, faux 3D, drop shadows on text.

---

## 5. Companion piece, ability cards

Not part of the mat, but the slot is sized for these, so spec them together.

| Property | Value |
|---|---|
| Size | 63.5 x 88 mm, standard poker card |
| Bleed | 3 mm, safe margin 4 mm |
| Corners | 3 mm radius |

Card layout top to bottom:
1. Title bar, 12 mm, ability name in caps.
2. Icon panel, 30 mm, one line illustration of the ability.
3. Timing band, 7 mm, a coloured strip with one of three words: ALWAYS, PER ATTEMPT,
   PER ROUTE. Use three distinct colours so players can sort by timing at a glance.
4. Rules text, 26 mm, 8 pt, maximum 25 words.
5. Flavour line, 8 mm, italic, 7 pt.

The six abilities currently in play, with their timing bands:

| Ability | Timing | Text |
|---|---|---|
| Arête Specialist | PER ATTEMPT | On the outer columns, add 1 to any category. Once per hold, so a retry gets nothing. |
| Onsighter | PER ROUTE | Declare before rolling on a face-down hold. Establish it clean and gain 2 drops. Come up short and lose 2. |
| Dynamic Mover | ALWAYS | When you are short by exactly 1, force the move for free. |
| Deep Lungs | PER ROUTE | The first water symbol you roll on each row returns 1 extra drop. Five rows, five chances. |
| Long Reach | PER ROUTE | Once per route, attempt a hold two rows straight up. |
| Poacher | ALWAYS | You may attempt a hold another climber is on. Establish it and swap places with them. |

---

## 6. Prompt for an image AI

Use this as a starting prompt, then iterate zone by zone.

> A board game player mat, 260 x 180 mm landscape, for a rock climbing race game. Dark
> basalt grey background with faint granite grain. Top edge has a full-width deep red
> banner with the words BOULDERER in condensed white capitals, and a red circular token at
> the right end. Below left, a framed comic-style illustration of a powerful boulderer
> compressed on a steep block, both hands crimping. Under the portrait, three small boxes
> showing +2 STR in red, -1 END in teal, 0 TEC in amber, each with a small line icon.
> Centre, a recessed empty card well the size of a playing card, dashed outline, faint
> capitals reading ABILITY CARD. Right, a vertical gauge of eight drop-shaped cubbies
> stacked bottom to top, the lower five outlined teal and the upper three hatched green,
> with a solid red horizontal bar between the fifth and sixth cubby. Beside it, a small
> panel of ten empty hexagons labelled FIRST ASCENTS, and a row of five circles labelled
> PUMP-OUTS. A dark footer strip across the bottom holds three columns of small
> instructional text. Flat vector illustration, single-weight line icons, restrained
> climbing guidebook aesthetic, no gradients, no glows, no drop shadows, print-ready.

Swap the name, accent colour, portrait description and the three stat numbers for each of
the other three mats.
