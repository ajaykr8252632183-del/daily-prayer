---
name: Sacred Devotion
colors:
  surface: '#0f131f'
  surface-dim: '#0f131f'
  surface-bright: '#353946'
  surface-container-lowest: '#0a0e1a'
  surface-container-low: '#171b28'
  surface-container: '#1b1f2c'
  surface-container-high: '#262a37'
  surface-container-highest: '#313442'
  on-surface: '#dfe2f3'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#dfe2f3'
  inverse-on-surface: '#2c303d'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#fff9ef'
  on-secondary: '#3a3000'
  secondary-container: '#ffdb3c'
  on-secondary-container: '#725f00'
  tertiary: '#bfcdff'
  on-tertiary: '#082b72'
  tertiary-container: '#97b0ff'
  on-tertiary-container: '#254188'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#ffe16d'
  secondary-fixed-dim: '#e9c400'
  on-secondary-fixed: '#221b00'
  on-secondary-fixed-variant: '#544600'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#27438a'
  background: '#0f131f'
  on-background: '#dfe2f3'
  surface-variant: '#313442'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  hindi-label:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-padding: 24px
  gutter: 16px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 40px
---

## Brand & Style

This design system is crafted to evoke a sense of divine tranquility, reverence, and premium craftsmanship. It serves a bilingual audience seeking a sanctuary for daily reflection and spiritual growth. 

The aesthetic is a sophisticated blend of **Modern Minimalism** and **Glassmorphism**, characterized by deep, celestial backgrounds contrasted with luminous, radiant accents. The interface relies on subtle glows and translucent layers to simulate a "divine light" filtering through digital surfaces. Every element is designed to feel intentional and precious, moving away from utility-only interfaces toward an immersive, meditative experience.

## Colors

The palette is anchored in a profound **Midnight Navy (#0A0E1A)**, providing a stable, infinite backdrop that reduces eye strain during evening prayers. 

**Gold (#D4AF37)** is used exclusively as the "Sacred Accent." It denotes divinity and high priority. We use it for primary iconography, critical borders, and active states.

Functional colors:
- **Primary:** Metallic Gold for high-emphasis actions and religious symbols.
- **Surface:** Semi-transparent glass layers to create depth without breaking the solid navy background.
- **Typography:** Warm White (#F5F5F5) for primary text to ensure high legibility against the dark void, with Muted Gold (#A68B30) for secondary bilingual labels.

## Typography

The typographic hierarchy prioritizes a graceful, bilingual reading experience. 

- **Headlines:** Use **Playfair Display**. This serif font conveys authority and timelessness, essential for scriptural titles and prayer names.
- **Body & Labels:** Use **Plus Jakarta Sans**. Its modern, geometric curves offer excellent legibility for long-form scripture and prayer text.
- **Bilingual Treatment:** When displaying Hindi and English together, the Hindi script should be placed above the English equivalent. Hindi text should be 1-2px larger than the English body text to match visual weight, given the complexity of the characters.
- **Emphasis:** Key scriptural verses should be italicized when in English or given a subtle gold tint to differentiate from instructional text.

## Layout & Spacing

The layout follows a **Fixed-Width Column** approach on larger devices to maintain a "journal" or "psalms" feel, centered in the viewport. On mobile, we use a single-column fluid layout with generous horizontal margins (24px) to ensure the content feels breathy and unhurried.

Spacing is liberal; avoid crowding elements. Vertical rhythm should be driven by the `stack-md` (24px) unit to separate distinct prayer sections. Use `stack-lg` (40px) to separate major content blocks like "Verse of the Day" from "Prayer Categories."

## Elevation & Depth

This system avoids traditional shadows in favor of **Luminous Depth**. 

- **Glassmorphism:** All cards use a backdrop filter (`blur(12px)`) with a highly transparent white or navy fill (5-10% opacity). 
- **Gold Outlines:** Elevation is indicated by the intensity of the border. Lower-level elements have a faint navy border; high-priority elements (like the current prayer card) feature a 1px solid Gold border with a 4px soft outer gold glow (`drop-shadow`).
- **The Glow Effect:** Central spiritual icons (the Cross, Lotus, or Holy Spirit symbols) should feature a radial gradient "aura" behind them, using a soft gold (#D4AF37) at 20% opacity to simulate a holy radiance.

## Shapes

The design uses **Rounded (0.5rem)** corners as the baseline. This balance provides a modern feel while maintaining the structural integrity required for a premium app. 

- **Cards:** 16px (rounded-lg) for a soft, welcoming container.
- **Buttons:** Fully pill-shaped (rounded-xl) to contrast against the rectangular nature of the cards.
- **Interactive Glyphs:** Small icons should be encased in circular glass backgrounds.

## Components

### Buttons
- **Primary:** Pill-shaped, solid Gold (#D4AF37) with dark navy text. Use for "Amen" or "Start Prayer."
- **Secondary/Ghost:** Pill-shaped, transparent with a 1px Gold border.

### Prayer Cards
Large glassmorphic containers with 16px corner radius. They must include a subtle gold top-border (2px) to act as a "crown" for the content. Inside, Hindi and English text should be clearly separated by an 8px vertical gap.

### Input Fields
Underlined style (rather than boxed) to maintain a minimal, elegant aesthetic. The underline is 1px white (30% opacity), turning solid Gold on focus.

### Navigation Bar
A blur-heavy glass bar at the bottom. Active icons use solid Gold and a small glowing dot underneath. Inactive icons remain in Muted White.

### Progress Indicators (Prayer Tracking)
Thin, circular gold lines that fill as the user completes their daily devotion. Avoid heavy bars; use delicate, jewelry-like strokes.