# Extractable components

The static page has no framework components. The following repeated UI patterns
can be extracted as Superdesign draft components.

## SiteHeader

- Source: `index.html` (`header.site-header`)
- Category: layout
- Description: Sticky WhatsCart brand navigation with section anchors and CTA.
- Extractable props: `activeItem`, `ctaHref`
- Hardcoded: WhatsCart logo, link labels, button styles.

## SiteFooter

- Source: `index.html` (`footer.site-footer`)
- Category: layout
- Description: Brand statement, navigation, and copyright.
- Extractable props: none
- Hardcoded: logo, navigation labels, copyright, dark surface.

## PrimaryButton

- Source: `styles.css` (`.button` variants)
- Category: basic
- Description: Green conversion CTA with small, large, full-width, and white variants.
- Extractable props: `href`, `label`, `variant`
- Hardcoded: radius, shadow, hover lift.

## SectionHeading

- Source: `index.html` (`.section-heading`)
- Category: basic
- Description: Eyebrow, large title, and optional supporting paragraph.
- Extractable props: `eyebrow`, `title`, `description`, `align`
- Hardcoded: typography scale and spacing.

## FeatureCard

- Source: `index.html` (`article.feature-card`)
- Category: basic
- Description: Capability card with icon, title, explanation, and optional visual.
- Extractable props: `title`, `description`, `variant`
- Hardcoded: 24px radius, border, green accent.

## FAQItem

- Source: `index.html` (`details`)
- Category: basic
- Description: Native accessible expandable question and answer.
- Extractable props: `question`, `answer`, `open`
- Hardcoded: plus/minus affordance and border treatment.
