# Infinity Floral Designs

A mobile-first floral website concept for Infinity Floral Designs, combining warm editorial art direction with clear local-shop conversion patterns.

## Important prototype status

Public research found a historical Boynton Beach listing, but the current address, phone, hours, ordering channel, services, delivery area, pricing, reviews, and operating entity were not sufficiently verified. This implementation intentionally **does not invent or republish stale business details as current facts**.

The visual build is therefore a relaunch-ready prototype. Three user-supplied concept screenshots inform the visual hierarchy and responsive patterns only; their invented sample content is not reused. Once the owner supplies verified business data, the conversion scaffolding can be connected without redesigning the site.

## Design plan

See [`DESIGN_PLAN.md`](./DESIGN_PLAN.md) for the evidence baseline, audience, conversion goals, creative direction, color and typography systems, image strategy, accessibility, performance, SEO, rights notes, implementation sequence, and acceptance criteria.

## Image rights

See [`IMAGE_CREDITS.md`](./IMAGE_CREDITS.md). The live prototype uses real, free-to-use Unsplash floral photography as illustrative stock. It is not presented as the shop's own portfolio work.

## Tech

- Semantic static HTML
- Responsive CSS
- Vanilla JavaScript
- Native `<dialog>` lightbox
- Client-side inquiry draft builder (no data transmission)
- Three.js loaded dynamically as a progressive, non-interactive petal enhancement
- `prefers-reduced-motion` support
- GitHub Pages deployment workflow

## Local preview

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Production data required

Before presenting the site as a current operating florist, verify and add:

- legal/current business identity;
- current street address;
- current phone;
- current email/domain;
- current hours;
- current services and ordering method;
- pickup/delivery/service area;
- prices or product inventory, if used;
- current social profiles;
- verified reviews/social proof;
- owner-controlled logo and photography rights.
