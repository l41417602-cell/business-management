---
name: Emerald Operations Engine
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
  on-surface-variant: '#3c4a42'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#6c7a71'
  outline-variant: '#bbcabf'
  surface-tint: '#006c49'
  primary: '#006c49'
  on-primary: '#ffffff'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#4edea3'
  secondary: '#4648d4'
  on-secondary: '#ffffff'
  secondary-container: '#6063ee'
  on-secondary-container: '#fffbff'
  tertiary: '#565e74'
  on-tertiary: '#ffffff'
  tertiary-container: '#9ba2bb'
  on-tertiary-container: '#31394d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#e1e0ff'
  secondary-fixed-dim: '#c0c1ff'
  on-secondary-fixed: '#07006c'
  on-secondary-fixed-variant: '#2f2ebe'
  tertiary-fixed: '#dae2fd'
  tertiary-fixed-dim: '#bec6e0'
  on-tertiary-fixed: '#131b2e'
  on-tertiary-fixed-variant: '#3f465c'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.025em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  title-sm:
    fontFamily: Inter
    fontSize: 14px
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
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.005em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  stat-counter:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.03em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 1.5rem
  margin-sm: 1rem
  margin-lg: 2rem
  space-2xs: 0.125rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

This design system delivers a highly utilitarian, trustworthy, and precise enterprise environment crafted specifically for small-to-medium business operations. The emotional tone is dependable, clear, and proactive—instilling calm control over complex business workflows like inventory, invoicing, CRM, and omni-channel messaging.

Rooted in a **Corporate / Modern** aesthetic, the visual style prioritizes Swiss typography, tight micro-interactions, deliberate information density, and low-noise data surfaces. The architecture relies on deep slate structural anchors, pure white data modules, crisp hairline borders, and energetic emerald indicators that directly signal positive momentum, successful transactions, and real-time operational health.

## Colors

The palette is engineered for high-density SaaS workflows, blending a deep slate navigation anchor with crisp, legible content planes and immediate semantic clarity.

### Color Tokens & Roles

- **Primary (`#10B981`)**: Represents positive growth, active states, settled transactions, WhatsApp integration channels, and primary completion calls to action.
- **Secondary (`#6366F1`)**: Utilized for platform intelligence, configuration toggles, integration hubs, batch utilities, and secondary visual tags.
- **Tertiary / Structural Dark (`#0F172A`)**: The persistent root canvas for primary navigation sidebars, high-contrast badges, deep data headers, and modal backdrops.
- **Neutral Core (`#64748B`)**: Drives structural borders, muted metadata, input placeholders, and inactive states across the slate spectrum.

### Surface System
- **Canvas Base**: `#F8FAFC` (Slate 50) for outer frame contrast.
- **Surface Elevation**: `#FFFFFF` for data cards, data tables, sheets, and popovers.
- **Surface Subdued**: `#F1F5F9` (Slate 100) for table headers, segment tracks, and inactive form fields.
- **Hairline Border**: `#E2E8F0` (Slate 200) for high-precision, 1px module separation.

### Status System
- **Success / Active / Paid**: `#10B981` (Base), `#ECFDF5` (Soft Fill), `#047857` (Text on Soft Fill).
- **Warning / Pending / Low Stock**: `#F59E0B` (Base), `#FFFBEB` (Soft Fill), `#B45309` (Text on Soft Fill).
- **Danger / Overdue / Void**: `#F43F5E` (Base), `#FFF1F2` (Soft Fill), `#BE123C` (Text on Soft Fill).
- **Info / Neutral Status**: `#0284C7` (Base), `#F0F9FF` (Soft Fill), `#0369A1` (Text on Soft Fill).

## Typography

Typography relies on `Inter` across all structural layers to maximize tabular numeric alignment, scannability, and structural cohesion. 

### Typographic Hierarchy Rules
- **Tabular Figures**: All data displays, monetary columns, invoice quantities, and metric counters require `font-feature-settings: 'tnum' on, 'cv05' on, 'cv11' on` to enforce monospaced number alignment without switching fonts.
- **Metric Cards (`stat-counter`)**: Reserved strictly for high-level KPIs. Always pair with `label-sm` in all-caps uppercase tracking for unambiguous context.
- **Data Table Headers**: Rendered exclusively via `label-sm` with a secondary color treatment (`#64748B`) to keep attention focused on the primary row data.
- **Microcopy**: Tooltips, badge tags, and secondary row descriptions must not drop below 11px to maintain full legibility and regulatory compliance.

## Layout & Spacing

The layout philosophy follows a rigid 12-column fluid grid system paired with a standardized 4px/8px incremental spacing rhythm. It supports high density without clutter by prioritizing structured padding, vertical rhythm, and structural boundary cards.

### Layout Frame Architecture
- **Sidebar Navigation**: Fixed 260px desktop rail styled in `#0F172A`, collapsing into an overlay slide-out drawer below 1024px.
- **Top Application Bar**: Fixed 64px header featuring global search, active business entity switcher, notifications, and quick WhatsApp action buttons.
- **Content Canvas**: Fluid main pane on `#F8FAFC` base, capped at a maximum width of `1600px` for extreme ultrawide monitors to prevent unreadable tabular spans.

### Breakpoints & Adaptive Reflow
- **Mobile (< 768px)**: 4-column layout, `margin-sm` (16px), stacked metric cards, single-column detail drawers, and horizontal scroll wrappers for dense financial tables.
- **Tablet (768px – 1023px)**: 8-column layout, `gutter-sm` (16px), 2x2 grid for KPI cards, drawer-based secondary detail views.
- **Desktop (1024px+)**: 12-column layout, standard `gutter` (24px), persistent 260px navigation, multi-column operational dashboards, and split-screen side sheets for fast record editing.

## Elevation & Depth

This design system favors **crisp boundaries and ambient depth** over heavy drop shadows. Surfaces communicate hierarchy through calibrated structural borders paired with ultra-diffused, cool-tinted shadow skirts.

### Elevation Hierarchy

1. **Flat Level (Canvas & Inset Panels)**:
   - Elevation: Zero shadow.
   - Border: None or `1px solid #E2E8F0` on sub-panels.
   - Used for: Primary background `#F8FAFC`, neutral table row striping, disabled buttons.

2. **Base Level (Cards, Tables, KPI Modules)**:
   - Shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.05), 0 1px 2px -1px rgba(15, 23, 42, 0.05)`.
   - Border: `1px solid #E2E8F0`.
   - Used for: Primary data containers, operational summaries, metric cards.

3. **Raised Level (Hovered Modules, Segmented Controls)**:
   - Shadow: `0 4px 6px -1px rgba(15, 23, 42, 0.07), 0 2px 4px -2px rgba(15, 23, 42, 0.05)`.
   - Border: `1px solid #CBD5E1`.
   - Used for: Clickable card hover states, active segment buttons, inline search flyouts.

4. **Floating Level (Dropdowns, Popovers, Action Menus)**:
   - Shadow: `0 10px 15px -3px rgba(15, 23, 42, 0.08), 0 4px 6px -4px rgba(15, 23, 42, 0.04)`.
   - Border: `1px solid #E2E8F0`.
   - Used for: Context menus, autocomplete lists, date picker sheets.

5. **Overlay Level (Modals, Slide-over Drawers)**:
   - Backdrop: `rgba(15, 23, 42, 0.5)` with `backdrop-filter: blur(4px)`.
   - Shadow: `0 20px 25px -5px rgba(15, 23, 42, 0.12), 0 8px 10px -6px rgba(15, 23, 42, 0.06)`.
   - Border: `1px solid #E2E8F0`.
   - Used for: Invoice creators, contact editors, payment confirmation flows.

## Shapes

With a roundedness level of `1`, the shape geometry communicates stability, technical precision, and high utility. Geometry avoids overly organic curves to maintain tight spatial efficiency and alignment across dense tabular modules.

### Radius Scale Breakdown
- **Base Components (`rounded`: 0.25rem / 4px)**: Input fields, checkboxes, data table cells, small badges, dropdown menu items.
- **Medium Structural Containers (`rounded-lg`: 0.5rem / 8px)**: KPI metric cards, data table wrappers, modal windows, side-sheets, notification banners.
- **Large Contextual Surfaces (`rounded-xl`: 0.75rem / 12px)**: Standalone dashboard modules, onboarding canvases, persistent filter bars.
- **Pill Exception (`rounded-full`: 9999px)**: Reserved strictly for numeric avatars, notification dot counters, and compact inline status indicator tags.

## Components

### Buttons
- **Primary**: Solid emerald `#10B981`, white text, 4px corner radius. States: Hover `#059669`, Active `#047857`, Focus `ring-2 ring-emerald-500 ring-offset-2`.
- **Secondary**: Solid `#FFFFFF`, text `#0F172A`, 1px `#E2E8F0` border. States: Hover `#F8FAFC` and border `#CBD5E1`.
- **Tertiary / Ghost**: Transparent fill, text `#64748B`. States: Hover `#F1F5F9`, text `#0F172A`.
- **Destructive**: Solid `#F43F5E`, white text. Secondary destructive is white with `#F43F5E` text and border.
- **Sizes**: Small (32px height, 12px horizontal padding), Default (40px height, 16px horizontal padding), Large (48px height, 20px horizontal padding).

### Metric Cards (KPI Displays)
- Constructed with `#FFFFFF` background, `1px solid #E2E8F0`, and 8px border radius.
- Padding: `space-lg` (24px).
- Layout: Top row displays label (`label-sm` in Slate 500) alongside an optional category icon. Middle row highlights the KPI stat counter (`stat-counter` in Slate 900). Bottom row pairs a pill trend badge with a secondary caption (`body-sm` in Slate 500).

### Data Tables
- Encased in an 8px rounded container with an outer `1px solid #E2E8F0` stroke.
- **Header**: `#F8FAFC` background, height 40px, uppercase `label-sm` text in `#64748B`, sorted columns denoted by mini directional arrows.
- **Rows**: 52px standard row height, 40px compact mode. Border bottom `1px solid #F1F5F9`. Hover state fills `#F8FAFC`.
- **Active / Selected Row**: `#ECFDF5` background with an emerald `#10B981` 2px vertical left indicator.

### Input Fields & Controls
- **Text Inputs**: Height 40px, background `#FFFFFF`, border `1px solid #CBD5E1`, text `#0F172A`, placeholder `#94A3B8`. Focus state shifts border to `#10B981` with an ambient `0 0 0 3px rgba(16, 185, 129, 0.15)` ring.
- **Checkboxes & Radios**: 16x16px footprint. Checked state fills `#10B981` with crisp white iconography. Unchecked state holds a 1px `#CBD5E1` border over white.
- **Segmented Controls**: Inset container `#F1F5F9`, 4px padding, active tab is `#FFFFFF` with Base elevation and 4px radius.

### Badges & Status Chips
- Height 22px, horizontal padding 8px, font size 11px, weight 600.
- **Active / Paid**: `#ECFDF5` fill, `#047857` text, 6px solid `#10B981` dot prepended.
- **Pending / Attention**: `#FFFBEB` fill, `#B45309` text, 6px solid `#F59E0B` dot prepended.
- **Overdue / Void**: `#FFF1F2` fill, `#BE123C` text, 6px solid `#F43F5E` dot prepended.
- **Platform / Integration (e.g. WhatsApp)**: `#F0FDF4` fill, `#15803D` text, paired with native branding indicator.

### Cards & Drawers
- **Standard Cards**: `#FFFFFF` background, `1px solid #E2E8F0`, 8px roundedness, `space-md` or `space-lg` internal padding.
- **Slide-out Side Sheets**: Width 480px (or 100vw on mobile), background `#FFFFFF`, border-left `1px solid #E2E8F0`, elevated with Overlay Level shadow for fast multi-field record editing without context lost.