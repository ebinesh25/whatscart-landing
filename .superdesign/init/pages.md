# Page dependency trees

## `/` — WhatsCart landing page

Entry: `index.html`

Dependencies:

- `index.html`
  - `styles.css`
  - `assets/whatscart-app-icon.png`

The page has no JavaScript and no nested component imports. Every rendered branch
is present in `index.html`. Responsive behavior is entirely in the two media
queries at the end of `styles.css`.

### Section tree

- Sticky header
- Hero with storefront browser mockup and order/growth proof chips
- Three-part trust strip
- Feature bento grid
- Four-step setup sequence
- Pricing story and launch-offer card
- FAQ disclosures
- Full-bleed final CTA
- Footer
