---
name: Editorial Stylist
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#444748'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#98471d'
  on-secondary: '#ffffff'
  secondary-container: '#fe9666'
  on-secondary-container: '#752d03'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#241a00'
  on-tertiary-container: '#958251'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#ffdbcd'
  secondary-fixed-dim: '#ffb596'
  on-secondary-fixed: '#360f00'
  on-secondary-fixed-variant: '#7a3006'
  tertiary-fixed: '#f9e0a7'
  tertiary-fixed-dim: '#dbc48d'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#55451a'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-sm:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 26px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 28px
  headline-sm:
    fontFamily: Bodoni Moda
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 9px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.14em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 2.5rem
  space-3xl: 3.5rem
  screen-edge: 1.25rem
  card-gap: 0.875rem
  stack-gap: 1.5rem
---

## Brand & Style

This design system delivers a bespoke, digital-first haute couture styling experience. It captures the curated restraint of high-fashion print publications like *Vogue* and *SSENSE* while maintaining the effortless utility of an intelligent, predictive personal wardrobe assistant. 

The aesthetic is grounded in **Editorial Minimalism**: deliberate, generous negative space, commanding typographic hierarchy, architectural composition, and disciplined restraint. The visual language avoids synthetic tech tropes, opting instead for tactile refinement, bespoke framing, and atmospheric frosted surfaces. 

Every interaction evokes intimacy, discerning taste, and quiet luxury. Content is treated as curated exhibition pieces, positioning user wardrobe pieces and AI recommendations with the reverence of a luxury runway edit.

## Colors

The color palette embraces an organic, archival foundation balanced by decisive architectural accents.

- **Primary (`#111111`)**: A deep carbon charcoal. Used for definitive typography, primary CTA surfaces, high-contrast framing, and foundational icons. Avoid true digital `#000000` to preserve warmth and depth.
- **Secondary (`#C4683C`)**: A sun-baked terracotta ochre. Reserved for selective discovery moments, high-intent callouts, dynamic AI suggestion indicators, and featured badges.
- **Tertiary (`#9E8A58`)**: An antique patina gold. Used for premium tier badges, bespoke styling tags, curation ratings, and delicate decorative elements.
- **Neutral Base (`#FBF9F5`)**: An unbleached warm linen cream. Acts as the primary canvas, providing a soft, non-fatiguing backdrop reminiscent of heavy matte stock paper.
- **Supporting Tones**:
  - `Surface Muted`: `#EAE6E1` (soft taupe gray) for hairline borders, neutral pill surfaces, and inactive structural elements.
  - `Surface Pure Light`: `#FFFFFF` utilized strictly on frosted glass cards (`rgba(255, 255, 255, 0.72)`) to yield clean luminescence over warm backgrounds.

## Typography

The typographic system creates an interplay between high-contrast editorial drama and crisp utilitarian legibility.

- **Bodoni Moda** anchors display and headline levels. Its neoclassical vertical stress, sharp serifs, and high stroke contrast evoke the legacy of premier fashion periodicals. Headlines must lean into mixed case or italic accents rather than all-caps treatments to maintain bespoke elegance.
- **Plus Jakarta Sans** powers all body copy, interaction elements, metadata, and data points. Its modern geometric curves and open apertures guarantee legibility on small mobile viewports.
- **Micro-Copy & Eyebrows**: Use `label-sm` or `label-md` rendered in uppercase with deliberate tracking (`+0.08em` to `+0.14em`) to denote categories, dates, seasonal chapters, and AI attributes.

## Layout & Spacing

The layout is engineered around a 390px mobile-first standard viewport, adopting a 4-column fluid grid system with `1.25rem` (20px) outside margins and a `0.875rem` (14px) gutter width.

- **Vertical Cadence**: Spacing between unrelated editorial modules uses expansive breathing room (`space-2xl` or `space-3xl`), rejecting the dense tiling typical of commodity apps. Within an editorial card or module, spacing contracts to `space-xs` through `space-md`.
- **Bleed & Carousels**: Primary editorial hero cards and outfit carousels extend past right viewport edges (`-screen-edge` bleed) to invite horizontal gesture discovery, showing exactly a 20% peek of adjacent look-cards.
- **Edge Restraint**: Interactive actions and floating toolbars conform strictly to iOS safe-area insets, suspended cleanly above content flows.

## Elevation & Depth

This system avoids heavy drop shadows, relying on physical layering, translucent frosted planes, and low-contrast borders.

- **Base Layer**: Pure canvas `#FBF9F5` texture.
- **Surface Elevation 1 (Cards & Modules)**: Flat `#FFFFFF` with a hairline stroke (`1px solid #EAE6E1`) and a soft atmospheric shadow: `0px 8px 24px -4px rgba(17, 17, 17, 0.04)`.
- **Surface Elevation 2 (Floating Action & Modal Drawers)**: Frosted glass panels using `backdrop-filter: blur(20px) saturate(180%)`, surface fill `rgba(251, 249, 245, 0.85)`, and a light-reflecting hairline top stroke `1px solid rgba(255, 255, 255, 0.6)`. Shadow: `0px 16px 36px -6px rgba(17, 17, 17, 0.08)`.
- **Tactile Depth**: AI recommendation tags and action overlays float 2px off their parent images, anchored by a micro-halo: `0px 2px 8px rgba(17, 17, 17, 0.06)`.

## Shapes

The design system employs an editorial hybrid architecture: architectural structure on content framing juxtaposed with gentle organic radii on interactive controls.

- **Framing & Cards (`0.5rem` / `rounded-lg`)**: Garment displays, lookbook cards, and dialog containers follow crisp, tailored boundaries that mirror matted picture frames.
- **Controls & Metadata (`9999px` / Full Pill)**: Buttons, segmented tabs, filter pills, and AI tags are rendered as continuous capsules. This establishes a tactile distinction between photographic art (architectural) and functional UI tools (ergonomic pills).
- **Steppers & Progress Tracks**: Ultra-slim horizontal lines with zero border-radius to preserve a technical drafting feel.

## Components

### Buttons
- **Primary CTA**: Solid `#111111` fill with `#FBF9F5` typography (`body-md`, semibold). Full pill silhouette (`rounded-full`), height of 52px. Micro-interaction: scales down to `0.98` with subtle opacity shift on tap.
- **Secondary / Accent CTA**: Terracotta ochre (`#C4683C`) fill with `#FFFFFF` typography. Used exclusively for primary conversion tasks (e.g., "Style with AI", "Complete Look").
- **Ghost / Editorial Outline**: Transparent background, `1px solid #111111`, `#111111` text. No drop shadow.

### Pills & Badges
- **Status & Attribute Badges**: Height of 26px, padding `0 10px`. Background `#EAE6E1` with `#111111` label text in `label-sm`.
- **AI Recommendation Badge**: Frosted glass pill with a subtle terracotta tint (`rgba(196, 104, 60, 0.1)`), hairline border (`1px solid rgba(196, 104, 60, 0.3)`), and `#C4683C` text accompanied by a 10px mono-line spark icon.
- **Luxury/Archive Badge**: `#9E8A58` text over a soft champagne tint (`rgba(158, 138, 88, 0.12)`).

### Segmented Controls
- Continuous pill tray with a warm taupe base (`#EAE6E1`).
- The active tab transitions with a floating white card element (`#FFFFFF`) bound by `0px 2px 8px rgba(17, 17, 17, 0.06)` and rounded pill geometry. Text changes from `#77726D` to `#111111`.

### Card Carousels & Lookboards
- Aspect ratios are locked to fashion standards: `4:5` (outfit overview) and `3:4` (garment close-up).
- Images feature edge-to-edge photography within cards, accompanied by an absolute floating lower glass scrim displaying the item title in `headline-sm` and designer/season in `body-sm`.
- Hairline borders (`1px solid #EAE6E1`) separate card perimeters.

### Form Inputs
- Minimalist underline or low-contrast boxed inputs (`#FFFFFF` background, `1px solid #EAE6E1`).
- Labels sit floating above in uppercase tracking (`label-md`).
- Focus state shifts border cleanly to `1px solid #111111` with no glowing halo.

### Interactive Stepper / AI Progress
- Multi-phase quiz and styling progress utilizes 2px segmented horizontal bars spanning the top margin.
- Completed steps fill solid `#111111`; current step pulses between `#C4683C` and `#111111`; upcoming steps remain muted `#EAE6E1`.

### Checkboxes & Radios
- Selection indicators abandon standard mobile checkmarks in favor of an editorial concentric ring: outer 20px circle with `1.5px solid #111111`, inner solid dot (`8px`) in `#111111` when selected.