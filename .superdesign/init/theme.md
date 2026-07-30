# Theme

## Compact token summary

### Color

| Token | Value | Use |
|---|---|---|
| `--green` | `#3aaa34` | Brand, CTAs, emphasis |
| `--green-dark` | `#247d28` | CTA hover, strong emphasis |
| `--ink` | `#171717` | Primary text, dark surfaces |
| `--muted` | `#64748b` | Supporting text |
| `--soft` | `#f4f8f3` | Alternating section surface |
| `--line` | `#dfe8df` | Borders and dividers |
| `--white` | `#ffffff` | Cards and inverse text |

Additional surfaces use `#fbfdfb` and the dark card/footer family
`#1d2920` / `#162018`.

### Type

- Family: `Inter`, then system UI fallbacks.
- Hero: `clamp(46px, 6vw, 78px)`, 1.03 line-height, `-0.07em`.
- Section title: `clamp(36px, 4vw, 53px)`, 1.08 line-height.
- Body: 14–18px, 1.5–1.7 line-height.
- Labels: 10–12px, uppercase, bold, tracked.
- Voice: direct, plain-language, confident, locally relevant.

### Layout and spacing

- Content width: 1180px with 24px desktop gutters and 16px mobile gutters.
- Section rhythm: 120px desktop, 78px mobile.
- Major layouts: two-column hero; 3-column feature grid; 4-step process;
  two-column pricing and FAQ.
- Main card radius: `--radius: 24px`; button radius 14px; pill radius 999px.

### Shadows and motion

- Soft green-tinted elevation for conversion cards.
- Buttons lift 2px on hover.
- Store preview rotates from 2deg to 0deg on hover.
- Header uses translucent white plus 16px backdrop blur.

### Breakpoints

- `900px`: major two-column layouts collapse; feature grid becomes two columns.
- `640px`: navigation links hide; feature grid becomes one column; spacing and
  type reduce; CTAs become full-width.

## Raw source files

The complete unmodified source is deliberately kept in its canonical files and
passed directly to every design call:

- `styles.css` — full global stylesheet and all tokens (15,542 bytes, one
  minified source line).
- `index.html` — full page markup and actual content.

The root token block from the raw stylesheet is:

```css
:root{--green:#3aaa34;--green-dark:#247d28;--ink:#171717;--muted:#64748b;--soft:#f4f8f3;--line:#dfe8df;--white:#fff;--radius:24px}
```

There is no Tailwind configuration, theme provider, CSS module, dark theme, or
JavaScript-driven token layer in this project.
