# Infinity Floral Designs — Website Design & Implementation Plan

_Last updated: 2026-09-08_

## 1. Evidence baseline

- **Working business name:** Infinity Floral Designs.
- **Historical category:** florist / floral design.
- **Historical Google Maps listing:** 3469 W Boynton Beach Blvd #4, Boynton Beach, FL 33436.
- **Critical verification issue:** public research indicates that the historical suite is now occupied by another business and the historical phone number is associated with another florist. The inactive Florida corporation with the exact name is also historical evidence, not proof of a current operating entity.
- **Production rule:** do **not** publish the historical street address, phone number, hours, prices, delivery promises, services, reviews, or policies as current facts until the owner verifies them.
- **Current build status:** public design prototype / relaunch shell. It will intentionally avoid unverified NAP and commerce claims.
- **Reference-image status:** three user-supplied concept images are now available and have been reviewed. They are used strictly for visual direction; their sample business names, phone numbers, addresses, hours, prices, reviews, delivery promises, products, and service claims are not reused as facts.

### Evidence sources

- Historical/current business research from the Google Maps listing and Florida public records gathered before implementation.
- Licensed floral photography from Unsplash. Individual image pages and photographer credits are documented in `IMAGE_CREDITS.md`.
- Unsplash states that its standard-license images can generally be used for commercial and noncommercial projects, subject to third-party rights considerations: https://help.unsplash.com/en/articles/2612315-can-i-use-unsplash-images-for-personal-or-commercial-projects

## 2. Audience

Primary audience: local flower buyers motivated by emotion and aesthetics — celebration, affection, appreciation, comfort, and spontaneous gifting.

Secondary audience to validate before launch: custom floral commissions, events, business/corporate floral work, pickup and delivery customers.

The site should answer quickly: **Is the work beautiful? Does this feel trustworthy? What style fits my moment? What should I do next?**

## 3. Conversion goals

### Prototype conversion hierarchy

1. **Explore the floral edit** — primary, fully functional internal journey.
2. **Plan an arrangement** — opens the inquiry-builder UI without pretending an order can currently be submitted.
3. **View gallery / craft direction** — confidence-building actions.

### Production conversion hierarchy after owner verification

1. Order / request flowers.
2. Call the florist.
3. Get directions or choose pickup/delivery.
4. Browse verified products/services.

No fake phone number, email address, order endpoint, or form destination will be invented in the prototype.

## 4. Creative direction

**Warm Local Atelier / Botanical Editorial**

The experience should feel like a premium independent floral studio with the clarity of a strong local shop and the browse rhythm of a modern florist:

- warm ivory, paper-like surfaces with restrained texture;
- deep forest utility color and oxblood editorial accents;
- oversized, real floral photography;
- generous serif headlines and compact sans-serif utility text;
- product-like visual cards that are explicitly labeled as mood directions rather than current inventory;
- clear action rails and a persistent mobile CTA pattern;
- soft borders, captions, and editorial three-panel storytelling;
- a subtle 3D petal atmosphere that complements photography instead of becoming the experience.

### Reference-image synthesis

The three user-supplied reference images contribute different strengths:

1. **Local-shop concept:** borrow the immediate visual clarity, high-contrast action areas, image-forward service rhythm, and mobile bottom action bar. Do **not** reuse its sample phone, address, hours, reviews, or service claims.
2. **E-commerce concept:** borrow the compact browse rhythm, horizontally scannable occasion/motivation chips, clean deep-green utility surfaces, and disciplined card grid. Do **not** reuse its prices, best-seller claims, same-day-delivery promise, subscriptions, products, reviews, or checkout language.
3. **Editorial concept:** use this as the strongest art-direction reference—cream paper, oxblood serif headlines, large floral hero, refined rules, quiet botanical line art, and three-part editorial storytelling. Do **not** reuse its fictional studio identity, prices, wedding service claims, testimonials, contact data, or social accounts.

The final design intentionally sits between all three: **editorial first, local clarity second, commerce rhythm third**.

Avoid coupon-heavy e-commerce tropes, generic wedding-template blush styling, game-like interactions, floating emojis, and exaggerated luxury gold.

## 5. Color system

| Role | Color |
| --- | --- |
| Forest | `#173C2A` |
| Deep Forest | `#102D20` |
| Warm Cream | `#F7F1E8` |
| Paper | `#FFFAF3` |
| Oxblood | `#772F35` |
| Rose | `#B45B59` |
| Coral | `#D4614D` |
| Hairline | `#D9CBBC` |

Flowers carry most of the visual color. Interface accents stay restrained.

## 6. Typography

- **Display:** Newsreader — editorial serif for hero and section statements.
- **Body/UI:** Manrope — modern, highly legible sans serif.
- Strong system fallbacks remain usable if web fonts fail.
- No script font for navigation, forms, or important actions.

## 7. Image strategy

### Production imagery

Use real photography first. Current prototype photos are licensed Unsplash imagery and are **illustrative floral photography, not photographs of Infinity Floral Designs**. This distinction is documented in credits and in the public prototype status.

Photo mix:

- hero still life with intentional negative space;
- bouquet details;
- hand-held arrangements without relying on identifiable faces;
- market/studio flower abundance;
- macro ranunculus texture;
- rich purple / green composition for visual contrast.

### Generated imagery

Original SVG botanical assets will be created for decorative purposes:

- infinity/leaf brand mark;
- petal/bloom line art;
- abstract botanical corner motifs;
- favicon/OG-safe vector treatment.

Generated/vector imagery is decorative only and will never masquerade as real inventory or business photography.

### Rights

All production photo sources and credits live in `IMAGE_CREDITS.md`. Owner-supplied photography should replace stock imagery whenever it becomes available.

## 8. Information architecture

Single-page mobile-first prototype:

1. Hero
2. Customer-motivation chip rail
3. Floral directions / mood cards
4. Experience promise band
5. Three-panel creative direction
6. Editorial gallery
7. Inquiry-builder prototype
8. Local-information verification rail
9. Final CTA
10. Footer / image credits

Production IA can expand to Shop, Custom Flowers, Story, Gallery, Contact, and verified service pages only after inventory and services are confirmed.

## 9. Section-by-section layout

### Header

Compact wordmark, in-page navigation, high-contrast CTA, accessible mobile menu.

### Hero

Split editorial composition. Left: concise emotional proposition. Right: real floral still-life photography. The Three.js canvas stays behind copy/image and only adds a small sense of depth through drifting translucent petals.

### Motivation rail

A compact horizontally scrollable row inspired by the e-commerce reference, using generic customer motivations—celebrate, appreciate, comfort, connect, just because—rather than unsupported service categories.

### Floral directions

Four clean photo cards with evocative **mood labels**, not product names or purchasable inventory: Soft Blush, Quiet White, Wild Color, and Deep Botanicals. Each is explicitly positioned as visual direction.

### Experience promise

A deep-green editorial band explains how the digital experience is designed to work: see the feeling, choose a direction, make the next action clear. These are UX principles, not shop-service claims.

### Creative direction

A three-panel editorial spread—copy / real photo / botanical principles—borrows the strongest composition cue from the editorial reference. It is positioned as the **brand direction for the relaunch**, not a fabricated history or current process claim.

### Gallery

Responsive masonry-style grid with accessible lightbox. Every photo gets meaningful alt text and source credit metadata.

### Inquiry builder

A client-side UI that helps a visitor describe a floral mood, occasion, date, and notes. In prototype mode it produces a copyable inquiry summary; it does not claim to submit an order.

### Local information / verification

Uses the high-conversion utility-rail pattern from the local-shop reference but fills it only with evidence-safe states: working business name, Boynton Beach historical market context, and explicit “awaiting verification” states for current contact and hours/ordering. Once verified, the same component can become call / hours / directions utilities without redesign.

### Final CTA

A strong visual close returning users to the floral edit or inquiry builder.

## 10. Three.js / animation plan

Three.js is optional enhancement only:

- dynamically imported after the core page is interactive;
- translucent, low-poly petal sprites / points with extremely low density;
- pointer-events disabled;
- no scroll-jacking, cursor chasing, physics games, or blocking loaders;
- no dependency on WebGL for content or navigation;
- disabled under `prefers-reduced-motion: reduce` and on constrained conditions where appropriate.

CSS/WAAPI motion handles small reveals, hover lift, nav transition, and lightbox transitions.

## 11. Responsive behavior

- Mobile-first from 320px.
- Hero stacks text then image; CTA stays large and thumb-friendly.
- Cards use one column on narrow screens, two on medium, editorial stagger on large desktop.
- Gallery switches from two-column mobile composition to a 12-column desktop mosaic.
- No interaction depends on hover.
- Text line lengths are constrained for readability.

## 12. Accessibility

Target WCAG 2.2 AA:

- semantic landmarks and heading hierarchy;
- skip link;
- keyboard-operable menu, lightbox, and inquiry builder;
- visible `:focus-visible` states;
- 44px minimum important tap targets;
- meaningful alt text;
- decorative SVGs hidden from assistive tech;
- dialog focus management and Escape handling;
- reduced-motion behavior;
- no information conveyed by color alone;
- robust 200% zoom behavior.

## 13. Performance

- Static HTML/CSS/JS, no framework runtime.
- Three.js loaded only as progressive enhancement.
- Responsive Unsplash image URLs with `srcset` and aggressive below-fold lazy loading.
- Hero uses `fetchpriority="high"`.
- Image aspect ratios specified to reduce CLS.
- Minimal JS and no analytics by default.
- Static content and core CTA remain usable if JS/WebGL fail.

Performance targets: LCP < 2.5s, CLS < 0.1, INP < 200ms under reasonable network/device conditions.

## 14. SEO / local discovery

Prototype:

- accurate title/meta description stating that this is a floral design preview;
- canonical GitHub Pages URL;
- Open Graph metadata;
- `Organization` + `WebSite` JSON-LD only, avoiding unverified local-business fields;
- semantic content and descriptive image alt text.

Production after verification:

- `Florist` JSON-LD;
- verified address, phone, hours, service area, social links;
- consistent NAP with the current Google Business Profile;
- current service/product schema only where factual;
- sitemap and canonical production domain.

## 15. Rights / licensing notes

- Stock photos are from free-to-use Unsplash sources listed in `IMAGE_CREDITS.md`.
- They are **not** presented as work made by Infinity Floral Designs.
- No Google Maps contributor photos, competitor photos, Arizona Infinity Floral Designs photos, or review-platform photos are reused.
- Original SVGs in `assets/art/` are created for this project.
- Owner should provide/confirm rights to the final logo, brand name, real portfolio images, reviews, and team/location photography before commercial launch.

## 16. Implementation sequence

1. Commit this plan to the empty repository.
2. Build semantic single-page HTML shell.
3. Implement editorial responsive CSS and design tokens.
4. Add real licensed floral photography and credits.
5. Add original SVG botanical assets.
6. Build accessible navigation, lightbox, and inquiry builder.
7. Add optional Three.js petal field with reduced-motion/static fallback.
8. Add SEO, Open Graph, JSON-LD, favicon, sitemap, robots.
9. Run local validation and headless-browser checks.
10. Add GitHub Pages deployment workflow.
11. Push implementation to `main`.
12. Verify workflow status and published URL where permissions allow.

## 17. Acceptance criteria

### Evidence / truthfulness

- [ ] No invented prices, hours, services, reviews, delivery promises, address, phone, email, or policies.
- [ ] Historical NAP is not presented as current.
- [ ] Stock photos are not implied to be Infinity Floral Designs portfolio work.
- [ ] Photo credits and licensing notes are documented.

### Design

- [ ] Real photography dominates the visual story.
- [ ] Generated botanical art is complementary only.
- [ ] Site feels editorial and brand-specific rather than template-like.
- [ ] No game-like motion or excessive animation.

### Conversion

- [ ] Primary CTA is obvious on mobile and desktop.
- [ ] Inquiry-builder prototype is understandable and honest about its non-submitting state.
- [ ] Production contact/order endpoints have explicit verification gates.

### Accessibility

- [ ] Full keyboard journey works.
- [ ] Focus states are visible.
- [ ] Dialog behavior is accessible.
- [ ] Reduced-motion mode removes ornamental animation.
- [ ] Contrast and zoom behavior are checked.

### Performance / resilience

- [ ] Core content works without JS.
- [ ] Core content works without WebGL.
- [ ] Below-fold images lazy-load.
- [ ] No major CLS from images.
- [ ] Three.js is deferred and non-blocking.

### SEO / deployment

- [ ] Title, description, canonical, OG metadata present.
- [ ] JSON-LD excludes unverified NAP.
- [ ] `robots.txt` and `sitemap.xml` present.
- [ ] GitHub Pages workflow is committed and completes successfully, or any repository-level Pages enablement blocker is documented.

---

## Implementation status — 2026-09-08

The static implementation described above has been completed locally and then visually retuned after the three supplied reference images became available.

- Semantic HTML, responsive CSS, vanilla JS, SVG brand/botanical art, licensed floral photography, lightbox, inquiry builder, deferred Three.js enhancement, metadata, JSON-LD, sitemap, robots, and GitHub Pages workflow are present.
- The retune adds the reference-inspired cream/forest/oxblood palette, a cleaner hero, motivation chip rail, four-card floral browse grid, deep-green promise band, three-panel editorial story, local-information verification rail, and persistent two-action mobile bar.
- JavaScript syntax, HTML parsing, XML parsing, and local HTTP serving checks passed.
- Automated Chromium screenshot/interaction validation could not run in this environment because browser navigation to local/file URLs is blocked by an administrator policy; this is an environment limitation, not a detected site error.
- GitHub publication is currently blocked because the connected GitHub App installation for `Prithiraj` is configured for **selected repositories** and `Prithiraj/Infinity_Floral_Designs` is not in that selected set. The repository itself is public and empty, but write calls return `403 Resource not accessible by integration` until the repository is added to the installation.
- Deployment workflow is ready to publish at `https://prithiraj.github.io/Infinity_Floral_Designs/` once repository access is granted and the files are pushed to `main`.
