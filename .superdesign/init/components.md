# Shared UI primitives

The landing page is a static HTML/CSS site. It has no component framework or shared
component directory; reusable primitives are class-based and defined in
`styles.css`.

## Button

- Source: `styles.css`
- Variants: `.button`, `.button-small`, `.button-large`, `.button-full`,
  `.button-white`
- Used for every primary and secondary CTA.

```css
.button{display:inline-flex;justify-content:center;align-items:center;gap:12px;border-radius:14px;background:var(--green);color:#fff;font-weight:800;box-shadow:0 12px 26px rgba(58,170,52,.18);transition:.2s ease}
.button:hover{background:var(--green-dark);transform:translateY(-2px);box-shadow:0 16px 30px rgba(58,170,52,.24)}
.button-small{padding:11px 18px;border-radius:999px}
.button-large{padding:17px 25px;font-size:16px}
.button-full{width:100%}
.button-white{color:var(--green);background:#fff;box-shadow:none}
.button-white:hover{background:#f2fff1}
```

## Container

- Source: `styles.css`
- Centers content at a maximum width of 1180px.

```css
.container{width:min(1180px,calc(100% - 48px));margin:0 auto}
@media(max-width:640px){.container{width:min(100% - 32px,1180px)}}
```

## Eyebrow

- Source: `styles.css`
- Small uppercase green label used above section headings.

```css
.eyebrow{display:inline-flex;align-items:center;gap:8px;margin:0 0 20px;color:var(--green);font-size:12px;font-weight:800;letter-spacing:.12em;text-transform:uppercase}
```

## Feature card

- Source: `styles.css`
- White bordered card with 24px radius and optional dark variant.

```css
.feature-card{position:relative;min-height:260px;padding:28px;border:1px solid var(--line);border-radius:var(--radius);background:#fff;overflow:hidden}
.feature-card:hover{border-color:#acd4a6}
.dark-card{border-color:#2b3a2e;color:#fff;background:#1d2920}
```

## FAQ disclosure

- Source: `index.html`, `styles.css`
- Native `details`/`summary` control with plus/minus indicator.

```html
<details>
  <summary>Question</summary>
  <p>Answer</p>
</details>
```

```css
.faq-list details{padding:18px 21px;border:1px solid var(--line);border-radius:14px;background:#fff}
.faq-list summary{cursor:pointer;font-size:15px;font-weight:800;list-style:none}
.faq-list summary::after{float:right;color:var(--green);content:"+";font-size:20px}
.faq-list details[open] summary::after{content:"−"}
```
