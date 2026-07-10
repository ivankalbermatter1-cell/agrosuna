---
name: AgroTerra Formosa
colors:
  surface: '#fbf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#42493e'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#72796e'
  outline-variant: '#c2c9bb'
  surface-tint: '#3b6934'
  primary: '#154212'
  on-primary: '#ffffff'
  primary-container: '#2d5a27'
  on-primary-container: '#9dd090'
  inverse-primary: '#a1d494'
  secondary: '#645d58'
  on-secondary: '#ffffff'
  secondary-container: '#e8ded7'
  on-secondary-container: '#68615c'
  tertiary: '#533200'
  on-tertiary: '#ffffff'
  tertiary-container: '#724700'
  on-tertiary-container: '#ffb451'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bcf0ae'
  primary-fixed-dim: '#a1d494'
  on-primary-fixed: '#002201'
  on-primary-fixed-variant: '#23501e'
  secondary-fixed: '#ebe1da'
  secondary-fixed-dim: '#cec5be'
  on-secondary-fixed: '#1f1b17'
  on-secondary-fixed-variant: '#4c4641'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Source Sans 3
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Source Sans 3
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Source Sans 3
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  max-width: 1280px
---

## Brand & Style

This design system is engineered for an agricultural services powerhouse in Formosa, Argentina. The brand personality is rooted in the soil: **solid, experienced, and unflinchingly reliable**. It moves away from flighty startup aesthetics toward a "Corporate-Industrial" hybrid style—combining the precision of modern SaaS with the rugged dependability of heavy machinery and land management.

The visual direction utilizes **Modern Corporate** principles: structured layouts, generous professional whitespace, and a high-contrast hierarchy that ensures clarity even in high-glare outdoor environments. It balances technical sophistication with the earthy reality of the agricultural sector, favoring realistic photography and clear, purposeful lines over abstract decorations.

## Colors

The palette is derived from the Formosan landscape and agricultural utility.
- **Primary (Deep Field Green):** Used for brand identity, primary navigation, and core structural elements. It evokes growth, stability, and deep-rooted experience.
- **Secondary (Earth Brown):** Used for secondary accents and grounded structural pieces. It provides a warm, organic counterpoint to the greens.
- **Accent (Action Orange):** Reserved strictly for high-priority calls to action (CTAs), status indicators, and critical highlights. Its warmth ensures high visibility against the green and neutral tones.
- **Neutral (Dark Gray):** Applied to primary body text and iconography to ensure maximum legibility and a professional, industrial feel.
- **Background (Off-White):** A clean, slightly warm base that reduces eye strain and provides a premium "paper-like" feel for data-heavy views.

## Typography

The typography strategy pairs the industrial strength of **Montserrat** for headings with the high-utility legibility of **Source Sans 3** for body copy and data.
- **Headlines:** Set in Montserrat with tighter letter-spacing and bold weights to convey authority and modern professionalism.
- **Body:** Source Sans 3 provides a neutral, highly readable experience across mobile and desktop. Its humanist characteristics ensure it feels approachable yet precise.
- **Labels:** Used for metadata, table headers, and small UI descriptors, often employing a slight tracking increase and uppercase styling for a structural, organized appearance.

## Layout & Spacing

The design system uses a **Fixed Grid** philosophy for desktop to maintain a professional, editorial feel, transitioning to a fluid model for mobile devices.
- **Desktop:** A 12-column grid with a 1280px max-width. Large 24px gutters provide breathing room between complex data points.
- **Mobile:** A 4-column fluid grid with 16px side margins.
- **Vertical Rhythm:** Built on an 8px base unit. Component padding and sectional margins should always be multiples of 8 (e.g., 16, 24, 32, 48, 64) to ensure mathematical harmony and visual stability.
- **Fixed Header:** A persistent 72px tall header provides constant access to primary navigation and contact actions, reinforcing the "always-available" brand promise.

## Elevation & Depth

To maintain a "solid" and "grounded" feel, depth is achieved through **Tonal Layers** and subtle, tight shadows.
- **Base Layer:** The off-white background (#F9FAFB).
- **Surface Layer:** White cards (#FFFFFF) used for content containers.
- **Shadows:** Use low-offset, high-diffusion shadows (e.g., `0px 4px 12px rgba(0,0,0,0.05)`) to lift cards slightly off the page without creating a "floating" or "airy" effect. 
- **Outlines:** Use 1px solid borders in a very light gray (#E5E7EB) for secondary containers to maintain structure without relying on heavy shadows, keeping the UI clean and industrial.

## Shapes

The shape language is **Soft (Level 1)**. This choice provides a modern touch that takes the edge off a purely industrial look without becoming "bubbly" or overly consumer-focused.
- **Buttons & Inputs:** 0.25rem (4px) corner radius. This reinforces a sense of precision and mechanical accuracy.
- **Cards & Sections:** 0.5rem (8px) corner radius. This provides a clear containerization for agricultural services and data modules while maintaining a professional silhouette.

## Components

- **Buttons:**
  - **Primary:** Solid #2D5A27 with white text. High contrast, bold weight.
  - **CTA:** Solid #F59E0B with dark neutral text. Used sparingly for "Get a Quote" or "Emergency Service."
  - **Shape:** Rectangular with a 4px radius; height of 48px for primary actions to ensure "gloved-hand" hit areas on mobile.
- **Cards:** White background, 8px radius, subtle 1px border. Use for "Service Categories" (e.g., Soil Analysis, Crop Monitoring). Include a top-aligned photographic area to showcase realistic agricultural imagery.
- **Input Fields:** 1px #D1D5DB border, white fill. Labels are always positioned above the field in #4B4540 (Source Sans 3, Label-md). Focus states should use a 2px #2D5A27 border.
- **Lists:** Data lists use alternating row colors (Zebra striping) in #F3F4F6 to ensure readability for technical logistics and inventory tracking.
- **Iconography:** Use thick-stroke (2px) linear icons in #333333. Avoid overly decorative or colorful icons; favor functional, representational glyphs (tractors, wheat, droplets, maps).
- **Persistent Header:** Solid white background with a #2D5A27 top-border accent. High-contrast navigation links with a clear "active" state indicated by a bottom bar in the primary green.