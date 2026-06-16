# Gray Matter — Landing Page Drafts

A trust-first B2C landing page for **Gray Matter Cognition**, inspired by
[functionhealth.com](https://www.functionhealth.com/) (premium, medical authority,
peer-reviewed science) and [mitohealth.com](https://mitohealth.com/) (modern,
clinician-guided, personalized plan).

> ⚠️ All copy in `[BRACKETS]`, marked `TODO`, names, stats, and reviews are
> **placeholders**. Swap in your real numbers, advisors, headshots, and quotes
> before going live. Nothing here is legal/medical-reviewed.

## Quick start

```bash
open index.html        # macOS
xdg-open index.html    # Linux
# or just drag index.html into a browser
```

No build step, no dependencies. One self-contained file (fonts load from Google Fonts CDN).

## What's in `index.html` (draft 1 — "Clinical Premium")

Section order, all chosen to **signal trust & credibility**:

1. **Announcement bar** – urgency / promo
2. **Sticky nav** – with primary CTA
3. **Hero** – headline + subhead + dual CTA + trust strip (★ rating, member count, HIPAA/CLIA badge) and a mock "Brain Health Score" report card
4. **Press logos** – "As featured in" (replace with real SVGs)
5. **Stats bar** – biomarkers / members / clinician-reviewed / advisors
6. **What's Included** – 6 biomarker/cognitive panel categories
7. **How It Works** – 4 steps
8. **The Science** (dark section) – peer-reviewed, CLIA labs, clinician oversight, privacy, independence, longitudinal
9. **Advisory Board** ← *your "advisor section"* — 4 advisor cards
10. **Patient Reviews** ← *your "patient review"* — 3 verified testimonial cards
11. **Pricing** – single membership card
12. **FAQ** – accordion
13. **Final CTA**
14. **Footer** – with medical disclaimer

## Rebranding in 30 seconds

Everything visual is driven by CSS variables at the top of `index.html`:

```css
:root {
  --brand:   #5b4bdb;   /* primary violet — your brand color */
  --accent:  #19c39c;   /* "good/optimal" signals */
  --bg-deep: #14122b;   /* dark sections + footer */
  ...
}
```

Change `--brand` and the whole page re-themes. Fonts: `Fraunces` (serif display)
+ `Inter` (body) — swap the Google Fonts `<link>` to change.

## Replace before launch
- [ ] Real advisor names, credentials, institutions + **headshots** (swap the `.photo` divs for `<img>`)
- [ ] Real, **verified** patient reviews (and confirm you can use them)
- [ ] Real press logos or remove the strip
- [ ] Real stats (biomarker count, member count, rating)
- [ ] Pricing
- [ ] Legal: Privacy, Terms, HIPAA notice, and **have the medical disclaimer reviewed**
- [ ] Logo asset (currently a gradient square)

## Other draft directions to consider

I built **Draft 1 (Clinical Premium)**. If you want, I can spin up variants:

- **Draft 2 — "Warm & human":** softer palette, lifestyle photography, story-led hero
  ("Stay sharp for the people you love"), less clinical.
- **Draft 3 — "Data-forward":** dark-mode default, big animated biomarker dashboard
  as the hero, for a more tech/quantified-self audience.
- **Draft 4 — "Conversion sprint":** shorter single-scroll page optimized for paid
  ads (one promise, one CTA repeated, condensed proof).

Tell me which direction(s) and I'll build them out as separate files.
