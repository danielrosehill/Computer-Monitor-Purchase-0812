# Computer monitor purchase

One external monitor to pair with a laptop, bought in the US and left there
permanently, mounted at **eye level** so the laptop panel becomes the secondary
screen. Mounting had to be **freestanding** — no drilling, no C-clamps — and the
whole thing had to disassemble for storage between visits.

Researched and decided 2026-08-12. US retail, pre-tax.

> A companion **private** repo holds the cheapest-alternatives research, which was
> too budget-sensitive to publish. Everything else is here.

## Recommendations

| Size | Monitor | Panel | Stand | Price |
|---|---|---|---|---|
| **23.8″** | **HP E24 G5** | IPS 1080p 75 Hz, 99% sRGB | Full 4-way | **$99** — EOL clearance |
| **21.5″** | **Dell P2225H** | IPS 1080p **100 Hz**, 1500:1, 99% sRGB | **150 mm** 4-way | **~$169.99** |
| 21.5″ budget | Dell P2222H, refurbished | IPS 1080p 60 Hz | 150 mm 4-way | $95–110 |
| 24″ premium | Dell P2425 | **1920×1200 16:10**, 100 Hz | 150 mm 4-way | $239.99, 3 yr advanced exchange |

Full size-by-size costing in [`research/size-options.md`](research/size-options.md).

**The deciding factor was always the stand, not the panel.** Eye-level height was
the point of the purchase, and a monitor whose own stand provides it needs no
aftermarket hardware — which mattered because drilling and clamping were both
unavailable.

**Note on 21.5″ versus 23.8″:** the 21.5″ preference is long-standing but comes
from a three-monitor desktop, where one panel is not carrying the whole workload.
It also costs about **$70 more** than the 23.8″ pick for 30% less screen — or
nothing at all if bought refurbished.

## Findings worth reusing

### Business lines ship the stand you want; price does not predict it

A $200 gaming monitor is frequently tilt-only while a $95 refurbished business
panel has height, tilt, swivel and pivot. Look for **Dell P/U**, **Lenovo
ThinkVision T/P**, **HP E/Z**. Avoid **Dell E and S** series.

Reading a listing:

- Height adjustment quoted **as a number in millimetres**. "Tilt adjustable" alone
  means tilt-only.
- The word **"pivot"** appears — pivot is only fitted to stands that also have
  height, since the panel must rise before it can rotate.

Typical business stands give **130–155 mm** of travel. An aftermarket freestanding
stand costs ~$23, so a business panel including one is often the cheaper total.

### Smaller monitors are not cheaper monitors

There is no affordable 15.6″ desktop monitor — the size was discontinued around
2018, and everything at 14–16″ is now a **portable monitor** at portable pricing.
The floor for a conventional desktop monitor is **19″**, mostly 1600×900 at
$85–120, i.e. more than a 23.8″ costs for a worse screen. Chassis, stand and
controller cost the same regardless of panel size, so nobody builds small ones.

### Portable monitors cost 2–4× more per square inch

A 16″ portable runs about **$1.22 per square inch** of display against **$0.31**
for a 24″ desktop panel — and a tabletop VESA stand costs roughly the same ($23–29)
either way, so the mount is never the variable. The panel is.

### The folding-stand trap

Freestanding stands that genuinely fold flat exist — the WEARSON WS-03T is one —
but they are **low-profile risers** with 7–11 inches of pole and cannot reach eye
level. Storability and height work against each other across that entire class,
which is a further argument for a business monitor: its stand is both tall and
fully disassembles, since these ship as three unassembled pieces with a
quick-release panel.

### LCDs break from flex, not impact

Relevant to anyone considering moving a monitor: panels crack from **flex and point
pressure**, not blunt knocks, which is why bubble wrap and clothing fail no matter
how thick. What works is rigidity across the panel face. Cases, weights and the
lightest option that actually works are in
[`research/transporting-a-monitor.md`](research/transporting-a-monitor.md).

### Check what cable is in the box

The Dell P2425 ships a **DisplayPort-to-DisplayPort** cable, and many laptops — the
ThinkPad E15 Gen 3 among them — have **no DisplayPort socket**, adding a hidden
$8–20. The HP E24 G5 ships HDMI, VGA, DisplayPort and USB-B cables.

### One laptop-specific note

The ThinkPad E15 Gen 3 (AMD) caps **HDMI at 4K@30 Hz** while its USB-C carries
DisplayPort 1.2 Alt Mode and reaches 4K@60. Irrelevant at 1080p, but it makes any
4K purchase on that machine USB-C-only. Source: Lenovo PSREF, checked 2026-08-12.

## Repo map

| Path | What |
|---|---|
| [`research/size-options.md`](research/size-options.md) | 21″ vs 24″, priced side by side — **start here** |
| [`context/decisions.md`](context/decisions.md) | Every question, its answer, and what it settled, including the reversals |
| [`context/travel-profile.md`](context/travel-profile.md) | Usage pattern and the prior-experience anecdotes that ruled out carrying a monitor |
| [`research/mounting-approaches.md`](research/mounting-approaches.md) | Mounting permutations, identifying a good built-in stand, storage |
| [`research/transporting-a-monitor.md`](research/transporting-a-monitor.md) | Whether a monitor survives checked luggage, and the lightest case that works |
| [`context/requirements.md`](context/requirements.md) | The spec, with overturned constraints marked |
| [`context/open-questions.md`](context/open-questions.md) | Original intake questions and answers |
| [`context/existing-hardware.md`](context/existing-hardware.md) | The laptop and what it can drive |
