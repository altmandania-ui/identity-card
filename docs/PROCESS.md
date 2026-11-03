# Process: Identity Card, Order and Rupture (the quiet version)

Dania Altman · Homework Assignment 1 · design MA

This is the second build of the same homework. The first build lives at https://altmandania-ui.github.io/hit1/ and its process file is https://github.com/altmandania-ui/hit1/blob/main/docs/PROCESS.md. That version is loud on purpose: a 1999 desktop, marquees, a countdown wall, seven videos. This version keeps the same argument and the same material and says it as quietly as possible: an inventory of one person on a white page.

> ✍️ marks the places that still need my own words, sketches or photos before submitting.

---

## 1. The concept

**The grid is the plan. The cats are what actually happens. The page is the space between them.**

This version tells it as a scroll story in twenty-five steps on one white screen. The identity card stays in the middle; what changes is what lands on it. One thing happens per scroll, and nothing else moves.

| Step | What happens | Layer |
|---|---|---|
| 0 | The passport photo, alone. "It took six tries." | — |
| 1 to 5 | The five rejected attempts, one per scroll: smiling, eyes closed, 7am, not facing the camera, holding a Kinder egg. Each one gets a red REJECTED stamp that slams onto the photo, and a red tally mark. | Rupture (my face, as the state refused it) |
| 6 | Attempt 6, accepted. A black stamp. The frame of the card appears. | Order (the face the state knows) |
| 7 | The order: twelve red columns draw themselves top to bottom, the name and the nine fields fade in one by one, the margin says "Grid integrity 100%". | Order |
| 8 to 11 | The day lands on the card as four rows of a timetable: 07:10 school run, 08:00 four bowls in order of seniority, 09:00 to 17:00 the 9 to 5 and then the MA, 22:30 the dough into the fridge. "Grid integrity 100%. On paper." | Order |
| 12 to 15 | The cats arrive one by one. Tova drops from above and lands on the card. Sofi walks in from the right. Moffi climbs up from below. Toffy, 102 pixels wide, flickers in like a bad JPEG. With each cat the fields tilt and slide a little further off the columns, and the margin counts down: 90, 78, 70, 61%. | Rupture |
| 16 | "Order can be restored. The cats cannot." The fields snap back to the grid. The cats stay exactly where they were. | The encounter |
| 17 to 19 | The Saint-Honoré. Hour one: the dough slides onto the card. Hour six: the finished cake drops onto it. Six minutes: it is gone, and seventy poppy seeds are left on everything, the card included. | Rupture, by weight |
| 20 to 22 | Friday. Two candles light, with the live countdown to candle lighting in Tel Aviv. Then שבת שלום fills the screen, the card and the grid dim to rest, the cats do not. Then Saturday night: the flames go out, the card comes back, the countdown starts again. | Rupture that keeps time |
| 23 to 24 | Exhibit A: the AI's default hero fades in over the dimmed card. A red line cuts through it, and a red "no." | Templatology |
| 25 | The template goes. The card comes back with the cats on it. "The grid is the plan. The cats are what actually happens." | Both |

After the story: the position text, Sofi at her drafting table, and the colophon. Scroll back up and it plays again.

**How the layers meet:** on one stage, in sequence, with a number. Every cat costs the grid a measured amount of integrity, and the margin says how much. The restoration in step 16 is the thesis: the order can always be put back, and it never erases what landed on it.

---

## 2. Order: every measurement chosen

| Decision | Value | Why |
|---|---|---|
| Grid | 12 columns, 24px gutter, drawn in red on step 7 | You watch it being built before anything lands on it. It stays under everything after that. |
| Card | 760px, centered, a 1px frame | One object in the middle of the stage, like a passport on a counter. The only centered thing on the page, by decision. |
| Typeface | Helvetica, four sizes: 11, 15, 36, 72 | The most ordinary grotesque there is. Nothing to load. |
| Colour | white, black, grey `#777`, red `#E3000F`, blue `#1636E8` | Red for the grid, the stamps and the "no.". Blue for my own hand in the position text. |
| Motion | One event per step, 0.2 to 0.9 seconds, spring easing for things that land | Motion only to show what changed. Reduced-motion users get the states without the transitions. |
| Photos | Natural ratio in the card; cut-outs for the cats that land | The cut-outs were made with Magnific's background removal from my own photos. Toffy stays a 102px JPEG because that is the only photo of him. |
| Live data | hebcal.com for the Hebrew date and Shabbat times, GitHub for this page's own history | Three fields on the card and the countdown in step 13 are real. No keys. |

## 3. Templatology vs. conscious modernism

| | Template (Exhibit A) | This page |
|---|---|---|
| Alignment | Centered because that's the default | One centered card, like a passport on a counter; everything else flush left |
| Type | Inter (already there) | Helvetica only, in four sizes |
| Corners | 16px radius everywhere | Square. A box is a one pixel line |
| Colour | Gradient `#667eea → #764ba2` | White, black, red for the grid, blue for me |
| Copy | "Passionate designer crafting delightful experiences" | Sixteen captions, one per step, and a table of facts including today's Hebrew date |
| Ideology | None: the look of order without the belief | Clarity, honesty, a reason for every measurement, and a story about what happens to it |

---

## 4. What the AI suggested, and how I responded

| # | What I asked / what happened | What was built | Commit |
|---|---|---|---|
| 1 | After thirteen rounds on the loud version, I asked for **the whole site again in a new repo, more modern, clean and quiet**, as the same homework. | First draft: white page, Archivo, the identity card as one big red colour field, cats with white frames, a "show the grid" button. | first commit |
| 2 | **"I don't like it. More quiet than that, and the grid more interesting."** | Second draft: no colour fields, smaller type, a modular grid of 96px modules drawn faintly all the time, and the card's fields stepping down the grid one module each like a timetable. Not committed: before I saw it I sent a reference. | — |
| 3 | I sent a Pinterest pin: a one-screen Carrd site, a cut-out hand on white with five small numbered objects around it, a serif question, a credit line. **"Maybe more like this."** | This page. Times and Helvetica only. My cut-out portrait on a 12 × 8 grid with six numbered things around it in thin boxes, "Who is this? [ Identity card ]" underneath, "Made in Holon ©" as the credit, and the rest of the homework as numbered entries with a lot of white space. The grid is hidden until asked for, and the index at the bottom gives every thing's coordinates. The cut-outs were made with Magnific from my own photos. | this commit |
| 4 | I kept the live data. | The Hebrew date, this week's candle-lighting and havdalah times for Tel Aviv, and this repository's own git history are fetched when the page loads, from hebcal.com and api.github.com, with no keys. The countdown is one Hebrew line, and the candles, on the stage and in entry 3, light themselves on Friday. | this commit |
| 5 | **"I don't think there is something interesting. Clean can be interesting as well. Put things in weird places but keep it clean."** | The centered column went. The page is now twelve columns across the whole screen with rows of 80px, and things sit where they sit: the cut-out portrait is cut again by the left edge of the screen, the name runs off the right edge in 168px Times, the cake hangs over the top corner, the cats are far apart, each entry starts from a different column and the position text's heading sits on the opposite side of the page from its text. Four things are pinned to the screen and travel with you: the 7am selfie in the top right corner, the candles with the live countdown in the bottom left, Tova in the bottom right, and a vertical Hebrew line along the right edge. Still white, still Times and Helvetica, still a grid you can switch on, and the index still gives every thing's coordinates. | this commit |
| 6 | **"Are you normal? This is the most boring thing I saw in my life."** The AI asked which kind of interesting I meant and offered four: interaction, a scroll story, a passport you flip, giant scale. I chose **the scroll story**. | This page. Sixteen steps on one sticky stage, one event each: five rejected passport photos with stamps, the grid drawing itself, four cats landing and pulling the card off the grid with the integrity counting down, order restored with the cats still there, the candles, the template crossed out, and the card back with everything on it. Still white, still one typeface, still one red. The interest is in time, not in decoration. | this commit |
| 7 | **"I liked it, I liked the motion. I want to add more story to the motion."** Offered four threads, I chose the timetable, the Saint-Honoré and the full Shabbat evening, in sequence. | Sixteen steps became twenty-five. After the grid is built, the day lands on the card as four rows of a timetable (school run, four bowls, the 9 to 5 and the MA, the dough into the fridge), so the order earns its 100% before the cats break it. After order is restored, the Saint-Honoré: the dough slides in, the finished cake drops onto the card, then it is gone in one scroll and seventy poppy seeds are left scattered over everything. Friday grew into three steps: the candles light with the live countdown, שבת שלום fills the screen and the card dims to rest while the cats stay awake, then Saturday night: the flames go out, the card comes back, and the countdown starts again. The card scales itself to fit short screens so every step stays on one screen. | this commit |

✍️ **Add here:** which of the two versions you will submit, and why. If the answer is "both", say what each one is for.

---

## 5. Manual work and raw materials

- **Real photos** (`images/`): me (deadpan, laughing, asleep, 7am, side, with the Kinder egg, at a wedding, in a laundromat, with the sandwich), my cats Sofi, Moffi, Toffy and Tova, my baking (Saint-Honoré, poppy-seed dough).
- **Cut-outs** (`images/cut-*.png`): my portrait, the Saint-Honoré, Tova, Sofi and the Kinder egg, cut out of the photos above with Magnific's background removal.
- **Metadata** was stripped from all photos.
- ✍️ **Sketches:** put paper sketches of the grid and the card in `docs/sketches/` and link them here.
- ✍️ **Handwriting:** the blue measurements could be set in a scan of your own handwriting instead of italic Times. That is the most non-replicable upgrade available.
