---
name: Wild Refinement
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#4d4637'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#7e7665'
  outline-variant: '#d0c5b2'
  surface-tint: '#755b00'
  primary: '#755b00'
  on-primary: '#ffffff'
  primary-container: '#c9a84c'
  on-primary-container: '#503d00'
  inverse-primary: '#e6c364'
  secondary: '#4e644c'
  on-secondary: '#ffffff'
  secondary-container: '#cee7c8'
  on-secondary-container: '#526850'
  tertiary: '#5f5e5e'
  on-tertiary: '#ffffff'
  tertiary-container: '#adabab'
  on-tertiary-container: '#403f3f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe08f'
  primary-fixed-dim: '#e6c364'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#584400'
  secondary-fixed: '#d0e9cb'
  secondary-fixed-dim: '#b5cdb0'
  on-secondary-fixed: '#0c200d'
  on-secondary-fixed-variant: '#374c36'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c9c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474646'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  headline-display:
    fontFamily: EB Garamond
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Outfit
    fontSize: 18px
    fontWeight: '300'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Outfit
    fontSize: 16px
    fontWeight: '300'
    lineHeight: '1.6'
  label-md:
    fontFamily: Outfit
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 1.5rem
  margin-desktop: 4rem
  margin-mobile: 1.5rem
  section-gap: 8rem
---

## Brand & Style

The design system embodies the spirit of the Colombian Orinoquía—a dialogue between the untamed wild and world-class luxury. It targets high-end travelers seeking an immersive natural experience without sacrificing sophistication. 

The aesthetic is rooted in **Minimalism** with a **High-Contrast** edge. It utilizes expansive whitespace to reflect the vastness of the eastern plains, punctuated by deep architectural blacks and radiant gold accents. Visuals are treated with subtle dark overlays to evoke the mysterious depths of the jungle while ensuring the elegant typography remains the focal point. The interface should feel quiet, expensive, and grounded in the earth.

## Colors

The palette is a curated reflection of the lodge's physical environment. 

*   **Sand Gold (#c9a84c):** Our primary accent, used to draw attention to interactive elements and luxury highlights.
*   **Jungle Green (#1a2e1a):** A deep, organic shade used for secondary backgrounds and rich textures.
*   **Deep Black (#0d0d0d):** The grounding force, used for high-contrast sections, footers, and scrolled states of the navigation.
*   **Bone White & Warm Cream:** The primary canvas colors, providing a soft, natural alternative to clinical whites.

Image overlays must use a consistent `rgba(0,0,0,0.3)` to maintain legibility and a cohesive atmospheric mood.

## Typography

This design system uses a pairing of a classical serif and a modern, airy sans-serif to bridge the gap between tradition and contemporary comfort.

**EB Garamond** (serving as the elegant serif for Cormorant Garamond) is used for all titles. It should be typeset with generous leading and occasional negative letter-spacing for large display sizes to emphasize its graceful curves.

**Outfit** (serving as the airy sans-serif for Jost) provides a lightweight, highly readable counterpoint. Body text should remain light in weight (300) to maintain the "airy" feel. Labels and small navigation items use increased letter-spacing and uppercase styling to evoke a sense of curated precision.

## Layout & Spacing

The layout utilizes a **Fixed Grid** philosophy to create a sense of architectural stability and luxury. 

*   **Desktop:** A 12-column grid with a maximum width of 1280px. Margins are generous (4rem) to let the content breathe.
*   **Sectioning:** High vertical spacing (8rem) between major content blocks reinforces the premium, unhurried pace of the brand.
*   **Mobile:** Transitions to a 4-column fluid grid with 1.5rem margins. 

Content should frequently utilize asymmetrical alignments—such as text blocks offset against large-scale imagery—to mirror the organic patterns of the natural landscape.

## Elevation & Depth

Depth is handled through **Tonal Layers** and **Glassmorphism** rather than traditional heavy shadows.

*   **Surface Tiers:** Use the transition between Bone White and Warm Cream to define subtle shifts in content priority.
*   **Navigation:** The header begins as a translucent glass layer (backdrop-blur) to blend with hero photography, transitioning to a solid Deep Black (#0d0d0d) on scroll to provide a clear, "anchored" experience as the user dives into the content.
*   **Imagery:** Use soft, ambient shadows only when elements like "Book Now" cards float over complex backgrounds. Shadows should be low-opacity and tinted with the secondary Jungle Green to avoid a "muddy" appearance.

## Shapes

The shape language is **Soft**. While the overall grid is rigid and structured, individual components like buttons and cards feature a subtle 0.25rem (4px) corner radius. This "slight" rounding prevents the design from feeling too clinical or sharp, adding a touch of organic softness that aligns with the natural environment of the lodge. Icons should follow a thin-stroke, minimal aesthetic to match the weight of the typography.

## Components

### Buttons
*   **Primary:** Sand Gold (#c9a84c) background with Deep Black (#0d0d0d) text. Slightly rounded corners. This is the high-visibility call to action.
*   **Secondary:** Transparent background with a 1px border (White on dark backgrounds, Gold on light backgrounds). Text matches the border color.

### Navigation & Footer
*   **Header:** Floating and translucent with a heavy backdrop-blur. On scroll, it must animate to a solid #0d0d0d background.
*   **Footer:** A heavy, 3-column layout on a Deep Black (#0d0d0d) background. Use Bone White text for high contrast. Column 1: Brand/Logo, Column 2: Navigation Links, Column 3: Contact & Socials.

### Cards & Inputs
*   **Cards:** Use minimal containers. Often just a change in background color (Warm Cream) or a very thin Bone White border against a Jungle Green section.
*   **Inputs:** Bottom-border only for a sophisticated, "boutique hotel" feel. Focus states highlight the border in Sand Gold.

### Overlays
*   All hero and full-width background images must include a dark scrim (rgba(0,0,0,0.3)) to ensure the light serif titles are always legible.