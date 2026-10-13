# Akhila Mathur — Portfolio site brief

## Who this is for
Akhila Mathur, UX/Product Design leader (15+ years). Currently Senior Design Manager,
YouTube Shopping. Previously Samsung (2011–2022) and Amazon (2015–2017). Audience:
hiring managers, recruiters, design peers.

## Site structure (6 pages, static HTML/CSS, no build step)
- `index.html` — home: hero + selected work list
- `case-study-checkout.html` — YouTube Native Shopping Checkout
- `case-study-samsung-infinity.html` — Naming the Infinity Display (Samsung)
- `case-study-alive-intelligence.html` — Alive Intelligence: Make for India (Samsung)
- `about.html` — full career timeline, patents, publications, interests
- `contact.html` — email + LinkedIn

Three more case studies are planned but not yet built (shown as "Coming soon" on
the homepage): Samsung Accessibility & Localization, Amazon Seller Onboarding,
Samsung Indian-Language Keyboard.

## Design tokens
- **Color:** Ink `#201F1C` (text), Chalk `#EEF0EA` (background, cool sage-paper —
  deliberately not the generic cream/terracotta look), Chalk Deep `#E2E5DB` (borders/
  dividers), Plum `#5B2333` (primary accent), Brass `#B98A2E` (secondary accent, used
  for year markers), Sage `#7C8471` (muted supporting tone), White `#FFFFFF`.
- **Type:** Fraunces (serif, headlines/display) + IBM Plex Sans (body, UI, labels).
  Loaded via Google Fonts CDN.
- **Layout motif:** role/company/year metadata shown as a literal price-tag shape
  (clip-path polygon with a small circular "hole") rather than a generic dot-separated
  eyebrow label — grounded in the fact that Akhila's actual work is commerce/checkout
  UI. Career history and "what shipped" timelines use real years as markers, not
  generic 01/02/03 numbering.
- **Motion:** minimal — one hero fade/rise on load, hover states only on interactive
  work-list items.

## Content rules already established (please preserve)
- Every case study is built ONLY from material that is (a) publicly documented via
  independent press or the company's own newsroom/blog, or (b) the person's own
  factual accomplishment record (not internal confidential research). Each case study
  ends with a short "note on sourcing" box confirming this.
- Case studies not yet cleared for public sharing are shown honestly as disabled
  "Coming soon" tiles on the homepage — never faked or filled with placeholder content.
- Real press/official images are hotlinked directly to their original source (Samsung
  Newsroom CDN, etc.) with captions and attribution — not downloaded/rehosted.

## What to iterate on next
- Visual polish pass now that real content is in place
- Information architecture: consider whether "About" should be split (career vs.
  patents/publications) as more case studies are added
- Add remaining 3 case studies once source material is cleared
