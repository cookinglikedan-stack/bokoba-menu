---
name: Artisanal Essence
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#454840'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#75786f'
  outline-variant: '#c5c8bd'
  surface-tint: '#546346'
  primary: '#28351c'
  on-primary: '#ffffff'
  primary-container: '#3e4c31'
  on-primary-container: '#acbc9a'
  inverse-primary: '#bccca9'
  secondary: '#785839'
  on-secondary: '#ffffff'
  secondary-container: '#fed2ab'
  on-secondary-container: '#79593a'
  tertiary: '#32312c'
  on-tertiary: '#ffffff'
  tertiary-container: '#484842'
  on-tertiary-container: '#b8b6af'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e8c4'
  primary-fixed-dim: '#bccca9'
  on-primary-fixed: '#131f08'
  on-primary-fixed-variant: '#3d4b30'
  secondary-fixed: '#ffdcbf'
  secondary-fixed-dim: '#e9bf99'
  on-secondary-fixed: '#2c1601'
  on-secondary-fixed-variant: '#5e4124'
  tertiary-fixed: '#e5e2da'
  tertiary-fixed-dim: '#c9c6bf'
  on-tertiary-fixed: '#1c1c17'
  on-tertiary-fixed-variant: '#474741'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

This design system translates the rustic, hand-crafted charm of the physical coffee shop into a digital experience defined by **Minimalism** and **Glassmorphism**. The brand personality is sophisticated yet grounded, targeting coffee enthusiasts who value both quality and aesthetic tranquility.

The visual language balances the "earthy" origins of coffee—using textures inspired by the provided menu's grain and the deep tones of the logo—with high-end modern UI techniques. Expect generous whitespace, smooth micro-interactions, and a sense of "digital tactile" through translucent layers that mimic steam on glass or the clarity of a cold-brew carafe.

## Colors

The palette is derived directly from the organic elements of the coffee-making process.
- **Primary (Deep Olive Green):** Used for primary actions and brand accents, evoking the coffee plant and natural freshness.
- **Secondary (Warm Earth):** A direct pull from the roasted coffee tones in the existing logo, used for highlights and secondary buttons.
- **Background (Cream White / Beige):** A warm, high-contrast base that is softer on the eyes than pure white, providing a "paper-like" editorial feel.
- **Neutral (Matte Black):** Used for high-priority typography to ensure legibility and a premium "ink-on-paper" look.

## Typography

The typography strategy employs a classic "Serif for Display, Sans for Utility" pairing. 
- **Playfair Display** provides the editorial elegance required for a premium specialty shop, used for headings and menu categories.
- **Inter** ensures maximum readability for ingredient lists, prices, and descriptions, maintaining a clean and modern contrast to the decorative serif.
- **Letter Spacing:** Headlines should use tighter tracking to feel cohesive, while small labels use increased tracking for a modern, architectural feel.

## Layout & Spacing

This design system utilizes a **Fixed Grid** on desktop (12 columns) and a **Fluid Grid** on mobile (4 columns). The layout philosophy is "Centric and Focused," pushing core content to the middle with expansive margins to evoke a feeling of luxury and breathing room.

- **Desktop:** 12-column grid, 1200px max-width, 24px gutters.
- **Mobile:** 4-column grid, full-bleed with 20px side margins.
- **Rhythm:** Use multiples of 8px for all internal component spacing to maintain a consistent mathematical scale.

## Elevation & Depth

Hierarchy is established through **Glassmorphism** and **Tonal Layering** rather than traditional heavy shadows.
- **The Glass Layer:** Elevated elements (like floating navigation bars or modal cards) use a 70% opacity fill of the background color with a 20px backdrop blur and a subtle 1px "silk" border (white at 20% opacity).
- **Shadows:** When used, shadows must be "Ambient"—low opacity (#3E4C31 at 8%), high blur (40px), and zero spread, creating a soft glow rather than a hard lift.
- **Depth:** Content is organized in three tiers: 
  1. Base (Cream White)
  2. Content Cards (Solid White)
  3. Overlays/Navigation (Glassmorphic)

## Shapes

The shape language is **Soft (0.25rem - 0.75rem)**. While the brand is modern, overly rounded or "bubbly" shapes are avoided to maintain the sophisticated, premium tone. 

Corners should be sharp enough to feel precise but softened enough to feel approachable. Large imagery, such as product photos of coffee and food, should use the `rounded-lg` (0.5rem) token to sit comfortably within the layout.

## Components

### Buttons
- **Primary:** Solid Matte Black with White Inter text. Minimalist, no icon unless necessary for navigation.
- **Secondary:** Ghost style with a 1px Primary Green border.
- **Interaction:** On hover, primary buttons should shift to Deep Olive Green with a slow (300ms) transition.

### Input Fields & Selectors
- Underline-only style or very light-filled containers to maintain the minimalist aesthetic. Focus states should use the Secondary (Earth) color for the indicator.

### Cards (Menu Items)
- Use a "Floating" card style. Images should have a slight zoom-in effect on hover. Prices should be displayed in the Serif font to highlight the premium nature of the offering.

### Chips (Dietary/Category Labels)
- Small, uppercase Inter text inside a Soft-rounded pill with a 10% opacity fill of the Primary Green.

### Glass Navigation
- The top navigation bar should be a persistent glassmorphic element, allowing the rich coffee photography to blur beautifully as the user scrolls.