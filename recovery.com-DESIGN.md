---
version: alpha
name: Recovery
description: |
  Recovery.com's design system projects trust, clarity, and accessibility
  through a serene, empathetic visual language. The palette combines a deep navy
  canvas (#232452) with soft, approachable accent hues and abundant whitespace
  to create an inviting experience for users seeking mental health and addiction
  treatment resources. The aesthetic prioritizes legibility and emotional
  safety: primary typography is bold and authoritative, backgrounds are calm and
  non-clinical, and interactive elements use rounded corners and gentle colour
  transitions to reduce friction. This is a design system built for vulnerable
  audiences, where clarity and reassurance are paramount.
source:
  url: "https://recovery.com"
  pagesAnalyzed: 1
  extractedAt: 2026-10-29
  tokensMeasured: true
colors:
  primary: "#FFFFFF"
  accent: "#C3C0FC"
  canvas: "#232452"
  on-primary: "#394E66"
  ink: "#FFFFFF"
  hairline: "#E1E7EF"
  accent-1: "#677D95"
  accent-2: "#4D657F"
  accent-3: "#162941"
  accent-4: "#25217A"
  accent-5: "#222263"
  accent-6: "#31279B"
  neutral-1: "#000000"
  neutral-2: "#EFEDFF"
typography:
  heading-lg:
    fontFamily: FieldsVariable
    fontSize: 34px
    fontWeight: 400
    lineHeight: 1.24
    letterSpacing: 0px
  heading-md:
    fontFamily: Figtree
    fontSize: 32px
    fontWeight: 300
    lineHeight: 1.19
    letterSpacing: 0px
  heading-md-strong:
    fontFamily: FieldsVariable
    fontSize: 32px
    fontWeight: 500
    lineHeight: 1.19
    letterSpacing: 0px
  heading-sm:
    fontFamily: FieldsVariable
    fontSize: 24px
    fontWeight: 500
    lineHeight: 1.33
    letterSpacing: 0px
  heading-sm-tight:
    fontFamily: FieldsVariable
    fontSize: 24px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: 0px
  heading-xs:
    fontFamily: Figtree
    fontSize: 20px
    fontWeight: 500
    lineHeight: 1.6
    letterSpacing: 0px
  body-lg:
    fontFamily: Figtree
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.56
    letterSpacing: 0px
  body-lg-strong:
    fontFamily: FieldsVariable
    fontSize: 18px
    fontWeight: 500
    lineHeight: 1.56
    letterSpacing: 0.2px
  body-lg-2:
    fontFamily: Figtree
    fontSize: 18px
    fontWeight: 500
    lineHeight: 1.56
    letterSpacing: 0px
  body-md:
    fontFamily: Figtree
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0px
  body-md-strong:
    fontFamily: Figtree
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: 0px
  body-sm:
    fontFamily: Figtree
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.43
    letterSpacing: 0.35px
  button-md:
    fontFamily: Figtree
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: 0px
  button-sm:
    fontFamily: Figtree
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.43
    letterSpacing: 0.35px
  caption-xs:
    fontFamily: Figtree
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.33
    letterSpacing: 0px
  caption-xs-capitalize:
    fontFamily: Figtree
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.33
    letterSpacing: 0px
    textTransform: capitalize
  caption-xs-strong:
    fontFamily: Figtree
    fontSize: 12px
    fontWeight: 600
    lineHeight: 1.33
    letterSpacing: 0px
rounded:
  none: 0px
  xs: 14px
  full: 9999px
spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 28px
  xxl: 32px
  xxxl: 40px
  section: 48px
  band: 80px
borderWidths:
  thin: 1px
shadows:
  sm: "rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px"
  md: "oklab(0.675596 -0.0119494 -0.0372961) 0px 4px 6px -1px, oklab(0.675596 -0.0119494 -0.0372961) 0px 2px 4px -2px"
elevationStrategy: layered-micro
themes:
  derived: light   # the other theme is the site's measured palette
  light:
    bg: "#F7F7FF"
    surface: "#EDEDF5"
    surfaceRaised: "#E6E6ED"
    text: "#1A1A1D"
    textMuted: "#6D6D72"
    border: "#D4D4DB"
    accent: "#544BF6"
    accentFg: "#FFFFFF"
    focusRing: "#7972F8"
    elevation: shadow
  dark:
    bg: "#232452"
    surface: "#222350"
    surfaceRaised: "#34355E"
    text: "#FFFFFF"
    textMuted: "#B2B2C2"
    border: "#E1E7EF"
    accent: "#C3C0FC"
    accentFg: "#0B0B0C"
    focusRing: "#C3C0FC"
    elevation: "border+surface"
gradients:
  - context: hero
    kind: radial
    value: "radial-gradient(289.99% 94.23% at 2.04% 22.21%, rgba(18, 10, 68, 0.5) 0%, rgba(74, 60, 157, 0.5) 99.99%, rgba(74, 60, 157, 0.5) 100%)"
components:
  button-filled:
    typography: "{typography.button-md}"
    textColor: "{colors.accent-6}"
    height: 44px
    padding: "8px 24px 8px 24px"
    rounded: "{rounded.xs}"
    backgroundColor: "{colors.neutral-2}"
  button-filled-2:
    typography: "{typography.button-md}"
    textColor: "rgb(248, 249, 251)"
    height: 44px
    padding: "8px 24px 8px 24px"
    rounded: "{rounded.xs}"
    backgroundColor: "{colors.accent-5}"
  button-text:
    typography: "{typography.body-md}"
    textColor: "{colors.neutral-1}"
    height: 56px
  button-outline:
    typography: "{typography.button-md}"
    textColor: "{colors.on-primary}"
    border: "1px solid {colors.hairline}"
    height: 44px
    padding: "8px 24px 8px 24px"
    rounded: "{rounded.xs}"
    backgroundColor: "{colors.primary}"
  button-icon:
    typography: "{typography.body-md}"
    textColor: "{colors.neutral-1}"
    border: "1px solid {colors.hairline}"
    height: 44px
    padding: "8px 4px 8px 4px"
    rounded: "3.35544e+07px"
    backgroundColor: "{colors.primary}"
  badge-icon:
    typography: "{typography.body-lg}"
    textColor: "{colors.ink}"
    height: 18px
  footer:
    typography: "{typography.body-md}"
    textColor: "{colors.neutral-1}"
    padding: "80px 16px 40px 16px"
    backgroundColor: "{colors.canvas}"
  link:
    textColor: "{colors.accent-3}"
    fontSize: 14px
    fontFamily: Figtree
    fontWeight: 600
    lineHeight: 1.43
  link-lg:
    typography: "{typography.body-sm}"
    textColor: "{colors.accent-3}"
states:
  input-focus:
    target: input
    state: focus
    outline: "rgba(0, 0, 0, 0) solid 2px"
    borderColor: "rgb(31, 89, 241)"
    outlineColor: "rgba(0, 0, 0, 0)"
    outlineWidth: 2px
  input-hover:
    target: input
    state: hover
    borderColor: "rgba(0, 0, 0, 0)"
    backgroundColor: currentcolor
  other-hover:
    target: other
    state: hover
    backgroundColor: "lab(0 0 0 / 0.03)"
  other-active:
    target: other
    state: active
    backgroundColor: "lab(0 0 0 / 0.06)"
breakpoints:
  - width: 375
    containerWidth: 197
    gridColumns: 2
    navLinksVisible: 0
    menuToggleVisible: true
    headingPx: 24
    bodyPx: 16
    sectionPaddingX: 0
  - width: 768
    containerWidth: 768
    gridColumns: 6
    navLinksVisible: 0
    menuToggleVisible: true
    headingPx: 24
    bodyPx: 16
    sectionPaddingX: 0
  - width: 1024
    containerWidth: 1024
    gridColumns: 6
    navLinksVisible: 0
    menuToggleVisible: false
    headingPx: 24
    bodyPx: 16
    sectionPaddingX: 0
  - width: 1280
    containerWidth: 1280
    gridColumns: 6
    navLinksVisible: 0
    menuToggleVisible: false
    headingPx: 24
    bodyPx: 16
    sectionPaddingX: 0
  - width: 1440
    containerWidth: 1280
    gridColumns: 6
    navLinksVisible: 0
    menuToggleVisible: false
    headingPx: 24
    bodyPx: 16
    sectionPaddingX: 0
coverage:
  statesFound: 61
  gradientsFound: 1
  rolesUnassigned: 8
  archetypesUnnamed: 0
  archetypesDetected: 0
  responsiveMeasured: true
  stylesheetsBlocked: false
  semanticRampDeclared: false
---

# Design System Inspired by Recovery.com

## 1. Visual Theme & Atmosphere

Recovery.com's design system projects trust, clarity, and accessibility through a serene, empathetic visual language. The palette combines a deep navy canvas (`{colors.canvas}` — `#232452`) with soft, approachable accent hues and abundant whitespace to create an inviting experience for users seeking mental health and addiction treatment resources. The aesthetic prioritizes legibility and emotional safety: primary typography is bold and authoritative, backgrounds are calm and non-clinical, and interactive elements use rounded corners and gentle colour transitions to reduce friction. This is a design system built for vulnerable audiences, where clarity and reassurance are paramount.

**Key Characteristics**
- Deep navy hero and canvas surfaces creating a grounded, trustworthy atmosphere
- Soft, pastel accent palette (lavender, sky blue, mint, peach) used for category and interaction affordances
- Generous whitespace and breathing room between content blocks
- Rounded button corners (`{rounded.xs}` — 14px) balanced with sharp card geometry for modern minimalism
- Layered micro-shadows for subtle depth without visual noise
- High-contrast text on neutral backgrounds ensuring accessibility
- Typography-first hierarchy with deliberate weight and sizing shifts
- Empathetic, non-clinical tone conveyed through colour warmth and spacing generosity

## 2. Color Palette & Roles

### Primary
- **Brand White** (`{colors.primary}` — `#FFFFFF`): Primary CTA fills, brand accent, active states, headings, and primary text across all contexts. The foundational ink colour anchoring the interface.
- **Brand Accent** (`{colors.accent}` — `#C3C0FC`): Lavender accent used alongside the primary white to create brand presence in decorative and secondary interactive contexts.

### Canvas & Surfaces
- **Canvas** (`{colors.canvas}` — `#232452`): Default page background and hero band fill. Deep navy establishes trust and creates a calm, grounded container for content.

### Interactive & Semantic
- **On Primary** (`{colors.on-primary}` — `#394E66`): Label and secondary text colour on brand surfaces; muted slate used for supporting information.

### Neutral Scale
- **Text Black** (`{colors.neutral-1}` — `#000000`): Primary body text and link copy; maximum contrast for readability.
- **Off-White** (`{colors.neutral-2}` — `#EFEDFF`): Light neutral surface used for subtle background differentiation and card fill.

### Surface & Borders
- **Hairline** (`{colors.hairline}` — `#E1E7EF`): 1px borders, dividers, and subtle input stroke. Provides separation without visual harshness.

### Decorative Accents (no measured role)
- **Slate Blue** (`{colors.accent-1}` — `#677D95`): Decorative; measured in non-interactive contexts.
- **Muted Navy** (`{colors.accent-2}` — `#4D657F`): Decorative; used for gradient and overlay depth.
- **Deep Navy** (`{colors.accent-3}` — `#162941`): Decorative; contributes to hero and background layering.
- **Purple** (`{colors.accent-4}` — `#25217A`): Decorative; measured in gradient overlays and non-interactive areas.
- **Dark Purple** (`{colors.accent-5}` — `#222263`): Decorative; part of background colour blocking and depth layers.
- **Vivid Purple** (`{colors.accent-6}` — `#31279B`): Decorative; used in gradient transitions and hero backgrounds.

## 3. Typography Rules

### Font Family
**FieldsVariable** (primary display and heading font)
- Fallback stack: `system-ui, -apple-system, sans-serif`

**Figtree** (secondary body and interface font)
- Fallback stack: `system-ui, -apple-system, sans-serif`

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|---|---|---|---|---|---|---|
| Display Extra Large | FieldsVariable | 34px | 400 | 1.24 | 0px | Hero headline; measured on large heading |
| Heading Large Strong | FieldsVariable | 32px | 500 | 1.19 | 0px | Section title with emphasis; measured on prominent heading |
| Heading Medium | Figtree | 32px | 300 | 1.19 | 0px | Large section heading; light weight for elegance |
| Heading Medium Strong | FieldsVariable | 32px | 500 | 1.19 | 0px | Prominent section title |
| Heading Small | FieldsVariable | 24px | 500 | 1.33 | 0px | Subsection title; measured on h2 |
| Heading Small Tight | FieldsVariable | 24px | 500 | 1 | 0px | Compact heading; minimal line spacing |
| Heading Extra Small | Figtree | 20px | 500 | 1.6 | 0px | Card and component headline |
| Body Large | Figtree | 18px | 400 | 1.56 | 0px | Primary body copy; breathing line height |
| Body Large Strong | Figtree | 18px | 500 | 1.56 | 0px | Emphasized body text with weight |
| Body Large FieldsVariable | FieldsVariable | 18px | 500 | 1.56 | 0.2px | Brand body text; slight tracking |
| Body Medium | Figtree | 16px | 400 | 1.5 | 0px | Standard body and list item copy |
| Body Medium Strong | Figtree | 16px | 600 | 1.5 | 0px | Emphasized paragraph text |
| Button Medium | Figtree | 16px | 500 | 1.5 | 0px | Primary and secondary button labels |
| Button Small | Figtree | 14px | 500 | 1.43 | 0.35px | Small button and tertiary action text |
| Body Small | Figtree | 14px | 400 | 1.43 | 0.35px | Supplementary and link copy |
| Caption Extra Small | Figtree | 12px | 400 | 1.33 | 0px | Supporting caption text |
| Caption Extra Small Strong | Figtree | 12px | 600 | 1.33 | 0px | Emphasized caption; badge labels |
| Caption Extra Small Capitalize | Figtree | 12px | 400 | 1.33 | 0px | Capitalized label text; text-transform: capitalize |

### Principles
- **Weight and size drive hierarchy, not colour**: Typography shifts in weight (300–600) and size (12–34px) establish information importance; colour remains consistent.
- **Generous line height improves accessibility**: Body text uses 1.5–1.56x line height to ensure comfort for extended reading on mental health topics.
- **FieldsVariable for moments of emphasis**: The variable serif-like FieldsVariable font is reserved for display and headings, adding personality and trust.
- **Figtree for clarity and function**: The primary interface font Figtree is clean, legible, and used for all body, button, and supporting text.
- **Tight line heights on headings reduce visual bulk**: Headings use 1–1.33x line height to maintain visual economy despite their size.

## 4. Component Stylings

### Buttons

#### Primary Filled (Purple Accent)
- **Background**: `rgb(239, 237, 255)` (light lavender)
- **Text Color**: `rgb(49, 39, 155)` (deep purple)
- **Font**: Figtree, 16px, weight 500, line-height 24px
- **Padding**: `{spacing.xs}` 24px (8px vertical, 24px horizontal)
- **Border Radius**: `{rounded.xs}` (14px)
- **Border**: None
- **Box Shadow**: None
- **Width**: 257px
- **Height**: 44px

#### Secondary Filled (Dark Navy)
- **Background**: `rgb(34, 34, 99)` (dark navy)
- **Text Color**: `rgb(248, 249, 251)` (off-white)
- **Font**: Figtree, 16px, weight 500, line-height 24px
- **Padding**: `{spacing.xs}` 24px
- **Border Radius**: `{rounded.xs}` (14px)
- **Border**: None
- **Box Shadow**: None
- **Width**: 214px
- **Height**: 44px

#### Outline (White Border)
- **Background**: `rgb(255, 255, 255)` (white)
- **Text Color**: `rgb(57, 78, 102)` (slate blue)
- **Font**: Figtree, 16px, weight 500, line-height 24px
- **Padding**: `{spacing.xs}` 24px
- **Border**: `1px solid {colors.hairline}` (`1px solid #E1E7EF`)
- **Border Radius**: `{rounded.xs}` (14px)
- **Box Shadow**: None
- **Width**: 156px
- **Height**: 44px

#### Text (Transparent)
- **Background**: Transparent
- **Text Color**: `rgb(0, 0, 0)` (black)
- **Font**: Figtree, 16px, weight 400, line-height 24px
- **Padding**: None
- **Border**: None
- **Border Radius**: `{rounded.none}` (0px)
- **Box Shadow**: None
- **Width**: 462px
- **Height**: 56px

#### Icon Button (Pill)
- **Background**: `rgb(255, 255, 255)` (white)
- **Text Color**: `rgb(0, 0, 0)` (black)
- **Font**: Figtree, 16px, weight 400, line-height 24px
- **Padding**: 8px 4px
- **Border**: `1px solid {colors.hairline}` (`1px solid #E1E7EF`)
- **Border Radius**: `{rounded.full}` (9999px — renders as pill)
- **Box Shadow**: None
- **Width**: 44px
- **Height**: 44px

### Cards & Containers

#### Center Card (Image + Text)
- **Background**: `rgb(255, 255, 255)` (white)
- **Border**: None
- **Border Radius**: `{rounded.none}` (0px — sharp edges)
- **Padding**: Varies by section; typically `{spacing.md}` horizontal
- **Box Shadow**: `{colors.shadow-sm}` — `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px`
- **Image Border Radius**: `{rounded.none}` (0px)
- **Text (Location)**: `{typography.body-md}` (`16px`, weight 400)
- **Text (Facility Name)**: `{typography.heading-xs}` (`20px`, weight 500)
- **Rating Colour**: Yellow/gold (measured RGB varies by hover state; primary use is 5-star display)

#### Treatment Category Card (Coloured Background + Icon)
- **Background**: Pastel colour block (Mint `#C8F0ED`, Lavender `#D9D6FF`, Sky Blue `#B7D6FF`, Peach `#FFCA9E`, Yellow `#FFCF70`)
- **Border**: None
- **Border Radius**: `{rounded.none}` (0px)
- **Padding**: `{spacing.lg}` (24px)
- **Icon**: Center-aligned, 24–32px
- **Text (Category Name)**: `{typography.heading-xs}` (`20px`, weight 500, color: `#162941`)
- **Text (Subtext)**: `{typography.body-sm}` (`14px`, weight 400, color: `#394E66`)
- **Box Shadow**: None

### Inputs & Forms

#### Search Input (Text)
- **Background**: `rgb(255, 255, 255)` (white)
- **Text Color**: `rgb(0, 0, 0)` (black)
- **Border**: `1px solid {colors.hairline}` (`#E1E7EF`)
- **Border Radius**: `{rounded.xs}` (14px)
- **Padding**: `{spacing.md}` (16px)
- **Font**: Figtree, `{typography.body-md}` (16px, weight 400)
- **Placeholder**: `rgb(103, 125, 149)` (muted slate)
- **Focus Border**: `rgb(31, 89, 241)` (blue)
- **Focus Box Shadow**: `var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow)`
- **Focus Outline**: Transparent 2px

### Navigation

#### Header Navigation (Desktop)
- **Background**: `{colors.primary}` (`#FFFFFF`)
- **Text Color**: `{colors.neutral-1}` (`#000000`)
- **Font**: Figtree, `{typography.body-md}` (16px, weight 400)
- **Padding**: `{spacing.md}` vertical
- **Link Hover State**: Opacity 0.9 or subtle background shift
- **Brand Logo**: Positioned left; vertically centered

#### Footer
- **Background**: `rgb(35, 36, 82)` (dark navy; matches hero)
- **Text Color**: `{colors.primary}` (`#FFFFFF`)
- **Font**: Figtree, `{typography.body-md}` (16px, weight 400)
- **Padding**: `{spacing.band}` top (80px), `{spacing.md}` sides (16px), `{spacing.xxxl}` bottom (40px)
- **Width**: Full viewport
- **Height**: 512px (measured container)
- **Box Shadow**: None

### Badges

#### Verification Badge (Icon)
- **Background**: Transparent
- **Icon Color**: `rgb(255, 255, 255)` (white)
- **Size**: 18px
- **Font**: Figtree, 18px, weight 400, line-height 28px

### Links

#### Default Link (Body)
- **Text Color**: `rgb(22, 41, 65)` (deep blue-grey)
- **Font**: Figtree, `{typography.caption-xs-strong}` (12px, weight 600, line-height 20px)
- **Underline**: Measured as transparent (no underline visible in base state)
- **Hover State**: Color remains same; optional opacity shift to 0.9

#### Link Large (Breadcrumb / Navigation)
- **Text Color**: `rgb(22, 41, 65)` (deep blue-grey)
- **Font**: Figtree, `{typography.body-sm}` (14px, weight 400, line-height 20px)
- **Padding**: None
- **Border**: None
- **Hover State**: Opacity 0.9 or subtle colour shift

## 5. Layout Principles

### Spacing System

Recovery.com uses a base unit of `{spacing.xxs}` (4px), scaling in a consistent geometric progression up to section-level spacing:

- **`{spacing.xxs}`** = 4px — Icon margins, tight element coupling
- **`{spacing.xs}`** = 8px — Button padding internal, small gaps
- **`{spacing.sm}`** = 12px — Form field margins, list item spacing
- **`{spacing.md}`** = 16px — Card padding, standard text spacing, header padding
- **`{spacing.lg}`** = 24px — Category card padding, section internal spacing
- **`{spacing.xl}`** = 28px — Medium section spacing
- **`{spacing.xxl}`** = 32px — Large section spacing
- **`{spacing.xxxl}`** = 40px — Hero padding, feature section separation
- **`{spacing.section}`** = 48px — Between major content blocks
- **`{spacing.band}`** = 80px — Full-width hero, footer top padding

**Usage Context**: Padding inside cards and containers typically uses `{spacing.md}` to `{spacing.lg}`. Margins between sections scale from `{spacing.section}` (48px) on desktop to `{spacing.lg}` (24px) on mobile. Hero sections and full-width bands use `{spacing.band}` (80px) for breathing room.

### Grid & Container

- **Max Width**: 1280px for content column (measured at 1440px viewport, which constrains to 1280px)
- **Column Strategy**: 6-column grid system (measured across all breakpoints where content is visible)
- **Content Column**: Expands from 197px (375px mobile) → 768px (768px tablet) → 1024px (1024px+) → capped at 1280px
- **Section Padding Horizontal**: 0px (content is full-width edge-to-edge; no forced side margins measured)
- **Breakpoint Behaviour**: Content expands proportionally with viewport up to the 1280px max width

### Whitespace Philosophy

Recovery.com prioritizes accessible, breathing whitespace. Vertical rhythm is maintained through consistent `{spacing.section}` (48px) gaps between major sections on desktop, collapsing to `{spacing.lg}` (24px) on mobile. Cards and containers use `{spacing.md}` (16px) internal padding to avoid visual clutter. Hero sections are deliberately spacious (`{spacing.band}` — 80px) to emphasize key messaging. This philosophy reflects the brand's empathetic approach: generous space reduces cognitive load and signals that the interface is approachable and not rushed.

### Border Radius Scale

- **`{rounded.none}`** = 0px — Cards, container images, badge base shapes; geometric minimalism
- **`{rounded.xs}`** = 14px — Button corners, input fields; approachable rounded touch
- **`{rounded.full}`** = 9999px — Icon buttons (pill-shaped for strong affordance)

**Component Contexts**:
- Card images: `{rounded.none}` (sharp, modern)
- Form inputs: `{rounded.xs}` (softer, inviting)
- Primary buttons: `{rounded.xs}` (consistent with input affordance)
- Icon buttons: `{rounded.full}` (unmistakable as interactive)
- Badge: `{rounded.none}` (minimalist)

### Border Widths

- **Thin** = `1px` — Used on outlines buttons, input strokes, and hairline dividers (`{colors.hairline}`)

## 6. Depth & Elevation

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow | Text buttons, transparent overlays, backgrounds |
| Micro | `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px` | Card lifts, subtle component depth (measured as `{colors.shadow-sm}`) |
| Medium | `oklab(0.675596 -0.0119494 -0.0372961) 0px 4px 6px -1px, oklab(0.675596 -0.0119494 -0.0372961) 0px 2px 4px -2px` | Dropdown and modal elevation (measured as `{colors.shadow-md}`) |

**Shadow Philosophy**: Recovery.com uses a layered-micro elevation strategy. Rather than relying on one bold shadow, the system stacks multiple transparent black layers (10–15px blur radius, 10% opacity) to create barely-perceptible depth. This prevents the interface from feeling flat while maintaining a calm, approachable aesthetic. Shadows are warm and soft, never harsh or clinical. Drop shadows are used sparingly: primarily on featured cards and dropdowns where layering aids usability.

### Z-index / Layering

- **Base** = 0 — Page content, normal flow
- **Dropdown** = 10, 15, 20, 30, 40, 50 — Cascading dropdowns and popovers (varied z-index suggests component specificity)
- **Sticky** = 301 — Sticky header or persistent navigation

**Layering Strategy**: The system uses a stacked z-index scale that reserves headroom for future modals and notifications. Dropdowns occupy the 10–50 range, allowing for multiple overlapping UI layers. The sticky navigation (301) floats well above interactive content, ensuring visibility without dominating.

## 7. Do's and Don'ts

### Do
- **Use `{rounded.xs}` (14px) for all primary interactive elements** (buttons, inputs) to create consistent affordance and approachability.
- **Maintain generous line heights (1.5+)** on body text to ensure accessibility and reduce cognitive load for users in vulnerable states.
- **Layer whitespace intentionally**: Use `{spacing.section}` (48px) between major content sections on desktop to guide eye movement and reduce overwhelm.
- **Apply shadow-sm sparingly** to card containers and featured content; reserve shadow-md for modals and elevation breaks.
- **Build typography hierarchy using weight and size**, not colour; this ensures legibility and maintains a calm, trusting tone.
- **Use the pastel category colours** (mint, lavender, sky blue, peach, yellow) to distinguish treatment types; these are warm, non-clinical, and approachable.
- **Keep buttons to a maximum of two primary actions per section** to avoid decision paralysis.
- **Test focus states explicitly**: Input focus borders should shift to `rgb(31, 89, 241)` with a visible ring for keyboard navigators.

### Don't
- **Avoid sharp card corners** (`{rounded.none}` is only for card containers and images; do not apply to interactive elements).
- **Do not invent new colours outside the palette**; the system is intentionally limited to canvas navy, white, slate, and soft accents.
- **Do not use error/success/warning colours**: The site does not declare semantic status states; avoid red, green, or orange outside the category palette.
- **Do not add shadows beyond shadow-sm and shadow-md**: Avoid custom drop shadows or layered effects; they break the micro-layering philosophy.
- **Do not compress line height on body text**: Minimum is 1.5x; tighter line heights reduce legibility for the audience.
- **Do not apply text underlines to links in body copy** unless explicitly marked for focus or hover states.
- **Do not use the brand accent lavender (`{colors.accent}` — `#C3C0FC`) for interactive CTAs**; it is decorative. Reserve it for brand marks and secondary accents.
- **Do not auto-hide navigation on tablet (768px)**; measured data shows nav links remain accessible (visible: 0) with a menu toggle, but this should be intentional, not assumed.

## 8. Responsive Behavior

### Breakpoints

| Breakpoint | Viewport Width | Content Width | Grid Columns | Nav Links Visible | Menu Toggle | Heading Size | Body Size | Section Padding X |
|---|---|---|---|---|---|---|---|---|
| Mobile | 375px | 197px | 2 | 0 | Yes | 24px | 16px | 0px |
| Tablet | 768px | 768px | 6 | 0 | Yes | 24px | 16px | 0px |
| Desktop | 1024px | 1024px | 6 | 0 | No | 24px | 16px | 0px |
| Large Desktop | 1280px | 1280px | 6 | 0 | No | 24px | 16px | 0px |
| Extra Large | 1440px | 1280px (capped) | 6 | 0 | No | 24px | 16px | 0px |

**Breakpoint Notes**:
- No breakpoint uses a full-width layout; content column always has an implicit max-width constraint.
- Navigation links remain hidden (visible: 0) across all measured breakpoints; a menu toggle appears instead. This suggests the site uses a persistent mobile-first hamburger strategy even on desktop.
- Typography sizes (heading: 24px, body: 16px) do not change across breakpoints; rhythm and spacing adapt instead.
- Section padding-x is consistently 0px, meaning content bleeds to viewport edges; padding is handled internally by container margins.

### Touch Targets

- **Minimum interactive element size**: 44px (measured on buttons and icon buttons)
- **Button padding**: `{spacing.xs}` vertical × 24px horizontal = comfortable tap target
- **Icon button**: 44×44px (meets 48px guideline threshold)
- **Link hit area**: Implicit from text size; recommend min 44px for standalone links

### Collapsing Strategy

**Mobile (375px)**
- Content width compresses to 197px (roughly 50% of viewport after margin collapse)
- Grid shifts from 6 columns to 2-column layout
- Hero headline remains 24px (not compressed further)
- Body text remains 16px for legibility
- Spacing scales down: `{spacing.section}` (48px) → `{spacing.lg}` (24px) between sections
- Hero section maintains `{spacing.band}` (80px) padding top/bottom to preserve visual impact

**Tablet (768px)**
- Content width expands to full 768px
- Grid remains 6-column
- No typography shifts
- Section spacing adapts to viewport proportionally
- Search input and featured cards expand to fill available width

**Desktop (1024px+)**
- Content width maxes at 1280px (measured constraint at 1440px viewport)
- Typography and spacing remain fixed
- Multi-column grids unlock fully (6 columns available)
- Menu toggle disappears (though nav links remain hidden; menu is likely still present off-screen)

**Key Adaption Rule**: Rather than compressing typography, the system adapts spacing and grid columns. Headings and body text remain readable at all breakpoints; visual hierarchy is maintained through rhythm shifts instead of size reductions.

## 9. Agent Prompt Guide

### Quick Color Reference
- **Primary CTA / Brand**: White (`{colors.primary}` — `#FFFFFF`) — button fill, headings, brand mark
- **Accent / Category Tags**: Lavender (`{colors.accent}` — `#C3C0FC`) — decorative, secondary accents
- **Canvas / Hero Background**: Navy (`{colors.canvas}` — `#232452`) — page background, hero band
- **Body Text**: Black (`{colors.neutral-1}` — `#000000`) — primary copy
- **Links / Supporting Text**: Deep Blue-Grey (`rgb(22, 41, 65)`) — links, secondary labels
- **Input Border / Divider**: Hairline (`{colors.hairline}` — `#E1E7EF`) — 1px strokes
- **Focus State**: Blue (`rgb(31, 89, 241)`) — input focus border
- **Category Background** (Mint, Lavender, Sky, Peach, Yellow): Pastel blocks for treatment type cards

### Iteration Guide

1. **Always use the measured colour values verbatim**: Never approximate `#232452` as `#232450` or `#E1E7EF` as `#E0E7EF`. Hexadecimal precision ensures brand consistency.

2. **Button radius is always `{rounded.xs}` (14px) for CTA and form inputs**: Icon buttons use `{rounded.full}` (9999px) to render as pills; card images use `{rounded.none}` (0px).

3. **Shadow treatment is micro-layered, not bold**: Apply `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px` + `rgba(0, 0, 0, 0.1) 0px 4px 6px -4px` for subtle lift on cards. Do not invent new shadows.

4. **Typography hierarchy is weight + size, not colour**: Use Figtree 16px / weight 500 for buttons; FieldsVariable 24px / weight 500 for headings. Never change text colour to indicate hierarchy.

5. **Line height on body text is non-negotiable**: Minimum 1.5x (measured as 24px line-height on 16px body). This accessibility measure is central to the brand's empathetic positioning.

6. **Spacing units scale predictably**: 4px base unit → 8, 12, 16, 24, 28, 32, 40, 48, 80px. Use these tokens only; do not invent intermediate values.

7. **Form inputs, buttons, and search fields all share `{rounded.xs}` (14px) and the hairline border**: This creates a unified affordance language; users immediately recognize interactive surfaces.

8. **Focus states on inputs shift border to `rgb(31, 89, 241)` and show a ring shadow**: Keyboard navigation must be fully supported; do not hide focus indicators.

9. **Hero section uses the radial gradient** (`radial-gradient(289.99% 94.23% at 2.04% 22.21%, rgba(18, 10, 68, 0.5) 0%, rgba(74, 60, 157, 0.5) 99.99%, rgba(74, 60, 157, 0.5) 100%)`) over a navy canvas background for atmospheric depth.

10. **Breakpoints adapt spacing and grid, not typography**: Heading and body text remain 24px and 16px respectively from 375px to 1440px. Adjust `{spacing.section}` and container padding proportionally based on viewport.

## 10. Known Gaps

- **No explicit error/success/warning semantic colours extracted**: The site does not declare a status colour ramp in its markup. Avoid inventing red, green, or amber states; record such additions as design extensions outside this document.
- **Eight accent colours (`{colors.accent-1}` through `{colors.accent-6}`) have no measured role**: They appear in gradients, overlays, and decorative contexts but lack a specific semantic function. Treat them as decorative only; do not assign them functional roles.
- **Interaction states are incomplete**: Hover, active, and focus-visible states are partially extracted but not comprehensive across all components. Icon button hover, card hover, and category card hover states were observed; button pressed/active states and disabled states were not explicitly measured.
- **Dark mode or theme switching not observed**: The extraction covered one visual state only. If a dark mode variant exists, it was not captured; record any dark-mode implementation as an extension.
- **Surfaces behind authentication not analysed**: Login, account, and user-specific pages were not visited. Any authenticated-user-only UI patterns (e.g., saved centres, user preferences) are outside the scope of this document.
- **Modal and toast component patterns not extracted**: The interaction states reference modals and toast elements, but full component styling and layout were not measured on a live page.
- **Opacity scale not fully mapped**: While opacity values appear in interaction states (e.g., `opacity: 0.9`), the system does not declare a formal opacity token scale (e.g., for disabled or overlay states).
- **Specific link underline and hover animations not confirmed**: Links show color shifts on hover, but the precise animation timing, underline behaviour, and text-decoration properties were not explicitly captured.
- **Dropdown and sticky nav interaction detail missing**: Z-index values for dropdowns and sticky nav exist, but padding, animation timing, and full visual treatment of these components were not measured on a live interaction.

---

# Token Reference

```yaml
colors:
  primary: "#FFFFFF"
  accent: "#C3C0FC"
  accent-1: "#677D95"
  accent-2: "#4D657F"
  accent-3: "#162941"
  accent-4: "#25217A"
  accent-5: "#222263"
  accent-6: "#31279B"
  canvas: "#232452"
  on-primary: "#394E66"
  hairline: "#E1E7EF"
  neutral-1: "#000000"
  neutral-2: "#EFEDFF"
  shadow-sm: "rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px"
  shadow-md: "oklab(0.675596 -0.0119494 -0.0372961) 0px 4px 6px -1px, oklab(0.675596 -0.0119494 -0.0372961) 0px 2px 4px -2px"

typography:
  heading-sm: { font: FieldsVariable, size: "24px", weight: 500, lineHeight: 1.33, letterSpacing: "0px" }
  body-lg-strong: { font: FieldsVariable, size: "18px", weight: 500, lineHeight: 1.56, letterSpacing: "0.2px" }
  heading-lg: { font: FieldsVariable, size: "34px", weight: 400, lineHeight: 1.24, letterSpacing: "0px" }
  heading-md-strong: { font: FieldsVariable, size: "32px", weight: 500, lineHeight: 1.19, letterSpacing: "0px" }
  heading-sm-tight: { font: FieldsVariable, size: "24px", weight: 500, lineHeight: 1, letterSpacing: "0px" }
  heading-xs: { font: Figtree, size: "20px", weight: 500, lineHeight: 1.6, letterSpacing: "0px" }
  body-sm: { font: Figtree, size: "14px", weight: 400, lineHeight: 1.43, letterSpacing: "0.35px" }
  button-sm: { font: Figtree, size: "14px", weight: 500, lineHeight: 1.43, letterSpacing: "0.35px" }
  body-md: { font: Figtree, size: "16px", weight: 400, lineHeight: 1.5, letterSpacing: "0px" }
  body-lg: { font: Figtree, size: "18px", weight: 400, lineHeight: 1.56, letterSpacing: "0px" }
  body-lg-2: { font: Figtree, size: "18px", weight: 500, lineHeight: 1.56, letterSpacing: "0px" }
  button-md: { font: Figtree, size: "16px", weight: 500, lineHeight: 1.5, letterSpacing: "0px" }
  caption-xs-strong: { font: Figtree, size: "12px", weight: 600, lineHeight: 1.33, letterSpacing: "0px" }
  heading-md: { font: Figtree, size: "32px", weight: 300, lineHeight: 1.19, letterSpacing: "0px" }
  caption-xs-capitalize: { font: Figtree, size: "12px", weight: 400, lineHeight: 1.33, letterSpacing: "0px", textTransform: "capitalize" }
  caption-xs: { font: Figtree, size: "12px", weight: 400, lineHeight: 1.33, letterSpacing: "0px" }

spacing:
  xxs: "4px"
  xs: "8px"
  sm: "12px"
  md: "16px"
  lg: "24px"
  xl: "28px"
  xxl: "32px"
  xxxl: "40px"
  section: "48px"
  band: "80px"

rounded:
  none: "0px"
  xs: "14px"
  full: "9999px"

shadows:
  sm: "rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px"
  md: "oklab(0.675596 -0.0119494 -0.0372961) 0px 4px 6px -1px, oklab(0.675596 -0.0119494 -0.0372961) 0px 2px 4px -2px"

borders:
  thin: "1px"
```