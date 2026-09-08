# Infinity Floral Designs

A mobile-first, editorial redesign concept for the historical **Infinity Floral Designs** florist listing in Boynton Beach, Florida.

## Live preview

Expected GitHub Pages URL:

https://prithiraj.github.io/Infinity_Floral_Designs/

## Design approach

The implementation blends the strongest ideas from the three supplied reference screenshots:

- local-first clarity, a compact information strip, and obvious mobile actions;
- e-commerce-like mood browsing and a four-card floral inspiration shelf without fake products/prices;
- editorial serif typography, warm paper-like surfaces, and premium image-led storytelling;
- deep green / claret / blush palette;
- responsive mobile navigation and a compact mobile action dock;
- restrained animation with a decorative, optional Three.js hero layer.

The screenshots are **visual references only**. Their sample phone numbers, addresses, hours, prices, delivery promises, product names, reviews, services, and policies are not treated as facts for Infinity Floral Designs.

The site is intentionally static: semantic HTML, CSS, and vanilla JavaScript. Three.js is dynamically imported only on larger screens when reduced motion and data-saving modes are not active.

## Important business-data note

Research indicates the supplied Boynton Beach Maps listing is historical. The former address appears to be occupied by another business, and the historical phone number is currently associated with a different florist. This preview therefore does **not** present the old phone, hours, prices, ordering policies, or current reviews as active business facts.

Read [`PLAN.md`](./PLAN.md) for the evidence baseline, conversion strategy, design system, accessibility rules, SEO plan, and commercial-launch checklist.

## Photography

The preview uses real photographs sourced from pages marked free under the Unsplash License. They are not photographs of Infinity Floral Designs. See [`IMAGE_SOURCES.md`](./IMAGE_SOURCES.md) for source links and rights notes.

For a commercial launch, replace lifestyle/stock photography with owner-controlled current storefront, team, process, and arrangement photography whenever possible.

## Local development

No build step is required.

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## GitHub Pages

The project is designed to publish directly from a `gh-pages` branch. A `.nojekyll` file is included so GitHub serves the static files as-is.

## Files

- `index.html` — semantic page structure, metadata, JSON-LD
- `styles.css` — responsive visual system and reduced-motion behavior
- `script.js` — navigation, reveal enhancement, optional Three.js petals
- `PLAN.md` — approved plan and evidence guardrails
- `IMAGE_SOURCES.md` — image licensing/source log
