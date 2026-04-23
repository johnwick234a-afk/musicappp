---
name: Aura
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1b1b1b'
  on-surface-variant: '#4c4546'
  inverse-surface: '#303030'
  inverse-on-surface: '#f1f1f1'
  outline: '#7e7576'
  outline-variant: '#cfc4c5'
  surface-tint: '#5e5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1b'
  on-primary-container: '#848484'
  inverse-primary: '#c6c6c6'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e1dfdf'
  on-secondary-container: '#626262'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b1b1b'
  on-tertiary-container: '#848484'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#e4e2e2'
  secondary-fixed-dim: '#c7c6c6'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1b1b1b'
  on-tertiary-fixed-variant: '#474747'
  background: '#f9f9f9'
  on-background: '#1b1b1b'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-md:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Manrope
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
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  gutter: 16px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style
The brand personality of this design system is sophisticated, immersive, and serene. It is designed for music enthusiasts who value a focused listening experience without visual clutter. The UI should evoke a sense of "quiet luxury," where the interface recedes to let the artistry of the music and album photography take center stage.

The chosen style is **Minimalism** with a touch of **Glassmorphism**. By prioritizing expansive whitespace and a monochromatic foundation, the system ensures that the vibrant colors of album art provide the primary visual energy. Interactions are subtle and fluid, creating a premium, tactile feel that rewards exploration.

## Colors
The color strategy uses a "Gallery" approach. The primary canvas is a pure neutral spectrum ranging from absolute white to deep obsidian. 

- **Primary & Neutrals:** Used for structural elements, text, and icons to maintain a high-contrast, legible hierarchy.
- **Accent:** A single vibrant "Electric Poppy" red is reserved exclusively for active states, playback progress, and primary call-to-action buttons. 
- **Dynamic Adaptivity:** While the system is light-mode by default, the "Now Playing" screens should dynamically sample colors from the album art to create subtle background gradients, ensuring the UI feels integrated with the content.

## Typography
This design system utilizes a dual sans-serif pairing to achieve a balance between editorial character and functional clarity. 

**Manrope** is used for headings and display titles. Its refined, modern geometric construction provides the "premium" feel required for artist names and album titles. **Inter** is used for all functional UI elements, body text, and metadata. It is selected for its exceptional legibility at small sizes, specifically within dense tracklists. Tighten letter-spacing on larger headings to maintain a cohesive, "locked-in" aesthetic.

## Layout & Spacing
The layout follows a **Fixed Grid** model for desktop and a **Fluid Grid** for mobile devices. On mobile, a 4-column grid is used with generous 20px side margins to prevent content from feeling cramped. 

The spacing rhythm is strictly based on a 4px baseline grid. Use "xl" (40px) or larger spacing between major sections (e.g., between "Recently Played" and "Your Playlists") to reinforce the minimal aesthetic and provide the requested "plenty of whitespace." Album art should always maintain a 1:1 aspect ratio and be the dominant anchor of every layout.

## Elevation & Depth
Depth is created through **Ambient Shadows** and **Tonal Layers** rather than heavy lines. 
- **Surface Level 0:** The main background, pure white or soft grey.
- **Surface Level 1:** Cards and containers use a very subtle, highly diffused shadow (Blur: 20px, Opacity: 4%, Color: Black) to appear as if floating slightly above the canvas.
- **Interactive Layers:** Use a soft backdrop blur (Glassmorphism) for persistent elements like the bottom playback bar or navigation headers. This allows the colors of the album art to bleed through as the user scrolls, maintaining a sense of place.

## Shapes
The shape language is consistently **Rounded**, reflecting the fluid nature of music. 
- **Standard Elements:** Buttons and input fields use a 0.5rem radius.
- **Album Art:** Large album covers use a `rounded-xl` (1.5rem) radius to soften the high-quality imagery.
- **Chips/Badges:** Use a full pill-shape for genre tags or status indicators to distinguish them from structural cards.

## Components
- **Buttons:** Primary buttons are solid black with white text. Ghost buttons use the accent color only for the text label. All buttons feature a subtle lift on hover.
- **Playback Controls:** The "Play" button is the only element allowed to use the vibrant accent color as a solid background. Other controls (Skip, Shuffle) use secondary grey.
- **Cards:** Music cards (albums/playlists) should have no borders. Use a soft shadow and ensure the typography is placed with at least 12px of internal padding from the edge of the artwork.
- **Tracklists:** Use "Inter" at `body-md` for track names. Metadata (duration, artist) should use `secondary_color` at a smaller scale. List items should have a hover state that slightly darkens the background (`surface_low`).
- **Progress Bars:** Use a thin 4px track. The background is `surface_medium`, and the active progress is the `accent_color`. The "scrubber" handle should only appear on interaction.
- **Input Fields:** Search bars should be `surface_low` with no border, using a search icon as a leading element and rounded-lg corners.
