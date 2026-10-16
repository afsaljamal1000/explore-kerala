---
name: Terra Nova
colors:
  surface: '#fcf9f3'
  surface-dim: '#dcdad4'
  surface-bright: '#fcf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ed'
  surface-container: '#f0eee8'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e5e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#56423d'
  inverse-surface: '#31312d'
  inverse-on-surface: '#f3f0ea'
  outline: '#8a726c'
  outline-variant: '#ddc0ba'
  surface-tint: '#a04028'
  primary: '#9d3d26'
  on-primary: '#ffffff'
  primary-container: '#bd553b'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4a2'
  secondary: '#166873'
  on-secondary: '#ffffff'
  secondary-container: '#a7eefb'
  on-secondary-container: '#1f6e79'
  tertiary: '#7b542b'
  on-tertiary: '#ffffff'
  tertiary-container: '#966c41'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad2'
  primary-fixed-dim: '#ffb4a2'
  on-primary-fixed: '#3c0700'
  on-primary-fixed-variant: '#802913'
  secondary-fixed: '#a7eefb'
  secondary-fixed-dim: '#8bd2de'
  on-secondary-fixed: '#001f24'
  on-secondary-fixed-variant: '#004f58'
  tertiary-fixed: '#ffdcbd'
  tertiary-fixed-dim: '#f0bd8b'
  on-tertiary-fixed: '#2c1600'
  on-tertiary-fixed-variant: '#623f18'
  background: '#fcf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e5e2dc'
typography:
  display-hero:
    fontFamily: Newsreader
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Newsreader
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-sm:
    fontFamily: Newsreader
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 30px
  subhead-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an editorial, high-end travel discovery experience. It channels the poise of archival travel journalism blended with contemporary digital fluidity. The aesthetic sits at the intersection of modern minimalism and warm tactile depth—conveying effortless luxury, thoughtful curation, and worldly sophistication without feeling unapproachable.

### Personality & Tone
- **Curated & Discerning:** Every element feels intentionally placed, avoiding visual clutter in favor of spacious, high-impact imagery and deliberate typographic pacing.
- **Warm & Grounded:** Textural warmth and earthy undertones replace sterile digital whites, inviting prolonged exploration.
- **Refined Exploration:** Balances the romanticism of wanderlust with precise, functional utility for complex itineraries and booking flows.

### Emotional Response
The interface should evoke the quiet luxury of opening a heavy-stock, cloth-bound travel quarterly: calm confidence, wanderlust, and trust in peerless editorial recommendations.

## Colors

The palette is anchored in natural geographic elements: sunbaked clay, deep coastal waters, wind-carved stone, and fine desert sands.

- **Primary (`#C2593F` - Terracotta):** Represents earth, warmth, and vitality. Used for high-intent actions, key badges, interactive accents, and selected filter states.
- **Secondary (`#1B6B76` - Oceanic Teal):** Provides a cooling, oceanic counterbalance. Used for secondary highlights, verified indicators, interactive map markers, and tags denoting coastal or water-centric experiences.
- **Tertiary (`#D4A373` - Ochre Dune):** A warm transitional tone for subtle borders, ratings, star highlights, and secondary chips.
- **Neutral Surface (`#F7F4EE` - Warm Sand):** The primary canvas background. Prevents eye fatigue, providing an editorial paper-like reading plane.
- **Neutral Dark / Slate (`#1D2327` - Dark Slate):** Used for primary typography, solid iconography, high-contrast footer surfaces, and rich structural dividers.
- **Muted Slate (`#5A646E`):** Used for metadata, secondary descriptions, and tertiary controls.
- **Border / Divider Sand (`#E6E0D2`):** Used for low-contrast borders and structural grid outlines.

## Typography

The type system blends literary authority with clear information architecture.

- **Headlines (Newsreader):** Brings a refined, editorial stance to destination titles, article intros, and hero showcases. It conveys timelessness and discovery.
- **Body & Interface (Plus Jakarta Sans):** Delivers clean geometry, exceptional legibility at reduced sizes, and a modern, airy cadence for listings, dates, rates, and navigation.

### Typographic Rules
- Headlines larger than 32px employ optical tracking tightening (`-0.01em` to `-0.02em`) to maintain an authoritative, tightly bound editorial presence.
- Uppercase styling is reserved strictly for `label-md` and `caption` tags (e.g., regional tags, flight numbers, status flags) with generous letter spacing (`0.04em` to `0.08em`).
- Body text must never be purely black (`#000000`). It utilizes `#1D2327` for body copy and `#5A646E` for secondary descriptions to maintain harmony against the sand backgrounds.

## Layout & Spacing

This design system uses a flexible 12-column grid system paired with strict horizontal rhythm based on 4px and 8px step increments.

### Grid Anatomy
- **Desktop (>= 1280px):** 12-column layout with 24px (`1.5rem`) gutters and a dynamic page margin capped at 1440px content width with minimum 48px (`3rem`) lateral safety margins.
- **Tablet (768px – 1279px):** 8-column layout with 20px gutters and 32px outer canvas margins.
- **Mobile (< 768px):** 4-column layout with 16px (`1rem`) gutters and 20px (`1.25rem`) side margins.

### Vertical Spacing & Rhythm
- High-level sections (e.g., hero to curated collections) demand deliberate, unhurried negative space: 80px to 120px desktop padding.
- Card internals follow a strict rhythm: `space-sm` (8px) between icon and metadata, `space-md` (16px) between heading and description, and `space-lg` (24px) for card body padding.

## Elevation & Depth

Visual hierarchy avoids heavy drop shadows, relying instead on tonal surface layering, delicate warmth-tinted ambient glows, and hairline structural borders.

### Surface Tiers
1. **Base Layer (`#F7F4EE` - Warm Sand):** The root canvas for all screens.
2. **Surface Layer 1 (`#FFFFFF` - Pure Alabaster):** Destination cards, search modules, and itinerary summaries sit on crisp white, creating soft physical contrast against the sand base.
3. **Surface Layer 2 (`#FAF8F3` - Pale Linen):** Secondary panels, nested details, and inactive chip bases.
4. **Surface Drawer / Overlay (`#FFFFFF` with Glass Backdrop):** Modal flyout drawers and search overlays utilize a `rgba(29, 35, 39, 0.4)` scrim combined with a `12px` background blur.

### Shadow Characteristics
- **Resting Cards:** Low-contrast hairline border (`1px solid #E6E0D2`) paired with an ambient shadow: `0 4px 20px -2px rgba(90, 100, 110, 0.05)`.
- **Hover / Focus:** Lifts with a warm, subtle shadow: `0 12px 32px -4px rgba(194, 89, 63, 0.08), 0 4px 12px -2px rgba(29, 35, 39, 0.04)`.
- **Flyouts & Modals:** High elevation using a diffused, natural slate spread: `0 24px 48px -12px rgba(29, 35, 39, 0.18)`.

## Shapes

The shape system balances modern structural rigor with organic, welcoming radii. A base roundedness of 2 (`0.5rem` / 8px) ensures that content cards feel sturdy and architectural, while interactive controls and interactive tokens (chips, pill badges) utilize higher contextual radii to invite touch.

- **Cards & Modal Drawers:** `rounded-lg` (16px / `1rem`) for smooth, tactile containment of photography and dense text.
- **Nested Media & Images:** `rounded-md` (8px / `0.5rem`) within cards to maintain internal visual symmetry.
- **Interactive Pills, Filters, & Floating Action Buttons:** Overridden to full pill curvature (`9999px`) to create distinction between functional triggers and static structural panels.
- **Input Fields & Search Bars:** `rounded-lg` (8px) for clean integration alongside button groups.

## Components

### Buttons
- **Primary:** Terracotta background (`#C2593F`), white text (`#FFFFFF`), `font-weight: 600`, full pill radius (`9999px`) or `rounded-md` (8px) for in-form actions. Subtle scale transition (`scale(1.02)`) and darkening hover (`#AA4B34`).
- **Secondary:** Oceanic Teal border (`1.5px solid #1B6B76`), oceanic teal text, transparent background. Transitions to solid teal with white text on hover.
- **Ghost / Editorial:** Dark Slate text, no border, accompanied by an animated hairline underline expanding on hover.

### Chips & Pill Filters
- **Default State:** Pale Linen background (`#FAF8F3`), fine Sand border (`1px solid #E6E0D2`), slate text (`#1D2327`). Height: 36px, horizontal padding: 16px, pill radius (`9999px`).
- **Active / Selected State:** Solid Terracotta or Oceanic Teal fill with white text and no border.
- **Filter Count Badge:** Micro-pill inside the chip with contrasting background.

### Destination & Itinerary Cards
- Pure Alabaster background (`#FFFFFF`) with `rounded-lg` corners and fine outline (`1px solid #E6E0D2`).
- Imagery features an aspect ratio of 4:3 or 16:10 with smooth zoom (`scale(1.04)`) on hover.
- Top-right floating glass bookmark button: circular (`36px`), frosted translucent background (`rgba(255, 255, 255, 0.85)` with `backdrop-filter: blur(8px)`), housing a vector bookmark icon that fills Terracotta when active.
- Card footer displays location tags, star rating with tertiary ochre star (`#D4A373`), and bold typographic price/duration cues.

### Input Fields & Search Bars
- Background: `#FFFFFF`. Border: `1px solid #E6E0D2`. Padding: `12px 16px`. Text: `#1D2327`.
- Focus State: Terracotta border (`#C2593F`), zero browser-native ring, replaced with a `0 0 0 3px rgba(194, 89, 63, 0.15)` focus aura.
- Floating Search Bar: Merges date picker, destination text, and guest selectors into an integrated pill container with interior hairline vertical dividers.

### Checkboxes & Radio Buttons
- Checkbox: `18px x 18px`, `rounded` (4px), sand border (`#E6E0D2`). When checked: solid Terracotta fill with white checkmark.
- Radio Button: `18px x 18px`, circular, concentric inner indicator dot (`8px`) in Oceanic Teal or Terracotta on selection.

### Modal & Flyout Drawers
- Positioned from the right viewport boundary for detailed itineraries and booking summaries.
- Width: `480px` on desktop, `100vw` on mobile.
- Header showcases Newsreader headline styling with an understated close icon.
- Divided into chronological day-by-day itinerary nodes linked with a subtle dashed vertical guide line in `#D4A373`.