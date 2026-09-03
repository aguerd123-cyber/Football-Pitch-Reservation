---
name: Kinetic Pitch
colors:
  surface: '#111415'
  surface-dim: '#111415'
  surface-bright: '#373a3b'
  surface-container-lowest: '#0c0f10'
  surface-container-low: '#191c1d'
  surface-container: '#1d2021'
  surface-container-high: '#282a2b'
  surface-container-highest: '#323536'
  on-surface: '#e1e3e4'
  on-surface-variant: '#bbcbbb'
  inverse-surface: '#e1e3e4'
  inverse-on-surface: '#2e3132'
  outline: '#869486'
  outline-variant: '#3d4a3e'
  surface-tint: '#4ae183'
  primary: '#54e98a'
  on-primary: '#003919'
  primary-container: '#2ecc71'
  on-primary-container: '#005027'
  inverse-primary: '#006d37'
  secondary: '#c8c6c8'
  on-secondary: '#303032'
  secondary-container: '#474649'
  on-secondary-container: '#b6b4b7'
  tertiary: '#ffc197'
  on-tertiary: '#4f2500'
  tertiary-container: '#ff9a4a'
  on-tertiary-container: '#6e3600'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6bfe9c'
  primary-fixed-dim: '#4ae183'
  on-primary-fixed: '#00210c'
  on-primary-fixed-variant: '#005228'
  secondary-fixed: '#e4e2e4'
  secondary-fixed-dim: '#c8c6c8'
  on-secondary-fixed: '#1b1b1d'
  on-secondary-fixed-variant: '#474649'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#ffb783'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#713700'
  background: '#111415'
  on-background: '#e1e3e4'
  surface-variant: '#323536'
typography:
  display:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Montserrat
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  container-padding: 20px
  gutter: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is engineered for a high-energy, athletic audience. It captures the intensity of a live match through a high-contrast, modern aesthetic that prioritizes speed of action and professional reliability. 

The style combines **Modern Corporate** structure with **Glassmorphism** and **High-Contrast** accents. The interface utilizes deep, "Pitch Black" surfaces to allow vibrant "Grass Green" and "Action Orange" elements to pop, simulating the feel of a night game under floodlights. Depth is achieved through translucent layers rather than traditional shadows, creating a sleek, futuristic feel that is both premium and accessible.

## Colors

The palette is rooted in a dark-mode first philosophy to reduce glare during evening bookings and emphasize the "Pitch" atmosphere.

- **Primary (Grass Green):** Used for success states, active selections, and confirming availability. It represents the field of play.
- **Secondary (Pitch Black):** The foundational surface color. Use variations in opacity for layering.
- **Tertiary (Action Orange):** Reserved strictly for high-priority Call-to-Actions (CTAs) like "Book Now" or "Pay." It creates an urgent, energetic focal point.
- **Neutral:** Pure white and cool grays are used for high-readability text and subtle borders to maintain a professional, clean look.

## Typography

Typography balances the "athletic" weight of **Montserrat** for headings with the "utilitarian" clarity of **Inter** for data-heavy booking flows.

- **Headlines:** Use Montserrat in Bold or ExtraBold. Apply tight letter-spacing to large displays to evoke the feel of sports jerseys and stadium signage.
- **Body:** Use Inter for all functional text. The neutral character of Inter ensures that even dense schedules and pricing tables remain legible at a glance.
- **Labels:** Small labels should use uppercase with slight tracking (letter-spacing) to create a refined, professional hierarchy.

## Layout & Spacing

The layout follows a **fluid grid** model optimized for mobile-first interaction. 

- **Grid:** Use a 4-column grid for mobile with 16px gutters.
- **Margins:** Standardize on 20px lateral margins for main containers to ensure content doesn't feel cramped against the screen edges.
- **Rhythm:** Use a 4px baseline shift. All spacing between elements should be multiples of 4 (e.g., 8, 16, 24, 32) to maintain a systematic, "engineered" appearance.
- **Touch Targets:** Ensure all interactive elements have a minimum height of 48px to accommodate players using the app on the go.

## Elevation & Depth

This design system eschews traditional soft shadows in favor of **Glassmorphism** and **Tonal Layering**.

- **Surface Levels:** 
  - **L0 (Base):** Pitch Black (#1C1C1E).
  - **L1 (Cards):** Use a semi-transparent fill (White at 5-8% opacity) with a `backdrop-filter: blur(20px)`. 
  - **L2 (Modals/Popovers):** Higher opacity fill (White at 12%) with a 1px subtle stroke (White at 10%) to define edges.
- **Visual Distinction:** Depth is signaled by the intensity of the background blur. Elements "closer" to the user have a clearer, more opaque surface and a slightly brighter border.

## Shapes

The shape language is friendly yet structured. The default `rounded-2xl` (1rem / 16px) is the standard for cards and major containers, providing a modern, "app-centric" feel.

- **Buttons:** Use fully rounded (pill-shaped) corners for primary actions to distinguish them from informational cards.
- **Input Fields:** Use 12px (rounded-lg) for a slightly more structured, "reliable" look.
- **Selection States:** When a time slot or pitch is selected, use a 2px Grass Green border to reinforce the shape.

## Components

- **Buttons:** 
  - *Primary (Action Orange):* High-contrast, white or black text depending on readability, pill-shaped.
  - *Secondary (Outline):* 1px green border with transparent center, used for "View Details" or "Add to Calendar."
- **Cards (Glass):** Feature a 1px inner stroke (White at 10%) and 20px blur. Content inside should follow the 16px internal padding rule.
- **Time-Slot Chips:** Rectangular with `rounded-md`. Available slots are Pitch Black with a green border; booked slots are low-opacity gray with a strikethrough.
- **Input Fields:** Dark fill (slightly lighter than Pitch Black), subtle bottom border that glows Green when focused.
- **Status Indicators:** Use a glowing "pulse" animation for live-availability indicators.
- **Progress Steppers:** Use thick, 4px bars rather than thin lines to mirror the bold lines found on a football pitch.