# WhatsCart landing page design system

## Product context

WhatsCart is a mobile-first storefront and lightweight commerce workspace for
small Indian businesses that already sell mainly through WhatsApp and promote
products through Instagram and Facebook.

It is not positioned as “another ecommerce platform.” Its job is to help a
WhatsApp-first seller graduate from scattered posts, repeated photo messages,
and an in-app catalog into one owned, shareable, searchable storefront without
adopting a high-cost or high-complexity stack.

Primary audience:

- Home bakers
- Garment and boutique sellers
- Handmade and handicraft businesses
- Solo founders who manage their business from a phone
- Sellers who currently juggle WhatsApp, Instagram, and Facebook

Primary job to be done:

> Turn the products already being sold in chats and social posts into a branded
> online store, then make every share, customer visit, and order easier to manage.

## Evidence-backed product capabilities

The source app and live tenant storefront prove the following:

1. Five-stage store setup: business category, business details, brand identity,
   review and launch, store ready.
2. A dedicated tenant URL in the form `business-name.whatscart.in`.
3. Business branding: logo, theme color/palette, business description, service
   region, address, social links, featured products, and shipping banner.
4. Products with images, prices, descriptions, stock state, categories, sizes,
   audience, variants, product-specific options, and customizations.
5. Business-aware product inputs for garments, home bakeries, and handicrafts.
6. Public storefront with branded navigation, hero product, search, filter,
   sorting, categories, product grid, footer, and cart.
7. Curated collections with their own public share URL; useful for Diwali edits,
   wedding gifts, birthday gifts, ready-to-ship products, and similar buying
   moments.
8. UTM-tagged sharing to WhatsApp, Instagram, Facebook, X, copied link, and the
   native share sheet.
9. Structured cart, checkout, customer/address/location capture, order IDs,
   order status, and direct WhatsApp conversation.
10. Mobile dashboard with revenue, visits, orders, best sellers, top customers,
    revenue trend, and traffic-source attribution.
11. Search/discovery infrastructure on live stores: canonical URLs, title and
    description metadata, Open Graph and Twitter cards, `robots.txt`, XML
    sitemap, human-readable sitemap, product/store/collection share images, and
    Schema.org `OnlineStore`, `Offer`, and product structured data.
12. Public live proof at `https://loops-by-ak.whatscart.in/`.
13. User-confirmed launch metrics for public use: 3+ businesses onboarded,
    60+ products published, and 1,000+ storefront visits.

Do not describe “GEO/LLMO” as magic ranking or guaranteed AI discovery. Explain
the concrete implementation: structured product/store data, crawlable pages,
canonical metadata, sitemaps, and machine-readable Schema.org markup that helps
search engines and AI systems understand the store.

## Positioning

Core category statement:

> The online store built for businesses that already sell on WhatsApp.

Supporting promise:

> One link for every product, post, collection, customer, and order.

Proof-led transformation:

- Before: products scattered across WhatsApp, Instagram posts, Facebook posts,
  photo galleries, and repeated customer replies.
- After: one branded storefront, curated links for each buying moment,
  structured orders, and clear insight into what brought the customer.

The page must communicate that WhatsCart complements WhatsApp rather than asking
the seller to replace it.

## Comparison framework

The comparison must be respectful and precise. WhatsCart is the best fit for a
specific segment, not universally “better” than every alternative.

### WhatsApp Business catalog

- Strength: free, familiar, in-chat browsing; supports up to 500 items,
  collections, and sharing individual items or collections.
- Constraint relevant to the audience: it remains an in-app catalog, not an
  owned, crawlable business website with a branded tenant URL, public search/AI
  metadata, cross-channel storefront attribution, or a WhatsCart-style revenue
  and traffic dashboard.
- Best for: a simple product list inside existing WhatsApp conversations.

Official reference:
`https://whatsappbusiness.com/resources/resource-library/whatsapp-business-app-resources-whatsapp-business-catalog/`

### WhatsCart

- Strength: public branded storefront, five-stage setup, curated public
  collection pages, structured orders, direct WhatsApp connection, UTM
  attribution, store analytics, and automatic technical discoverability.
- Price used by the current landing page: three months free, then ₹99/month.
- Best for: small WhatsApp-first sellers who need more than an in-app catalog
  without adopting a full ecommerce stack.

### Shopify

- Strength: mature full commerce platform with themes, checkout, payments,
  multichannel commerce, large app ecosystem, advanced reporting, and global
  operations.
- Tradeoff for this audience: materially more capability, setup surface, and
  cost than a lightweight WhatsApp-first seller may need.
- Current India Basic price (30 July 2026): ₹1,499/month billed yearly or
  ₹1,994 month-to-month, after the introductory offer. Prices must be written
  with “as of July 2026” or linked to the live pricing page.
- Best for: businesses that need a broad ecommerce operating system, online
  checkout, apps, and deeper scale.

Official reference: `https://www.shopify.com/in/pricing`

Recommended comparison rows:

- Where customers browse
- Branded public website
- Curated collection links
- WhatsApp-first conversation
- Search and AI discoverability foundation
- Cross-channel traffic attribution
- Structured order tracking
- Online payment checkout
- Setup and ongoing complexity
- Starting ongoing price
- Best-fit business

## Page architecture

The redesign keeps the current one-page conversion flow but makes it far more
useful and demonstrative:

1. Sticky header
   - Logo
   - “See a live store”
   - “Why WhatsCart”
   - “Compare”
   - “Pricing”
   - Login
   - Primary start CTA

2. Hero: problem, promise, and proof
   - Eyebrow: “Built for WhatsApp-first businesses”
   - Headline: “Your WhatsApp business deserves a place of its own.”
   - Lede: move from scattered posts and repeated replies to one searchable store.
   - Primary CTA: “Create my store”
   - Secondary CTA: “Explore a live store”
   - Visible “5 stages • 3 months free • ₹99/month after” proof.
   - Use a real-store-style browser/phone preview based on Loops_by_ak rather
     than abstract placeholder products.

3. Pain-to-outcome strip
   - A visual “Scattered → together” journey connecting WhatsApp, Instagram,
     Facebook, storefront, collections, orders, and analytics.

4. “Everything in one place” product walkthrough
   - Storefront
   - Products and variants
   - Collections
   - Orders
   - Analytics
   - Discoverability
   - Use screenshots/micro-UI, not generic icon-only cards.

5. Collections feature spotlight
   - Show a seller selecting products and producing a public collection link.
   - Examples: Diwali Collection, Wedding Gifts, Birthday Gifts, Ready to Ship.
   - Show the recipient-facing collection page beside the editor.
   - CTA: “Build a collection in minutes.”

6. WhatsApp catalog vs WhatsCart vs Shopify comparison
   - Lead with “Choose the right next step for your business.”
   - Visually highlight WhatsCart as “Best for WhatsApp-first sellers.”
   - Keep honest strengths for both alternatives.
   - Price and feature notes include qualification where needed.

7. Five-stage setup
   - Use the actual stages from the product.
   - Make “within five stages” credible with named steps.

8. SEO + GEO/LLMO explained in plain language
   - “Your store is built to be understood.”
   - Show crawlable tenant URL, sitemap, product metadata, share previews,
     structured Schema.org data, and traffic sources.
   - Avoid ranking promises.

9. Analytics payoff
   - Revenue, views, orders, best sellers, customers, trend, traffic source.
   - Connect source tags to Instagram/Facebook/WhatsApp shares.

10. Live-store proof
    - Present Loops_by_ak as an actual storefront example.
    - CTA to open `https://loops-by-ak.whatscart.in/`.

11. Pricing
    - Three months free.
    - ₹99/month after.
    - No hidden transaction fee claim may only be used if confirmed by the
      product owner; keep the current claim but do not make it more prominent
      until reconfirmed.

12. FAQ
    - Do I need a website or computer?
    - Is WhatsCart replacing WhatsApp?
    - What is different from a WhatsApp catalog?
    - Can people find my products on Google or AI tools?
    - How do payments work?
    - Can I use my own domain?
    - Is Shopify a better fit for me?

13. Final CTA
    - Reiterate the WhatsApp-first category.
    - Primary CTA to the app.
    - Secondary live-store link.

## Visual language

This is a controlled redesign of the existing system.

Keep:

- WhatsCart green `#3AAA34` and darker `#247D28`.
- Warm green-tinted background `#F4F8F3`.
- Near-black `#171717` and dark green-black surfaces.
- Inter/system sans typography.
- Large tightly tracked headlines.
- Rounded 14px buttons and 24px cards.
- Soft green-tinted shadows.
- Calm white space and practical mobile-first behavior.
- Existing app icon and WhatsCart wordmark treatment.

Improve:

- Higher information density in the middle of the page.
- Stronger real-product demonstrations.
- More obvious navigation to the comparison and live store.
- Compact annotations, badges, connector lines, and UI diagrams that explain
  flows without becoming decorative clutter.
- More editorial variety: alternating asymmetric product walkthroughs rather
  than one large field of similar feature cards.
- Stronger proof near each claim.

Do not introduce:

- New fonts.
- Purple, neon, glassmorphism-heavy, or unrelated SaaS styling.
- Fake customer counts, testimonials, revenue figures, ratings, logos, or
  conversion claims. The user-confirmed 3+ businesses, 60+ products, and
  1,000+ visits are approved proof metrics and may be shown.
- Stock-photo founders or generic AI people.
- Guaranteed SEO, Google ranking, or AI recommendation claims.

## Interaction and responsive behavior

- Maintain accessible semantic HTML and visible focus states.
- Header remains sticky; mobile header uses a compact CTA plus menu or a short
  anchor set.
- Buttons have clear hover/focus/active states and no layout shift.
- Comparison table becomes stacked comparison cards on narrow screens while
  preserving every row.
- Product walkthroughs become one-column with the visual before or immediately
  after its explanation.
- Collection editor/storefront demo becomes a swipeable or vertically stacked
  two-panel story on mobile.
- FAQ stays native `details`/`summary`.
- Respect `prefers-reduced-motion`.
- Keep important CTA targets at least 44px high.

## Content voice

- Indian English, simple and direct.
- Prefer “store”, “collection”, “share”, “order”, “customer”, and “WhatsApp”
  over ecommerce jargon.
- Explain technical discoverability in outcomes first, implementation second.
- Use short concrete examples from garments, bakeries, and handmade sellers.
- Lead with the user’s current reality, not abstract digital transformation.

## Hard design constraints

Use ONLY the fonts, colors, spacing, and component styles defined in this design
system and the supplied `styles.css`. Do not introduce fonts, colors, gradients,
or visual styles not defined here. Keep Inter/system sans, the green/white/
near-black palette, rounded cards, and practical product-demo aesthetic.
