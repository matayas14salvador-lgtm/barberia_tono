---
name: Toño Professional Grooming
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#444748'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5c5f61'
  on-secondary: '#ffffff'
  secondary-container: '#e1e2e6'
  on-secondary-container: '#626567'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#261a00'
  on-tertiary-container: '#9b8046'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#e1e2e6'
  secondary-fixed-dim: '#c5c6ca'
  on-secondary-fixed: '#191c1e'
  on-secondary-fixed-variant: '#44474a'
  tertiary-fixed: '#ffdf9e'
  tertiary-fixed-dim: '#e3c381'
  on-tertiary-fixed: '#261a00'
  on-tertiary-fixed-variant: '#59430e'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 42px
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  title-lg:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-padding-mobile: 20px
  container-padding-desktop: 64px
  gutter: 16px
  section-gap: 80px
---

## Brand & Style
The brand personality centers on "Trusted Excellence." It bridges the gap between the traditional neighborhood barbershop and a high-end modern salon. The target audience is local residents of Morelia who value precision, cleanliness, and a professional atmosphere without the pretension of luxury franchises.

The design style is **Modern Minimalism**. It utilizes heavy whitespace to evoke the cleanliness of a sanitized station, high-contrast typography for an authoritative voice, and subtle metallic accents to hint at the tools of the trade (shears, razors). The emotional response should be one of immediate confidence and reliability.

## Colors
The palette is rooted in professional discipline. 
- **Deep Charcoal (Primary):** Used for primary text and high-impact UI elements like main buttons to establish authority.
- **Elegant Silver (Secondary):** Used for borders, inactive states, and decorative rules, reflecting the stainless steel of professional tools.
- **Muted Gold (Tertiary):** A sophisticated accent used sparingly for calls-to-action, badges of quality, or highlighting special offers.
- **Off-White (Neutral):** A clean, slightly warm background color to reduce eye strain compared to pure white while maintaining a clinical feel.

## Typography
This design system employs a high-contrast typographic pairing to reflect "The Modern Artisan." 
- **Libre Caslon Text** provides the authoritative, editorial feel of a high-end salon. Use it for headings and display prices.
- **Hanken Grotesk** serves as the functional workhorse. Its sharp, contemporary cuts ensure maximum legibility for service menus and booking forms.
- All labels and small metadata should use **Hanken Grotesk** in bold caps with increased letter spacing to maintain a clean, organized hierarchy.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a mobile-first priority. 
- **Mobile:** A single-column layout with generous 20px side margins to ensure touch targets are comfortable.
- **Desktop:** A 12-column grid with a maximum content width of 1200px. 
- **Rhythm:** Use an 8px base unit. Section spacing should be aggressive (80px+) to allow the design to "breathe," reinforcing the premium, unhurried service experience. Service menus should utilize a 2-column split on desktop but stack vertically on mobile.

## Elevation & Depth
Depth is conveyed through **Low-contrast outlines** and **Tonal layering** rather than heavy shadows.
- **Surfaces:** Use the neutral background for the base, with pure white (#FFFFFF) for cards and floating elements to create a subtle lift.
- **Borders:** 1px solid strokes in the Secondary Silver color are preferred over shadows for defining sections.
- **Active State:** When an element is pressed or active, use a 2px stroke of the Muted Gold accent to provide clear feedback without disrupting the flat aesthetic.

## Shapes
The shape language is **Soft (0.25rem)**. This provides just enough curvature to feel approachable and modern while maintaining the sharp, professional "cut" associated with barbering. 
- Avoid circles except for icon backgrounds. 
- Image containers should have the same 0.25rem radius to maintain consistency across the UI.

## Components
- **Buttons:** Primary buttons are solid Deep Charcoal with white text. Secondary buttons are outlined in Silver. Use Muted Gold only for the "Book Appointment" primary call-to-action.
- **Service Cards:** Use a clean layout with the service name in Caslon and the price in Hanken Grotesk Bold. Use a 1px Silver bottom border to separate items in a list.
- **Inputs:** Form fields should be rectangular with a subtle Silver border. On focus, the border transitions to Deep Charcoal.
- **Chips/Status:** Use for "Available" or "Specialty" tags. These should have a light gray background with bold, small-caps Hanken Grotesk text.
- **Stylized Icons:** Use thin-line SVG icons representing shears, combs, and chairs. Avoid filled icons to keep the interface feeling light and high-end.