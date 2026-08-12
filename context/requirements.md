# Requirements

Opened 2026-08-12, revised the same day after the first round of intake and
research. Spec revision is a stage of the method, not a failure of it — this pass
overturned two constraints that had been recorded as hard.

## Hard, confirmed with the buyer

- **Exactly one external monitor.** Not two, not a stackable path to three.
- **Bought in the US, used in the US, stays in the US** — Connecticut, at a
  residence visited roughly annually. It is never carried back to Israel.
- **Eye-level mounting is the point of the purchase.** A panel that cannot be
  raised to eye level fails the requirement no matter how good it is. This is why
  laptop-attached and pull-out auxiliary screens are excluded outright.
- **Freestanding weighted-base mount only.** The furniture is not the buyer's;
  clamping and drilling are out.
- **No DisplayLink.** Proprietary Synaptics drivers are disqualified on
  Linux/Wayland grounds, regardless of price.

## Overturned by research — read before using older notes

| Was | Now | Why |
|---|---|---|
| "DisplayPort input required" | **HDMI is acceptable at ≤1440p** | That constraint came from the dock's DP-based MST outputs. One monitor connects direct to the laptop, so the dock leaves the path entirely |
| "At most two external panels" | Moot | One screen |
| "Bought in Israel rather than carried from the US" | **Bought in the US** | The monitor never travels; it is deposited at the destination |

**New hardware constraint, replacing the old one:** on the ThinkPad E15 Gen 3
(AMD), HDMI tops out at **4K@30 Hz**. USB-C carries DisplayPort 1.2 Alt Mode and
reaches 4K@60. So *4K is a USB-C-only purchase on this machine*; at 1440p and
below either port is fine. Source: Lenovo PSREF, checked 2026-08-12.

## Assumed until confirmed

| Assumption | Basis | Confidence |
|---|---|---|
| Primary use is text, terminals and long-form reading | Daily work is CLI-heavy and document-heavy | Medium |
| Matte coating preferred over glossy | Text work under variable daylight | Low |
| Screen area matters more than pixel density here | This is a second screen replacing nothing; the laptop panel supplies the sharp text | Medium — reversible |

## Added 2026-08-12 from the traveller profile

- **Usage intensity: ~15 working days a year**, one three-week visit, one
  destination. See [`travel-profile.md`](travel-profile.md).
- **Portability is worth $0** and must not be paid for, in either money or screen
  area.
- **Abandonment is the exit strategy.** The purchase should be cheap enough that
  stranding it in Connecticut is a shrug, which argues against premium panels.
- **Refurbished and used are first-class channels here**, not compromises — at 15
  days a year the marginal value of a warranty is low.
- **Target 24″.** 15.6″ is not a real desktop category (it resolves to a portable
  monitor at portable prices); 19″ costs more than 24″ for a worse panel; 27″
  triples the cost and complicates storage and an unknown guest desk.

## Closed 2026-08-12

- **No spare monitor or idle TV at the property.** The zero-cost option is out.
- **Storage space exists.** This was the last constraint that could have justified
  a small panel; it does not apply, so the small-panel route is closed.
- **Size: 24″, confirmed.** The buyer's habitual size is 21″, but that is across a
  three-monitor desktop. A single panel doing that job alongside the laptop screen
  warrants the extra area.
- **Mounting hardware: none required.** Business-line monitors (Dell P/U, Lenovo
  ThinkVision T/P, HP E/Z) ship a four-way stand — height in mm, tilt, swivel,
  pivot — as standard. This satisfies eye level, no-drill, no-clamp *and*
  disassembly-for-storage in one purchase.
- **Screening rule for listings:** height adjustment quoted in millimetres, and the
  word "pivot". Listings that say only "tilt adjustable" are tilt-only. Price is
  not a signal — a $200 gaming SKU is often tilt-only, a $67 refurb P-series is not.

- **Bought new, firsthand.** Buyer preference, stated 2026-08-12: start from a
  known-good unit rather than trust an account of a used one. This overrides the
  pure value ranking, which favoured refurbished. The gap is ~$2.30 per day of use.
- **Resolution: 1920×1200 16:10.** Chosen over 1080p for 11% more vertical space,
  the axis that matters for terminals and documents, and the only compensation
  available for going from three screens to one.

## Settled

**Dell P2425** — 24″, 1920×1200, 100 Hz, IPS, 150 mm height / tilt / swivel / pivot
stand, $239.99 new with a 3-year Dell warranty and advanced exchange.

Two purchase-time checks that are easy to get wrong:

1. **`P2425H` is 16:9 1080p; `P2425` is 16:10 1920×1200; `P2425E` is a pricier
   USB-C/Ethernet SKU.** Read the resolution field, not the model number.
2. **A video cable must be bought separately.** The box has DisplayPort-to-
   DisplayPort and this laptop has no DisplayPort socket. HDMI (~$8, 60 Hz) or
   USB-C-to-DisplayPort (~$15–20, full 100 Hz).

Budget was never given as a number, and the analysis in
[`research/value-analysis.md`](../research/value-analysis.md) argues it did not need
to be: the whole viable range was $30–290, or $1–3 per day of use.

The full question-and-answer trail behind all of this, including the decisions that
were later reversed, is in [`decisions.md`](decisions.md).

## Notes to carry into research

- Quote **landed cost** — panel + shipping + VAT + any import handling — never the
  headline price. This has reversed a decision in this repo family before.
- Israeli retail and US retail diverge sharply on monitors and the same model number
  can differ in panel revision between regions. Pin the exact SKU.
- Verify variant-level stock on the actual storefront; search results do not show it.
