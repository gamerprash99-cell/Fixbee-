---
name: Premium Device Care System
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
  on-surface-variant: '#4d4732'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#7e775f'
  outline-variant: '#d0c6ab'
  surface-tint: '#705d00'
  primary: '#705d00'
  on-primary: '#ffffff'
  primary-container: '#ffd700'
  on-primary-container: '#705e00'
  inverse-primary: '#e9c400'
  secondary: '#005cba'
  on-secondary: '#ffffff'
  secondary-container: '#5095fe'
  on-secondary-container: '#002d61'
  tertiary: '#565e74'
  on-tertiary: '#ffffff'
  tertiary-container: '#d2d9f4'
  on-tertiary-container: '#575e75'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe16d'
  primary-fixed-dim: '#e9c400'
  on-primary-fixed: '#221b00'
  on-primary-fixed-variant: '#544600'
  secondary-fixed: '#d7e3ff'
  secondary-fixed-dim: '#aac7ff'
  on-secondary-fixed: '#001b3e'
  on-secondary-fixed-variant: '#00458e'
  tertiary-fixed: '#dae2fd'
  tertiary-fixed-dim: '#bec6e0'
  on-tertiary-fixed: '#131b2e'
  on-tertiary-fixed-variant: '#3f465c'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  title-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  technical-data:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  margin-mobile: 16px
  margin-desktop: 32px
  gutter: 16px
  container-max: 1440px
---

## Brand & Style
The design system establishes a high-trust, premium ecosystem for Indian device care, balancing clinical efficiency with high-end luxury. The personality is **Reliable, Premium, and Efficient**, designed to bridge the gap between high-street repair services and luxury retail experiences.

The visual style is a hybrid of **Corporate Modern** and **Tactile Glassmorphism**. It utilizes the structural clarity of Apple Support for navigation, the functional density of Amazon for service listings, and the elevated, dark-mode surfaces characteristic of high-end fintech apps. This ensures that while the base utility remains accessible, "premium" tiers and service tracking feel exclusive and high-tech.

## Colors
The palette is centered on "Bee Yellow" for high-visibility action and "Trust Blue" for institutional reliability. 

*   **Primary (Bee Yellow):** Used for primary CTAs, urgency-driven progress indicators, and brand accents.
*   **Secondary (Trust Blue):** Used for navigation, links, and verification status to evoke professional stability.
*   **Surfaces:** The system defaults to a "Paper White" for customer apps to maintain cleanliness, transitioning to a deep "Midnight Slate" (#0F172A) for premium membership tiers and technician job views to reduce eye strain and denote a high-tier status.
*   **Status Accents:** Vibrant, high-saturation colors ensure that repair status (In-Progress, Success, Delayed) is immediately legible at a glance.

## Typography
The typography strategy utilizes **Hanken Grotesk** for headlines to provide a sharp, contemporary "fintech" feel. **Inter** handles the heavy lifting for body text and functional UI elements due to its exceptional legibility on mobile screens. 

For technical data (device specs, IMEI numbers, job IDs), **JetBrains Mono** is used at a small scale to provide a sense of precision and technical authority. All display styles utilize tighter tracking to maintain a compact, premium appearance, while body text uses standard spacing for maximum readability.

## Layout & Spacing
This design system employs a **Fluid-Fixed Hybrid** grid. 
*   **Mobile:** A 4-column fluid grid with 16px margins. Components like "Device Cards" should span the full width minus margins to maximize tap targets.
*   **Admin Dashboard:** A 12-column fixed grid with a 280px sidebar. Content is organized in "Linear-style" vertical stacks for density and clarity.
*   **Technician View:** Focused on single-task focus modes. Padding is increased (24px) around primary action buttons to prevent accidental taps during active repair work.

## Elevation & Depth
The system uses **Tonal Layering** combined with **Glassmorphism** for its hierarchy.
*   **Base Layer:** Flat, high-contrast surface.
*   **Component Layer:** Subtle 1px borders (#E2E8F0 in light, #1E293B in dark) instead of heavy shadows for a clean, modern aesthetic.
*   **Premium Layer (CRED-style):** High-end cards use a backdrop blur (20px) with a semi-transparent surface and a very subtle 0.5px white "inner-glow" stroke to simulate physical glass.
*   **Active Elements:** Primary buttons and active tracking cards use a soft, large-radius ambient shadow (15% opacity primary color) to feel "lifted" and interactive.

## Shapes
The shape language is defined by **Optimized Roundedness**.
*   **Standard Components:** Buttons and Input fields use a **12px (rounded)** radius to feel friendly yet professional.
*   **Container Cards:** Outer containers use **16px (rounded-lg)** to create a soft, modern framing effect.
*   **Status Indicators:** Small chips and tags use a full **Pill-shape** to distinguish them from interactive buttons.

## Components
### Buttons
*   **Primary:** Solid Bee Yellow with black text. Tactile feel achieved through a subtle inner-shadow on press.
*   **Secondary:** Ghost style with Trust Blue border and text.
*   **Technician Action:** Large, full-width buttons with icons for "Start Repair" or "Complete Job."

### Input Fields
*   **Modern Institutional:** Large 16px font size (to prevent iOS zoom), 1px stroke that thickens to 2px Trust Blue on focus. Labels are persistent and positioned above the field in Label-Caps style.

### Device Vault Cards
*   Glassmorphic cards displaying device icons, warranty status, and a "Health Score" radial gauge. These cards should feel like digital assets in a wallet.

### Tracking Components (Uber-style)
*   A persistent bottom sheet for live repair tracking. It uses a 4px "grabber" bar and contains a condensed timeline of the technician's journey.

### Admin Data Tables
*   High-density, low-contrast rows. Hover states should highlight the entire row in a soft blue tint. Sortable headers use JetBrains Mono for a professional, data-driven feel.