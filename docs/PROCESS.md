# Process: Identity Card, Order and Rupture (the quiet version)

Dania Altman · Homework Assignment 1 · design MA

This is the second build of the same homework. The first build lives at https://altmandania-ui.github.io/hit1/ and its process file is https://github.com/altmandania-ui/hit1/blob/main/docs/PROCESS.md. That version is loud on purpose: a 1999 desktop, marquees, a countdown wall, seven videos. This version keeps the same argument and the same material, and says it quietly.

> ✍️ marks the places that still need my own words, sketches or photos before submitting.

---

## 1. The concept

**The grid is the plan. The cats are what actually happens. The page is the space between them.**

| Layer | Where | How it is said this time |
|---|---|---|
| Templatology | Exhibit A | The AI's default hero is shown small, in grey, with one red line through it, next to a two-column list: what the template did, what I decided. |
| Order | Fig. 1, Fig. 3, the whole page | One grid, one typeface, ink and paper. The only colour field is the identity card, which is red. Press **Show the grid** (or the `g` key) and the twelve columns and the 8px baseline appear under everything. |
| Rupture | The cats on the card, Fig. 2 | The four real cats sit on the card with a slight tilt and a caption. Every photo in Fig. 2 is a measured distance off its column, and the distance is written under it in blue. The dial on the card takes the cats from four to zero: at zero the fields sit perfectly on the grid and the margin admits that this has never been observed in the wild. |

**How they meet:** the rupture is measured in the order's own units. A cat is a photo with a width and an angle. A photo sits +6 px and −1.2° off its column, and says so. The grid can be shown at any time to check. Red belongs to the system (figure numbers, the card, the line through the template). Blue belongs to me (the notes, the measurements, the corrected words in the position text).

---

## 2. Order: every measurement chosen

| Decision | Value | Why |
|---|---|---|
| Grid | 12 columns, 4 on mobile | 12 divides into halves, thirds and quarters: three columns for the photo, nine for the fields, three by three for the fields themselves. |
| Gutter / margin | 24px / 48px (16 / 20 on mobile) | Multiples of the 8px baseline. |
| Baseline | 8px | Every line-height and vertical space is a multiple of 8. The grid toggle draws it. |
| Typeface | Archivo, one family | A grotesque in the Akzidenz line, not Inter, which is the template's default. Rubik only as the Hebrew fallback. |
| Type scale | 13 / 17 / 26 / 40 / 96 | Label, body, field value, heading, name. The 176 of the loud version is gone; nothing here needs to shout. |
| Colour | ink `#000`, paper `#fff`, red `#E3000F`, blue `#1636E8` | True black on true white. Red is used once as a whole field (the card) and otherwise only as a thin mark. Blue is reserved for my own hand. |
| Alignment | Flush left, ragged right, everywhere | The opposite of the template's centered hero. |
| Photos | Natural ratio, never cropped or stretched | The 7am selfie is shown at its real 150px. Toffy is 102px wide. |
| Motion | Only in answer to an action | The dial, the grid toggle, the photo click. The candles flicker only during Shabbat. Reduced-motion users get none of it. |

## 3. Templatology vs. conscious modernism

| | Template (Exhibit A) | This page |
|---|---|---|
| Alignment | Centered because that's the default | Flush left on a 12-column grid |
| Type | Inter (already there) | Archivo, chosen for its lineage |
| Corners | 16px radius everywhere | Square. A rule is a one pixel line |
| Colour | Gradient `#667eea → #764ba2` | Ink, paper, one red |
| Copy | "Passionate designer crafting delightful experiences" | Facts: name, age, household, what I make, today's Hebrew date |
| Ideology | None: the look of order without the belief | Clarity, honesty, a reason for every measurement |

---

## 4. What the AI suggested, and how I responded

| # | What I asked / what happened | What was built | Commit |
|---|---|---|---|
| 1 | After thirteen rounds on the loud version, I asked for **the whole site again in a new repo, more modern, clean and quiet**, as the same homework. | This repository. Same content, same five criteria, no desktop, no marquees, no videos. White page, one red field, one typeface, a grid you can switch on. The cats stay, because they are the rupture; they just stop shouting. | first commit |
| 2 | I kept the live data. | The Hebrew date, this week's candle-lighting and havdalah times for Tel Aviv, and this repository's own git history are fetched when the page loads, from hebcal.com and api.github.com, with no keys. The Shabbat countdown is a single line of text, and the candles are a line drawing that lights itself at the right minute on Friday. | first commit |

✍️ **Add here:** which of the two versions you will submit, and why. If the answer is "both", say what each one is for.

---

## 5. Manual work and raw materials

- **Real photos** (`images/`): me (deadpan, laughing, asleep, 7am, side, with the Kinder egg, at a wedding, in a laundromat, with the sandwich), my cats Sofi, Moffi, Toffy and Tova, my baking (Saint-Honoré, poppy-seed dough, cherry pastry), and one AI picture of Sofi as a Swiss designer, made with Magnific from a real photo.
- **Metadata** was stripped from all photos.
- ✍️ **Sketches:** put paper sketches of the grid and the card in `docs/sketches/` and link them here.
- ✍️ **Handwriting:** the blue notes could be set in a scan of your own handwriting instead of italic Archivo. That is the most non-replicable upgrade available.
