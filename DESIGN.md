---
name: Luxury Streetwear Atelier
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#444748'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#745a27'
  on-secondary: '#ffffff'
  secondary-container: '#ffdb9b'
  on-secondary-container: '#795f2a'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#251a00'
  on-tertiary-container: '#9a8145'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e4c284'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5a4311'
  tertiary-fixed: '#fedf99'
  tertiary-fixed-dim: '#e1c380'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#58440d'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 80px
    fontWeight: '700'
    lineHeight: 84px
    letterSpacing: -0.04em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 46px
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 30px
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0em
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0.01em
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.18em
  label-spec:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 12px
    letterSpacing: 0.12em
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.25rem
  margin-tablet: 2.5rem
  margin-desktop: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style

This design system channels an uncompromising, architectural luxury streetwear sensibility. It marries the sparse restraint of brutalist high fashion with the tactile warmth of raw heavyweight cottons, garment-dyed textiles, and archival presentation. 

### Core Ethos
- **Severe Elegance:** Compositional confidence shown through monumental scale shifts, extreme letter tracking, and vast planes of negative space.
- **Architectural Utility:** Interfaces reflect technical garments—functional, structural, stripped of arbitrary adornment, and focused on material honesty (textile weights, precise tailoring, numbered drops).
- **Tactile Materiality:** Digital surfaces mimic off-white archival stationery, raw French terry, and patinated brass hardware.

### Aesthetic Movement
The aesthetic sits at the intersection of **Minimalism** and **Refined Editorial Brutalism**. High typographic contrast pairs with razor-sharp geometry, hair-thin divider rules, and an intentional rejection of artificial depth (no simulated drop shadows or glassmorphism). The atmosphere feels curated, tactile, and quiet.

## Colors

The palette relies on nuanced textural neutrals and off-blacks, punctured exclusively by muted antique gold and olive-beige accents.

### Palette Architecture
- **Primary Canvas (`#F7F5F0` & `#FAF8F5`):** Warm unbleached bone and paper tones. These replace sterile digital white with organic warmth.
- **Structural Ink (`#121212`):** A dense off-black used for primary typographic hierarchy, solid action buttons, and dominant silhouettes. Never pure `#000000`.
- **Secondary Surfaces (`#EFECE6`):** Pale warm sand used for product card backdrops, filter containers, and specimen cards.
- **Micro Borders (`#E5E0D8`):** Subtle tone-on-tone lines that establish spatial structure without breaking fluidity.
- **Accents (`#C2A267` & `#B59A5B`):** Muted bullion and tarnished brass tones reserved for fabric spec callouts (e.g., "500 GSM"), limited edition tags, hover indicators, and micro-branding.
- **Muted Text (`#75726B`):** Desaturated warm grey for secondary editorial metadata, measurements, and timestamps.

## Typography

The type system balances technical brutalism with immaculate editorial rhythm.

- **Primary Display & Headings (`Space Grotesk`):** Delivers a deliberate, sharp geometric presence. Display titles are set tight, dense, and impactful.
- **Body & Continuous Copy (`Hanken Grotesk`):** Modern, clear, and quiet, providing effortless legibility for garment descriptions, care guides, and sizing guides.
- **Labels & Technical Specifiers (`Space Grotesk` Tracked Caps):** Applied to category trackers, currency toggles, edition counters, and textile specs (e.g., `480 GSM LOOPBACK FLEECE`). Always set uppercase with expansive letter spacing (`0.12em` to `0.18em`).

## Layout & Spacing

The layout model is governed by an architectural fixed-gutter fluid grid:
- **Mobile (up to 767px):** 4-column system with `1.25rem` margins and `1rem` gutters. Product listings fall into single-column or tight 2-column configurations.
- **Tablet (768px – 1023px):** 8-column system with `2.5rem` margins and `1.5rem` gutters.
- **Desktop (1024px+):** 12-column system, max container width of `1680px`, anchored by generous `4rem` outer margins.

Vertical rhythm relies on generous intervals of unconstrained whitespace (`space-xl` and higher) juxtaposed against compact metadata clusters, mirroring the stark pacing of a physical luxury lookbook.

## Elevation & Depth

This system avoids blurred drop shadows, ambient fuzz, or skeuomorphic dimensionality. Hierarchy is communicated through surface layering and hairline borders:

1. **Planar Hierarchy:** 
   - Base canvas: `#F7F5F0`.
   - Structural elements and product cradles: `#EFECE6`.
   - Overlay panels, drawers, and modal sheets: `#FAF8F5`.
2. **Hairline Framing:** Crisp 1px borders using `#E5E0D8` define cards, dividers, and modular containers.
3. **Modal Overlay:** Overlays and slide-out cart drawers use `#121212` at 40% opacity, providing a neutral dim without losing the warm underlayer.

## Shapes

In keeping with high-fashion packaging, razor-cut tailoring, and brutalist architecture, the corner radius across all elements is strictly **0px (Sharp)**. 

Every button, image frame, input container, toast, chip, and card terminates in a sharp 90-degree corner. The discipline of the rectangle reinforces the boxy, structured silhouette characteristic of heavy luxury streetwear garments.

## Components

### Buttons
- **Primary:** Background `#121212`, text `#FAF8F5`, 0px radius, uppercase `label-caps`. Hover transitions to `#C2A267` with `#121212` text.
- **Secondary / Outline:** Background transparent, border 1px solid `#121212`, text `#121212`. Hover inverts to solid `#121212` with text `#FAF8F5`.
- **Text Link:** Underlined with a 1px offset line; transitions to muted gold on interaction.

### Chips & Badges
- **Fabric/Spec Badge:** Background `#EFECE6`, border 1px solid `#E5E0D8`, text `#121212`, tracked uppercase `label-spec`. Features details like `460 GSM`, `100% COMBED COTTON`, or `EDITION OF 150`.
- **Status Indicator:** Minimal circular glyph (4px) in `#C2A267` followed by uppercase label text (e.g., `IN PRODUCTION`, `ARCHIVED`).

### Cards & Modules
- **Lookbook / Product Card:** Unbounded or encased in a 1px `#E5E0D8` border with a `#EFECE6` backdrop. Images sit flush with a zero-radius crop. The footer displays garment titles in `headline-md` alongside right-aligned technical GSM and price callouts in `label-spec`.

### Form Fields & Inputs
- **Inputs:** Flat rectangular containers. Background `#FAF8F5`, bottom-only or full 1px border `#E5E0D8`. Focus states shift the border to `#121212`. Labels sit above in tracked uppercase `label-spec`.
- **Checkboxes & Radios:** Sharp square geometries (0px radius). Checked state displays a solid `#121212` fill with a crisp inner square or check.

### Additional Specialized Components
- **Textile Spec Bar:** A modular technical data grid embedded on product display pages detailing Yarn Origin, Weave Structure, Garment Weight (GSM), and Dye Method.
- **Lookbook Slider Nav:** Minimal monospaced pagination index (e.g., `01 / 12`) flanked by bare bracket arrows (`[←]` / `[→]`).