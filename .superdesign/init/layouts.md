# Shared layouts

This is a one-page static site. The shared shell consists of the sticky header,
centered `.container` wrapper, and footer below.

## SiteHeader

- Source: `index.html`
- Sticky primary navigation with brand, section anchors, login, and primary CTA.

```html
<header class="site-header">
  <nav class="nav container" aria-label="Primary navigation">
    <a class="brand" href="#top" aria-label="WhatsCart home">
      <span class="brand-mark"><img src="./assets/whatscart-app-icon.png" alt="" /></span>
      <span>WhatsCart</span>
    </a>
    <div class="nav-links">
      <a href="#features">Features</a>
      <a href="#how-it-works">How it works</a>
      <a href="#pricing">Pricing</a>
    </div>
    <div class="nav-actions">
      <a class="login-link" href="https://app.whatscart.in/">Log in</a>
      <a class="button button-small" href="https://app.whatscart.in/">Start selling</a>
    </div>
  </nav>
</header>
```

## Main page shell

- Source: `index.html`
- All page sections are wrapped by `<main id="top">`; alternating surfaces use
  `.section`, `.section-soft`, and full-bleed CTA backgrounds.

```html
<main id="top">
  <section class="hero section-soft">...</section>
  <section class="trust-strip">...</section>
  <section id="features" class="section features-section">...</section>
  <section id="how-it-works" class="section section-soft steps-section">...</section>
  <section id="pricing" class="section pricing-section">...</section>
  <section class="section faq-section">...</section>
  <section class="final-cta">...</section>
</main>
```

## SiteFooter

- Source: `index.html`
- Brand, value statement, short navigation, and copyright.

```html
<footer class="site-footer">
  <div class="container footer-inner">
    <a class="brand footer-brand" href="#top">
      <span class="brand-mark"><img src="./assets/whatscart-app-icon.png" alt="" /></span>
      <span>WhatsCart</span>
    </a>
    <p>Helping local businesses build their digital storefront.</p>
    <div>
      <a href="https://app.whatscart.in/">Owner login</a>
      <a href="#pricing">Pricing</a>
      <a href="#features">Features</a>
    </div>
    <small>© 2026 WhatsCart India. Built for local businesses.</small>
  </div>
</footer>
```
