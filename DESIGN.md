---
name: Serene Care System
colors:
  surface: '#fff9ee'
  surface-dim: '#dfd9cf'
  surface-bright: '#fff9ee'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f9f3e9'
  surface-container: '#f3ede3'
  surface-container-high: '#ede7dd'
  surface-container-highest: '#e8e2d8'
  on-surface: '#1d1b15'
  on-surface-variant: '#474741'
  inverse-surface: '#33302a'
  inverse-on-surface: '#f6f0e6'
  outline: '#787770'
  outline-variant: '#c8c7be'
  surface-tint: '#5f5e5b'
  primary: '#5f5e5b'
  on-primary: '#ffffff'
  primary-container: '#f5f2ed'
  on-primary-container: '#6f6e6a'
  inverse-primary: '#c9c6c2'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e4e2e1'
  on-secondary-container: '#656464'
  tertiary: '#536259'
  on-tertiary: '#ffffff'
  tertiary-container: '#e6f6ea'
  on-tertiary-container: '#637168'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2dd'
  primary-fixed-dim: '#c9c6c2'
  on-primary-fixed: '#1c1c19'
  on-primary-fixed-variant: '#474743'
  secondary-fixed: '#e4e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#d7e6db'
  tertiary-fixed-dim: '#bbcabf'
  on-tertiary-fixed: '#111e17'
  on-tertiary-fixed-variant: '#3c4a42'
  background: '#fff9ee'
  on-background: '#1d1b15'
  surface-variant: '#e8e2d8'
typography:
  display-lg:
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
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  button:
    fontFamily: DM Sans
    fontSize: 15px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.02em
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
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

The brand personality is **premium, serene, and meticulous**. It aims to transform a utilitarian chore—laundry—into a luxurious self-care experience. The design system targets a discerning audience that values time, quality, and aesthetic harmony. 

The visual style is a blend of **Minimalism** and **Editorial Elegance**. It utilizes generous white space (macro-typography), a soft organic color palette, and high-end photography to evoke a sense of calm. Unlike typical service platforms that feel transactional and "busy," this system prioritizes a boutique, atelier-like atmosphere where every detail feels intentional and "crafted."

**Emotional Response:** Trust, tranquility, and a feeling of "elevated living."

## Colors

The palette is rooted in earth-toned neutrals to create a soothing backdrop, punctuated by deep charcoals for authoritative legibility.

- **Primary (Sand/Beige):** Used for large surface areas and background layers to maintain a warm, airy feel.
- **Secondary (Charcoal):** Reserved for primary headings and body text to ensure high contrast and a professional, grounded tone.
- **Tertiary (Sage Green):** A muted, natural green used for secondary accents, success states, or eco-friendly service highlights.
- **Accent (Soft Slate Blue):** Used sparingly for primary Calls to Action (CTAs), providing a gentle but clear path for user interaction without disrupting the serene mood.
- **Neutral (Cream/Stone):** Used for subtle borders, dividers, and secondary container backgrounds to create soft depth.

## Typography

This system uses a classic pairing: a high-contrast serif for narrative elements and a geometric sans-serif for functional data.

- **Headlines:** Use *EB Garamond*. It should be set with tight letter-spacing for large displays. Use italic styles sparingly for emphasis or "editorial" pull-quotes to mimic high-end magazine layouts.
- **Body & Functional Text:** Use *DM Sans*. Its low-contrast, clean forms ensure readability in service descriptions and forms. 
- **Hierarchy:** Ensure a clear distinction between "Reading" text (Serif) and "Action" text (Sans-serif). Uppercase styling is reserved for labels and small navigation links to create a structured, organized feel.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to maintain "white-space-as-luxury," and a fluid approach for mobile.

- **Rhythm:** An 8px base unit drives all spacing. 
- **Sectioning:** Large vertical gaps (120px+) are used between major content blocks to prevent the interface from feeling crowded, allowing each service offering room to breathe.
- **Grid:** A 12-column grid is used for desktop. For premium "Editorial" sections, content should often be offset or centered within a 6-8 column span to create asymmetric interest.
- **Breakpoints:**
  - Desktop: 1024px+ (12 columns, 64px margins)
  - Tablet: 768px - 1023px (8 columns, 40px margins)
  - Mobile: < 767px (4 columns, 20px margins, typography scales down)

## Elevation & Depth

This system avoids heavy shadows, instead using **Tonal Layering** and **Fine Outlines** to convey hierarchy.

- **Layers:** Use subtle shifts in background color (e.g., a Cream container on a Sand background) to group related items.
- **Outlines:** Elements like cards and buttons use thin (1px), low-contrast borders (using the Neutral color) rather than drop shadows.
- **Depth:** When depth is required (e.g., for modals or sticky headers), use an **Ambient Blur** (backdrop-filter) to maintain the "Glassmorphism" lightness without the weight of a traditional shadow.
- **Imagery:** Photography should be the primary driver of depth. Use "soft focus" backgrounds in images to create a natural sense of three-dimensional space.

## Shapes

The shape language is **Soft and Architectural**. 

- **Corners:** While the brand is "premium," it is also "homely" and approachable. We use a subtle 4px (Soft) radius for standard UI elements like buttons and inputs to take the "edge" off without becoming playful or overly bubbly. 
- **Containers:** Service cards and large image containers should maintain this consistent soft corner to feel integrated with the typography.
- **Icons:** Use thin-stroke, linear icons with slightly rounded caps to match the refined weight of the *DM Sans* typeface.

## Components

### Buttons
- **Primary:** Filled with the Accent Slate Blue, white text, soft 4px corners. No shadow.
- **Secondary:** Transparent background with a thin Charcoal border. Used for "Learn More" or secondary actions.
- **Tertiary/Ghost:** Text-only with a subtle underline on hover, used for low-priority navigation.

### Cards
- **Service Cards:** Minimalist white or cream containers. Images should be top-aligned with a subtle "fade-in" transition on scroll. Text inside should be center-aligned or left-aligned with ample padding (32px+).
- **Price Toggles:** Horizontal pill-shaped containers with a soft background shift to indicate the active state.

### Inputs & Forms
- **Fields:** Bottom-border only or very light four-sided borders. Labels should use the *Label-md* style (uppercase, small).
- **Focus State:** A gentle shift in border color to the Tertiary Sage Green.

### Specific Service Elements
- **Process Stepper:** Thin lines with small serif numbers to guide the user through the "How it Works" section, maintaining an editorial timeline aesthetic.
- **Floating Action:** A "Book Now" floating bar on mobile that uses the primary accent color but remains slim and unobtrusive.