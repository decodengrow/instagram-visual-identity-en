# Example output (illustrative)

> **Note.** This is an illustrative excerpt for **Halden**, a fictional brand-strategy studio. It shows the shape and depth of the skill's output; it was not produced from real client references. A full run also includes the reference analysis, the comparison matrix and three creative directions — omitted here because they depend on the references you supply.

![Sample carousel: four slides](images/carousel-strip.png)

## 5. Recommended direction — "Marginalia"

**Core concept:** the feed as a well-edited notebook. Large serif statements carry the argument; a single red margin rule and handwritten-feeling italic notes act as the editor's voice.
**Why it fits:** Halden sells thinking, not decoration. The system makes restraint and editorial judgment visible.
**Trade-off:** low visual noise means weak posts look empty — copy quality has to carry the work.

## 7. Color and typography

| Token | HEX | Role |
|---|---|---|
| Paper | `#F3EFE6` | Default background |
| Ink | `#141414` | Headlines, body |
| Graphite | `#5C5A55` | Secondary text, labels |
| Rule | `#CFC8BA` | Dividers, table lines |
| Signal | `#D2421B` | Margin rule, one emphasis per slide, annotations |
| Deep | `#1F2A24` | Closing / manifesto slides only |

Forbidden: Signal as a background fill; Signal body text; more than one Signal emphasis per slide.

| Level | Face | Size on 1080 | Leading | Tracking | Case |
|---|---|---|---|---|---|
| Display | Instrument Serif | 180–240 px | 0.86–0.9 | −2.5% | Sentence |
| H2 | Instrument Serif | 84–132 px | 0.95–1.0 | 0 | Sentence |
| Body | Inter 400 | 32–34 px | 1.4–1.45 | 0 | Sentence |
| Annotation | Instrument Serif Italic, Signal | 34–36 px | 1.15 | 0 | Sentence |
| Label / folio | JetBrains Mono 400 | 22 px | 1 | +8% | UPPER |

## 8. Grid

Canvas 1080×1350 (4:5). Outer margin 96 px (8.9%). Header baseline at 64 px from top, footer rule at 1206 px. Margin rule: 4 px Signal at x = 72 px, full bleed, on paper slides only. Main column 96–700 px; annotation column 770–1020 px. Spacing scale: 8 / 16 / 24 / 32 / 64 / 96.

## 9. Signature elements

- **Margin rule** — the red vertical line. Present on every paper slide; absent on Deep slides so closings feel like a change of register.
- **Marginal note** — one italic Signal annotation per slide, max 12 words. Never decorative; it must add a judgment the body doesn't state.
- **Folio** — `NN / NN` top right in mono. Always.

## 13. Production spec — carousel "Your logo is not your brand" (Architecture C, 4 slides)

| # | Purpose | Elements (x, y, w as % of canvas) | Background |
|---|---|---|---|
| 01 | Cover — the claim | Display headline, 3 lines, last word in Signal italic (9%, 17%, 75%); dek in Graphite (9%, 78%, 52%); footer "Swipe →" | Paper |
| 02 | The usual advice | H2 quote (9%, 15%, 59%); body (9%, 41%, 56%); marginal note (71%, 41%, 23%) | Paper |
| 03 | A working model | H2 (9%, 13%, 70%); 5-row ruled list, row 05 marked "← smallest" (9%, 35%, 82%); footer states "Model, not measured data" | Paper |
| 04 | Discussion question | H2, last word in Signal-tint italic (9%, 24%, 81%); prompt (9%, 67%, 57%); "Save for later" | Deep |

Not yet produced: final copy review, alt text, export at 1080×1350.

## 14. Quality control (this carousel)

| Criterion | Score | Note |
|---|---|---|
| Visual hierarchy | 9 | |
| Typography | 9 | |
| Phone legibility | 8 | Mono labels at 22 px are the floor; don't go smaller |
| Visual variety | 7 | Slides 02–03 share a rhythm. **Fix:** give slide 02 a full-width pull quote instead of a heading |
| Originality | 8 | |
| Accessibility | 8 | Signal on Paper passes for large text only — keep it out of body copy |

## 15. Master prompt (excerpt)

```
# Halden — Instagram visual system, v1.0

## Fixed core
- Colors: Paper #F3EFE6 (bg), Ink #141414 (text), Graphite #5C5A55 (secondary),
  Rule #CFC8BA, Signal #D2421B (margin rule + one emphasis/slide), Deep #1F2A24 (closings only)
- Type: Instrument Serif display/H2, Inter body 32–34 px, JetBrains Mono labels 22 px UPPER +8%
- Grid: 1080×1350, 96 px margins, margin rule at x=72, folio top-right on every slide
...
## System evolution
Change the core only deliberately: state the problem, propose the change, note what it
affects, bump the version and log it.
```
