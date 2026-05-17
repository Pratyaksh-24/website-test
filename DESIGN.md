---
name: Warm Minimal Dental
colors:
  surface: '#f7faf6'
  surface-dim: '#d8dbd7'
  surface-bright: '#f7faf6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f0'
  surface-container: '#ecefeb'
  surface-container-high: '#e6e9e5'
  surface-container-highest: '#e0e3df'
  on-surface: '#181c1a'
  on-surface-variant: '#3f4944'
  inverse-surface: '#2d312f'
  inverse-on-surface: '#eef2ee'
  outline: '#6f7974'
  outline-variant: '#bec9c2'
  surface-tint: '#1a6b52'
  primary: '#00523c'
  on-primary: '#ffffff'
  primary-container: '#1b6b52'
  on-primary-container: '#9de9c9'
  inverse-primary: '#8ad5b7'
  secondary: '#735b28'
  on-secondary: '#ffffff'
  secondary-container: '#fedb9c'
  on-secondary-container: '#785f2b'
  tertiary: '#73342e'
  on-tertiary: '#ffffff'
  tertiary-container: '#904b44'
  on-tertiary-container: '#ffcec8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a6f2d2'
  primary-fixed-dim: '#8ad5b7'
  on-primary-fixed: '#002116'
  on-primary-fixed-variant: '#00513c'
  secondary-fixed: '#ffdea3'
  secondary-fixed-dim: '#e3c285'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#594312'
  tertiary-fixed: '#ffdad6'
  tertiary-fixed-dim: '#ffb4ab'
  on-tertiary-fixed: '#3a0907'
  on-tertiary-fixed-variant: '#72342e'
  background: '#f7faf6'
  on-background: '#181c1a'
  surface-variant: '#e0e3df'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 36px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.5'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style

The design system is anchored in "Warm Minimalism"—a philosophy that replaces the sterile, clinical coldness typically associated with dentistry with a sense of organic tranquility and high-end hospitality. The target audience seeks a premium, anxiety-reducing experience that feels both technologically advanced and deeply human.

The style leverages **Minimalism** with a **Tactile** edge. It utilizes expansive whitespace (negative space) to suggest cleanliness and breathing room, while employing a palette of earthy, organic tones to evoke comfort. Visual hierarchy is established through elegant serif typography and purposeful use of gold accents, moving away from aggressive "sales-driven" UI toward an editorial, boutique aesthetic.

## Colors

The palette is designed to lower cortisol levels while maintaining an air of professional authority. 

- **Primary (Deep Forest Green):** Used for primary actions and brand presence. It represents health, growth, and stability.
- **Background (Off-white Cream):** The foundation of the UI. It provides a softer, more inviting canvas than pure white.
- **Surface (Soft Stone):** Used for cards, sections, and input backgrounds to create subtle contrast against the cream base.
- **Accent (Warm Gold):** Reserved for subtle highlights, interactive hovers, and premium signifiers.
- **Neutral/Text:** Near-black is used for maximum legibility in body copy, while Medium Gray is reserved for captions and secondary metadata.

## Typography

This system uses a sophisticated pairing of **EB Garamond** (as a high-quality alternative to Cormorant) for editorial expression and **Plus Jakarta Sans** for functional clarity.

- **Headlines:** Set in serif to convey tradition, excellence, and a "boutique" feel. Use tight letter-spacing for larger display sizes to maintain a bespoke look.
- **Body & UI:** Set in the modern sans-serif for high legibility, especially for elderly patients or those with visual impairments. 
- **Accessibility:** The scale starts at a generous 16px base to ensure all patients can easily navigate treatment plans and appointment details. Use Medium weight (500/600) for UI labels to ensure they stand out against soft backgrounds.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** on desktop to maintain an editorial, centered feel, while transitioning to a fluid model on mobile.

- **Generous Gaps:** Section vertical spacing is intentionally large (120px+) to prevent the interface from feeling "crowded," mirroring the physical space of a high-end clinic.
- **Rhythm:** All spacing (padding, margins, gutters) is derived from an 8px base unit.
- **Grid:** Use a 12-column grid for desktop. Content usually sits in a central 8-column span for better readability, leaving wide margins to emphasize the minimalist aesthetic.

## Elevation & Depth

Depth in this design system is communicated through **Tonal Layers** and **Ambient Shadows** rather than harsh borders.

- **The Base:** The `Off-white Cream` background is the lowest level.
- **Surface Elevation:** Cards and containers use the `Soft Stone` color or pure white with a very soft, diffused shadow (15% opacity Deep Forest Green or Neutral) to suggest they are floating slightly above the surface.
- **Interaction Depth:** On hover, cards should "lift" (the shadow expands and softens) and reveal a 2px top-border in `Warm Gold` to provide clear, elegant feedback.

## Shapes

The shape language is primarily **Pill-shaped** and highly rounded to communicate safety and friendliness. 

- **Primary Elements:** Buttons and tags use the full pill shape (100px+ radius).
- **Secondary Elements:** Cards and input fields use a `rounded-xl` (1.5rem) setting to maintain consistency without becoming overly circular.
- **Strict Rule:** Avoid sharp 90-degree corners to ensure the UI feels approachable and soft to the touch.

## Components

- **Buttons:** Primary buttons are pill-shaped, filled with `Deep Forest Green` with white text. Secondary buttons use a `Warm Gold` outline or a `Soft Stone` fill.
- **Cards:** Feature a subtle shadow (Blur: 20px, Y: 10px, Color: rgba(26, 26, 24, 0.05)). On hover, add a 4px top border in `Warm Gold`.
- **Input Fields:** Backgrounds should be `Soft Stone` with no border in their default state. On focus, they transition to a white background with a thin `Deep Forest Green` stroke.
- **Chips/Badges:** Used for service categories or dental specialties. These are small pill shapes with `Warm Gold` text on a semi-transparent gold background.
- **Lists:** Use generous 24px padding between items and thin, low-contrast horizontal dividers (`Soft Stone`).
- **Calendar/Booking:** A high-priority component. Use clear, rounded day-pickers with `Deep Forest Green` for selected states and `Warm Gold` for "Today" indicators.