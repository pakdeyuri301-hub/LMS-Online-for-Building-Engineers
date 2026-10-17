---
name: RuangTeknik M&E Engineering LMS
colors:
  surface: '#f8f9ff'
  surface-dim: '#d6dae4'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f4fd'
  surface-container: '#eaeef8'
  surface-container-high: '#e4e8f2'
  surface-container-highest: '#dee2ec'
  on-surface: '#171c23'
  on-surface-variant: '#584140'
  inverse-surface: '#2c3138'
  inverse-on-surface: '#edf1fb'
  outline: '#8b716f'
  outline-variant: '#dfbfbd'
  surface-tint: '#aa3435'
  primary: '#540008'
  on-primary: '#ffffff'
  primary-container: '#790d16'
  on-primary-container: '#ff7f7b'
  inverse-primary: '#ffb3af'
  secondary: '#6a5d40'
  on-secondary: '#ffffff'
  secondary-container: '#f3e1bc'
  on-secondary-container: '#706346'
  tertiary: '#132834'
  on-tertiary: '#ffffff'
  tertiary-container: '#293e4b'
  on-tertiary-container: '#93a9b8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad7'
  primary-fixed-dim: '#ffb3af'
  on-primary-fixed: '#410005'
  on-primary-fixed-variant: '#891b20'
  secondary-fixed: '#f3e1bc'
  secondary-fixed-dim: '#d6c5a1'
  on-secondary-fixed: '#231a04'
  on-secondary-fixed-variant: '#51452a'
  tertiary-fixed: '#cfe6f6'
  tertiary-fixed-dim: '#b3c9da'
  on-tertiary-fixed: '#071e2a'
  on-tertiary-fixed-variant: '#354957'
  background: '#f8f9ff'
  on-background: '#171c23'
  surface-variant: '#dee2ec'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.005em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
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
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: -0.01em
  label-badge:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  label-k3:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system establishes a high-precision, industrial engineering aesthetic tailored for Building Mechanical & Electrical (M&E) technicians, facility managers, and engineering teams. The product balances rigorous operational discipline with ergonomic, eye-fatigue-reducing learning surfaces.

### Brand Personality & Core Values
- **Authoritative & Standardized:** Evoking strict engineering standards, building codes, and safety protocols.
- **Pragmatic & Field-Tested:** Designed for clarity in both desktop study environments and on-site tablet operation.
- **Calm & Functional:** Mitigates the glare and sterile coldness of typical enterprise software by leveraging warm, drafting-paper-inspired tones.

### Visual Style
The design language combines **Modern Technical Blueprint** principles with **Structured Industrial Card Systems**:
- Clean, hairline architectural borders mimicking schematics and technical drafting.
- Clear structural division between operational modules, SOP checklists, wiring schematics, and K3 (Occupational Health & Safety) warning systems.
- High-contrast typography paired with tactile, utilitarian indicators and distinct status badges.

## Colors

The palette grounds high-consequence engineering learning in authoritative maroon and warm, non-fatiguing drafting backgrounds.

### Core Roles
- **Primary (`#790D16` - Industrial Maroon):** Used for foundational brand actions, primary completion flows, certificate badges, and active module anchors.
- **Secondary (`#E5D3AF` - Drafting Beige):** Structural accents, callout containers, step counter highlights, and technical module badges.
- **Tertiary (`#AEC4D4` - M&E Technical Blue):** Mechanical/electrical circuit indicators, technical diagrams, flow meters, reading progress tracks, and operational references.
- **Neutral Dark (`#1E232A` - Engineering Slate):** High-contrast body text, vector schematics, line art, and dominant headers.

### Surface System
- **App Canvas:** Cream (`#F5EFE1`) provides an anti-glare, tactile base reminiscent of engineering manuals.
- **Card Surface & Readout:** White (`#FFFFFF`) for primary content reading panels, test questions, and schematic viewports.
- **Elevated / Secondary Container:** Cream Light (`#FAF7F2`) for sidebars, secondary tools, parameter grids, and filter toolbars.
- **Subtle Outline / Hairline:** `#E1D5C1` for card borders and table rules.

### Operational & K3 Status Tokens
- **K3 Bahaya / Critical:** `#BA1A1A` with `#FFDAD6` background (high-voltage risks, emergency lockouts, critical SOP failures).
- **K3 Peringatan / Warning:** `#8F4E00` with `#FFE088` background (maintenance cautions, pending certification checks).
- **Selesai / Operational Normal:** `#1B6D2F` with `#D7F5D7` background (passed modules, energized status, verified SOP).
- **Sedang Berjalan / Active:** `#0F5B8C` with `#D2E7FF` background (in-progress courses, ongoing inspection tasks).
- **Draft / Archived:** `#5B6068` with `#E5E7EB` background (unpublished content, historical logs).

## Typography

The typography architecture uses a strict combination of **Inter** for administrative and didactic material and **JetBrains Mono** for technical specs, machinery codes, sensor units, and SOP step numbers.

### Hierarchy & Usage
- **Display & Headline Levels (Inter Bold/SemiBold):** Set in neutral dark `#1E232A`. Provides a clear, uncluttered header presence across complex dashboards and training modules.
- **Body Text (Inter Regular):** Tuned for sustained reading during technical diagnostic reviews. The 26px line height at 16px font size ensures high readability in ambient field light.
- **Technical Readouts & Machine IDs (`label-code` via JetBrains Mono):** Applied to equipment tags (e.g., `AHU-CH-04`, `MCCB-3P-400A`), parameter values (`415V / 50Hz`), and measurement tables.
- **Badges & K3 Safety Labels (`label-badge`, `label-k3`):** Uppercase, tracked out (+0.04em to +0.06em) for rapid identification under urgent diagnostic scenarios.

## Layout & Spacing

The design system implements a 12-column grid system tuned for dense technical dashboards, split-screen diagnostic readers, and multi-step assessment forms.

### Grid & Form Factors
- **Desktop (>= 1280px):** 12-column layout with 20px (`1.25rem`) gutters and 32px (`2rem`) margins. Allows a persistent 280px left rail for module navigation/schematic index and an 8-column reading viewport flanked by a 3-column reference/SOP sidebar.
- **Tablet / Industrial Rugged Pads (768px - 1279px):** 8-column layout with 16px gutters and 24px margins. Navigation collapses to an off-canvas drawer or top persistent segmented bar. Diagnostic diagrams support horizontal pan-and-pinch viewports.
- **Mobile (<= 767px):** 4-column layout with 12px (`0.75rem`) gutters and 16px (`1rem`) page margins. Technical data tables switch to responsive key-value definition cards.

### Layout Rhythm
- Spacing follows an 8px base rhythm (`space-xs` = 4px, `space-sm` = 8px, `space-md` = 16px, `space-lg` = 24px, `space-xl` = 40px).
- Module sections, SOP procedures, and quiz groups are bound within white cards separated by `space-lg`.

## Elevation & Depth

To preserve an industrial blueprint and engineering ledger appearance, this system avoids exaggerated shadows, frosted glass blurs, or neomorphic bevels. Visual hierarchy is achieved via **tonal layering and hairline precision borders**.

### Depth Layers
- **Floor (Canvas):** Tone `#F5EFE1`. Provides background contrast for all white and cream modules.
- **Level 1 (Module & Reading Cards):** Tone `#FFFFFF` with a 1px border of `#E1D5C1`. Zero ambient blur shadow. Resting state is completely flat, grounded, and paper-like.
- **Level 2 (Active Focus & Flyout Panels):** Tone `#FFFFFF` with a 1px border of `#AEC4D4` and a crisp, directional structural shadow: `0 4px 12px rgba(30, 35, 42, 0.08)`.
- **Level 3 (Modal Dialogs & Schematic Overlays):** Tone `#FFFFFF` framed by a 1.5px border of `#790D16` and a deep shadow: `0 12px 32px rgba(30, 35, 42, 0.16)`.
- **K3 Alert Stacking:** High-priority safety warnings (K3) do not use drop shadows; they utilize high-contrast 2px solid boundary borders (`#BA1A1A` or `#8F4E00`) with high-chroma fill tints to immediately demand attention.

## Shapes

The design system adopts controlled, modern industrial roundedness (`roundedness: 2`).

### Corner Geometry
- **Standard Cards, Panels & Module Wrappers:** `rounded-lg` (16px / `1rem`), providing a refined and approachable shell that softens the dense technical content inside.
- **Interactive Controls (Buttons, Inputs, Selects):** `rounded` (8px / `0.5rem`), conveying physical structural strength and precise hit targets.
- **Badges, Tags, and Status Lozenges:** `rounded` (6px / `0.375rem`), maintaining crisp, compact stamp-like aesthetics rather than circular pills.
- **K3 Warning Banners:** `rounded` (8px / `0.5rem`) with a flat left edge border (0px) accentuated by a 4px solid left status bar.

## Components

### Buttons
- **Primary:** Solid `#790D16` fill with white `#FFFFFF` text. Hover: `#5F0B11`. Active: `#46080D`. Height: 44px (field-friendly touch target). Border radius: 8px.
- **Secondary (Technical):** Background `#FFFFFF`, 1px solid border `#790D16`, text `#790D16`. Hover: `#F5EFE1`.
- **Tertiary (Subtle Blueprint):** Background `#AEC4D4` at 20% opacity, border `#AEC4D4`, text `#1E232A`. Used for diagram toggles, schematic layer controls, and export tools.
- **Danger (K3 Emergency / Reset):** Solid `#BA1A1A` fill with white text.

### Badges & Status Chips
- **Selesai (Completed):** Background `#D7F5D7`, text `#1B6D2F`, border 1px solid `#A3E2A3`.
- **Sedang Berjalan (In Progress):** Background `#D2E7FF`, text `#0F5B8C`, border 1px solid `#9DC9FA`.
- **Draft:** Background `#E5E7EB`, text `#4B5563`, border 1px solid `#D1D5DB`.
- **Published:** Background `#FAF7F2`, text `#790D16`, border 1px solid `#E5D3AF`.
- **Archived:** Background `#E5E7EB`, text `#6B7280`, dashed border 1px solid `#9CA3AF`.

### K3 Safety Warnings & SOP Alerts
- Card-level callout with a 4px solid left indicator.
- **Critical Danger (Bahaya Listrik/Mesin):** `#FFDAD6` background, `#410002` text, `#BA1A1A` left strip, featuring a bold `[K3 - BAHAYA]` prefix in `label-k3`.
- **Caution / Warning:** `#FFE088` background, `#2A1700` text, `#8F4E00` left strip.

### Cards & Module Containers
- Solid white `#FFFFFF` body with 1px border `#E1D5C1`, rounded to 16px.
- Card headers feature an optional drafting grid subtitle, equipment code badge in `JetBrains Mono`, and clear step/completion indicators.

### Inputs & Controls
- **Input Fields:** `#FAF7F2` background, 1px solid `#D5C8B2` border, 8px radius. Focus state shifts to white `#FFFFFF` background with a 1.5px solid `#790D16` outline and zero glow.
- **Checkboxes & Radios:** 20px hit boxes with `#790D16` active state and crisp white check/dot indicators, structured for checklist verification in maintenance SOPs.

### Data Tables (Technical Parametric Logs)
- Header row in `#E5D3AF` (25% tint), uppercase bold labels in 11px Inter.
- Alternating row styling: pure `#FFFFFF` and subtle `#FAF7F2`.
- Numeric values and units right-aligned in `JetBrains Mono`.