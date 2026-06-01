---
name: Vitality Care
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#3f4a3c'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#6f7a6a'
  outline-variant: '#becab8'
  surface-tint: '#006e15'
  primary: '#006713'
  on-primary: '#ffffff'
  primary-container: '#128220'
  on-primary-container: '#dcffd2'
  inverse-primary: '#76dd6f'
  secondary: '#2d6a42'
  on-secondary: '#ffffff'
  secondary-container: '#b0f2bf'
  on-secondary-container: '#337048'
  tertiary: '#515a54'
  on-tertiary: '#ffffff'
  tertiary-container: '#69726c'
  on-tertiary-container: '#eef7ef'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#91fa88'
  primary-fixed-dim: '#76dd6f'
  on-primary-fixed: '#002202'
  on-primary-fixed-variant: '#00530d'
  secondary-fixed: '#b0f2bf'
  secondary-fixed-dim: '#95d5a4'
  on-secondary-fixed: '#00210d'
  on-secondary-fixed-variant: '#10512c'
  tertiary-fixed: '#dce5dd'
  tertiary-fixed-dim: '#c0c9c1'
  on-tertiary-fixed: '#151d19'
  on-tertiary-fixed-variant: '#404943'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e5e2e1'
typography:
  headline-xl:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
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
  label-sm:
    fontFamily: JetBrains Mono
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
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style

The design system is rooted in the "Professional Healthcare" aesthetic, emphasizing reliability, vitality, and clinical precision. It targets families and individuals seeking home-based medical and personal care. The visual language evokes a sense of growth and security by pairing a vibrant, life-affirming green with a deep, authoritative forest green.

The style is **Corporate / Modern** with a focus on high-contrast accessibility. It utilizes sharp white surfaces to convey cleanliness and hygiene, while using bold, saturated green accents to guide user actions and reinforce brand identity. This system prioritizes clarity and speed of information retrieval, essential for healthcare environments.

## Colors

The palette is centered on a dual-green strategy that replaces all legacy blue tones. 

- **Primary Green (#128220):** Used for primary calls to action, active states, and success indicators. This color represents growth and vitality.
- **Deep Forest (#004723):** Used for headers, footers, and structural elements to provide a sense of grounded stability and professionalism.
- **Surface Tint (#F0F9F1):** A very light green wash used for background sections to distinguish them from the pure white "Clinical White" surfaces without losing the clean aesthetic.
- **Neutral:** A range of high-contrast grays ensures legibility, with the darkest neutral reserved for body text to maintain a strict 4.5:1 contrast ratio.

## Typography

This design system uses **Manrope** as its primary typeface to balance modern geometric shapes with humanist warmth. Headlines are set with tight tracking and heavy weights to appear impactful and trustworthy. 

For technical details, timestamps, or small metadata, **JetBrains Mono** is used sparingly to introduce a precise, systematic feel that complements the healthcare context. Body text is always optimized for readability with generous line heights to ensure accessibility for older populations.

## Layout & Spacing

The design system utilizes a **12-column Fluid Grid** for desktop and a **4-column Fluid Grid** for mobile devices. 

- **Vertical Rhythm:** Built on an 8px base unit. Component heights and vertical spacing should always be multiples of 8.
- **Safe Areas:** Large 40px margins on desktop provide "breathing room," reinforcing the premium healthcare feel. 
- **Density:** High-density layouts are preferred for data-heavy sections (like schedules), while marketing sections use low-density spacing with large gaps between content blocks to maintain focus.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows.

- **Level 0 (Background):** Pure white (#FFFFFF) or Surface Tint (#F0F9F1).
- **Level 1 (Cards/Containers):** Pure white with a 1px solid stroke in a light neutral or a subtle, highly diffused 10% opacity Deep Forest shadow.
- **Level 2 (Interactive):** Elements that are hovered or active use the Primary Green as a subtle glow effect or a slight upward translation (Y-axis) to indicate interactability.

## Shapes

The design system uses "Rounded" geometry (0.5rem base) to appear approachable and friendly. 

- **Primary Buttons:** Use the standard `rounded` (8px) setting.
- **Service Tags / Chips:** Use the `rounded-xl` (24px) setting to create a softer, pill-like appearance.
- **Imagery:** Photos of caregivers and patients should use `rounded-lg` (16px) or be contained within circular masks to mirror the organic "leaf" shapes found in the brand identity.

## Components

- **Buttons:** Primary buttons are solid Primary Green with white text. Secondary buttons use a Deep Forest outline. All buttons feature a 2px stroke and 8px corner radius.
- **Cards:** Cards use a white background with a thin Deep Forest border (10% opacity) to provide structure without clutter.
- **Inputs:** Text fields use a 1px gray border that transitions to Primary Green on focus. Labels sit outside the field in a bold, smaller Manrope font.
- **Checklists:** Use custom green checkmarks within rounded squares, directly inspired by the "Our Services" section of the marketing materials.
- **Schedule Blocks:** High-contrast containers using Deep Forest backgrounds with white text for headers, and white backgrounds with green text for time slots to ensure maximum visibility.
- **Iconography:** Icons should be thick-stroked and rounded, colored in either Primary or Deep Forest green to maintain monochromatic harmony.