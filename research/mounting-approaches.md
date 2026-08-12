# Mounting approaches for a single external monitor that never moves

Researched 2026-08-12. US market, prices from US retail (Amazon buy box fetched
via a New York egress, plus vendor storefronts). All prices are pre-tax; add
Connecticut sales tax at the 6.35% general rate for landed cost. No shipping
across borders, no VAT, no import handling — this is the rare case in this repo
family where landed cost is nearly the sticker price.

## The use case that decides everything

One external screen, bought in Connecticut, **left in Connecticut**, used on
roughly annual visits to a residence that is not the buyer's own. Driven by the
ThinkPad E15 Gen 3. Mounted at eye level, because the whole point is that the
laptop panel becomes the *secondary* screen.

Two consequences that prune the field harder than any spec:

1. **The monitor never travels.** Portability is therefore a feature that will be
   used exactly zero times after the walk from the shop.
2. **It is stored in someone else's house for ~11 months a year.** Physical
   footprint when not in use is a real cost, and it is the only argument that
   survives in favour of a portable panel.

## The four permutations

| # | Approach | Panel | Mount | Total (pre-tax) |
|---|---|---|---|---|
| A | Portable monitor with **native VESA** + tabletop VESA stand | $140–280 | $23–29 | **$163–309** |
| B | Portable monitor **without** VESA + clamp adapter + stand | $140–190 | $48–54 | **$188–244** |
| C | Desktop monitor, use its **own** stand | $76–270 | $0 | **$76–270** |
| D | Desktop monitor + freestanding VESA stand | $76–200 | $23 | **$99–223** |

### The mount is not the variable

The single most useful finding: a tabletop VESA stand costs roughly the same
(~$23–29) whether it is holding a 15.6″ portable or a 27″ desktop panel. The
mounting problem is solved for under $30 in every permutation. So the mount is
not what distinguishes these options — **the panel is**, and portable panels cost
far more per unit of screen.

Rough cost per square inch of usable display area:

| Panel | Area | Typical price | $/in² |
|---|---|---|---|
| 16″ 16:10 portable (2560×1600) | ~115 in² | $140 | $1.22 |
| 15.6″ 16:9 portable (1920×1080) | ~104 in² | $140 | $1.35 |
| 24″ 16:9 desktop (1920×1080) | ~247 in² | $76 | $0.31 |
| 27″ 16:9 desktop (2560×1440) | ~311 in² | $200 | $0.64 |

A portable panel costs **2–4× more per square inch** and delivers roughly
one-third to one-half the area. That premium buys thinness, low weight and a
battery-free USB-C single-cable hookup. Only the last of those has any value in a
screen that sits on the same desk forever.

## Approach A — portable with native VESA

Native 75×75 mounting holes in a portable monitor are uncommon but not rare.
Candidates found:

- **UPERFECT BE156BU**, 15.6″ 1080p, matte IPS, built-in VESA 75×75 @ M4, USB-C
  (100W PD passthrough) + HDMI, ~900 g. **$139.99** on sale at
  [uperfect.com](https://uperfect.com/products/uperfect-15-6-vesa-portable-monitor),
  list $249.99. The Amazon listing for the VESA variant (ASIN `B0HB4PN6QC`) read
  **Currently unavailable** when checked on 2026-08-12 — a live example of the
  repo's own rule that a search result is not stock.
- **UPERFECT BE156EU**, 15.6″ true 4K, VESA 75×75 landscape or portrait,
  **$279.99** (list $359.99).
- **Gechic M1 series** (M161H / M152H / M141E) — no holes in the chassis, but a
  first-party [quick-release VESA 75 plate](https://store.gechic.com/quick-release-wall-mount-plate-vesa-75-for-m1-monitor/)
  that is a cleaner solution than a third-party clamp.
- **VisionOwl 16″ 2.5K** — flagged in a July 2026 roundup as carrying 75×75 holes;
  85% sRGB, no battery. Not price-verified here.

### Stands that take them

- [UPERFECT portable VESA stand](https://www.amazon.com/UPERFECT-Portable-Monitor-Freestanding-Rotation/dp/B0B24NKF2T),
  7″–18.5″, M3/M4 @ 75 mm, swivel/tilt/360° rotation — **$28.99**
- [WEARSON foldable 75 mm stand](https://www.amazon.com/WEARSON-75mm-Mount-Monitor-Stand/dp/B0CT324B6V) — lay-flat, small
- [JUNEBOX aluminium base](https://www.amazon.com/JUNEBOX-Portable-Anti-Loss-Aluminum-Fits100x100mm/dp/B0DZ6FTG13),
  7″–18″, M4, explicitly **not** 100×100
- [Waveshare mini monitor stand](https://www.waveshare.com/mini-monitor-stand.htm) — 50/75/100 mm

**The trap in this category:** the purpose-built "portable monitor stands" are
*short*. They are designed to lift a small panel a few inches off a desk, not to
put it at eye level. If eye level is the requirement — and it is — skip them and
use a full-size freestanding stand instead. The
[MOUNTUP B0875SL7VL](https://www.amazon.com/MOUNTUP-Single-Monitor-Stands-Adjustable/dp/B0875SL7VL)
takes 13″–32″, supports 75×75, and has **17.49″ of height travel** for **$22.99** —
cheaper than the little portable stands and roughly triple the lift.

**Thread size caveat, verified across several listings:** portable monitors
commonly use **M3** screws at 75 mm spacing; full-size stands ship **M4**. The
hole spacing matches and the screws do not. An M3 screw set costs a few dollars —
buy one alongside, or the stand arrives unusable.

## Approach B — portable without VESA, plus an adapter

Most portable monitors (including the well-reviewed ones) have a kickstand or a
magnetic folio and a completely smooth back. Adapters exist:

- [VIVO MOUNT-UVM02](https://www.amazon.com/VIVO-Universal-Portable-Adjustable-MOUNT-UVM02/dp/B08LL73T31),
  purpose-built for tablets, 2-in-1s and 15.6″ portables, output up to VESA
  100×100 — **$24.99**
- [Mount-It! MI-780](https://www.amazon.com/Mount-Mounting-Non-VESA-Monitors-Compatible/dp/B01MFDQR5D)
  and [HUANUO HNMUA4](https://www.amazon.com/Universal-Adapter-Non-VESA-Monitor-Screens/dp/B088CWY5Q3) —
  four-arm clamp kits, but rated from 13″–17″ **minimum** and for panel
  thicknesses of ~26–65 mm. A 6 mm portable panel is far outside that range and
  the clamps will not tension properly.
- Adhesive 100×100 plates exist as a last resort (24-hour cure, rated ~22 lb).

**Verdict on B: avoid.** It adds ~$25 and a mechanical weak point to save nothing,
since native-VESA portables exist at the same price. The only clamp worth
considering on a slim panel is the VIVO, and even that is a compromise compared
with holes in the chassis.

## Approaches C and D — a normal monitor

A desktop monitor already *is* the thing being reconstructed at higher cost in A
and B: it has VESA holes as standard, and mid-range models include a
height/tilt/swivel/pivot stand in the box, making the mount free.

| Model | Spec | Stand | Price |
|---|---|---|---|
| Dell SE2426H | 24″ 1080p 144 Hz IPS, 100×100 VESA, HDMI only | tilt only | ~$76 |
| Dell SE2425HM | 23.8″ 1080p 100 Hz IPS | tilt only | $99 (Walmart) |
| ASUS ROG Strix XG27ACG | 27″ 1440p 180 Hz Fast IPS | full ergo | $199.99 |
| Samsung Odyssey G5 G50F | 27″ 1440p 180 Hz | full ergo | $269 |
| Dell S2725QC | 27″ 4K, 65W USB-C single cable | full ergo | ~$285–300 |
| Dell Outlet P-series refurb | 22–23″ 1080p IPS | full ergo | $25–60 |

For a tilt-only budget panel, add the MOUNTUP freestanding stand at $22.99 to get
height — approach D, and still under $100 all in for a 24″.

**Freestanding, not clamped.** In someone else's house, a weighted-base stand that
sits on the desk is the correct category; a C-clamp or grommet arm needs
permission to grip (or drill) furniture that is not yours. Freestanding options
verified: MOUNTUP ($22.99, 13–32″, 17.6 lb), Mount-It! (~$83, 21.5–32″), VIVO
STAND-V011H (~$44, 13–27″), Monoprice (up to 27″, 13.2 lb).

## Recommendation

**Superseded — see [`value-analysis.md`](value-analysis.md).** The hardware
comparison above stands, but once the usage pattern was captured (~15 working days
a year at one destination) the recommendation sharpened: buy a **refurbished 24″
business-class monitor** whose own ergonomic stand makes the mount free, at roughly
$70–90. The new-purchase route in this document (Dell SE2426H + MOUNTUP, $99)
remains the answer if new and hassle-free is preferred.

The reasoning here is unchanged: the portability premium on a portable monitor buys
a property this screen will never exercise, and it is paid in screen area — the one
thing the multi-monitor workflow actually wants.

**The one condition that reverses it:** storage footprint. If a 24″ panel has
nowhere to live for eleven months in a house that is not yours, take approach A — a
native-VESA portable (UPERFECT BE156BU, $139.99) plus the MOUNTUP stand ($22.99)
plus an M3 screw set, about **$170**.

Approach B is dominated in every scenario. Do not clamp an adapter onto a
kickstand panel.

## Connection notes for this specific laptop

From Lenovo PSREF for the ThinkPad E15 Gen 3 (AMD), confirmed 2026-08-12:

- **HDMI port is capped at 4K@30 Hz** — HDMI 1.4b-class bandwidth. Fine for 1080p
  and 1440p at 60 Hz and above; unusable for a 4K panel.
- **USB-C is USB 3.2 Gen 1 with DisplayPort 1.2 Alt Mode**, good for 4K@60. So a
  4K purchase is a USB-C-only purchase on this machine.
- A single external monitor does **not** need the dock. Either port drives it
  directly, which means nothing extra has to be carried to Connecticut.
- The dock-derived "DisplayPort input required" constraint in
  [`requirements.md`](../context/requirements.md) applies to the two-display MST
  path. For one screen connected directly, an HDMI-only panel is acceptable at
  1440p or below — which is what makes the ~$76 HDMI-only Dell viable.

## Sources

- [MOUNTUP freestanding stand](https://www.amazon.com/MOUNTUP-Single-Monitor-Stands-Adjustable/dp/B0875SL7VL) — $22.99, buy box 2026-08-12
- [UPERFECT portable VESA stand](https://www.amazon.com/UPERFECT-Portable-Monitor-Freestanding-Rotation/dp/B0B24NKF2T) — $28.99, buy box 2026-08-12
- [VIVO MOUNT-UVM02](https://www.amazon.com/VIVO-Universal-Portable-Adjustable-MOUNT-UVM02/dp/B08LL73T31) — $24.99, buy box 2026-08-12
- [UPERFECT 15.6″ VESA business monitor](https://uperfect.com/products/uperfect-15-6-vesa-portable-monitor) — $139.99 sale
- [UPERFECT VESA monitor on Amazon](https://www.amazon.com/15-6-Inch-Portable-Monitor-UPERFECT/dp/B0HB4PN6QC) — currently unavailable 2026-08-12
- [ARZOPA Z1RC](https://www.amazon.com/ARZOPA-Portable-Monitor-2560x1600-Kickstand/dp/B0CH9XR3G4) — 16″ 2.5K, kickstand, no VESA
- [Gechic VESA 75 quick-release plate](https://store.gechic.com/quick-release-wall-mount-plate-vesa-75-for-m1-monitor/)
- [Waveshare mini monitor stand](https://www.waveshare.com/mini-monitor-stand.htm)
- [Display Ninja — best 24″ monitors](https://www.displayninja.com/best-24-inch-monitors/)
- [Newegg Insider — 27″ gaming monitors under $300](https://www.newegg.com/insider/best-27-inch-gaming-monitors-under-300-in-2026/)
- [Lenovo PSREF — ThinkPad E15 Gen 3 (AMD)](https://psref.lenovo.com/syspool/Sys/PDF/ThinkPad/ThinkPad_E15_Gen_3_AMD/ThinkPad_E15_Gen_3_AMD_Spec.PDF)
