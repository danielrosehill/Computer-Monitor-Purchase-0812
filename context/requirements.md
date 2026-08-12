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

## Explicitly not decided

Size, resolution, panel technology, budget. Two facts would settle the rest:

1. **Budget ceiling in USD.**
2. **Where the monitor is stored between visits.** This is not a detail — it is the
   only argument that favours a portable panel over a desktop one, and it flips the
   recommendation on its own. See
   [`research/mounting-approaches.md`](../research/mounting-approaches.md).

## Notes to carry into research

- Quote **landed cost** — panel + shipping + VAT + any import handling — never the
  headline price. This has reversed a decision in this repo family before.
- Israeli retail and US retail diverge sharply on monitors and the same model number
  can differ in panel revision between regions. Pin the exact SKU.
- Verify variant-level stock on the actual storefront; search results do not show it.
