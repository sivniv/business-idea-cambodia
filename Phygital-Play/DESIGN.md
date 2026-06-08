---
version: alpha
name: Cat AI
description: Premium dark-themed investor pitch for a Phygital Virtual Pet Ecosystem in Phnom Penh, Cambodia.
colors:
  primary: "#f59e0b"
  secondary: "#94a3b8"
  tertiary: "#8b5cf6"
  neutral: "#0a0a0f"
  surface: "#12121a"
  surface-hover: "#1a1a26"
  on-primary: "#0a0a0f"
  on-neutral: "#f1f5f9"
  on-surface: "#e2e8f0"
  muted: "#64748b"
  border: "rgba(245,158,11,0.12)"
  success: "#10b981"
  error: "#ef4444"
typography:
  h1:
    fontFamily: Outfit
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.02em"
  h2:
    fontFamily: Outfit
    fontSize: 32px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.5px"
  h3:
    fontFamily: Outfit
    fontSize: 1rem
    fontWeight: 600
    lineHeight: 1.3
  body-md:
    fontFamily: Rubik
    fontSize: 1rem
    lineHeight: 1.65
  body-sm:
    fontFamily: Rubik
    fontSize: 0.875rem
    lineHeight: 1.6
  label-caps:
    fontFamily: Outfit
    fontSize: 0.75rem
    fontWeight: 600
    letterSpacing: "0.08em"
    textTransform: uppercase
rounded:
  sm: 8px
  md: 14px
  lg: 20px
  full: 9999px
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 48px
  section: 80px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.sm}"
    padding: 13px 28px
    fontSize: 0.875rem
    fontWeight: 600
    fontFamily: Rubik
  button-primary-hover:
    backgroundColor: "#d97706"
    textColor: "{colors.on-primary}"
  button-outline:
    backgroundColor: transparent
    textColor: "{colors.on-neutral}"
    borderColor: "{colors.border}"
    rounded: "{rounded.sm}"
    padding: 13px 28px
    fontSize: 0.875rem
    fontWeight: 500
  button-outline-hover:
    borderColor: "{colors.primary}"
    textColor: "{colors.primary}"
  card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    borderColor: "{colors.border}"
    rounded: "{rounded.md}"
    padding: 24px
  card-hover:
    borderColor: "rgba(245,158,11,0.3)"
    backgroundColor: "{colors.surface-hover}"
  nav-link:
    textColor: "{colors.muted}"
    fontSize: 0.8125rem
    fontWeight: 500
  nav-link-hover:
    textColor: "{colors.primary}"
  badge:
    backgroundColor: "rgba(245,158,11,0.08)"
    textColor: "{colors.primary}"
    borderColor: "{colors.border}"
    rounded: "{rounded.full}"
    padding: 6px 14px
    fontSize: 0.75rem
  quote-block:
    borderLeftColor: "{colors.primary}"
    backgroundColor: "{colors.surface}"
    padding: 16px 20px
  highlight-box:
    backgroundColor: "rgba(245,158,11,0.06)"
    borderColor: "{colors.border}"
    rounded: "{rounded.md}"
    padding: 32px
  input:
    backgroundColor: "rgba(255,255,255,0.04)"
    textColor: "{colors.on-neutral}"
    borderColor: "{colors.border}"
    rounded: "{rounded.sm}"
    padding: 12px 14px
    fontSize: 0.875rem
  submit-btn:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.sm}"
    padding: 14px
    fontSize: 1rem
    fontWeight: 700
---

## Overview

Cat AI is a premium, dark-themed investor pitch website for a Phygital (Physical + Digital) virtual pet ecosystem in Phnom Penh, Cambodia. The visual identity combines **playful warmth** (gold/amber accents) with **serious investor credibility** (dark slate backgrounds, clean typography, data-rich layout). The brand evokes a feeling of "cute meets professional" — approachable enough for Gen Z consumers, but structured enough for institutional investors.

## Colors

- **Primary (#f59e0b):** Warm amber-gold. The sole accent color for CTAs, highlights, key metrics, and brand moments. Use sparingly to preserve its signal.
- **Neutral (#0a0a0f):** Near-black background. Creates a premium, infinite-canvas feel.
- **Surface (#12121a):** Raised card and container backgrounds. One step up from neutral.
- **Surface-hover (#1a1a26):** Card hover state — subtle brightening for interactivity.
- **Muted (#64748b):** Secondary text, metadata, supporting copy.
- **Tertiary (#8b5cf6):** Purple accent for secondary brand elements (v2 roadmap phase, secondary CTAs).
- **Success/Error (#10b981/#ef4444):** Used in simulation results and risk analysis. Semantic, not decorative.

### Color Usage Rules

- Gold on dark = interaction. Never use gold on light backgrounds.
- Secondary text must meet WCAG AA (4.5:1) against neutral and surface backgrounds.
- Semantic colors (success/error) must always be paired with text or icon, never color alone.

## Typography

**Outfit** (Google Font) for all headings — bold, geometric, modern. **Rubik** (Google Font) for body text — slightly rounded, highly readable at any size.

| Style | Font | Size | Weight | Line Height |
|-------|------|------|--------|-------------|
| h1 | Outfit | clamp(36px,5vw,64px) | 700 | 1.1 |
| h2 | Outfit | clamp(24px,3.2vw,38px) | 700 | 1.2 |
| h3 | Outfit | 1rem | 600 | 1.3 |
| body | Rubik | 1rem | 400 | 1.65 |
| body-sm | Rubik | 0.875rem | 400 | 1.6 |
| caps | Outfit | 0.75rem | 600 | — |

- Body text uses Rubik at 16px minimum (prevents iOS auto-zoom on forms).
- All-caps labels use Outfit with 0.08em letter-spacing.
- Font import: `@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;500;600;700;800&family=Rubik:wght@300;400;500;600;700&display=swap');`

## Layout & Spacing

- **Max content width:** 1100px (container centered).
- **Spacing scale:** 4px baseline. md (16px) for intra-component gaps, lg (24px) for inter-component gaps, xl (48px) for section padding.
- **Section padding:** 80px top/bottom (reduced to 50px on mobile).
- **Grid:** 2-col, 3-col, 4-col responsive grids for content cards. Collapse to 1-col at 768px.
- **Navigation:** Fixed top bar at 60px height. Blur background (backdrop-filter: blur(20px)). Bottom border at 1px border color.

### Responsive Breakpoints

- **Mobile:** 375px (default) — single column, compact spacing
- **Tablet:** 768px — 2-column grids
- **Desktop:** 1024px — full layout
- **Wide:** 1440px — max container width kicks in

## Elevation

- Cards have no box-shadow by default. Elevation is communicated via border color and hover background change.
- Navigation bar uses backdrop-filter blur for depth.
- Section backgrounds alternate between neutral (#0a0a0f) and a very subtle warm tint (rgba(245,158,11,0.015)) for visual rhythm.

## Shapes

- **sm (8px):** Buttons, inputs, badges, small interactive elements.
- **md (14px):** Cards, highlight boxes, quote blocks, form containers.
- **full (9999px):** Pill badges, tag labels (not used for avatars — no avatars in this design).

## Components

### button-primary
The only high-emphasis action per page section. Gold background, dark text. Shows hover state via darker gold (#d97706) and translateY(-1px) lift.

### button-outline
Low-emphasis action. Transparent background with border. Hover: border turns gold, text turns gold.

### card
Default content surface. Hover: border becomes more visible (rgba(245,158,11,0.3)), background lightens slightly, card lifts 2px.

### nav-link
Top navigation items. Caps-style text in muted color. Hover: turns gold. Active/current: gold.

### badge
Small label for section tags and status indicators. Subtle gold background with gold text and rounded pill shape.

### quote-block
Left-accented block for testimonials and simulation quotes. 3px gold left border. Italic body text with attribution below.

### highlight-box
Full-width callout for key findings and simulation verdicts. Subtle gradient background (gold to purple at low opacity). Used once per section.

### input
Form fields. Dark background, light text, subtle border. Focus state: border turns gold. Placeholder: muted color.

## Do's and Don'ts

- **Do** use token references (`{colors.primary}`) over literal hex values.
- **Do** keep the dark background as the foundation — never introduce a white page.
- **Do** use gold sparingly — one accent per section maximum.
- **Don't** use emoji as structural icons in navigation or system controls. Use SVG icons from Lucide or inline SVG data.
- **Don't** nest component variants. `button-primary-hover` is a sibling, not a child.
- **Don't** introduce colors outside the palette — extend the palette first.
- **Don't** use box-shadows for elevation — use border + background changes instead.
- **Don't** exceed 5 items in bottom navigation (not applicable — this is a single-page scroll).
