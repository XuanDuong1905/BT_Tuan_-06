---
name: Reliable Commerce & Auction System
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
  on-surface-variant: '#444651'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#9d4300'
  on-secondary: '#ffffff'
  secondary-container: '#fd761a'
  on-secondary-container: '#5c2400'
  tertiary: '#00312c'
  on-tertiary: '#ffffff'
  tertiary-container: '#004942'
  on-tertiary-container: '#4ebdb0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#ffdbca'
  secondary-fixed-dim: '#ffb690'
  on-secondary-fixed: '#341100'
  on-secondary-fixed-variant: '#783200'
  tertiary-fixed: '#89f5e7'
  tertiary-fixed-dim: '#6bd8cb'
  on-tertiary-fixed: '#00201d'
  on-tertiary-fixed-variant: '#005049'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
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
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  price-numeric:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

The design system establishes a high-trust, frictionless transactional environment for an enterprise-grade online auction marketplace. Balancing structural rigor with real-time auction momentum, the aesthetic emphasizes transparency, regulatory clarity, and split-second decision-making. 

### Emotional Intent & Persona
- **Dependability & Institutional Integrity:** Reassures bidders handling high-value transactions with stable, clean interfaces.
- **Controlled Urgency:** Time-sensitive dynamics (active outbids, ending-soon lots, reserved prices met) are delivered through targeted accents without cognitive fatigue or clutter.
- **Ergonomic Precision:** High-density data points (bid logs, increments, buyer premiums, fee breakdowns) maintain generous whitespace and clear visual grouping.

### Visual Style
A contemporary Corporate & Modern standard tailored for premium e-commerce. It uses crisp borders, subtle layered elevations, balanced neutral surfaces, and high contrast for numbers and financial data.

## Colors

The palette balances administrative confidence with high-visibility calls to action:

- **Primary Navy (`#1E3A8A`):** Anchors headers, primary navigation, base typography, and standard transactional elements. Expresses security, stability, and authenticity.
- **Secondary Coral/Orange (`#F97316`):** Dedicated exclusively to high-intent actions—primary "Place Bid" triggers, live countdown clocks, active outbid alerts, and purchase flows.
- **Tertiary Teal (`#0D9488`):** Reserved for verification badges, "Reserve Met" confirmations, escrow guarantees, and successful payment summaries.
- **Neutrals (`#F8FAFC` to `#0F172A` with `#64748B` midtones):** Creates structured containment surfaces (`#FFFFFF` cards over `#F8FAFC` base) and crisp, low-contrast borders (`#E2E8F0`).

### Role-Based Rules
1. **Never use the secondary coral for static or non-interactive elements**; preserve its affordance strictly for real-time bids, countdown timers, and checkout confirmations.
2. Financial numbers and active currency inputs must display in deep slate (`#0F172A`) or primary navy (`#1E3A8A`) to maximize legibility.

## Typography

Inter serves as the foundational typeface across all viewports. Its tall x-height, neutral tone, and tabular figure support provide clear alignment for catalog listings, dynamic countdown timers, and checkout ledgers.

### Tabular Figures & Numerics
All price fields, currency tags, bid increments, and countdown digits (`hh:mm:ss`) must use tabular numbers (`font-variant-numeric: tabular-nums`) to prevent horizontal jitter during live auction updates.

### Hierarchical Restraint
- Uppercase styling is restricted to `label-sm` metadata badges (e.g., `LOT 402`, `RESERVE MET`, `BUYER'S PREMIUM`).
- Product titles utilize `headline-lg` or `headline-md` with strict line-clamp rules (maximum 2 lines) to keep card grids uniform.

## Layout & Spacing

The layout is built on an 8pt spatial grid configured within a structured 12-column fixed-max layout (`max-width: 1440px`) optimized for desktop e-commerce.

### Desktop Catalog & Product Layout
- **Lot Grid:** 4 columns on large screens (`1440px+`), collapsing to 3 columns on standard desktop (`1024px - 1439px`). Gutter size remains static at `space-lg` (`24px`).
- **Auction Detail View (PDP):** An asymmetric 7/5 column split. 7 columns dedicated to high-resolution gallery and provenance tabs; 5 columns anchor the sticky bidding console and cost ledger.
- **Checkout & Settlement Flow:** A centered 8-column layout (`~880px`) with split summaries for payment entry and transaction line items.

### Responsive Adjustments
- **Mobile (< 768px):** Adapts to a 4-column fluid layout with `16px` margins. Action buttons and real-time timers detach to an anchored sticky bottom sheet.

## Elevation & Depth

Visual hierarchy uses clean background contrast paired with three ambient, diffused elevation tiers. This keeps real-time cards distinct without heavy drop shadows.

### Elevation Levels
- **Level 0 (Flat / Canvas):** Neutral `#F8FAFC` base canvas with `1px` solid `#E2E8F0` borders for standard layout segments.
- **Level 1 (Card Default):** Pure `#FFFFFF` surface accompanied by a soft, tinted drop shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.05), 0 1px 2px -1px rgba(15, 23, 42, 0.05)`.
- **Level 2 (Active Auction / Hover State):** Lifted lot cards and interactive checkout inputs: `0 10px 15px -3px rgba(15, 23, 42, 0.06), 0 4px 6px -4px rgba(15, 23, 42, 0.03)`.
- **Level 3 (Sticky Bidding Rail / Modals / Alerts):** Pinned bid modules and instant outbid banners: `0 20px 25px -5px rgba(15, 23, 42, 0.08), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`.

### Border Discipline
Shadows are consistently backed by a subtle `1px` border (`#E2E8F0` or `#CBD5E1`) to maintain clean edges against white backgrounds.

## Shapes

With `roundedness: 2`, the UI balances modern approachability with structured order:

- **Base Radius (`0.5rem` / `8px`):** Applied to form inputs, utility badges, table headers, bid increment chips, and regular buttons.
- **Large Radius (`rounded-lg` - `1rem` / `16px`):** Applied to auction product cards, image thumbnails, summary ledgers, and dialog containers.
- **Extra Large Radius (`rounded-xl` - `1.5rem` / `24px`):** Applied to featured hero auction units and promotional banners.
- **Pill Radius (`9999px`):** Exclusively reserved for live indicator chips (e.g., `● LIVE AUCTION`), countdown timer containers, and step progression dots.

## Components

### 1. Auction Item Cards
- **Image Container:** Fixed 4:3 or 1:1 aspect ratio with an anchored top status badge (e.g., Coral for "Ends in 04m 12s", Teal for "Reserve Met").
- **Content Hierarchy:** Lot number and category in `label-sm` (`#64748B`), item title in `headline-sm` (`#0F172A`), followed by the current bid block.
- **Bid Display:** Labeled "Current Bid" with the price rendered in `price-numeric` Navy (`#1E3A8A`). Includes total bid count in `body-sm`.
- **Action:** Full-width quick-bid trigger or direct link button using secondary outline or solid navy tokens.

### 2. Buttons
- **Primary Bid Action:** Solid Coral (`#F97316`) background, white text, bold font weight. Interactive hover shifts to deeper amber (`#EA580C`), with an active inset state.
- **Standard Transactional:** Solid Navy (`#1E3A8A`) background, white text. Used for "Confirm Payment", "Register to Bid", and step navigation.
- **Secondary / Quick Increment:** Crisp white background with `1px` border (`#CBD5E1`), text in `#0F172A`. Used for quick bid add-ons (e.g., `+$50`, `+$100`, `+$250`).
- **Disabled State:** Background `#F1F5F9`, text `#94A3B8`, with cursor `not-allowed`.

### 3. Countdown Timers & Status Badges
- **Live Active:** Coral tint (`#FFF7ED`) background, Coral (`#C2410C`) text, with a pulsing circular indicator.
- **Upcoming:** Slate tint (`#F1F5F9`) background, text `#475569`.
- **Closed / Sold:** Deep neutral background (`#E2E8F0`), text `#334155`.

### 4. Input Fields & Steppers
- **Bid Value Field:** Large tabular input with fixed leading currency symbol (`$`, `₫`). Font size `20px` bold, border `1.5px` solid `#CBD5E1`.
- **Focus State:** Deep navy ring outline with `2px` offset (`#1E3A8A`).
- **Inline Increment Controls:** Stepper plus/minus buttons integrated directly into the input container for rapid bid modification.

### 5. Cost Summary Ledger (Fee Breakdown)
- **Structure:** Clean tabular ledger detailing High Bid, Buyer's Premium (percentage and subtotal), Estimated Shipping, Value Added Tax (VAT), and Final Total.
- **Separators:** Hairline horizontal rules (`#E2E8F0`).
- **Highlighting:** Final Total row set in `18px` bold Navy with an expanded vertical padding of `16px`.

### 6. Payment Gateways & Escrow Badges
- **Payment Method Selectors:** Radio card pattern featuring bank transfer, credit card, and verified escrow options. Selected state features a `2px` Navy border and `#EFF6FF` subtle background fill.
- **Trust Elements:** Secure SSL padlock and verified escrow seals rendered in tertiary teal (`#0D9488`) positioned right below the primary payment trigger.