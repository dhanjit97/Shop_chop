---
name: CommonCart Architectural Minimal
colors:
  surface: '#f9f9f8'
  surface-dim: '#dadad9'
  surface-bright: '#f9f9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f3'
  surface-container: '#eeeeed'
  surface-container-high: '#e8e8e7'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1f0'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#a23f1c'
  on-secondary: '#ffffff'
  secondary-container: '#fd835a'
  on-secondary-container: '#701f00'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1d1b1a'
  on-tertiary-container: '#868381'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#ffdbd0'
  secondary-fixed-dim: '#ffb59d'
  on-secondary-fixed: '#390b00'
  on-secondary-fixed-variant: '#822805'
  tertiary-fixed: '#e6e1df'
  tertiary-fixed-dim: '#cac6c3'
  on-tertiary-fixed: '#1d1b1a'
  on-tertiary-fixed-variant: '#484645'
  background: '#f9f9f8'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '500'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.015em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-xs:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style
The design system embodies understated, human-crafted modern minimalism. It balances the restrained luxury of architectural journals and high-end editorial commerce (SSENSE, Kinfolk) with the utilitarian precision of contemporary product tools like Linear.

The audience seeks clarity, deliberate craftsmanship, and quiet authority. The visual atmosphere rejects generic software tropes: no neon gradients, no bloated pill badges, and no aggressive, heavy tints. Instead, the UI relies on strict structural framing, generous intentional whitespace, hairline grid boundaries, and typographic weight contrast. The resulting impression is serene, exact, and impeccably curated.

## Colors
The palette is grounded in high-contrast neutrality with surgical accent application:
- **Base Surfaces:** Pure gallery white (`#FFFFFF`) layered over architectural limestone and warm alabaster (`#FBFBFA` primary canvas, `#F4F4F0` secondary grouping).
- **Text & Hierarchy:** Deep obsidian carbon (`#111111`) for primary titles and high-emphasis data, balanced with muted slate charcoal (`#57534E`) for metadata, sub-labels, and auxiliary information.
- **Structural Lines:** Razor-thin boundary lines using pencil gray (`#E5E5E2` base divider, `#D4D4CE` high-emphasis rule).
- **Focal Accent:** Burnt umber / raw sienna (`#B44C28`). Reserved exclusively for critical focal points—cart confirmation triggers, key active status pips, and deliberate editorial focus markers. Never blanketed over large container fills or generic backgrounds.
- **Functional Semantics:** Subdued, low-saturation indicators rather than loud status colors: deep charcoal for pending/neutral, forest olive (`#2D3B2D`) for settled actions, and raw sienna for errors or urgent notices.

## Typography
Typographic clarity is achieved using a single, hyper-refined grotesque typeface (`Inter`) to maintain strict editorial discipline. 

- Large display sizes feature negative letter-spacing and lighter weights (`400`–`500`), evoking the quiet elegance of print monographs.
- Body text prioritizes breathing room, utilizing line-heights exceeding 1.55x the font size to ensure effortless scannability across dense carts, multi-vendor orders, and receipt ledgers.
- Micro-labels and column headers use uppercase transformation with gentle positive letter-spacing (`0.04em`–`0.06em`) to establish crisp section delineations without relying on heavy visual cards.

## Layout & Spacing
The layout follows a disciplined 12-column architectural grid on desktop, collapsing to 6 columns on tablet and 4 columns on mobile. 

- **Outer Margins:** Wide, framing whitespace (`3rem` desktop) frames content like a printed editorial page, shrinking to `1.25rem` on mobile to preserve readable line lengths.
- **Vertical Rhythm:** Content sections are separated by expansive vertical intervals (`space-xl` to double `space-xl`), letting key modules claim physical importance.
- **Rhythmic Densities:** While page margins are expansive, functional table rows and purchase breakdown panels use tight, precise vertical pads (`space-sm` to `space-md`) anchored by hairline rules to maintain immediate operational clarity.

## Elevation & Depth
Depth is produced through flat planes, tonal contrasts, and razor-sharp borderlines—never through floating drop shadows or heavy blur diffusion.

- **Surface Layering:** The foundational viewport uses `#FBFBFA`. Focused workspace modules, cart tables, and modal drawers sit on crisp `#FFFFFF` surfaces. 
- **Low-Contrast Outlines:** Visual bounding boxes utilize crisp 1px hairline rules (`#E5E5E2`). Overlapping tiers are delineated by alternating surface hues (`#FFFFFF` against `#F4F4F0`) rather than drop shadows.
- **Contextual Overlays:** Flyouts and bottom sheets rely on a solid 1px border (`#D4D4CE`) paired with a minimal ambient falloff (`0 4px 24px rgba(17, 17, 17, 0.04)`), maintaining grounding and physical presence without visual fuzziness.

## Shapes
The shape language favors architectural precision over playfulness. Roundedness is kept strictly at micro-scales (`roundedness: 1`).

- Primary buttons, input containers, and editorial cards employ micro-radii (2px to 4px).
- Bubbly pill forms are entirely prohibited. Status chips, image frames, and tag indicators maintain clean, rectangular geometries with sharp or micro-softened corners, preserving an authentic and mature aesthetic.

## Components

### Buttons
- **Primary:** Solid obsidian (`#111111`) fill, stark white typography, 4px border radius. Hover introduces a subtle shift to `#262422` with immediate, non-spring transitions.
- **Secondary / Ghost:** Transparent base, 1px hairline border (`#D4D4CE`), obsidian text. Hover shifts background to `#F4F4F0`.
- **Accent Action:** Burnt umber (`#B44C28`) reserved solely for the definitive final action (e.g., "Complete Order").

### Form Inputs & Selectors
- Flat `#FFFFFF` fields framed with a 1px `#E5E5E2` border, 3px corner radius.
- Padding: 10px 14px for compact, deliberate touch surfaces.
- Focus state: Border transitions to `#111111` with no diffuse outer glow rings.
- Placeholder text in `#57534E` with reduced optical weight.

### Status Indicators & Micro-Chips
- Banish brightly colored pill badges. 
- Statuses are presented as text labels prefixed by a 6px geometric square or circular pip (e.g., `#B44C28` for attention required, `#2D3B2D` for confirmed, `#D4D4CE` for draft).
- If containerized, tags use an unbordered `#F4F4F0` background with dark charcoal typography in `label-xs`.

### Lists & Cart Tables
- Architectural, full-width tabular lines separated by 1px `#E5E5E2` borders.
- No alternating zebra striping; hierarchy is created strictly through column alignment, typography weights, and numerical tracking.
- Row heights are generous (minimum 56px) with clean numerical baselines.

### Cards & Editorial Containers
- Cards are framed by flat 1px rules or sit borderless over alternating background planes.
- Content relies on asymmetric whitespace: wide internal paddings (`space-lg`), headline groupings pushed directly to top-left bounds, and minimal visual noise.