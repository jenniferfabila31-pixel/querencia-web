---
name: Warm Architectural Organic
colors:
  surface: '#fcf9f2'
  surface-dim: '#dcdad3'
  surface-bright: '#fcf9f2'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ec'
  surface-container: '#f1eee7'
  surface-container-high: '#ebe8e1'
  surface-container-highest: '#e5e2db'
  on-surface: '#1c1c18'
  on-surface-variant: '#484839'
  inverse-surface: '#31312c'
  inverse-on-surface: '#f3f0e9'
  outline: '#787867'
  outline-variant: '#c9c7b4'
  surface-tint: '#5f620f'
  primary: '#5c600c'
  on-primary: '#ffffff'
  primary-container: '#757926'
  on-primary-container: '#fffbff'
  inverse-primary: '#c8cc6f'
  secondary: '#8d4f01'
  on-secondary: '#ffffff'
  secondary-container: '#feac5e'
  on-secondary-container: '#744000'
  tertiary: '#70564f'
  on-tertiary: '#ffffff'
  tertiary-container: '#8b6e67'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e4e888'
  primary-fixed-dim: '#c8cc6f'
  on-primary-fixed: '#1c1d00'
  on-primary-fixed-variant: '#474a00'
  secondary-fixed: '#ffdcc0'
  secondary-fixed-dim: '#ffb876'
  on-secondary-fixed: '#2d1600'
  on-secondary-fixed-variant: '#6b3b00'
  tertiary-fixed: '#ffdbd1'
  tertiary-fixed-dim: '#e1bfb6'
  on-tertiary-fixed: '#2a1711'
  on-tertiary-fixed-variant: '#59413a'
  background: '#fcf9f2'
  on-background: '#1c1c18'
  surface-variant: '#e5e2db'
typography:
  display-hero:
    fontFamily: Outfit
    fontSize: 80px
    fontWeight: '600'
    lineHeight: 84px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Outfit
    fontSize: 44px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Outfit
    fontSize: 48px
    fontWeight: '500'
    lineHeight: 54px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Outfit
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Outfit
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Outfit
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 28px
  title-md:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 24px
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '300'
    lineHeight: 28px
  body-md:
    fontFamily: DM Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: DM Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: DM Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.12em
  label-sm:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2.5rem
  margin: 2rem
  margin-mobile: 1.25rem
  margin-desktop: 4rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style

The design system embodies grounded comfort, artisanal craftsmanship, and contemporary residential calm ("Un lugar para quedarse" — a place to stay). The aesthetic merges editorial furniture design sensibilities with warm minimalism, evoking tactile serenity, high-end interior architecture, and sustainable lifestyle living.

Targeted at discerning design lovers, conscious consumers, and architectural lifestyle spaces, the emotional response evokes belonging, refuge, and quiet sophistication. Visual rhythm relies on sweeping atmospheric olive fields, subtle tinted blush micro-dividers, warm wood accents, and sculptural white text contrasts.

## Colors

The color palette centers on nature-imbued, interior-forward pigments directly derived from the brand visual identity:
- **Primary (`#7E822E`)**: Golden olive avocado base providing an immersive, calming architectural ground.
- **Secondary (`#C67D33`)**: Warm honey beech and cedarwood tone, providing tactile warmth, interactive energy, and active callouts.
- **Tertiary (`#E8C5BC`)**: Delicate muted blush pink, utilized for eyebrow metadata badges, hairline dividers, micro-labels, and subtle highlights.
- **Neutral (`#F5F2EB`)**: Warm bouclé off-white/cream, serving as high-contrast structural text, soft surface backdrops, and card surfaces.
- **Deep Tone (`#24260D`)**: Deep olive umber for rich legibility against neutral cream containers.

## Typography

The typography leverages **Outfit** for editorial titles, featuring a tailored geometric presence with modernist character, echoing architectural furniture catalogs. **DM Sans** delivers neutral, warm clarity across body copy, navigational metadata, and micro-labels.

Special styling rules:
- Subheadings directly underneath major display typography adopt a lighter weight (`300`) with generous track.
- Category pills and metadata headers (`label-caps`) are strictly uppercase with `0.12em` tracking, often enclosed inside blush tag banners or bordered by fine blush horizontal rules.

## Layout & Spacing

A structured 12-column fluid grid system anchors desktop layouts, condensing to 8 columns on tablet and 4 columns on mobile. Margins are generous, mimicking coffee table editorial publications and spatial interior design spreads. 

Horizontal separation frequently utilizes full-bleed or column-bound 1px rule dividers colored with the tertiary blush tone (`#E8C5BC` at 60% opacity), running alongside section pagination tags.

## Elevation & Depth

Visual hierarchy favors physical object tangibility and layered planar surfaces over harsh dropshadows:
- **Atmospheric Backgrounds**: The canvas predominantly floats on primary avocado olive (`#7E822E`), with card surfaces shifting to soft bouclé cream (`#F5F2EB`) or deep matte olive containers (`#727627`).
- **Warm Ambient Shadowing**: When physical furniture or modular products float above the canvas, employ warm, diffused, downward amber-tinted cast shadows (`rgba(50, 48, 20, 0.28) 0px 24px 48px -12px`), grounding objects without artificial digital glow.
- **Micro-borders & Inset Highlights**: Surface containers utilize a delicate 1px boundary tinted with off-white or muted blush (`rgba(245, 242, 235, 0.15)` on dark backgrounds; `rgba(200, 190, 180, 0.35)` on light surfaces).

## Shapes

The design uses balanced, modern geometric contours (`roundedness: 2`). Radii transition between gentle curves for cards and containers, and pill shapes strictly reserved for category markers, badges, and toggle chips. Architectural arches and pill cuts may frame hero imagery, echoing the curved cat arches and cylindrical bolster cushions of the physical identity piece.

## Components

### Buttons
- **Primary Action**: Solid honey wood beech (`#C67D33`) with crisp cream (`#F5F2EB`) typography. 0.5rem radius (`rounded-md`), subtle press elevation, and soft warmth on hover (`#B56F28`).
- **Secondary / Ghost**: Transparent base bordered with 1px solid `#F5F2EB` (or `#7E822E` on light backdrops), text matching border color.
- **Tertiary Architectural**: Pill badge button in warm blush tint (`#E8C5BC`) with deep olive typography (`#24260D`).

### Eyebrow Tags & Metadata Chips
- Micro-pill or sharp rectangular tabs inspired by visual identity stamps (e.g. `01 / IDENTIDAD`). Tinted background `#E8C5BC` with bold cream or olive lettering, accompanied by an adjacent 1px running baseline rule.

### Cards & Surfaces
- **Product & Content Cards**: Built with bouclé cream (`#F5F2EB`) base surfaces, containing deep olive typography. Rounded at 1rem (`rounded-lg`), subtle inner contour stroke, and ambient olive-wood shadows on hover lift.
- **Media Displays**: Clean image framing with soft, curved corners or integrated architectural arches.

### Form Inputs & Selectors
- Background filled with neutral cream or translucent surface (`rgba(245, 242, 235, 0.12)` on olive). 1px border styled with `#E8C5BC` that transitions to `#C67D33` on active focus.
- Placeholder text in muted warm tone with crisp label typography overhead.

### Lists & Dividers
- Hairline rules styled in muted blush (`#E8C5BC` at 40%–60% opacity) separating catalogue metadata, chapter indices, and specs.