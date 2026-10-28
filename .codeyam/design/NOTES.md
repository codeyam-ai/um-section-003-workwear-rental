# Design exploration notes

University of Michigan, section 003 (the 4th presentation in that section).

Working name: **Lapel**, a clothing-rental membership for new grads building a work wardrobe. "Lapel" and the brand names in the mockups (Arden & Vale, Kestrel, Noor Atelier, Halden, Harlow & Pierce) are placeholders.

## Brief

The full product description is `projectDescription` in `.codeyam/editor.json`. In short: rent or buy workwear, see brand deals, try clothes on virtually from your own photo, catalog the clothes you already own, check your employer's dress code (and follow changes to it), pick a membership tier, and upload inspiration boards. It should be easy, not overwhelming, and look modern and a little feminine while still corporate and put together.

## Answers to the design questions

The questions are in `questions.json` and the raw answers in `answers.json`.

- **Screen:** Home
- **Device:** Phone first (390×844)
- **Feel:** polished, professional, confident
- **Avoid:** all pink and pastel, stuffy like a bank, busy discount-store
- **Admired looks:** Rent the Runway, Pickle, Vogue, Aritzia
- **Directions:** 6

## Content on every mockup

Every mockup shows the same content: Maya's first box arriving Thursday (navy blazer, wide-leg trouser, silk shell), her Harlow & Pierce dress code (business casual, with denim allowed on Fridays since Oct 21), four picks for her first week with rent and buy prices, a try-on preview, three brands on sale, and 2 of 4 swaps left on the Essentials plan.

## The six directions (`project_mockups/`)

1. **Magazine, warm and serif.** Follows the catalog's Editorial system: parchment background, serif type and burgundy accents. The safest option.
2. **Pinboard of picks.** White, with a staggered grid of clothes, filter chips and cobalt accents.
3. **Plum poster, big type.** Deep plum and saffron, with oversized condensed type and slices that open into the picks.4. **Evening, photo-led.** Dark, opening on a full-bleed try-on photo, with champagne accents and a grid of picks.
5. **Week planner, clean grid.** A Swiss-style grid with an outfit for each day of the first week, plus emerald dress-code checks.
6. **Pinstripe, calm and centered.** A flannel-grey pinstripe background, centered and airy, with dusty-mauve accents.

**Chosen: #3, Plum poster, big type.** Its tokens are in `design_system.md`.

## How the images work

Each product photo slot has two layers. The bottom layer is an inline SVG drawing of the garment, which always shows. On top of it is a keyword photo from loremflickr.com, which replaces the drawing when the viewer is online.
