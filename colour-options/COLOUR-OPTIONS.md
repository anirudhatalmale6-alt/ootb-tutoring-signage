# Banner colour options

Seven colour schemes for the 6 ft × 4 ft banner. **The layout is identical in every
one** — same logo, same three subjects, same phone band, same letter heights. Only the
colour changes, so what you are picking here is a palette, not a design.

Pick one and I will recolour the whole set to match it: both banners, both signs, the
flyer and the business card.

---

## The seven

| | Option | Background | Phone band | Logo file |
|---|---|---|---|---|
| A | Deep Navy — *what you already have* | `#0B3D57` | navy on amber | reversed |
| B | Cream and Navy — light | `#F4F7F5` | amber on navy | mono-navy |
| C | White and Green — light, closest to your current banner | `#FFFFFF` | white on green | mono-navy |
| D | Amber field — light, loudest at distance | `#FDC64D` | amber on navy | mono-navy |
| E | Website hero gradient | `#11998E → #23A455` | navy on amber | mono-white |
| F | Website hero gradient, dark type and a white band | `#11998E → #23A455` | near-black on white | mono-white |
| G | Near black and bright green — dark | `#12222B` | near-black on bright green | reversed |

E and F use the **exact** gradient across the top of ootbtutoring.com. It was read off
the live page, not from memory:

```
linear-gradient(135deg, rgb(17,153,142) 0%, rgb(35,164,85) 100%)
```

---

## What is in this folder

- `banner-colour-options-grid.png` — all seven at a glance
- `banner-colour-distance-test.png` — all seven blurred by the same amount, which is a
  rough stand-in for viewing distance
- `OOTB-banner-colour-options.pdf` — one per page, large, with the reasoning
- `scheme-*.pdf` / `scheme-*.svg` — the print-ready artwork for each, 72 × 48 in exact
  trim, vector, fonts outlined

---

## How the colours were chosen

Not by eye. Every foreground/background pair in every scheme is measured with the WCAG
relative-luminance formula and the build **fails** below 3.0:1 for display type, and
below 4.0:1 for the phone number. Where the background is a gradient the worse of the
two endpoints is used, because half a banner passing is not passing.

The first run failed on eleven pairs, all of which looked perfectly fine on screen:

- OOTB Green `#23A455` on cream measures **2.99:1** — just under. The tagline, the
  grades line and the web address on the light schemes now use `#1B8A46`, the darker
  green that is already inside the logo. Not a new colour, just the right one.
- Amber on the hero gradient measures **2.05:1**. Nothing warm survives on that green —
  the accent on E and F is navy or white instead.
- White on `#23A455` measures **3.22:1**, which is not enough margin for the single most
  important thing on the banner. C's phone band is the darker green.

**The logo variant is chosen the same way.** The primary lockup has an amber spark, and
amber on white measures **1.57:1** — from the road the spark disappears and you are left
with a closed box, which is the opposite of what the mark means. So the light schemes
(B, C, D) carry the navy lockup. If you would rather have the colour version up close
and accept that the spark washes out at distance, say so and I will swap it.

## The distance test

`banner-colour-distance-test.png` blurs all seven by the same amount. It is not optics,
but it ranks them honestly and it is a far better check than looking at artwork at 100%
and deciding it seems bold. Whatever you can still read in that picture is roughly what
a driver gets. The phone number should be the last thing to go — in all seven, it is.
