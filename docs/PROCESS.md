# Process: Identity Card, Order and Rupture (the quiet version)

Dania Altman · Homework Assignment 1 · design MA

This is the second build of the same homework. The first build lives at https://altmandania-ui.github.io/hit1/ and its process file is https://github.com/altmandania-ui/hit1/blob/main/docs/PROCESS.md. That version is loud on purpose: a 1999 desktop, marquees, a countdown wall, seven videos. This version keeps the same argument and the same material and says it as quietly as possible: an inventory of one person on a white page.

> ✍️ marks the places that still need my own words, sketches or photos before submitting.

---

## 1. The concept

**The grid is the plan. The cats are what actually happens. The page is the space between them.**

The reference I gave was a one-screen Carrd site: a cut-out hand on white, five small objects placed on and around it in thin boxes with numbers and one-word labels, a serif question underneath, a credit line, nothing else. This page is built the same way.

| Layer | Where | How it is said this time |
|---|---|---|
| Order | The stage at the top, the identity card, the index | A grid of twelve columns and eight rows under the stage. Every thing on it has coordinates, written in the index at the bottom. Press **[ show the grid ]** (or the `g` key) and the cells and coordinates appear in red. The identity card is a plain table in Helvetica with hairlines. |
| Rupture | The six things on the stage, Fig. 2 | My cut-out passport photo in the middle, and around it: the Saint-Honoré, Tova belly up, Sofi, the Kinder egg, the 7am selfie, two candles that light themselves on Friday. Each sits a few pixels off its cell, and the dial on the card can take the cats away: at zero cats everything snaps exactly into place and the page admits it has never seen that happen. Fig. 2 lists the photos no grid has held, with their deviation written under each. |
| Templatology | Exhibit A | The AI's default hero, small and grey, with one red line through it, next to the list of what the template did and what I decided. |

**How they meet:** the rupture is measured in the order's own units. A cat is a thing with coordinates. The grid can be shown at any time to check. Red belongs to the system (the grid, the live dot), blue belongs to me (the measurements, the corrected words in the position text).

---

## 2. Order: every measurement chosen

| Decision | Value | Why |
|---|---|---|
| Grid | 12 columns × 8 rows on the stage | Twelve divides into halves, thirds and quarters. Eight rows give the stage a 12:9 frame. Every thing's cell is written in the index. |
| Column | 720px, centered | An inventory is laid out around its object, so the page is centered on purpose, not by default. Body text is still flush left inside the column. |
| Typefaces | Times for sentences, Helvetica for facts | The two faces that were already on every computer. I chose the defaults on purpose, which is not the same as accepting them. No web fonts, nothing to load. |
| Sizes | 11 / 13 / 17 / 22 / 24 | Label, data, body, lead, heading. Nothing shouts. |
| Colour | white, black, grey `#777`, red `#E3000F`, blue `#1636E8` | Red only for the grid and the live dot. Blue only for my own hand. |
| Lines | 1px, square | A box around each thing, a hairline between fields. No shadows, no corners. |
| Photos | Natural ratio, never cropped or stretched. Cut-outs for the stage. | The 7am selfie is shown at its real 150px. The five cut-outs were made with Magnific's background removal from my own photos, then shrunk. |
| Motion | Only in answer to an action | The dial, the grid toggle, the photo click. The candles flicker only during Shabbat. Reduced-motion users get none of it. |

## 3. Templatology vs. conscious modernism

| | Template (Exhibit A) | This page |
|---|---|---|
| Alignment | Centered because that's the default | Centered because an inventory surrounds its object; text flush left |
| Type | Inter (already there) | Times and Helvetica (also already there), chosen on purpose |
| Corners | 16px radius everywhere | Square. A box is a one pixel line |
| Colour | Gradient `#667eea → #764ba2` | White, black, red for the grid, blue for me |
| Copy | "Passionate designer crafting delightful experiences" | Six things, numbered, and a table of facts including today's Hebrew date |
| Ideology | None: the look of order without the belief | Clarity, honesty, a reason for every measurement |

---

## 4. What the AI suggested, and how I responded

| # | What I asked / what happened | What was built | Commit |
|---|---|---|---|
| 1 | After thirteen rounds on the loud version, I asked for **the whole site again in a new repo, more modern, clean and quiet**, as the same homework. | First draft: white page, Archivo, the identity card as one big red colour field, cats with white frames, a "show the grid" button. | first commit |
| 2 | **"I don't like it. More quiet than that, and the grid more interesting."** | Second draft: no colour fields, smaller type, a modular grid of 96px modules drawn faintly all the time, and the card's fields stepping down the grid one module each like a timetable. Not committed: before I saw it I sent a reference. | — |
| 3 | I sent a Pinterest pin: a one-screen Carrd site, a cut-out hand on white with five small numbered objects around it, a serif question, a credit line. **"Maybe more like this."** | This page. Times and Helvetica only. My cut-out portrait on a 12 × 8 grid with six numbered things around it in thin boxes, "Who is this? [ Identity card ]" underneath, "Made in Holon ©" as the credit, and the rest of the homework as numbered entries with a lot of white space. The grid is hidden until asked for, and the index at the bottom gives every thing's coordinates. The cut-outs were made with Magnific from my own photos. | this commit |
| 4 | I kept the live data. | The Hebrew date, this week's candle-lighting and havdalah times for Tel Aviv, and this repository's own git history are fetched when the page loads, from hebcal.com and api.github.com, with no keys. The countdown is one Hebrew line, and the candles, on the stage and in entry 3, light themselves on Friday. | this commit |

✍️ **Add here:** which of the two versions you will submit, and why. If the answer is "both", say what each one is for.

---

## 5. Manual work and raw materials

- **Real photos** (`images/`): me (deadpan, laughing, asleep, 7am, side, with the Kinder egg, at a wedding, in a laundromat, with the sandwich), my cats Sofi, Moffi, Toffy and Tova, my baking (Saint-Honoré, poppy-seed dough).
- **Cut-outs** (`images/cut-*.png`): my portrait, the Saint-Honoré, Tova, Sofi and the Kinder egg, cut out of the photos above with Magnific's background removal.
- **Metadata** was stripped from all photos.
- ✍️ **Sketches:** put paper sketches of the grid and the card in `docs/sketches/` and link them here.
- ✍️ **Handwriting:** the blue measurements could be set in a scan of your own handwriting instead of italic Times. That is the most non-replicable upgrade available.
