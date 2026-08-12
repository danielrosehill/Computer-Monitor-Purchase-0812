# Existing hardware and what it can drive

Carried over from prior work on the laptop (`linux-desktop/thinkpad-e15-upgrades`).
Confirmed there as of mid-2026; re-verify anything that decides a purchase.

## Laptop

| | |
|---|---|
| Machine | ThinkPad E15 Gen 3 (AMD Ryzen 7 5700U) |
| Built-in panel | 15.6″ FHD 1920×1080 IPS |
| USB-C | USB-C 3.1 Gen 1, 5 Gbps — **no Thunderbolt** |
| Dock | Lenovo ThinkPad USB-C Dock, 40AS family |
| GPU | Radeon integrated (Lucienne, Vega-class) |
| OS | Linux, KDE on Wayland |

**The binding constraint: two external displays, maximum.** Non-Thunderbolt USB-C
docks in the 40AS family top out at two externals via DisplayPort MST. The laptop's
own panel can serve as a third screen, but a third *external* is not available
without a new laptop with Thunderbolt 4 plus a TB4 dock.

Practical consequences for a monitor purchase:

- Bandwidth is finite. Two high-resolution panels over one 5 Gbps USB-C link will
  force compromises on refresh rate — worth checking against the specific dock
  variant before assuming 4K@60 on both.
- **DisplayLink docks are out.** They need proprietary Synaptics drivers on Linux,
  break on kernel updates and behave badly on Wayland. Native MST only.
- Dock video outputs are DisplayPort (or DP + HDMI depending on variant), so a
  monitor with a DisplayPort input is the safe default; HDMI-only is a risk.

## Desktop

Runs three external monitors already. Details of those panels are not recorded here
yet — if the new monitor joins or replaces one of them, capture what they are, since
mixing pixel densities across a Wayland multi-monitor setup causes real scaling pain.

## Relevant Linux quirks

- KDE on Wayland: fractional scaling works, but mixed-DPI setups are still the
  awkward case. A pixel density that lets every screen sit at the same integer or
  same fractional scale is worth more than it sounds.
- Chrome on Wayland does not see the KDE panel strut, so page controls in the
  bottom ~44 px can hide under the panel. Not a monitor-selection factor, but it
  affects how usable a very short window height is.
