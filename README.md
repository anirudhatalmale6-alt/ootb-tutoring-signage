# OOTB Tutoring — signage and print pack
Prepared 29 August 2026 · brand direction "The Spark" · Poppins, outlined

Everything here is **vector PDF**. Send the PDF to the printer or sign shop, not the PNG,
unless they specifically ask for a raster file.

---

## What is in the pack

| Piece | Finished size | File to send | Page size in the PDF |
|---|---|---|---|
| Outdoor banner, landscape | 6 ft wide × 4 ft tall | `banner-6ft-x-4ft-landscape.pdf` | 72 × 48 in |
| Outdoor banner, portrait | 4 ft wide × 6 ft tall | `banner-4ft-x-6ft-portrait.pdf` | 48 × 72 in |
| Sign, single sided | 18 × 12 in | `sign-18x12-single-sided.pdf` | 18.25 × 12.25 in |
| Sign, double sided — face A | 18 × 12 in | `sign-18x12-double-sided-face-A.pdf` | 18.25 × 12.25 in |
| Sign, double sided — face B | 18 × 12 in | `sign-18x12-double-sided-face-B.pdf` | 18.25 × 12.25 in |
| Flyer, front | 8.5 × 5.5 in | `flyer-8.5x5.5-front.pdf` | 8.75 × 5.75 in |
| Flyer, back | 8.5 × 5.5 in | `flyer-8.5x5.5-back.pdf` | 8.75 × 5.75 in |
| Business card, front | 3.5 × 2 in | `business-card-front.pdf` | 3.75 × 2.25 in |
| Business card, back | 3.5 × 2 in | `business-card-back.pdf` | 3.75 × 2.25 in |

`OOTB-signage-proofs.pdf` holds all nine pages in one file, for flipping through.

The two banners are the **same design in two shapes**. Print whichever fits the wall. You do
not need both.

The double sided sign has two different faces on purpose. Face A is what somebody reads
walking or driving past; face B is the course list they read once they have stopped.

---

## Bleed and trim

Every piece except the banners is supplied with **0.125 in of bleed on all four sides**, which
is why the PDF page is 0.25 in bigger than the finished size in each direction. The background
runs into that margin so a small drift at the guillotine cannot leave a white sliver on the
edge. Nothing that needs reading sits within 0.125 in of the trim line.

The banners are supplied at **exact finished size with no bleed**, which is what a vinyl shop
expects. They will add the hem themselves.

---

## Colours

The hex values are the authoritative ones — they match the website and the logo pack exactly.
The CMYK column is a **starting point only**, converted arithmetically. Ask the printer for a
proof before a long run and let them match to the hex.

| Role | Hex | CMYK starting point |
|---|---|---|
| Deep Navy — the field colour | `#0B3D57` | C87 M30 Y0 K66 |
| Spark Amber — the phone band | `#FDC64D` | C0 M22 Y70 K1 |
| OOTB Green | `#23A455` | C79 M0 Y48 K36 |
| Bright Green — on dark only | `#38EF7D` | C77 M0 Y48 K6 |
| Ink — body text on white | `#12222B` | C58 M21 Y0 K83 |

Navy is doing the heavy lifting outdoors. It holds up against a grey Surrey sky far better
than the white background the old banner used, and amber on navy is the strongest contrast
pair in the brand palette.

---

## Fonts

**None needed.** Every letter in every file is a vector outline, not live text. The printer
does not need Poppins installed and cannot substitute the wrong face. The trade-off is that
the text is no longer editable in the PDF — if wording needs to change, come back to me and
I will regenerate it.

---

## Legibility

Sign trade rule of thumb: a capital letter is comfortably readable at roughly **30 ft for
every inch of cap height**, and catches the eye at about 10 ft per inch.

| Piece | Element | Cap height | Comfortably readable at |
|---|---|---|---|
| Banner 6×4 | phone number | 5.95 in | about 175 ft |
| Banner 6×4 | MATH · SCIENCE · ENGLISH | 2.60 in | about 75 ft |
| Banner 4×6 | phone number | 3.97 in | about 115 ft |
| Banner 4×6 | MATH / SCIENCE / ENGLISH | 3.30 in | about 95 ft |
| Sign 18×12 | phone number | 1.45 in | about 43 ft |
| Sign 18×12 | MATH · SCIENCE · ENGLISH | 0.77 in | about 23 ft |

`banner-distance-test.png` shows the banner progressively blurred, which is a rough stand-in
for viewing distance. The logo, the three subjects and the phone number all survive the
heaviest blur; the small print does not, which is the correct order of priority.

---

## Materials worth asking for

- **Banner** — 13 oz scrim vinyl, hemmed all round, brass grommets in the corners and every
  24 in along the top and bottom. Ask for a matte or satin finish rather than gloss: gloss
  throws a reflection and the sun is low here most of the winter.
- **Signs** — 4 mm corrugated plastic (coroplast) if they are seasonal or move around, 3 mm
  aluminium composite if they are staying up. The double sided one needs printing on both
  faces of a single panel, not two panels back to back.
- **Flyers** — 100 lb gloss text, printed both sides, full bleed.
- **Business cards** — 16 pt stock with a matte laminate. Matte because the back is mostly
  white and gloss makes a phone number hard to read at an angle.

---

## Raster fallbacks

`print-png/` holds PNG versions for any shop that will not take a PDF. Each is generated at
the resolution that piece actually needs — 100 dpi for banners, 150 for signs, 300 for the
flyer and card. Do not scale them up.

---

## Things to check before you order

1. **The name and title on the business card.** It currently reads "Jagjit (Jag) Uppal —
   Founder and Tutor · P.Eng". Tell me if you want it different, or if you want a version
   with no name so the same card works for the whole team.
2. **The email address.** The card carries `ootbtutoring@gmail.com`, which is what the
   website uses.
3. **The claims on the flyer** — "10+ years in Surrey" and "5,000+ students taught" are the
   evergreen versions you approved for the website, so print and web now say the same thing.

---

## Banner colour options (29 August 2026)

Seven colour schemes for the banner, same layout in all of them, in `colour-options/`.
Start with `colour-options/banner-colour-options-grid.png`, then the blurred
`banner-colour-distance-test.png`. Details and the reasoning: `colour-options/COLOUR-OPTIONS.md`.
