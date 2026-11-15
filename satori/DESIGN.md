---
name: Contemplative Synthesis
colors:
  surface: '#13131a'
  surface-dim: '#13131a'
  surface-bright: '#393841'
  surface-container-lowest: '#0d0d15'
  surface-container-low: '#1b1b23'
  surface-container: '#1f1f27'
  surface-container-high: '#292932'
  surface-container-highest: '#34343d'
  on-surface: '#e4e1ec'
  on-surface-variant: '#c8c4d8'
  inverse-surface: '#e4e1ec'
  inverse-on-surface: '#303038'
  outline: '#928ea1'
  outline-variant: '#474555'
  surface-tint: '#c6bfff'
  primary: '#c6bfff'
  on-primary: '#2700a0'
  primary-container: '#5138e5'
  on-primary-container: '#d2ccff'
  inverse-primary: '#553ee9'
  secondary: '#ffb59d'
  on-secondary: '#5d1800'
  secondary-container: '#982d00'
  on-secondary-container: '#ffb49d'
  tertiary: '#ffb597'
  on-tertiary: '#591d00'
  tertiary-container: '#9e3a00'
  on-tertiary-container: '#ffc6af'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e4dfff'
  primary-fixed-dim: '#c6bfff'
  on-primary-fixed: '#160066'
  on-primary-fixed-variant: '#3c17d2'
  secondary-fixed: '#ffdbd0'
  secondary-fixed-dim: '#ffb59d'
  on-secondary-fixed: '#390b00'
  on-secondary-fixed-variant: '#842500'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb597'
  on-tertiary-fixed: '#360f00'
  on-tertiary-fixed-variant: '#7e2c00'
  background: '#13131a'
  on-background: '#e4e1ec'
  surface-variant: '#34343d'
  parchment-glow: '#FAF8F5'
  parchment-muted: '#F2EFE9'
  celestial-indigo: '#5138E5'
  cinders-ember: '#B84318'
  obsidian-base: '#181820'
  obsidian-elevated: '#20202B'
  telemetry-emerald: '#10B981'
typography:
  headline-hero:
    fontFamily: EB Garamond
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  headline-hero-mobile:
    fontFamily: EB Garamond
    fontSize: 38px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: EB Garamond
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: 0em
  headline-sm:
    fontFamily: EB Garamond
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 30px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  code-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: -0.01em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-desktop: 2rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system embodies the ethos of a high-leverage cognitive tool and personal wisdom engine built to eventually be outgrown. Merging Eastern philosophical restraint with the precision of modern Unix philosophy, the visual identity balances intellectual depth with developer-grade utility.

The aesthetic direction synthesizes **Modern Editorial Minimalist** and **Dark-Surface Technical Precision**:
- **Target Audience:** Developers, researchers, algorithmic thinkers, and polymaths seeking mental clarity, deep focus, and self-directed evolution rather than synthetic dependency.
- **Atmosphere:** Contemplative, quiet, authoritative, and luminous. High-contrast textual density alternates with generous negative space, evoking the tactile luxury of illuminated manuscripts alongside the uncompromising clarity of an unbloated terminal interface.
- **Visual Tenets:** Razor-sharp layout grids, subtle hairline dividers, micro-glow celestial accents, and deliberate typographical pacing.

## Colors

The palette establishes an introspective dark atmosphere framed by profound obsidian foundations, luminous ink parchment highlights, and purposeful chromatic accents:

- **Primary (`#5138E5` - Celestial Indigo):** Represents moments of cognitive leap, synthesis, and sudden insight (*satori*). Used exclusively for critical interactive hooks, active state indicators, telemetry focus nodes, and primary conversion targets.
- **Secondary (`#B84318` - Cinders Ember):** Represents human warmth, distillation, urgency, and transient thought processes. Applied to critical telemetry badges, latency warnings, and contrast milestones.
- **Neutral (`#181820` - Obsidian Deep):** The foundational substrate. Grounded in near-black charcoal with deep cool-slate undertones, eliminating OLED glare while retaining infinite depth.
- **Parchment Accents (`#FAF8F5` / `#F2EFE9`):** Reserved for primary editorial headings, active code brackets, and crystalline data metrics to mirror the tactile clarity of physical print against a void.
- **Semantic Usage:** Surfaces step sequentially from `#181820` (canvas) to `#20202B` (elevated panels), enclosed with hairline borders (`rgba(250, 248, 245, 0.08)`).

## Typography

The typographic hierarchy establishes a three-way dynamic between philosophical contemplation, clean readability, and technical precision:

1. **EB Garamond (Editorial Display):** Anchors major conceptual assertions, manifesto narratives, and section titles. Rendered at optical sizing with generous leading to communicate gravity, human heritage, and reflective thought.
2. **Inter (Systematic Sans):** Delivers cognitive prose, descriptive UI annotations, and form feedback with absolute neutrality and legibility across all display densities.
3. **JetBrains Mono (Technical / Telemetry):** Used for benchmarks, command syntax, latency measurements, tags, architectural metadata, and status badges, maintaining rigorous developer cred.

## Layout & Spacing

The layout is built upon a balanced, fluid 12-column grid designed for dense information parsing and breathing room for reflective contemplation:

- **Desktop (>=1200px):** 12-column configuration constrained to a `1280px` max-width. Employs `2rem` gutters and minimum `3rem` canvas margins. Content alternates between compact reading wells (6–8 columns) and wide terminal telemetry spans (12 columns).
- **Tablet (768px - 1199px):** 8-column layout with `1.5rem` gutters and `2rem` outer margins. Side-by-side analytical cards collapse into stacked dual-column sets.
- **Mobile (<768px):** 4-column responsive structure with `1rem` margins and `1rem` gutters. High-impact benchmarks and telemetry ribbons transition to horizontally scrolling snap-strips.
- **Vertical Cadence:** Multi-tier rhythmic pacing using `space-2xl` (`4rem`) to demarcate thematic shift, down to `space-xs` (`0.25rem`) for fine-grained badge internal alignment.

## Elevation & Depth

Rather than conventional drop shadows, this design system uses dark-surface physical layering combined with low-emittance celestial glows:

- **Ground Canvas:** Strict `#181820` matte obsidian surface.
- **Structural Elevation 1 (Card & Module Shells):** Elevated to `#20202B` and enclosed by a subtle 1px perimeter outline composed of `rgba(250, 248, 245, 0.08)`.
- **Structural Elevation 2 (Floating Popovers, Terminals, Focus Drawers):** `#252533` base surface, fortified with an ambient low-opacity shadow tinted with insight indigo: `0 16px 36px -8px rgba(81, 56, 229, 0.16), 0 0 1px 1px rgba(250, 248, 245, 0.12)`.
- **Backdrop Filters:** Translucent surfaces utilize `backdrop-filter: blur(12px)` over dynamic terminal code streams to produce a soft atmospheric depth without sacrificing line precision.

## Shapes

The geometric signature is architectural, deliberate, and restrained:

- **Base Radius (Soft - Level 1):** Interactive cards, code frames, and primary panels implement a disciplined `0.25rem` (4px) corner radius, extending to `0.5rem` (8px) for major modal containers.
- **Telemetry & Terminal Strips:** Adhere to square or micro-chamfered edges, reinforcing structural discipline.
- **Pill Exceptions:** Explicitly reserved for status badges, release chips, and real-time inference trackers to immediately signal non-containerized metadata.

## Components

### Buttons & Interactive Triggers
- **Primary Action (Moment of Insight):** `#5138E5` fill with `#FAF8F5` text, 4px radius, padded with `0.625rem 1.25rem`. On hover, casts a focused luminescence: `box-shadow: 0 0 20px rgba(81, 56, 229, 0.45)`.
- **Secondary Action (Ghost Protocol):** Transparent background, 1px perimeter of `rgba(250, 248, 245, 0.2)` with parchment text `#FAF8F5`. Transitions to `rgba(250, 248, 245, 0.06)` surface fill upon hover.
- **Tertiary Action:** Monospaced label (`JetBrains Mono`, 12px) featuring an inline terminal arrow `->`, underlined with a subtle indigo border on interaction.

### Telemetry Badges & Chips
- **Structural Chips:** 11px uppercase `JetBrains Mono` nestled inside a pill container with a `rgba(250, 248, 245, 0.06)` base and 1px border.
- **Status Indicators:** Micro-dots (6px) glowing with emerald (`#10B981`) for engine uptime or celestial indigo (`#5138E5`) for synthetic inference.

### Terminal & Code Blocks
- Deep `#121217` shell with a discrete header bar displaying source path, memory consumption, and an active copy trigger.
- Monospaced line numbers set at 40% parchment opacity; syntax-highlighted using cool lavenders, parchment whites, and ember warnings.

### Data Cards & Wisdom Benchmark Nodes
- Constructed with `#20202B` fill, hair-thin `rgba(250, 248, 245, 0.08)` borders, and generous `space-lg` inner padding.
- Metric cards showcase top-level numbers in high-contrast `#FAF8F5`, supported by delta indicators and editorial subtext explaining the qualitative benchmark.

### Input Fields
- Dark well `#14141A` with a 1px border (`rgba(250, 248, 245, 0.14)`), shifting to an unyielding `#5138E5` border with subtle outer glow on keyboard focus.
- Monospaced placeholder tokens set to 40% parchment opacity.

### Selection Controls (Checkboxes & Radios)
- Compact, sharp-cornered square inputs (4px) with custom checkmarks, adopting `#5138E5` fill only when confirmed.