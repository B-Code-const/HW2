# Stars & Stripes Canvas 🇺🇸

**A 4th of July Interactive Storybook — HTML & CSS Only**

## Project Structure

```
HW2/
├── index.html              # Main storybook page (3 chapters + cover)
├── stars-and-stripes.css   # All styles, animations, and interactions
├── assets/
│   ├── images/             # Patriotic images and SVGs
│   └── fonts/              # Custom fonts (Google Fonts CDN used)
└── README.md
```

## Pages / Chapters

| Page | ID | Theme |
|------|----|-------|
| Cover | `#cover` | Animated landing with fireworks and title |
| Freedom's Dawn | `#page-dawn` | Rising sun, Declaration cards, interactive flag |
| Patriot's Plaza | `#page-plaza` | Fireworks launcher, sparkler parade, Liberty Bell |
| United We Stand | `#page-united` | Eagle reveal, pillars of freedom, pledge quote |

## CSS Techniques Used

- **`:target`** — CSS-only multi-page navigation
- **`:checked`** — Fireworks launcher, flag wave toggle, eagle wing flap
- **`:hover` / `:focus`** — Card lifts, bell ring, nav underlines, button states
- **`@keyframes`** — 16+ animations (sunrise, fireworks, confetti, flag wave, sparkle, float, etc.)
- **CSS Grid + Flexbox** — All layouts, responsive at every breakpoint
- **CSS Variables** — Full patriotic palette + spacing scale
- **`::before` / `::after`** — Decorative stripes, nav underlines, bell crack detail
- **`prefers-reduced-motion`** — All animations disabled for accessibility
- **`prefers-contrast: high`** — Enhanced borders and text contrast

## Color Palette

| Variable | Hex | Usage |
|----------|-----|-------|
| `--patriot-blue` | `#002868` | Header, hero backgrounds |
| `--liberty-red` | `#BF0A30` | Stripes, buttons, accents |
| `--star-gold` | `#FFD700` | Stars, headings, highlights |
| `--cannon-smoke` | `#1A1A2E` | Page background |
| `--parchment` | `#F5F0E8` | Body text |

## Interactivity

All interactions are pure CSS — **zero JavaScript**:

- **Flag Wave** — Click the flag on Freedom's Dawn to toggle active wave animation
- **Fireworks Launch** — Click the LAUNCH button on Patriot's Plaza to trigger burst animations
- **Eagle Soar** — Click the eagle on United We Stand to flap its wings
- **Liberty Bell** — Hover/focus the bell to ring it
- **Card Hover** — All content cards lift and glow on hover/focus

## Accessibility

- Semantic HTML5 (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<nav>`, `<blockquote>`)
- `aria-label` on all interactive elements and landmark regions
- `aria-hidden="true"` on all decorative elements
- `prefers-reduced-motion` media query disables all animations
- `prefers-contrast: high` media query improves contrast
- Keyboard navigation fully supported (`:focus-visible` states)
- `role="list"` on `<ul>` elements

## Team

| Name | GitHub |
|------|--------|
| Member 1 | @username1 |
| Member 2 | @username2 |

## Deployment

Live at: [codd.cs.gsu.edu](#) *(update with actual URL)*
