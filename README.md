# Skein — landing page

ML-grade experiment tracking, built specifically for Etsy sellers. Run experiments on
your listings (photos, titles, pricing, SEO tags), track every metric, compare variants,
and learn what actually moved the needle — Weights & Biases, reimagined for handmade-goods
sellers doing $5K+/month.

## What's here

A single self-contained `index.html` landing page — hero, product-dashboard mockup,
features, how-it-works, pricing, testimonials, and CTA. No build step.

- **Tailwind CSS** via CDN (with an inline config for the custom clay / loom / paper palette)
- **Fonts:** Fraunces (display) + Inter (body) + Spline Sans Mono (data labels) via Google Fonts
- All icons, charts, and avatars are **inline SVG** — no remote images, works fully offline
- Responsive, accessible, smooth-scroll, with tasteful micro-interactions

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8077
# → http://localhost:8077
```

## How it was built

Generated through an iterative builder → critic loop: a builder agent wrote the page and a
deliberately exacting aesthetic critic scored it 1–10, looping feedback back until the score
cleared 8 (final: **8.4/10**).
