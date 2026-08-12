# Decision record

Every question that came up while working this purchase, the answer, and what it
settled. Recorded at the buyer's request so the reasoning survives the session that
produced it.

Structured as **question → answer → consequence** rather than chronologically, so
it can be read by someone picking this up cold. Where a decision was later reversed
the reversal is recorded in place rather than edited away — the wrong turns are the
part that a diff cannot carry.

Intake questions are in [`open-questions.md`](open-questions.md); this file covers
the decisions that came out of research. All dates 2026-08-12 unless noted.

---

## 1. One monitor or two?

**Answer:** One.

**Consequence:** Removed the dock from the problem entirely. The two-external-display
ceiling on the ThinkPad E15 Gen 3, and the DisplayPort-input requirement that came
with the dock's MST outputs, both stopped applying. A single monitor connects
straight to the laptop's HDMI or USB-C port.

---

## 2. Bought where, used where?

**Answer:** Bought in Connecticut, left in Connecticut, never carried home.

**Consequence:** The single most decisive fact in the whole exercise. US retail
pricing, US plug, no import, no VAT — landed cost is sticker plus Connecticut sales
tax at the 6.35% general rate. And, critically, **portability has no value**.

The buyer raised the objection themselves that stashing monitors around the world
seems illogical. It resolves this way: one screen at the one place visited annually
for three weeks is a single purchase, not a strategy. See
[`travel-profile.md`](travel-profile.md).

---

## 3. Does a portable monitor make sense?

**Answer:** No.

**Consequence:** A tabletop VESA stand costs roughly the same (~$23–29) whether it
holds a 15.6″ portable or a 27″ desktop panel, so the mount was never the variable —
the panel is. Portable panels run **2–4× more per square inch** of display and
deliver a third to a half the area. Full permutation table in
[`../research/mounting-approaches.md`](../research/mounting-approaches.md).

**Supporting evidence from the buyer:** several portable monitors owned over the
years, all underwhelming; poor carry-on fit; breakage anxiety in checked luggage;
and one 15.6″ monitor that **arrived broken** despite bubble wrap and clothing
padding. A hard case fixes the breakage and ruins the luggage economics.

**Important qualification, recorded because it is easy to get wrong:** that evidence
argues against *transporting* a monitor. It says nothing about *size*. A screen
bought at the destination is never exposed to any of those failure modes.

---

## 4. Is "a cheap 15.6″ monitor" a thing?

**Answer:** No. The category does not exist.

**Consequence:** This overturned the buyer's working plan. True 15″ desktop panels
were discontinued around 2018, and everything now sold at 14–16″ is a **portable
monitor** at portable pricing. The floor for a conventional desktop monitor with its
own stand is **19″**, and 19″ panels are mostly 1600×900 at $85–120 — more than a
24″ costs, for a worse screen. The economics are structural: chassis, stand, PSU and
controller cost about the same for a small panel as for a 24″ one.

So "a cheap 15.6″ monitor" resolves unavoidably to buying a portable monitor — the
exact category already found disappointing — and paying its premium for a screen
that never moves.

---

## 5. What size?

**Answer:** 24″. Reversed from an initial lean toward 21″.

**Consequence:** The buyer's habitual size is 21″, used for many years — but across
a **three-monitor** desktop. Here one panel carries the whole workload alongside the
laptop screen, so the extra area is worth having. 24″ is also where the market is
deepest and cheapest.

27″ was considered and rejected: triple the cost, harder to store, and more risk
against a guest desk of unknown dimensions.

---

## 6. Cost-benefit — how much is this worth spending?

**Answer:** The question mostly dissolves.

**Consequence:** At roughly **15 working days a year** (one three-week visit), the
entire viable range spans $30–290, or **$1–3 per day of use**. That spread is noise
against three weeks of not working hunched over a laptop panel.

So price optimisation is the wrong objective. What *is* worth optimising: not paying
for portability, getting eye-level height without extra hardware, and keeping the
abandonment loss small if the visits ever stop. Full table in
[`../research/value-analysis.md`](../research/value-analysis.md).

---

## 7. Is there a spare monitor or an idle TV at the property?

**Answer:** No.

**Consequence:** The zero-cost option is out. It was worth one question — free beats
every priced option — but it does not apply here.

---

## 8. Is there anywhere to store it between visits?

**Answer:** Yes.

**Consequence:** Closed the last argument that could have justified a small panel.
Storage footprint was the *only* consideration that favoured a 15.6″ screen, and it
does not bind.

---

## 9. Do any monitors ship with a stand that is actually useful?

**Answer:** Yes — an entire product line, not a lucky model.

**Consequence:** No mounting hardware needs to be bought at all. This mattered
because the usual fallbacks were both unavailable: **drilling through the desk and
C-clamping are impossible in a guest residence.**

The business/professional lines ship a four-way stand as standard — Dell **P**/**U**,
Lenovo ThinkVision **T**/**P**, HP **E**/**Z** — with 130–155 mm of height plus tilt,
swivel and pivot.

**Screening rule for listings, since price is not the signal** (a $200 gaming SKU is
often tilt-only while a $67 refurbished P-series is not):

- Height adjustment quoted **as a number in millimetres**. "Tilt adjustable" alone
  means tilt-only.
- The word **"pivot"** appears — pivot is only fitted to stands that also have
  height, because the panel must rise before it can rotate.
- A business-line letter in the model name. Avoid Dell **E** and **S** series.

---

## 10. How does it get stored away, given no drilling and no clamping?

**Answer:** The same choice solves it.

**Consequence:** Dell P-series ships as **three unassembled pieces** — panel, riser,
weighted base — and the panel **quick-releases** from the riser by button. It returns
to that state for the cabinet: a flat 24″ panel plus a flat base and a short arm.

**Trap identified in the aftermarket folding-stand category:** the WEARSON WS-03T
($49.99) is the only stand found that genuinely folds flat, which makes it look
ideal — but its range is **7–11 inches of pole**. That is a riser, not an eye-level
mount, so it fails the core requirement. Storability and height work against each
other across that whole product class. The built-in business stand is the only
option that is both tall and disassembles.

---

## 11. New or refurbished?

**Answer:** New, firsthand. Stated by the buyer; overrides the pure value ranking.

**Consequence:** The recommendation moved from a refurbished Dell P2422H at $67–90
to a new Dell **P2425** at $239.99. The reasoning given was to start from a
known-good unit rather than trust an account of an item's condition.

The analysis does not fight this. The gap is about **$2.30 per day of use**, which is
precisely the magnitude this repo has argued throughout is not worth optimising. And
new buys two concrete things: a **3-year Dell warranty with advanced exchange**
against 30–90 days on refurbished stock, and no grading lottery on a device that will
sit unattended in another country for eleven months at a time, where a return is
inconvenient.

The refurbished option is kept on record in
[`../research/value-analysis.md`](../research/value-analysis.md) rather than deleted.

---

## 12. Which exact model?

**Answer:** Dell **P2425** — 24″, 1920×1200, 16:10, 100 Hz, $239.99.

**Consequence:** Chosen over the 16:9 P2425H at $184.99 for the aspect ratio.
1920×1200 is **11% more vertical space** than 1920×1080, and vertical is the axis
that matters for terminals, documents and long-form reading. It is also the only
compensation available for dropping from three screens to one. The premium is $55,
or $0.73 per day of use over five years.

**Naming trap, recorded because it is easy to buy the wrong one:**

- `P2425H` = 16:9, 1920×1080
- `P2425` = **16:10, 1920×1200** ← the one to buy
- `P2425E` = 16:10 plus USB-C 90 W PD and Ethernet — different, pricier SKU

Read the **resolution field** at checkout, not the model number.

---

## 13. What actually connects it?

**Answer:** A cable that is not in the box.

**Consequence:** The P2425 ships with a **DisplayPort-to-DisplayPort** cable. **The
ThinkPad E15 Gen 3 has no DisplayPort socket**, so the included video cable is
useless on this laptop. Options:

- **HDMI cable** (~$8) → 1920×1200 @ 60 Hz. Simple and sufficient.
- **USB-C-to-DisplayPort cable** (~$15–20) → 1920×1200 @ 100 Hz via the laptop's
  DisplayPort 1.2 Alt Mode. Worth it for the full refresh rate.

Related finding from Lenovo PSREF: the E15 Gen 3's **HDMI port caps at 4K@30 Hz**
(HDMI 1.4b class) while USB-C reaches 4K@60. Irrelevant at 1920×1200, but it means
any future 4K purchase on this machine is USB-C-only.

The monitor's USB-C port is **downstream and data-only at 15 W** — it does not charge
the laptop and is not a video input. The laptop charger still travels.
