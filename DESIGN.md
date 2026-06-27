---
name: Lumina Noir
colors:
  surface: '#10131a'
  surface-dim: '#10131a'
  surface-bright: '#363941'
  surface-container-lowest: '#0b0e15'
  surface-container-low: '#191b23'
  surface-container: '#1d2027'
  surface-container-high: '#272a31'
  surface-container-highest: '#32353c'
  on-surface: '#e1e2ec'
  on-surface-variant: '#c2c6d6'
  inverse-surface: '#e1e2ec'
  inverse-on-surface: '#2e3038'
  outline: '#8c909f'
  outline-variant: '#424754'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e6a'
  primary-container: '#4d8eff'
  on-primary-container: '#00285d'
  inverse-primary: '#005ac2'
  secondary: '#a4c9ff'
  on-secondary: '#00315d'
  secondary-container: '#0267b8'
  on-secondary-container: '#d6e5ff'
  tertiary: '#ffb786'
  on-tertiary: '#502400'
  tertiary-container: '#df7412'
  on-tertiary-container: '#461f00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#d4e3ff'
  secondary-fixed-dim: '#a4c9ff'
  on-secondary-fixed: '#001c39'
  on-secondary-fixed-variant: '#004883'
  tertiary-fixed: '#ffdcc6'
  tertiary-fixed-dim: '#ffb786'
  on-tertiary-fixed: '#311400'
  on-tertiary-fixed-variant: '#723600'
  background: '#10131a'
  on-background: '#e1e2ec'
  surface-variant: '#32353c'
typography:
  display-xl:
    fontFamily: Space Grotesk
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  label-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  code:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  container-max: 1200px
  gutter: 24px
  margin-sm: 16px
  margin-md: 32px
  margin-lg: 64px
  section-gap: 128px
---

## Brand & Style

This design system is engineered for high-end developer portfolios, emphasizing technical sophistication and premium craftsmanship. The aesthetic is **Futuristic Minimalism**, drawing heavy inspiration from the "developer-experience" aesthetic found in modern infrastructure tools. 

The brand personality is precise, innovative, and focused. It prioritizes clarity of information through a high-contrast dark environment, using light not just as illumination, but as a structural element to guide the user's eye toward key achievements and technical skills. The emotional response should be one of "effortless power"—a professional digital presence that feels both state-of-the-art and meticulously organized.

## Colors

The palette is anchored in a deep, "ink-trap" black base to provide infinite depth, layered with a dark navy for surface containers.

- **Base Background:** Used for the main body of the application to ensure maximum contrast for neon elements.
- **Surface:** Used for cards and navigation bars, typically applied with varying levels of transparency (Glassmorphism).
- **Primary Accent:** A vibrant Neon Blue used for calls-to-action and critical indicators. This color should frequently be paired with a `0 0 20px` outer glow (box-shadow) to simulate a light-emissive source.
- **Text:** Headings utilize pure white for a "shining" effect, while body text uses a muted slate to reduce eye strain and establish hierarchy.

## Typography

The typography system relies on the interplay between the geometric, technical character of **Space Grotesk** and the neutral, functional clarity of **Inter**.

- **Headlines:** Must be set with tight letter spacing to achieve the "Linear-style" editorial look. Large display sizes should use a bold weight to anchor the page.
- **Body:** Use Inter for all long-form content. The line height is intentionally generous (1.6) to ensure readability against the dark background.
- **Labels & Mono:** Utilize Geist (monospaced) for technical metadata, tags, and code snippets to reinforce the developer-centric theme.

## Layout & Spacing

This design system utilizes a **12-column fluid grid** for desktop, transitioning to a **4-column grid** for mobile. 

- **Philosophy:** Negative space is treated as a premium asset. Section gaps are intentionally large (128px+) to allow the portfolio items to "breathe" and stand as individual pieces of work.
- **Alignment:** Consistent left-alignment is preferred for a structured, clean look. 
- **Grids:** Use a 24px gutter for card layouts to maintain a clear separation of glassmorphic effects.

## Elevation & Depth

Depth is conveyed through **Glassmorphism** and **Tonal Layering** rather than traditional heavy shadows.

1.  **Base Layer:** The deepest layer is the #020617 solid background.
2.  **Mid Layer (Cards):** Surfaces use a semi-transparent #0F172A (opacity 0.6) with a `backdrop-filter: blur(12px)`.
3.  **Outlines:** Every elevated element must have a 1px border. Use a linear gradient for borders: `top-left: rgba(255,255,255,0.1)` to `bottom-right: rgba(255,255,255,0.02)`.
4.  **Glows:** Use primary-colored shadows with high diffusion (30px+) and low opacity (0.2) to simulate light emanating from interactive elements.

## Shapes

The shape language is sophisticated and modern, utilizing large radii to soften the technical nature of the content.

- **Standard Elements:** Buttons and small inputs use `0.5rem` (rounded).
- **Featured Elements:** Project cards and main containers use `rounded-xl` (1.5rem) to create a distinct "pod" or "window" feel.
- **Interactive States:** Hovering over cards should trigger a subtle expansion of the border-radius or a sharpening of the inner glow.

## Components

- **Buttons:** Primary buttons are solid Neon Blue (#3B82F6) with white text. They feature a `0px 4px 20px rgba(59, 130, 246, 0.4)` box-shadow. Secondary buttons are "ghost" style with the glassmorphic border described in the Elevation section.
- **Cards:** Must include a subtle inner highlight—a 1px semi-transparent white line at the very top edge to catch the "light."
- **Chips/Tags:** Small, pill-shaped elements with a #0F172A background and a 1px border. Use monospaced font for technical tags (e.g., "React", "TypeScript").
- **Inputs:** Dark backgrounds (#020617) with a subtle 1px border that glows Neon Blue on focus.
- **Navigation:** A "floating" glassmorphic bar at the top of the viewport, using a heavy backdrop blur to maintain legibility over background content.