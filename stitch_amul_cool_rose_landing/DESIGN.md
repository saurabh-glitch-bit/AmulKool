---
name: Rosé Minimalist
colors:
  surface: '#fdf9f3'
  surface-dim: '#dddad4'
  surface-bright: '#fdf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ed'
  surface-container: '#f1ede7'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e6e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#514345'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f4f0ea'
  outline: '#837375'
  outline-variant: '#d6c2c4'
  surface-tint: '#864e5a'
  primary: '#864e5a'
  on-primary: '#ffffff'
  primary-container: '#ffb7c5'
  on-primary-container: '#7b4551'
  inverse-primary: '#fbb3c1'
  secondary: '#1d5fa8'
  on-secondary: '#ffffff'
  secondary-container: '#7ab0ff'
  on-secondary-container: '#00417e'
  tertiary: '#a5374b'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffb8bf'
  on-tertiary-container: '#992d42'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9df'
  primary-fixed-dim: '#fbb3c1'
  on-primary-fixed: '#360c19'
  on-primary-fixed-variant: '#6b3743'
  secondary-fixed: '#d5e3ff'
  secondary-fixed-dim: '#a6c8ff'
  on-secondary-fixed: '#001c3b'
  on-secondary-fixed-variant: '#004787'
  tertiary-fixed: '#ffd9dc'
  tertiary-fixed-dim: '#ffb2ba'
  on-tertiary-fixed: '#400010'
  on-tertiary-fixed-variant: '#861e35'
  background: '#fdf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e6e2dc'
  deep-rose: '#63001E'
  cream-surface: '#FDF9F3'
  ink-black: '#140008'
  soft-petal: '#FFB7C5'
  amul-blue: '#00529B'
typography:
  display-lg:
    fontFamily: ebGaramond
    fontSize: 84px
    fontWeight: '500'
    lineHeight: 92px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: ebGaramond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: ebGaramond
    fontSize: 36px
    fontWeight: '500'
    lineHeight: 42px
  headline-md:
    fontFamily: ebGaramond
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  body-lg:
    fontFamily: inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: jetbrainsMono
    fontSize: 12px
    fontWeight: '500'
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style
The design system is centered on a "refined indulgence" aesthetic. It targets a modern, lifestyle-conscious audience by elevating a traditional beverage into a premium sensory experience. 

The style is a blend of **Minimalism** and **Soft Modernism**. It utilizes expansive white space (using cream tones), high-contrast editorial typography, and subtle motion to create a sense of calm and luxury. The emotional response should be one of freshness, sophistication, and effortless cooling. Visuals should prioritize high-quality product photography set against minimalist backgrounds, avoiding cluttered compositions.

## Colors
The palette is inspired by the delicate infusion of rose in dairy. 
- **Primary (Soft Petal):** Used for soft backgrounds, accent shapes, and primary lifestyle callouts.
- **Secondary (Amul Blue):** Reserved for brand recognition, used sparingly in iconography, small UI accents, or subtle borders to tie back to the packaging.
- **Tertiary (Deep Rose):** Used for high-impact typography and interactive states to provide depth and contrast against the lighter tones.
- **Neutral (Cream Surface):** The foundational canvas. It replaces pure white to provide a warmer, more organic feel that evokes the milk-based nature of the product.

## Typography
The typographic scale emphasizes an editorial feel.
- **Headlines:** `ebGaramond` provides a classic, literary elegance. Use tight tracking for large display text to maintain a modern edge.
- **Body:** `inter` ensures maximum readability for product descriptions and nutritional information, providing a functional contrast to the serif headlines.
- **Labels:** `jetbrainsMono` is used for technical data, ingredients, or small meta-labels, adding a precise, contemporary touch that keeps the design from feeling overly traditional.

## Layout & Spacing
The layout follows a **Fluid Grid** model with generous margins to enforce the minimalist narrative. 
- **Desktop:** A 12-column grid with 64px outer margins. Content should often be offset or centered with significant "dead space" to focus the eye on the product imagery.
- **Mobile:** A 4-column grid with 20px margins. 
- **Rhythm:** Use an 8px base unit. Vertical spacing between sections should be aggressive (e.g., 120px to 160px) to allow the design to "breathe."

## Elevation & Depth
This design system avoids heavy shadows to maintain its clean, high-end aesthetic. 
- **Depth:** Created through **Tonal Layers**. Elements are separated by subtle shifts between the Cream Surface (#FDF9F3) and the Soft Petal (#FFB7C5) backgrounds.
- **Overlays:** Use high-diffusion backdrop blurs (Glassmorphism) for navigation bars or modals to maintain a sense of lightness.
- **Interactions:** Subtle scale-up effects or opacity shifts are preferred over shadow-based elevation for hover states.

## Shapes
Shapes are generally **Soft** and restrained. 
- **Cards & Containers:** Use a 0.25rem (4px) radius for a "sharp but not aggressive" look.
- **Buttons:** Can utilize a higher roundedness (up to 1rem) to differentiate them as interactive touchpoints, but never fully pill-shaped unless they are small utility chips.
- **Imagery:** Product photos should be contained in rectangular frames with soft corners or occasionally used as "cut-outs" floating over the tonal background.

## Components
- **Buttons:** Primary buttons use the Deep Rose background with Cream text. Secondary buttons use a Thin Amul Blue outline with a slight tint on hover.
- **Inputs:** Minimalist bottom-border only or very light cream fills with no heavy borders. Focus states use an Amul Blue underline.
- **Cards:** Borderless. Use subtle background color shifts (e.g., from Cream to Soft Petal) to define boundaries.
- **Chips:** Small, JetBrains Mono labels wrapped in a light Soft Petal tint, used for flavor notes or ingredient highlights.
- **Lists:** Clean, horizontal dividers using a low-opacity Deep Rose (#63001E) line to maintain structure without cluttering the view.
- **Product Carousel:** Large-scale imagery with minimal text overlays, emphasizing the visual appeal of the Rose flavor.