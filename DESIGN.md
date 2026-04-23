---
name: Modern Earth
colors:
  surface: '#fcf9f4'
  surface-dim: '#dcdad5'
  surface-bright: '#fcf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ee'
  surface-container: '#f0ede8'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e5e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#434843'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f3f0eb'
  outline: '#737973'
  outline-variant: '#c3c8c1'
  surface-tint: '#4d6453'
  primary: '#061b0e'
  on-primary: '#ffffff'
  primary-container: '#1b3022'
  on-primary-container: '#819986'
  inverse-primary: '#b4cdb8'
  secondary: '#7c5730'
  on-secondary: '#ffffff'
  secondary-container: '#fdcb9b'
  on-secondary-container: '#79542d'
  tertiary: '#0f1912'
  on-tertiary: '#ffffff'
  tertiary-container: '#242e25'
  on-tertiary-container: '#8a968a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d0e9d4'
  primary-fixed-dim: '#b4cdb8'
  on-primary-fixed: '#0b2013'
  on-primary-fixed-variant: '#364c3c'
  secondary-fixed: '#ffdcbd'
  secondary-fixed-dim: '#eebd8e'
  on-secondary-fixed: '#2c1600'
  on-secondary-fixed-variant: '#61401b'
  tertiary-fixed: '#dae6d9'
  tertiary-fixed-dim: '#becabd'
  on-tertiary-fixed: '#141e16'
  on-tertiary-fixed-variant: '#3f4940'
  background: '#fcf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e5e2dd'
typography:
  display:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin: 32px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

This design system establishes a visual identity that bridges the gap between rugged, outdoor labor and high-end residential architecture. The aesthetic is **Modern-Organic**, blending the structured precision of contemporary design with the raw, tactile elements of the natural world.

The UI should feel grounded and heavy, avoiding the ethereal or "floaty" nature of typical SaaS platforms. It prioritizes clarity and physical presence to communicate reliability. By utilizing a mix of minimalism for layout and tactile cues for interactive elements, the design system ensures the user feels they are in the hands of professionals who value both craft and cleanliness.

## Colors

The color palette is derived from late-afternoon landscapes. The primary color is a **Deep Forest Green**, chosen to represent growth and established authority. The secondary color is a **Warm Cedar**, used sparingly to highlight calls to action and evoke the scent and texture of fresh mulch or hardwood decks.

The background uses a **Warm Neutral** (Stone) rather than a pure white to reduce glare and provide a more inviting, parchment-like canvas. Functional colors (success, error, warning) should be slightly desaturated to maintain harmony with the earthy core palette.

## Typography

This design system uses a dual-font strategy to balance professionalism with approachability. **Manrope** is used for headlines and structural labels, providing a geometric, modern foundation that implies precision. **Be Vietnam Pro** is used for long-form body text; its slightly wider apertures and contemporary humanist traits make it highly readable and warm.

Type hierarchy is strictly enforced to guide the user through service tiers and project galleries. Use the `label-caps` style for section headers to provide a sense of architectural organization.

## Layout & Spacing

The layout utilizes a **Fixed Grid** model for desktop to maintain a premium, editorial feel, transitioning to a fluid model for tablets and mobile devices. A 12-column system is used to accommodate varied content types, such as asymmetrical project showcases and structured service lists.

The spacing rhythm is built on an 8px base unit. Generous vertical padding (`stack-lg`) is encouraged between sections to allow the high-quality imagery of landscaping projects to breathe, reflecting the open-space nature of the business.

## Elevation & Depth

To reflect the "Down and Dirty" hands-on nature of the brand, elevation is handled through **Tonal Layering** and **Ambient Shadows** rather than high-contrast light effects.

1.  **Surfaces:** Use subtle shifts in neutral tones to distinguish between the ground (background) and containers (cards).
2.  **Shadows:** Interactive elements like cards or primary buttons should use "Muddy Shadows"—diffused, low-opacity shadows with a slight green or brown tint (#1B3022 at 8% opacity) to ground them in the environment.
3.  **Depth:** Use "Inward Depth" (inset shadows) for form fields to simulate the look of carved wood or impressed earth.

## Shapes

The shape language is deliberately **Rounded** to echo organic forms found in nature—rolling hills, stones, and leaf shapes. While the grid is rigid and professional, the individual components have softened corners to feel safe and inviting.

-   **Standard Elements:** (Buttons, inputs) use a 0.5rem radius.
-   **Feature Elements:** (Cards, modal containers) use a 1rem radius.
-   **Media:** Images of landscaping work should always use the `rounded-lg` or `rounded-xl` setting to soften the visual impact and blend with the typography.

## Components

### Buttons
Primary buttons should be solid Deep Forest Green with White text. Secondary buttons should use the Warm Cedar as a border with a subtle tint on hover. The "Request a Quote" action should always use a high-contrast treatment to stand out against the earth-toned background.

### Cards
Cards are the primary vehicle for project portfolios. They should feature a "rim-light" border—a 1px solid stroke in a slightly lighter shade than the background—to provide definition without heavy shadows.

### Inputs
Fields should have a solid, high-contrast border in the Tertiary color. On focus, the border transitions to Primary Green with a soft outer glow. This provides a clear, high-quality feedback loop for users requesting services.

### Chips & Tags
Used for identifying service categories (e.g., "Hardscaping," "Irrigation"). These should use a semi-transparent background of the Primary Green with dark text, appearing like "pressed" labels.

### Gallery Interaction
Include a "Before/After" slider component. This is essential for this design system to showcase the transformation and reliability of the work performed.