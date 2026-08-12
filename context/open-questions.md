# Open questions

These are the questions whose answers change the shortlist. They are roughly in
order of how much they prune — the first three do most of the work.

## 1. Which machine drives it, and how many screens total?

This is the load-bearing question, because the current laptop's output path is
already at a hard limit (see [`existing-hardware.md`](existing-hardware.md)).

- Laptop (ThinkPad E15 Gen 3) via the USB-C dock — **max 2 external displays**, no
  Thunderbolt, so no daisy-chained third panel and no 4K@120 anything.
- Desktop — already running three externals.
- Both, switched — pushes hard toward a monitor with a **built-in KVM**.

**Answer (2026-08-12):** Laptop only, and **one external screen**, not two. This
screen never meets the desktop. A single monitor connects directly to the laptop's
HDMI or USB-C port, so the dock is not in the path at all — see the connection
notes in [`research/mounting-approaches.md`](../research/mounting-approaches.md).

## 2. Where is it bought and where is it used?

- Bought in Israel, used in Jerusalem — simplest; local warranty, no import.
- Bought on the US trip (in Connecticut until late August 2026) — cheaper sticker
  price, but a monitor is bulky and fragile in a suitcase, and the warranty is
  regional. Power is universal on most modern panels but the cable is not.
- Bought online and shipped — needs a landed-cost calculation including Israeli VAT
  and any import handling.

**Answer (2026-08-12):** Bought in Connecticut and **left in Connecticut**. It is
a screen deposited at a location visited roughly annually, not something carried
home. This settles several things at once: US retail pricing, US plug, no import,
no VAT — landed cost is sticker plus Connecticut sales tax at the 6.35% general
rate. It also means **portability has no value**, which is the finding that drives
the whole shortlist.

The obvious objection — that stashing monitors at locations around the world is
illogical — is noted and accepted by the buyer. A screen left at one recurring
destination is not a strategy, it is one purchase.

## 3. What is the screen actually for?

Ranked, not a list of everything. The candidates diverge sharply:

- **Text and terminals all day** → pixel density and matte coating win; refresh rate
  is nearly irrelevant. Points at 27″ 4K or 32″ 4K.
- **Lots of side-by-side windows** → physical area wins. Points at 32″+, or ultrawide.
- **Colour-accurate image work** → factory calibration and gamut coverage.
- **Video / motion / gaming** → refresh rate and response time.

Worth naming explicitly: Hebrew and RTL text rendering is part of daily use, and
small text at low pixel density is where cheap panels are worst.

**Answer (2026-08-12, partial):** Ordinary daily work away from the three-monitor
desktop. The stated requirement is not resolution but **position**: the external
panel mounted at eye level so that the laptop screen becomes the secondary
display. Ranked priorities beyond that are still open.

## 4. Budget, in the currency you will actually pay in

A ceiling prunes harder than any other single number. Rough tiers as of 2026 —
to be verified, not quoted:

- entry 27″ 1440p
- mid 27″ 4K / 32″ 1440p
- upper 32″ 4K, ultrawide, or anything with USB-C power delivery + KVM

**Answer:**

## 5. Single-cable USB-C (power delivery) — required or nice?

A monitor that carries video, USB hub and laptop charging over one cable replaces
the dock for a single-screen setup. It costs real money and it caps out at one
external display from this laptop. Worth knowing whether it is wanted before
shortlisting.

**Answer (2026-08-12):** The "caps out at one external display" objection is moot
now that the answer to Q1 is one screen. Single-cable USB-C is therefore a live
option rather than a compromise, and it is the **only** path to 4K on this laptop —
the E15 Gen 3's HDMI port is limited to 4K@30 Hz, while its USB-C carries
DisplayPort 1.2 and reaches 4K@60. Whether the extra cost is wanted is still open;
at 1440p and below, plain HDMI is sufficient and cheaper.

## 6. Physical constraints

- Desk depth (a 32″ panel needs roughly 70 cm of viewing distance to be comfortable)
- VESA arm already owned, or using the supplied stand?
- Height adjustment and pivot needed?
- Curved acceptable, or must be flat?

**Answer (2026-08-12, partial):** No VESA arm owned at the destination, so mounting
hardware is part of the purchase. **Eye-level height is the hard requirement** and
the reason a monitor was specified over any laptop-attached or pull-out screen —
those are explicitly ruled out.

The mount must be **freestanding on a weighted base**, not a C-clamp or grommet
arm: the furniture belongs to someone else and clamping or drilling it is not on
the table. Desk depth, curve tolerance and the room layout are still unknown.

**Still open and it changes the answer:** where the monitor is stored for the
eleven months between visits. If there is no space for a 27″ panel, that single
fact flips the recommendation from a desktop monitor to a native-VESA portable.

## 7. Replacing something, or adding?

If replacing, what is wrong with the current panel — that failure is usually the
real spec.

**Answer (2026-08-12):** Adding, and adding at a location that currently has
nothing. The failure being fixed is not a panel but a posture: working laptop-only
after years on a three-monitor desktop.
