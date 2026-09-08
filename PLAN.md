# Infinity Floral Designs — Website Plan

**Status:** implemented design concept and GitHub Pages publishing target.  
**Business-data status:** the supplied Google Maps listing is historical; current operating identity, NAP, hours, products, services, pricing, reviews, policies, and social accounts require owner verification before commercial launch.

The three supplied florist website mockups are used **only as visual direction**. Their example phone numbers, addresses, hours, delivery claims, products, prices, services, reviews, and policies are not treated as facts for Infinity Floral Designs.

## 1. Evidence baseline

### Evidence-backed facts used in the concept

- Business/listing name: **Infinity Floral Designs**.
- Historical location context: **Boynton Beach, Florida**.
- The supplied historical Maps listing points to **3469 W Boynton Beach Blvd #4, Boynton Beach, FL 33436**.
- Research indicates the historical storefront address is now occupied by another business; it is therefore **not presented as a current operating address**.
- A historical florist phone associated with the listing is now used elsewhere, so it is **not published as the current Infinity Floral Designs phone**.
- A separate current Arizona business also uses the name Infinity Floral Designs; none of its products, photos, copy, reviews, policies, services, or social proof are used here.

### Facts deliberately withheld pending verification

- current legal/trading business identity;
- current address, phone, email, and hours;
- ordering method and delivery area;
- same-day delivery or other fulfillment promises;
- weddings, events, sympathy, subscriptions, corporate, or other services;
- product catalog, prices, availability, guarantees, or returns;
- current reviews/ratings;
- owner/team story and years in business;
- social accounts.

### Research sources

- User-supplied Google Maps listing: `https://www.google.com/maps/search/?api=1&query=Infinity+Floral+Designs%2C+3469+W+Boynton+Beach+Blvd+%23+4%2C+Boynton+Beach%2C+FL+33436&query_place_id=ChIJcUgmHC1FK4cR89lYfOEy2vo`
- Historical directory listing: `https://www.showmelocal.com/profile.aspx?bid=8860343`
- Historical florist directory: `https://www.iloveflowers.com/flA2F.htm`

## 2. Audience

Primary audiences are people whose floral purchase begins with an emotional goal rather than botanical knowledge:

1. gift buyers celebrating a milestone or sending care;
2. people expressing love, gratitude, sympathy, comfort, or support;
3. visual shoppers choosing by mood, palette, and arrangement style;
4. local shoppers who value a nearby florist and want a clear contact/order path once current details are verified.

## 3. Conversion goals

### Current published concept

Because live business details are not verified, the preview optimizes for:

- exploring floral inspiration;
- understanding the brand and visual direction;
- viewing the historical listing context without mistaking it for current NAP;
- demonstrating the intended production conversion flow.

### Production version after verification

Recommended hierarchy:

1. **Primary:** Order / Call the shop.
2. **Secondary:** Explore arrangements.
3. **Tertiary:** Get directions / Contact.

Mobile should keep the primary conversion action persistently accessible once the data behind it is verified.

## 4. Creative direction

### Concept: Infinite Botanica

A classic, warm, editorial, premium florist identity with a strong local feel.

Visual translation of the supplied references:

- **Local florist reference:** clear above-the-fold hierarchy, strong local context, compact information strip, and obvious mobile action dock.
- **E-commerce reference:** clean merchandising rhythm, horizontally browsable mobile cards, and easy visual categorization without fake SKUs or pricing.
- **Editorial studio reference:** warm ivory paper surfaces, deep green anchors, claret/blush accents, expressive serif typography, generous whitespace, and image-led storytelling.

The design avoids black-and-gold luxury clichés, beach/turquoise Florida clichés, crowded marketplace layouts, autoplay carousels, and game-like motion.

## 5. Color system

| Token | Value | Use |
|---|---|---|
| Paper | `#FFFDF8` | cards, elevated surfaces |
| Cream | `#F7F1E8` | primary canvas |
| Ink | `#17231C` | primary text |
| Botanical Green | `#173C2A` | brand anchor, actions |
| Deep Green | `#0E2B1D` | header/footer/dark sections |
| Moss | `#536B58` | secondary text/accent |
| Claret | `#7A2432` | editorial emphasis |
| Coral | `#CF6047` | primary CTA/accent |
| Blush | `#D9AAA4` | soft supporting surface |
| Antique Gold | `#B59A68` | fine decorative details |

## 6. Typography

- Display: native editorial serif stack (`Iowan Old Style`, `Baskerville`, `Times New Roman`, serif).
- Functional/body: system sans-serif stack (`Inter`, `system-ui`, `-apple-system`, `Segoe UI`, sans-serif).
- No external font dependency is required, improving privacy and load performance.

## 7. Image strategy

### Current preview

Use real, licensed Unsplash photography as **editorial representation only**, never as evidence of Infinity Floral Designs' actual shop, team, products, or services. The source log lives in [`IMAGE_SOURCES.md`](./IMAGE_SOURCES.md).

### Commercial production

Replace editorial photography with owner-controlled current imagery wherever possible:

- signature arrangement hero;
- current storefront/interior;
- florist/team portraits with consent;
- hands arranging stems;
- wrapping, ribbon, card, cooler, workbench, and handoff details;
- 8–12 representative finished arrangements;
- event work only if the service is confirmed.

No Google reviewer, competitor, Pinterest, scraped social, or ambiguous third-party florist imagery should ship without explicit rights.

## 8. Information architecture

Current single-page concept:

- Home
- Moments
- Inspiration
- Gallery
- Story / process direction
- Boynton Beach listing context
- Final CTA

Production navigation may expand to Arrangements, Occasions, Story, Contact, and only verified service categories.

## 9. Section-by-section layout

### Preview bar

A visible research caveat prevents historical information from being interpreted as live business data.

### Header

Minimal wordmark, concise navigation, strong single action, mobile disclosure menu.

### Hero

Asymmetric editorial composition: high-emotion headline and CTA on the left, large real floral/shop imagery with a smaller overlapping bloom crop on the right. No carousel.

### Historical/local signal band

Surfaces only the historical name, Boynton Beach context, and verification status. It intentionally omits unverified phone, hours, and address-as-current.

### “What do you want the flowers to say?”

Mood-based discovery: Celebrate, Love, Comfort, Just Because, and a bolder visual direction. These are editorial paths, not claimed services/products.

### Floral direction shelf

Four image cards borrow the clarity of e-commerce but are explicitly labeled “Visual direction.” No invented prices, product names, SKUs, availability, or same-day claims.

### Editorial statement

A deep botanical-green pause creates rhythm and reinforces the non-marketplace positioning.

### Process / story direction

Shows how a production version should feature the real people and making process. The current copy does not invent a business history.

### Gallery

Responsive editorial mosaic using real licensed flower photography. No autoplay slideshow.

### Boynton Beach context

Explains the historical listing, old storefront address, current verification gap, and evidence policy. The supplied Google Maps listing is linked directly.

### Final CTA

Invites exploration of the concept and the plan rather than pretending the unverified business is ready to take orders.

## 10. Three.js / animation plan

Three.js is permitted only as a subtle decorative enhancement.

Implemented behavior:

- dynamically imported on desktop only;
- low-opacity botanical/petal forms behind the hero;
- never covers or replaces the actual floral photography;
- disabled for reduced motion, smaller screens, or data-saving connections;
- static layout remains complete if WebGL, JavaScript, or CDN loading fails.

Other motion is limited to reveal transitions, subtle image scale on hover, and short button transitions. No scroll-jacking, physics interactions, cursor gimmicks, or game-like behavior.

## 11. Responsive behavior

Mobile-first priorities:

- single-column hero with high-impact image;
- accessible disclosure navigation;
- 44px+ touch targets;
- horizontal swipe shelf for floral direction cards;
- simple mobile gallery rhythm;
- fixed three-action concept dock;
- no hover-dependent information.

Tablet moves to two-column cards. Desktop uses asymmetric editorial grids and generous whitespace.

## 12. Accessibility

Target: WCAG 2.2 AA.

- semantic landmarks and one logical H1;
- skip-to-content link;
- keyboard-operable navigation;
- visible `:focus-visible` states;
- descriptive image alt text;
- empty/decorative treatment for non-content visuals;
- no information communicated by color alone;
- no auto-rotating content;
- reduced-motion support;
- static/usable no-JavaScript fallback;
- mobile controls sized for touch.

## 13. Performance

The implementation is a static document with no framework or build step.

- critical CSS is inline;
- system fonts avoid font downloads;
- real images are served by Unsplash with responsive/cropped URLs;
- below-the-fold images lazy-load;
- Three.js loads dynamically only when enhancement conditions are met;
- no analytics, tag manager, UI library, or unnecessary runtime dependency is included.

Production target: LCP ≤ 2.5s, CLS ≤ 0.10, INP ≤ 200ms on representative mobile conditions.

## 14. SEO / local discovery

Because current NAP is unresolved, the concept deliberately uses:

- `noindex, nofollow`;
- a design-concept title/meta description;
- canonical and Open Graph tags for the GitHub Pages URL;
- `WebSite` JSON-LD only, not a false current `Florist` LocalBusiness entity.

After verification, production should add exact current NAP, `Florist`/`LocalBusiness` JSON-LD, verified hours, verified `sameAs` profiles, service-area copy, local landing content, and a production canonical domain.

## 15. Rights / licensing notes

- Unsplash imagery is documented in `IMAGE_SOURCES.md` and is editorial representation, not business evidence.
- Production should prioritize owner-controlled or commissioned commercial photography.
- Obtain appropriate consent for identifiable customers, employees, event guests, and private venues.
- Do not ship Google Maps reviewer photos, competitor photography, or scraped social imagery without rights.
- Supplied mockups are reference images only and are not included as site assets.

## 16. Implementation sequence

1. Preserve evidence guardrails and approval direction in this document.
2. Build semantic, mobile-first page structure.
3. Establish editorial color/type/spacing system.
4. Integrate real licensed floral photography.
5. Add mood discovery, gallery, story/process, and historical-context sections.
6. Add accessible navigation, focus states, reduced motion, and static fallback.
7. Add optional Three.js petal enhancement.
8. Add SEO/Open Graph metadata appropriate to a design concept.
9. Validate headings, anchors, alt text, responsive behavior, and JavaScript fallback.
10. Publish to GitHub Pages.
11. Before commercial launch, replace/verify all owner-specific data and production photography.

## 17. Acceptance criteria

- [x] Design plan is documented in Markdown.
- [x] Supplied screenshots influence visual direction only.
- [x] No invented prices, services, hours, products, reviews, guarantees, policies, or social accounts are presented as facts.
- [x] Historical address is clearly labeled as historical, not current.
- [x] Arizona Infinity Floral Designs content is not used.
- [x] Real licensed floral photography is used throughout the concept.
- [x] Demo/editorial imagery is clearly identified for replacement before commercial launch.
- [x] Design is mobile-first and responsive.
- [x] Keyboard navigation and visible focus states are supported.
- [x] Meaningful alt text is present.
- [x] Reduced-motion behavior is implemented.
- [x] Important content works without JavaScript/WebGL.
- [x] Three.js is decorative and lazy/dynamic rather than the core interface.
- [x] SEO title, description, canonical, Open Graph, and safe JSON-LD are included.
- [x] Static hosting requires no build dependencies.
- [ ] Current owner/business identity, NAP, hours, services, products, ordering flow, reviews, and social links are verified before commercial launch.
- [ ] Owner-controlled production photography replaces editorial imagery where available.
- [ ] `noindex` is removed only when the real operating business is verified and ready to launch.
