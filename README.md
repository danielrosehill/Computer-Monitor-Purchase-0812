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

### Buy: Dell P2425 — 24″, 1920×1200 (16:10), 100 Hz — $239.99, new

Bought **new and firsthand** by preference: start from a known-good unit rather than
trust an account of a used one. At 15 days of use a year the premium over a $67
refurbished equivalent is about $2.30 a day, and it buys a **3-year Dell warranty
with advanced exchange** on a device that sits unattended in another country for
eleven months at a time.

**Why 16:10:** 1920×1200 is 11% more vertical space than 1080p, and vertical is the
axis that matters for terminals and documents. It is also the only compensation
available for dropping from three screens to one. The premium over the 16:9 P2425H
is $55.

**No mounting hardware needed.** Its stand does **150 mm of height**, −5°/+21° tilt,
±45° swivel and ±90° pivot — so nothing gets drilled and nothing gets clamped, which
were both impossible in a guest residence. It ships as three unassembled pieces and
the panel quick-releases, so it goes back into a cabinet as a flat panel plus a flat
base.

### Two things to get right at checkout

1. **Read the resolution field, not the model number.** `P2425H` is 16:9 1080p;
   `P2425` is 16:10 1920×1200; `P2425E` is a pricier USB-C/Ethernet SKU.
2. **Buy a cable.** The box contains a DisplayPort-to-DisplayPort cable and the
   ThinkPad E15 Gen 3 **has no DisplayPort socket**. Either an HDMI cable (~$8,
   60 Hz) or a USB-C-to-DisplayPort cable (~$15–20, full 100 Hz).

Cheaper new alternative: **HP E24 G5 at $99** — same class of four-way stand, 23.8″
1080p, but end-of-life stock with thin warranty support.

**Not** a 15.6″ panel: that size no longer exists as a desktop product, so "a cheap
15.6″ monitor" resolves to buying a portable monitor at portable prices for a
screen that never moves. Full working in
[`research/value-analysis.md`](research/value-analysis.md).

## Repo map

| Path | What |
|---|---|
| [`context/decisions.md`](context/decisions.md) | **Start here.** Every question that came up, its answer, and what it settled — including the ones that were reversed |
| [`research/value-analysis.md`](research/value-analysis.md) | Cost per day of use, new vs refurbished, the shortlist and the pick |
| [`research/mounting-approaches.md`](research/mounting-approaches.md) | Mounting permutations, how to identify a good built-in stand, and the storage answer |
| [`context/travel-profile.md`](context/travel-profile.md) | Usage pattern and the prior-experience anecdotes that rule out carrying a monitor |
| [`context/requirements.md`](context/requirements.md) | The spec as it finally stands, with the constraints that were overturned marked |
| [`context/open-questions.md`](context/open-questions.md) | The original intake questions and their answers |
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
