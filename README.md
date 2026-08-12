# Computer monitor purchase — the decision

A short public record of what was bought and why. The working notes, requirements
and personal context live in a separate private repo; this one carries the outcome
and the generally useful findings that came out of the research.

Researched and decided 2026-08-12. US retail, pre-tax.

## The brief

One external monitor to pair with a laptop, mounted at **eye level** so the laptop
panel becomes the secondary screen. It stays permanently at one location, so
portability is worth nothing. Mounting had to be **freestanding** — no drilling
and no C-clamps — and the whole thing had to disassemble for storage.

## The decision

**A 23.8″ business-class monitor, ~$99–240 depending on how much of a warranty is
wanted.**

| Option | Panel | Stand | Price |
|---|---|---|---|
| **HP E24 G5** | 23.8″ 1080p IPS, 75 Hz, 99% sRGB | Full 4-way | **$99** — end-of-life clearance |
| Dell P2425 | 24″ **1920×1200 16:10**, 100 Hz | 150 mm, 4-way | $239.99 — 3 yr advanced exchange |
| Acer SH242Y Ebmihx | 23.8″ 1080p IPS, 100 Hz | 80 mm + swivel | ~$80–100 |

The deciding factor in every case was the **stand**, not the panel. Eye-level
height was the point of the purchase, and a monitor whose own stand provides it
needs no aftermarket hardware at all.

## Findings worth reusing

These are the parts that generalise beyond this purchase.

### Business lines ship the stand you want; price does not predict it

A $200 gaming monitor is frequently tilt-only while a $67 refurbished business
panel has height, tilt, swivel and pivot. Look for **Dell P/U**, **Lenovo
ThinkVision T/P**, **HP E/Z**. Avoid **Dell E and S** series.

How to read a listing:

- Height adjustment quoted **as a number in millimetres**. "Tilt adjustable" on
  its own means tilt-only.
- The word **"pivot"** appears — pivot is only fitted to stands that also have
  height, because the panel must rise before it can rotate.

Typical business stands run **130–155 mm** of height travel. An aftermarket
freestanding stand costs ~$23, so a business panel that includes one is often the
cheaper total.

### Small monitors are not cheap monitors

There is no affordable 15.6″ desktop monitor — the size was discontinued around
2018, and everything now sold at 14–16″ is a **portable monitor** at portable
pricing. The floor for a conventional desktop monitor is **19″**, and 19″ panels
are mostly 1600×900 at $85–120, i.e. more than a 23.8″ costs for a worse screen.

The cause is structural: chassis, stand, PSU and controller cost about the same for
a small panel as for a large one, so nobody builds them. **"20–24 inch" resolves
to "buy 23.8″"**, which is the volume size and therefore the cheap one.

### Portable monitors cost 2–4× more per square inch

If a screen is not going to be carried, a portable panel is the wrong purchase. A
16″ portable runs about **$1.22 per square inch** of display against **$0.31** for
a 24″ desktop panel — and a tabletop VESA stand costs roughly the same ($23–29)
either way, so the mount is never the variable. The panel is.

### The folding-stand trap

Freestanding stands that genuinely fold flat for storage exist — the WEARSON
WS-03T is one — but they are **low-profile risers**, with something like 7–11
inches of pole. They cannot reach eye level. Storability and height work against
each other across that entire product class, which is another argument for a
business monitor: its stand is both tall and fully disassembles, since these ship
as three unassembled pieces with a quick-release panel.

### Check what cable is in the box

The Dell P2425 ships a **DisplayPort-to-DisplayPort** cable. Many laptops — the
ThinkPad E15 Gen 3 among them — have **no DisplayPort socket**, making the included
cable useless and adding a hidden $8–20 to the purchase. The HP E24 G5 ships HDMI,
VGA, DisplayPort and USB-B cables and plugs in on arrival.

### Model-naming traps

Read the **resolution field**, not the model number:

- `P2425H` = 16:9 1920×1080 · `P2425` = 16:10 1920×1200 · `P2425E` = adds USB-C
  90 W PD and Ethernet, pricier
- `SH242Y Ebmihx` has VGA · `SH242Y Ebmihux` swaps VGA for USB-C
- `E24 G5` is 1080p 16:9 · `E24i` is 1920×1200 · `E24u` adds USB-C · `E24t` is
  touch. The standard SKU is **6N6E9AA**

### One laptop-specific note

The ThinkPad E15 Gen 3 (AMD) caps **HDMI at 4K@30 Hz** (HDMI 1.4b class) while its
USB-C carries DisplayPort 1.2 Alt Mode and reaches 4K@60. Irrelevant at 1080p or
1200p, but it means any 4K purchase on that machine is USB-C-only. Source: Lenovo
PSREF, checked 2026-08-12.
