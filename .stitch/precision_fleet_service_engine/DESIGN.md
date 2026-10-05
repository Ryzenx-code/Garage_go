---
name: Precision Fleet & Service Engine
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#444653'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#757684'
  outline-variant: '#c4c5d5'
  surface-tint: '#3755c3'
  primary: '#00288e'
  on-primary: '#ffffff'
  primary-container: '#1e40af'
  on-primary-container: '#a8b8ff'
  inverse-primary: '#b8c4ff'
  secondary: '#a73a00'
  on-secondary: '#ffffff'
  secondary-container: '#fd651e'
  on-secondary-container: '#571a00'
  tertiary: '#2d3449'
  on-tertiary: '#ffffff'
  tertiary-container: '#434b60'
  on-tertiary-container: '#b4bbd5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#173bab'
  secondary-fixed: '#ffdbce'
  secondary-fixed-dim: '#ffb599'
  on-secondary-fixed: '#370e00'
  on-secondary-fixed-variant: '#7f2b00'
  tertiary-fixed: '#dae2fd'
  tertiary-fixed-dim: '#bec6e0'
  on-tertiary-fixed: '#131b2e'
  on-tertiary-fixed-variant: '#3f465c'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
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
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system defines a high-trust, engineered interface for automotive maintenance and digital service booking. The design language marries modern SaaS efficiency with the tactile clarity of performance instrumentation. It balances deep institutional confidence—evoking seasoned mechanics and certified technicians—with frictionless, consumer-ready clarity.

The aesthetic follows an **Engineered SaaS** model: crisp, structured grid layouts, low-friction micro-interactions, subtle technical depth, and hyper-legible typography. It avoids playful fluff in favor of dependable utility, utilizing deep structural blues to anchor stability and high-visibility automotive amber-orange to direct operational focus and urgent actions.

## Colors

The palette establishes an authoritative, high-contrast visual environment engineered for clear readability in diverse environments—from brightly lit service desks to dim repair bays.

### Palette Architecture
- **Primary (`#1e40af` light / `#3b82f6` dark):** Automotive endurance blue. Applied to primary CTAs, active navigation items, confirmed states, and brand anchors.
- **Secondary / Accent (`#ea580c` light / `#f97316` dark):** High-visibility safety orange. Reserved for critical conversion funnels, "Book Now" prompts, real-time diagnostic alerts, and dispatch triggers.
- **Tertiary (`#0f172a` light / `#f8fafc` dark):** Structural dark slate/navy used for high-emphasis headlines, active card borders, and grounded structural headers.
- **Neutrals:**
  - Light mode canvas: `#f8fafc` (slate-50) with pure `#ffffff` cards and `#e2e8f0` (slate-200) structural dividers.
  - Dark mode canvas: `#0b1120` (deep automotive void) with `#131c31` surface panels and `#1e293b`/`#334155` subtle boundary borders.
- **Semantic Feedback:**
  - Success: `#16a34a` (light) / `#22c55e` (dark) for passed inspections and completed bookings.
  - Warning: `#d97706` (light) / `#f59e0b` (dark) for upcoming service milestones and tire wear warnings.
  - Error: `#dc2626` (light) / `#ef4444` (dark) for failed diagnostics and overdue repairs.
  - Info: `#2563eb` (light) / `#60a5fa` (dark) for service notes and telemetry updates.

## Typography

The typographic hierarchy implements **Plus Jakarta Sans** for headlines and interface labeling to provide a contemporary, geometric automotive demeanor, paired with **Inter** for dense technical logs, service manuals, and input data.

Numeric readouts such as VIN numbers, mileage, diagnostic fault codes (DTC), and pricing breakdowns must always utilize tabular figures (`font-variant-numeric: tabular-nums`) to preserve columnar alignment across table cells and telemetry modules.

## Layout & Spacing

This design system uses a strict **8-point spatial matrix** nested inside a 12-column responsive fluid grid.

- **Desktop (1024px+):** 12 columns, `margin: 2rem`, `gutter: 1.5rem`. Service schedules, garage calendars, and telemetry views render in high-density multi-pane splits (e.g., 4-col filter/vehicle tree + 8-col booking grid).
- **Tablet (768px – 1023px):** 8 columns, `margin: 1.5rem`, `gutter: 1rem`. Multi-step booking processes drop to single-column vertical flows with docked sticky bottom summaries.
- **Mobile (< 768px):** 4 columns, `margin: 1rem`, `gutter: 1rem`. All inspection checklists, time-slot selection carousels, and diagnostic cards stack to full viewport width.

## Elevation & Depth

Visual depth combines crisp surface delineations with directional ambient shadows. Instead of murky grey drop-shadows, elevations use subtle navy-tinted values that preserve structural clarity under harsh lighting.

- **Level 0 (Flat Canvas):** `#f8fafc` (dark: `#0b1120`). Static base layer.
- **Level 1 (Cards & Service Modules):** `#ffffff` (dark: `#131c31`) encased in a 1px border of `#e2e8f0` (dark: `#1e293b`) with shadow `0 1px 3px 0 rgba(15, 23, 42, 0.05), 0 1px 2px -1px rgba(15, 23, 42, 0.05)`.
- **Level 2 (Interactive Hover & Dropdowns):** Shadow `0 4px 6px -1px rgba(15, 23, 42, 0.08), 0 2px 4px -2px rgba(15, 23, 42, 0.06)`. Border sharpens to slate-300 or active brand blue.
- **Level 3 (Modals, Overlays & Sticky Booking Sheets):** Shadow `0 20px 25px -5px rgba(15, 23, 42, 0.12), 0 8px 10px -6px rgba(15, 23, 42, 0.08)` backed by a backdrop-filter blur of `4px` with a 40% `#0f172a` scrim.

## Shapes

The design system incorporates calibrated curvatures that soften clinical technical data while preserving industrial precision. 

Cards and modal containers strictly use `rounded-xl` (1.5rem / 24px) to create distinctive vehicle and booking pods. Interactive components—such as buttons, text inputs, and select triggers—use standard `rounded` (0.5rem / 8px). Micro-indicators, status chips, and diagnostic tags feature pill shaping (`rounded-full`) to immediately distinguish contextual status badges from actionable rectangular buttons.

## Components

### Buttons
- **Primary:** Background `#1e40af` (dark: `#3b82f6`), text white, `height: 44px`, horizontal padding `space-lg`, border-radius `0.5rem`, font `label-lg`. Subtle hover lift with brightness transition.
- **Action Accent (Booking/Dispatch):** Background `#ea580c` (dark: `#f97316`), text white, high-emphasis shadow tint.
- **Secondary / Outline:** 1px border `#e2e8f0` (dark: `#334155`), background transparent, text `#0f172a` (dark: `#f8fafc`). Hover fills with `#f1f5f9` (dark: `#1e293b`).

### Chips & Precision Badges
- **Status Tags:** Pill-shaped (`rounded-full`), padding `0.25rem 0.75rem`, font `label-sm`.
- **States:**
  - *Inspection Passed:* Background `#dcfce7`, text `#15803d` (dark: bg `#14532d`/40%, text `#4ade80`).
  - *Service Urgent:* Background `#ffedd5`, text `#c2410c` (dark: bg `#7c2d12`/40%, text `#fb923c`).
  - *Diagnostic Fault:* Background `#fee2e2`, text `#b91c1c` (dark: bg `#7f1d1d`/40%, text `#f87171`).

### Form Inputs & Selectors
- **Text Inputs:** `height: 44px`, background `#ffffff` (dark: `#131c31`), border 1px solid `#e2e8f0` (dark: `#334155`), padding `0 0.875rem`, radius `0.5rem`.
- **Focus State:** 2px ring `#1e40af` with an offset of 1px.
- **Helper Labels:** Positioned above the field in `label-md` using secondary text `#64748b` (dark: `#94a3b8`).

### Selection Controls (Checkboxes & Radios)
- Checkboxes: 18px × 18px, `rounded` (4px), checked fill `#1e40af` with crisp white checkmark vector.
- Radio buttons: 18px × 18px with a centered 8px active pip in `#1e40af`.

### Service Cards
- Container with `rounded-xl` (1.5rem), Level 1 elevation, padding `space-lg`.
- Top header carries vehicle registration/model in `headline-sm`, complemented by dynamic status badge in upper-right corner.
- Horizontal metric shelf displaying mileage, fluid health, and next booking slot divided by subtle 1px vertical borders.