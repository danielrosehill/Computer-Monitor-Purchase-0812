# Computer Monitor Purchase — August 2026

Buying a **computer monitor** (a display panel, not a monitoring tool — the word is
overloaded and this repo means the screen).

**Public.** Findings here are meant to be readable by anyone comparing panels; no
addresses, order numbers or account details go in this repo.

## Status: first research round done, spec revised

The shape of the purchase is settled: **one external monitor, bought in
Connecticut and left there**, at a residence visited roughly annually, mounted at
eye level so the laptop panel becomes the secondary screen.

That last fact — it never moves — is what the first research round turned on.
Portability is a feature this screen will never use, and portable panels cost
2–4× more per square inch of display. Full working: **[`research/mounting-approaches.md`](research/mounting-approaches.md)**.

The usage pattern then sharpened it further: **~15 working days a year**, one
visit, one destination. At that intensity the whole decision spans $30–290, or
$1–3 per day of use — too small a spread to be worth optimising for price.

## Decision

**A refurbished 24″ Dell P-series (P2422H / P2419H), $67–90.**

Its business-class stand gives 130 mm of height plus tilt, swivel and pivot, which
means **no separate mount, no drilling, no clamping** — none of which were possible
in a guest residence anyway — and it breaks down into a flat panel and a flat base
for the cabinet between visits. Cheap enough that stranding it in Connecticut is a
shrug.

Worth checking for **16:10** while shopping: the Dell P2423 / P2425 are 24″
1920×1200 with the same stand, 11% more vertical pixels. The naming is a trap —
`P2425H` is 16:9, `P2425` is 16:10. Read the resolution, not the model number.

**Not** a 15.6″ panel: that size no longer exists as a desktop product, so "a cheap
15.6″ monitor" resolves to buying a portable monitor at portable prices for a
screen that never moves. Full working in
[`research/value-analysis.md`](research/value-analysis.md).

## Repo map

| Path | What |
|---|---|
| [`research/value-analysis.md`](research/value-analysis.md) | Cost per day of use, channels, and the recommendation — **start here** |
| [`context/travel-profile.md`](context/travel-profile.md) | Usage pattern and the prior-experience anecdotes that rule out carrying a monitor |
| [`research/mounting-approaches.md`](research/mounting-approaches.md) | The four mounting permutations with prices; recommendation superseded |
| [`context/requirements.md`](context/requirements.md) | The spec. Revised 2026-08-12; two previously "hard" constraints overturned |
| [`context/open-questions.md`](context/open-questions.md) | Intake questions, six of seven now answered |
| [`context/existing-hardware.md`](context/existing-hardware.md) | What already exists and what it can drive |

## Method

Staged spec → research → **revise the spec** → choose channel → execute, per
[`Agentic-Purchase-Pipeline`](https://github.com/danielrosehill/Agentic-Purchase-Pipeline).
The stage that earns its keep is the third one: research feeding back and changing
the spec, rather than the spec being frozen before any evidence arrives.

Two rules carried over from previous runs in this family:

1. **Quote landed cost, never list price.** Shipping, VAT and import handling have
   reversed a monitor decision before they have ever been a rounding error.
2. **Confirm the specific variant is buyable.** Monitor model numbers differ by one
   suffix between regions and panel revisions; a search result is not stock.
