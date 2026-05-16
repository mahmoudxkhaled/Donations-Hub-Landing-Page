---
name: Serene Trust
colors:
  surface: '#f4fafd'
  surface-dim: '#d4dbdd'
  surface-bright: '#f4fafd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eef5f7'
  surface-container: '#e8eff1'
  surface-container-high: '#e2e9ec'
  surface-container-highest: '#dde4e6'
  on-surface: '#161d1f'
  on-surface-variant: '#414844'
  inverse-surface: '#2b3234'
  inverse-on-surface: '#ebf2f4'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3f6653'
  primary: '#012d1d'
  on-primary: '#ffffff'
  primary-container: '#1b4332'
  on-primary-container: '#86af99'
  inverse-primary: '#a5d0b9'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#272621'
  on-tertiary: '#ffffff'
  tertiary-container: '#3d3c37'
  on-tertiary-container: '#a9a69f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecd4'
  primary-fixed-dim: '#a5d0b9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#274e3d'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e6e2da'
  tertiary-fixed-dim: '#c9c6bf'
  on-tertiary-fixed: '#1c1c17'
  on-tertiary-fixed-variant: '#484741'
  background: '#f4fafd'
  on-background: '#161d1f'
  surface-variant: '#dde4e6'
  sage-wash: '#E8F0E9'
  gold-leaf: '#C5A028'
  parchment: '#FCF9F5'
  charcoal-haze: '#3D4543'
typography:
  display-lg:
    fontFamily: Source Serif 4
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Source Serif 4
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Source Serif 4
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Source Serif 4
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max-width: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

The design system is centered on the concept of "Sacred Stewardship"—a blend of professional excellence and spiritual warmth. The target audience includes community donors, non-profit administrators, and beneficiaries who seek a platform that feels both institutional and inviting.

The visual style is **Contemporary Minimalism** with a **Tactile** warmth. It avoids the coldness of standard SaaS platforms by utilizing organic textures, off-white foundations, and extremely subtle Islamic geometric motifs (low-opacity patterns in container backgrounds). The atmosphere should evoke a sense of quiet confidence, transparency, and communal belonging.

## Colors

The palette is rooted in the natural world to inspire tranquility. 
- **Primary (Deep Forest Green):** Used for primary actions, navigation headers, and authoritative text to signal growth and stability.
- **Secondary (Warm Gold):** Reserved for high-value accents, success states, and featured highlights (e.g., "Goal Reached" badges).
- **Background (Parchment):** The primary canvas is never pure white (#FFFFFF); instead, it uses a soft off-white to reduce eye strain and feel more organic.
- **Text (Charcoal Haze):** A deep, softened black ensures high legibility without the harshness of pure black.

## Typography

This design system uses a sophisticated serif-sans pairing. 
- **Headlines:** `Source Serif 4` provides an editorial, authoritative feel that communicates tradition and prestige.
- **Body & UI:** `Manrope` is used for its modern, geometric clarity and exceptional readability at smaller sizes. 
- **Styling:** Headlines should utilize tighter letter-spacing for a refined look. Body text maintains generous line-height to support the "airy" brand pillar.

## Layout & Spacing

The layout follows a **Fixed Grid** system for desktop to maintain an "organized hub" feel, while transitioning to a fluid model for tablet and mobile.

- **Grid:** 12-column grid for desktop (1280px max-width).
- **Rhythm:** An 8px linear scale guides all spatial decisions. 
- **White Space:** Generous margins and padding are mandatory. Information density should be kept low to medium to ensure the user never feels overwhelmed by data.
- **Breakpoints:**
  - Desktop: 1024px+ (64px margins)
  - Tablet: 768px - 1023px (40px margins)
  - Mobile: Under 767px (20px margins, single column reflow)

## Elevation & Depth

Hierarchy is achieved through **Tonal Layers** and **Ambient Shadows** rather than stark lines.

- **Surfaces:** Use `parchment` for the base and `white` for elevated card surfaces.
- **Shadows:** Shadows are highly diffused and slightly tinted with the primary green hue to prevent them from looking "dirty" or grey. 
  - *Example:* `0px 10px 30px rgba(27, 67, 50, 0.04)`.
- **Glassmorphism:** Use sparingly for sticky navigation bars with a high-intensity backdrop blur (20px) and a subtle 1px border using `sage-wash`.

## Shapes

The shape language is soft and welcoming. 
- **Standard Radius:** 0.5rem (8px) for inputs and smaller components.
- **Large Radius:** 1rem (16px) for cards and primary containers.
- **Extra Large Radius:** 1.5rem (24px) for feature hero sections or call-to-action banners.
- **Geometric Accents:** Subtle, repeating 8-point star patterns can be used as watermark backgrounds in card corners or as divider icons.

## Components

- **Buttons:** Primary buttons use a solid `primary-color` with white text. Hover states should involve a slight lift (shadow increase) and a shift to a slightly lighter green. Secondary buttons use a `sage-wash` background with primary-colored text.
- **Cards:** Cards should have a white background, no visible border, and the soft ambient shadow described in Elevation. They should feel "lifted" from the parchment background.
- **Input Fields:** Use a subtle `sage-wash` fill with a bottom-only 2px border that transitions to `primary-color` on focus.
- **Chips/Badges:** Use a light `secondary-color` (warm beige/gold) for status indicators like "Urgent" or "Featured" to draw attention without being alarming.
- **Progress Bars:** For donation tracking, use a `sage-wash` track with a `primary-color` fill. The progress indicator should be rounded and smooth.
- **Lists:** Use generous vertical padding (16px+) between list items, separated by very light `sage-wash` dividers.