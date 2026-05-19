---
name: Kinetic Performance
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1c'
  surface-container: '#202020'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c4c9ac'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#303030'
  outline: '#8e9379'
  outline-variant: '#444933'
  surface-tint: '#abd600'
  primary: '#ffffff'
  on-primary: '#283500'
  primary-container: '#c3f400'
  on-primary-container: '#556d00'
  inverse-primary: '#506600'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#4a4949'
  on-secondary-container: '#bab8b7'
  tertiary: '#ffffff'
  on-tertiary: '#2f3131'
  tertiary-container: '#e2e2e2'
  on-tertiary-container: '#636565'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c3f400'
  primary-fixed-dim: '#abd600'
  on-primary-fixed: '#161e00'
  on-primary-fixed-variant: '#3c4d00'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Bebas Neue
    fontSize: 80px
    fontWeight: '400'
    lineHeight: 80px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Bebas Neue
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 52px
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: Bebas Neue
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: Bebas Neue
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 36px
  title-lg:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
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
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  container-max: 1280px
---

## Brand & Style
The design system is engineered for high-performance fitness coaching, embodying the intensity and precision of elite athletic training. The brand personality is aggressive yet professional, utilizing a high-contrast aesthetic to evoke energy and immediate action. 

The visual style blends **High-Contrast / Bold** elements with a **Modern Corporate** structure. It prioritizes a dark-mode-first experience to minimize visual fatigue while allowing the electric accent colors to command attention. Layouts should feel organized and data-driven, reflecting a scientific approach to personal training.

## Colors
The palette is dominated by a deep, layered black environment to create a sense of focus and grit. 

- **Electric Green (#CCFF00):** Reserved exclusively for primary actions, success states, and critical performance metrics. It represents energy and growth.
- **Deep Black (#121212):** The foundation of the UI. Use variations (Surface, Container) to create depth without relying on heavy lines.
- **Crisp White (#FFFFFF):** Used for primary typography and high-priority content to ensure maximum legibility against dark backgrounds.
- **Muted Grey (#A1A1AA):** Used for secondary text, borders, and deactivated states to maintain a clear hierarchy.

## Typography
The typography system uses a dual-font approach to balance impact with clarity. 

**Bebas Neue** is the "Performance" typeface, used for all major headlines and impact statements. Its condensed, vertical nature mimics the strength and upward movement of fitness. **Hanken Grotesk** serves as the functional workhorse, providing a sharp, modern feel for body copy and UI labels. 

Always use uppercase for Display and Headline levels to maximize the "stadium" feel. Increase letter-spacing slightly for uppercase labels to improve scanability on dark backgrounds.

## Layout & Spacing
This design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The spacing rhythm is strictly based on an 8px base unit.

- **Desktop:** 24px gutters with 80px side margins. Content is housed in a max-width container of 1280px.
- **Mobile:** 16px gutters with 20px side margins.
- **Vertical Rhythm:** Large sections should be separated by significant whitespace (80px–120px) to allow the "Power Headlines" room to breathe.

## Elevation & Depth
Depth is achieved through **Tonal Layers** and **Low-Contrast Outlines**. 

Since the background is deep black, elevation is indicated by slightly lighter shades of grey/black rather than traditional heavy shadows.
- **Level 0 (Background):** #0A0A0A
- **Level 1 (Cards/Containers):** #161616 with a 1px border of #262626.
- **Level 2 (Modals/Popovers):** #1E1E1E with a soft, diffused shadow (0px 20px 40px rgba(0,0,0,0.5)).

Avoid heavy blurs; maintain a crisp, machined look to all elevated elements.

## Shapes
The shape language is "Soft" (0.25rem / 4px). This subtle rounding takes the edge off the brutalist tendencies of the black/green palette, making the professional coaching aspect feel modern and accessible without losing its competitive edge.

Buttons and form inputs should strictly adhere to the `rounded-sm` or `rounded-md` guidelines. Avoid pill shapes, as they are too "soft" for this performance-driven brand.

## Components

### Buttons
- **Primary:** Electric Green background, black text (Hanken Grotesk, Bold, Uppercase). On hover, add a subtle outer glow of the primary color and shift the background to a slightly brighter lime.
- **Secondary:** Transparent background with a 2px White or Green border. White text.
- **Animation:** Use snappy 150ms transitions for all hover states.

### Cards (Feature & Pricing)
- **Structure:** Level 1 background (#161616), 1px border (#262626).
- **Pricing:** Highlight the "Most Popular" plan with an Electric Green top-border (4px) and a primary-colored button. Use Hanken Grotesk for price figures, ensuring they are the largest element in the card.

### Inputs & Forms
- Dark background (#0A0A0A) with a 1px border (#3F3F46). On focus, the border turns Electric Green.
- Labels should be Hanken Grotesk, 12px, Uppercase, with high-contrast white text.

### Performance Chips
- Small badges used for "New Record," "Advanced," or "Personalized." Use a dark green background with electric green text for a subtle but "active" look.