# Infinity Floral Designs

A mobile-first, editorial floral website concept for the historical **Infinity Floral Designs** listing in Boynton Beach, Florida.

## Live site

**GitHub Pages:** https://prithiraj.github.io/Infinity_Floral_Designs/

## Important business-data status

Public research confirms the historical listing context, but the current operating identity, address, phone, hours, ordering channel, products/services, delivery area, pricing, reviews, policies, and social accounts are not sufficiently verified. The published concept therefore **does not invent or republish stale business details as current facts**.

The three user-supplied florist mockups are used only for visual direction. Their sample prices, hours, addresses, reviews, services, delivery promises, and other fictional business content are not reused as Infinity Floral Designs facts.

## Design plan

See [`PLAN.md`](./PLAN.md) for the evidence baseline, audience, conversion goals, creative direction, color and typography systems, image strategy, information architecture, layout, motion/Three.js plan, accessibility, performance, SEO/local discovery, rights notes, implementation sequence, and acceptance criteria.

## Image rights

See [`IMAGE_SOURCES.md`](./IMAGE_SOURCES.md). The published concept uses real Unsplash floral/editorial photography as illustrative stock. It is not presented as the shop's own portfolio work.

For commercial launch, replace stock/editorial imagery with owner-controlled current storefront, team, process, and arrangement photography wherever possible.

## Tech

- Semantic static HTML
- Responsive CSS
- Vanilla JavaScript
- Optional Three.js loaded dynamically as a subtle hero-petal enhancement
- `prefers-reduced-motion` support
- Static/no-JavaScript fallback
- Accessible mobile navigation and visible focus states
- Open Graph metadata and safe `WebSite` JSON-LD
- GitHub Pages deployment via GitHub Actions

The website is intentionally self-contained in `index.html` and requires no build step.

## Local preview

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Production data required

Before presenting the site as a current operating florist, verify and add:

- legal/current business identity;
- current street address;
- current phone and email/domain;
- current hours;
- current products/services and ordering method;
- pickup/delivery/service area;
- current prices/availability where displayed;
- current social profiles;
- verified reviews/social proof;
- owner-controlled logo and photography rights.

The current preview intentionally remains `noindex` until those items are verified.
