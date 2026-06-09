---
name: Aloha Chapter
colors:
  surface: '#fdf9f3'
  surface-dim: '#ddd9d4'
  surface-bright: '#fdf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ed'
  surface-container: '#f1ede7'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e6e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#3e484b'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f4f0ea'
  outline: '#6e797c'
  outline-variant: '#bec8cc'
  surface-tint: '#006879'
  primary: '#005d6d'
  on-primary: '#ffffff'
  primary-container: '#00778b'
  on-primary-container: '#d3f5ff'
  inverse-primary: '#7cd3e9'
  secondary: '#3b6934'
  on-secondary: '#ffffff'
  secondary-container: '#b9eeab'
  on-secondary-container: '#3f6d38'
  tertiary: '#8b3a3c'
  on-tertiary: '#ffffff'
  tertiary-container: '#a95253'
  on-tertiary-container: '#ffebea'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#abedff'
  primary-fixed-dim: '#7cd3e9'
  on-primary-fixed: '#001f26'
  on-primary-fixed-variant: '#004e5c'
  secondary-fixed: '#bcf0ae'
  secondary-fixed-dim: '#a1d494'
  on-secondary-fixed: '#002201'
  on-secondary-fixed-variant: '#23501e'
  tertiary-fixed: '#ffdad9'
  tertiary-fixed-dim: '#ffb3b2'
  on-tertiary-fixed: '#3f0209'
  on-tertiary-fixed-variant: '#7a2d30'
  background: '#fdf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e6e2dc'
typography:
  display-lg:
    fontFamily: Merriweather
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 60px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Merriweather
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Merriweather
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Merriweather
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 32px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 80px
---

## Brand & Style
The brand personality is a "Tropical Literary Retreat." It reimagines the shared family reading experience as a sun-drenched escape to the Hawaiian islands. The target audience is families seeking a serene, organized, yet emotionally warm space to discuss books.

The visual style is **Modern/Sophisticated Tropical**. It avoids kitsch in favor of a refined, airy aesthetic. It utilizes generous whitespace to mimic the openness of a beach, paired with "sun-drenched" depth—soft shadows that feel like natural light hitting a surface. The emotional response should be one of relaxation, intellectual curiosity, and warmth.

## Colors
The palette is inspired by the natural transitions of a Hawaiian day.
- **Primary (Ocean Teal):** Used for main actions and branding, representing the clear Pacific waters.
- **Secondary (Jungle Green):** Used for success states and secondary structural elements, evoking lush foliage.
- **Tertiary (Sunset Coral):** Reserved for highlights, notifications, and playful accents.
- **Neutral (Warm Sand):** The foundation of the UI. Avoid pure white (#FFFFFF); use the sand tones for surfaces to reduce eye strain and enhance the "sun-drenched" feel.
- **Ocean Deep:** Used for primary text to maintain high legibility while remaining softer than pure black.

## Typography
This design system pairs the authoritative, literary feel of **Merriweather** with the friendly, contemporary warmth of **Be Vietnam Pro**. 

- **Serif (Merriweather):** Used for all headlines and display text. It anchors the "book club" aspect of the app, providing a classic, scholarly contrast to the tropical theme.
- **Sans-Serif (Be Vietnam Pro):** Used for body copy, buttons, and navigation. Its open counters and friendly curves keep the interface feeling modern and approachable.
- **Scale:** Maintain a clear hierarchy. Large display type should use tighter letter spacing to feel like a premium editorial magazine.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a "breathable" philosophy. 

- **Desktop:** 12-column grid with wide 80px margins to simulate the feeling of a centered book page. 
- **Mobile:** 4-column grid with 16px margins.
- **Rhythm:** Use an 8px incremental system. For tropical "airiness," lean toward larger spacing values (`lg` and `xl`) between major sections to prevent the UI from feeling cluttered. 
- **Safe Zones:** Ensure content never touches the edges of the screen; the "Sand" neutral background should always act as a soft frame.

## Elevation & Depth
Depth is created through **Ambient Shadows** and **Tonal Layering**, mimicking a soft overhead sun.

- **Shadows:** Use extremely soft, diffused shadows with a slight primary-color tint (e.g., `rgba(0, 119, 139, 0.08)`) instead of grey. This makes elements feel like they are floating over the sand.
- **Surfaces:** Use `Sand Light` for the base background and `White` for elevated cards. This subtle contrast provides hierarchy without the harshness of heavy borders.
- **Patterns:** Apply low-opacity (2-3%) SVG patterns of monstera leaves or gentle waves to the `Sand Light` background sections to add tactile richness without distracting from the text.

## Shapes
The shape language is consistently **Rounded**, reflecting the organic curves of the islands.

- **Standard Elements:** Buttons and input fields use a `0.5rem` radius.
- **Containers:** Large cards and book covers use `1rem` (rounded-lg) to emphasize a soft, friendly container.
- **Interactive Prompts:** Modals and bottom sheets use `1.5rem` (rounded-xl) on top corners to create a "nested" and safe aesthetic.

## Components
- **Buttons:** Primary buttons use a solid `Ocean Teal` with white text. Secondary buttons use a `Jungle Green` outline with `0.5px` weight. Use a gentle "lift" animation on hover.
- **Cards:** Book cards should have a vertical orientation with `rounded-lg` corners. Include a very soft shadow to distinguish the book from the page.
- **Chips (Genres/Tags):** Use `Sunset Coral` or `Jungle Green` at 10% opacity with saturated text of the same color. Keep corners fully rounded (pill-shaped).
- **Inputs:** Backgrounds should be `White` with a `1px` border in `Sand Dark`. On focus, the border transitions to `Ocean Teal` with a soft outer glow.
- **Progress Bars:** Use a "Wave" animation for the progress fill—a subtle gradient from `Ocean Teal` to `Ocean Light` to signify reading completion.
- **Specialty Component - "The Hearth":** A shared family discussion area styled like a wooden deck, using a slightly darker tan hue and centered typography.