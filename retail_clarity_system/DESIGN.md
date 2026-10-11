---
name: Retail Clarity System
colors:
  surface: '#f7fafa'
  surface-dim: '#d7dbdb'
  surface-bright: '#f7fafa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f4'
  surface-container: '#ebeeee'
  surface-container-high: '#e6e9e9'
  surface-container-highest: '#e0e3e3'
  on-surface: '#181c1d'
  on-surface-variant: '#554434'
  inverse-surface: '#2d3131'
  inverse-on-surface: '#eef1f1'
  outline: '#887361'
  outline-variant: '#dbc2ad'
  surface-tint: '#8a5100'
  primary: '#8a5100'
  on-primary: '#ffffff'
  primary-container: '#ff9900'
  on-primary-container: '#653a00'
  inverse-primary: '#ffb86f'
  secondary: '#595f68'
  on-secondary: '#ffffff'
  secondary-container: '#dae0eb'
  on-secondary-container: '#5d636d'
  tertiary: '#b42906'
  on-tertiary: '#ffffff'
  tertiary-container: '#ff957c'
  on-tertiary-container: '#861900'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcbd'
  primary-fixed-dim: '#ffb86f'
  on-primary-fixed: '#2c1600'
  on-primary-fixed-variant: '#693c00'
  secondary-fixed: '#dde3ee'
  secondary-fixed-dim: '#c1c7d2'
  on-secondary-fixed: '#161c24'
  on-secondary-fixed-variant: '#414750'
  tertiary-fixed: '#ffdad2'
  tertiary-fixed-dim: '#ffb4a3'
  on-tertiary-fixed: '#3d0600'
  on-tertiary-fixed-variant: '#8b1a00'
  background: '#f7fafa'
  on-background: '#181c1d'
  surface-variant: '#e0e3e3'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 26px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 22px
    letterSpacing: 0em
  price-xl:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.02em
  price-lg:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.01em
  price-sm:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  gutter-desktop: 1.25rem
  margin: 1rem
  margin-mobile: 0.75rem
  margin-tablet: 1.25rem
  margin-desktop: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
  space-2xl: 2rem
---

## Brand & Style

This design system channels high-utility commercial vitality, engineered for trust, velocity, and zero-friction purchasing. The aesthetic elevates large-scale retail interfaces through disciplined typography, authoritative contrast, and clear transactional signposts.

### Core Philosophy
- **Utilitarian Elegance:** Function is aesthetic. Dense information architectures are structured with breathing room, scannable hierarchies, and distinct visual anchors.
- **Action Certainty:** Conversion actions are unambiguous, warm, and inviting, leaving zero friction between intent and transaction.
- **Commercial Trust:** Deep midnight foundations anchor the interface, balanced against crisp white container cards and subtle architectural dividers.

### Design Movement
- **Modern Commercial Utility:** High-contrast, tactile-accessible minimalism. Replaces dated gradients with crisp micro-borders, purposeful solid fills, and tight typographic rhythm built for fast browsing.

## Colors

The palette balances structural retail dark tones against high-visibility conversion warm tones and disciplined neutral surfaces.

### Palette Architecture
- **Primary (`#FF9900`):** Action Gold. Reserved for primary purchase triggers, active rating indicators, and high-priority callouts. Active/Pressed states darken toward `#CC6600` and `#E67A00`.
- **Secondary (`#131921`):** Deep Squid Ink / Anchor Black. Drives top navigation bars, categorical utility chrome, heavy headline text, and bottom structural anchors. Sub-tier headers and secondary utility bars map to `#232F3E`.
- **Tertiary (`#B12704`):** Direct Price Red. Strictly reserved for transactional numerals, discount deltas, urgent inventory notices, and strike-through comparisons. Secondary alert state: `#C7511F`.
- **Neutral Canvas (`#EAEDED`):** Atmospheric cool grey foundational ground layer that makes white product cards `#FFFFFF` pop forward with dimensional separation.
- **Structural Lines:** Neutral border rules leverage `#D5D9D9` for high-contrast accessibility without harsh line weights.

## Typography

Inter serves as the foundational voice across all weights and viewports. Its clean geometric architecture, tall x-height, and neutral grotesk profile mirror the high-velocity legibility of Amazon Ember.

### Execution Principles
- **Numeric Clarity:** Numbers and price expressions require tabular alignment and immediate visual weight. Currency signs superscript cleanly or sit on the baseline with proportionate sizing.
- **Product Title Control:** Title text caps line clamping at 2 lines in cards and 3 lines in search results to maintain vertical rhythm.
- **Weight Contrast:** Headlines jump decisively from 400 (specifications/body) to 700 and 800 (titles, buy box metrics). Avoid intermediate ambiguous weights like 300 or 900.

## Layout & Spacing

A fluid responsive grid model engineered for product density, scanning efficiency, and frictionless conversion checkout funnels.

### Grid Framework
- **Desktop (>= 1280px):** 12-column grid, max-width bounded at 1500px, 20px gutters, 24px side canvas margins. Provides stability for multi-rail product pages (Left Media, Center Details, Right Buy Box).
- **Tablet (768px - 1279px):** 8-column layout, 16px gutters, 20px side canvas margins. Buy Box anchors below primary descriptions or sticks into persistent slide-in bottom bars.
- **Mobile (< 768px):** 4-column layout, 12px gutters, 12px margins. Product listings shift seamlessly from 4-column card matrices to 2-column browse grids or single-column horizontal search results.

### Spacing Density
Information density is kept intentionally compact. Vertical padding within cards relies on `space-md` (12px) and `space-lg` (16px) to maximize above-the-fold catalog discoverability.

## Elevation & Depth

Visual hierarchy uses crisp boundary delineation and tonal layering, relying on low-profile functional elevation over dramatic ambient blur.

### Depth Tiers
- **Tier 0 (Base Ground):** Surface `#EAEDED`. Backdrops all category pages, feed canvases, and account settings.
- **Tier 1 (Surface Containers):** Pure `#FFFFFF` flat surface. Bound by a continuous 1px micro-border (`#D5D9D9`). Zero blur shadow in rested state. Used for all standard item tiles, list elements, and feature blocks.
- **Tier 2 (Elevated & Hover):** Subtle tactile lift (`0px 2px 5px rgba(15, 17, 17, 0.15)`). Applied when a user hovers a catalog item card, or to focus active checkout panes.
- **Tier 3 (Floating Overlays):** Controlled directional shadow (`0px 4px 20px rgba(0, 0, 0, 0.15)`). Used for department mega-menus, sticky add-to-cart bars, typeahead search auto-completes, and modal dialogues.

### Border Discipine
Never blur or tint surface dividers. Use strict 1px solid edges in `#E7E7E7` or `#D5D9D9` to separate table rows, product variants, and specification tables.

## Shapes

The design uses balanced, rounded geometries (level 2) to maintain a modern, friendly touch without sacrificing institutional structure.

### Radius Assignments
- **Core Elements (0.5rem / 8px):** Form controls, text input containers, dropdown selectors, and default card perimeters.
- **High-Velocity Actions (Pill / 9999px):** "Add to Cart" and "Buy Now" CTAs use fully rounded pill profiles. This isolates purchase triggers from rectangular content units and draws immediate focus.
- **Badges & Chips (0.25rem to 0.375rem / 4px to 6px):** Deal tags ("Limited time deal", "Best Seller") maintain tighter radii to preserve an authoritative, sticker-like quality.

## Components

### Buttons
- **Primary Action ("Add to Cart"):** Surface `#FF9900`, text `#0F1111` (dark charcoal, never pure black), pill-rounded (`border-radius: 9999px`), subtle perimeter ring border (`#E67A00`). Hover transitions to `#FA8900`.
- **Immediate Action ("Buy Now"):** Surface `#FFA41C`, text `#0F1111`, pill-rounded. Hover state shifts to `#FF8F00`.
- **Secondary Action:** Surface `#FFFFFF`, border `1px solid #D5D9D9`, text `#0F1111`. Hover introduces surface `#F7FAFA` and border `#888C8C`.
- **Height Scale:** Standard desktop conversion button is 40px; mobile action bars scale to 48px to satisfy touch-target safety.

### Cards
- **Product Tile:** Clean white background (`#FFFFFF`), 8px border radius, 1px solid `#D5D9D9`. Internal padding `12px` to `16px`. Hover state replaces flat border with a soft drop shadow (`0 2px 8px rgba(15, 17, 17, 0.12)`).
- **Buy Box Card:** Encased in a defined `#D5D9D9` border frame with `16px` padding. Contains stock indicators (`#007600` for in-stock, `#B12704` for low-stock countdowns), quantity stepper, and full-width action stack.

### Inputs & Typeahead
- **Global Search Header Bar:** 40px height, inset white input with `#131921` category selector dropdown on the left and `#FF9900` magnifying-glass action block on the right. Focus state outlines the input in an active high-contrast `#E77600` halo (`0 0 0 3px rgba(228, 121, 17, 0.5)`).
- **Form Controls:** Standard inputs sit on white backgrounds with a 1px `#888C8C` border, transitioning to active gold border `#E77600` on focus.

### Chips & Badges
- **Best Seller Badge:** Surface `#E67A00`, text `#FFFFFF`, bold 11px uppercase label, soft 3px top-left/bottom-left asymmetric ribbon curve.
- **Deal Badge:** Surface `#CC0C39`, text `#FFFFFF`, bold 12px pill badge signaling instant percentage discounts.
- **Filter Chips:** Pill shape, white fill, 1px `#D5D9D9` border. Selected state applies `#EDFDFF` background with `#007185` primary retail brand link coloring.

### Checkboxes & Radio Controls
- **Checkboxes:** 18x18px square with 3px border-radius. Border `#888C8C` rested; fill `#007185` checked with crisp white tick.
- **Radio Buttons:** 18x18px circle, `#007185` active ring with centered solid dot.

### Price Presentation Units
- **Currency Symbol:** Superscripted, 65% size of whole dollar figure, aligned to font cap-height.
- **Fractional Cents:** Superscripted alongside currency, ensuring large price points occupy minimum horizontal real estate while standing out in `#B12704`.