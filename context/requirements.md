# Requirements

Opened 2026-08-12. **Not yet captured from the buyer** — everything below is either
inherited from known hardware or an assumption flagged as such. Expect this file to
be rewritten once [`open-questions.md`](open-questions.md) is answered, and again
after research (spec revision is a stage of the method, not a failure of it).

## Hard, inherited from hardware

- **DisplayPort input required.** The dock's video outputs are DisplayPort-based.
  HDMI-only panels are a compatibility risk on this path.
- **No DisplayLink.** Anything requiring proprietary Synaptics drivers is
  disqualified on Linux/Wayland grounds, regardless of price.
- **At most two external panels** from the laptop. A purchase that only makes sense
  as part of a three-external-screen laptop setup is out of scope until the laptop
  itself changes.

## Assumed until confirmed

These are placeholders. Each one is a guess that research is allowed to overturn.

| Assumption | Basis | Confidence |
|---|---|---|
| Primary use is text, terminals and long-form reading | Daily work is CLI-heavy and document-heavy | Medium |
| Pixel density matters more than refresh rate | Follows from the above | Medium |
| Matte coating preferred over glossy | Text work under variable daylight | Low |
| Bought in Israel rather than carried from the US | A monitor is poor suitcase cargo | Low — genuinely open |

## Explicitly not decided

Size, resolution, aspect ratio, panel technology, refresh rate, budget, purchase
channel. All of these wait on the intake answers.

## Notes to carry into research

- Quote **landed cost** — panel + shipping + VAT + any import handling — never the
  headline price. This has reversed a decision in this repo family before.
- Israeli retail and US retail diverge sharply on monitors and the same model number
  can differ in panel revision between regions. Pin the exact SKU.
- Verify variant-level stock on the actual storefront; search results do not show it.
