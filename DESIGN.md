---
name: Deol Velocity
colors:
  surface: '#fff8f6'
  surface-dim: '#edd5cc'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1ec'
  surface-container: '#ffeae1'
  surface-container-high: '#fce3da'
  surface-container-highest: '#f6ded4'
  on-surface: '#251913'
  on-surface-variant: '#584238'
  inverse-surface: '#3c2d27'
  inverse-on-surface: '#ffede6'
  outline: '#8c7166'
  outline-variant: '#e0c0b2'
  surface-tint: '#a14000'
  primary: '#a14000'
  on-primary: '#ffffff'
  primary-container: '#f36d21'
  on-primary-container: '#531d00'
  inverse-primary: '#ffb694'
  secondary: '#5c5f62'
  on-secondary: '#ffffff'
  secondary-container: '#dee0e3'
  on-secondary-container: '#606366'
  tertiary: '#006493'
  on-tertiary: '#ffffff'
  tertiary-container: '#009ee4'
  on-tertiary-container: '#00314a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcc'
  primary-fixed-dim: '#ffb694'
  on-primary-fixed: '#351000'
  on-primary-fixed-variant: '#7b2f00'
  secondary-fixed: '#e1e2e6'
  secondary-fixed-dim: '#c4c7ca'
  on-secondary-fixed: '#191c1f'
  on-secondary-fixed-variant: '#44474a'
  tertiary-fixed: '#cae6ff'
  tertiary-fixed-dim: '#8ccdff'
  on-tertiary-fixed: '#001e2f'
  on-tertiary-fixed-variant: '#004b70'
  background: '#fff8f6'
  on-background: '#251913'
  surface-variant: '#f6ded4'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  container-max: 1440px
  gutter: 24px
---

## Brand & Style
This design system is built for **Deol Freight Carriers**, focusing on high-performance logistics, reliability, and precision. The brand personality is authoritative yet energetic, reflecting the movement of goods with speed and safety. 

The visual style is **Corporate / Modern** with a focus on high density and utility. It draws inspiration from the logo's angled geometry, utilizing diagonal accents and a clear hierarchy to communicate efficiency. The emotional response should be one of "certainty"—the user must feel that their cargo is in capable, professional hands.

## Colors
The color palette is anchored by the logo's energetic orange, used strategically for action-oriented elements like primary buttons and status indicators. 

- **Primary (#F36D21):** Reserved for high-priority CTA elements and progress indicators.
- **Secondary (#4A4D50):** A deep charcoal used for typography and headers to ensure high legibility and a grounded, professional feel.
- **Accents:** Coral is used for urgent alerts or deletions; Sky Blue is utilized for informational messaging and map interfaces.
- **Surface:** A neutral foundation of white and very light grey (#F8F9FA) ensures a clean, distraction-free environment for data-heavy logistics dashboards.

## Typography
Montserrat is the sole typeface for this design system to maintain a bold, urban, and geometric aesthetic that matches the logo’s wordmark. 

- **Headlines:** Use heavy weights (600-700) for section titles to convey strength.
- **Body:** Standard weights (400) ensure readability in long-form tracking data or documentation.
- **Labels:** Small, uppercase labels with slightly increased letter spacing are used for table headers and technical metadata to evoke a sense of precision and organization.

## Layout & Spacing
This design system utilizes a **Fixed Grid** model for desktop to maintain structural integrity, transitioning to a fluid model for mobile devices.

- **Grid:** A 12-column grid with 24px gutters is standard for desktop views. 
- **Density:** High density is preferred for operational dashboards. Use the 4px base unit to maintain a tight, industrial rhythm.
- **Breakpoints:** 
    - Mobile (<600px): 4 columns, 16px margins.
    - Tablet (600px - 1024px): 8 columns, 24px margins.
    - Desktop (>1024px): 12 columns, fixed 1440px max-width centered.

## Elevation & Depth
Hierarchy is established through **Tonal Layers** and crisp, low-opacity shadows. 

- **Base Level:** Surface White (#FFFFFF) for the primary content area.
- **Mid Level:** Light Grey (#F8F9FA) for background canvases and grouping containers.
- **High Level:** Elevated cards use a subtle 8% opacity charcoal shadow with a 4px blur and 2px offset. This creates enough depth to separate "floating" elements like modal windows or dropdown menus without sacrificing the "sharp" brand aesthetic.

## Shapes
To align with the "precision-driven" style, this design system employs **Soft (0.25rem)** roundedness for standard interactive elements. This subtle rounding softens the industrial feel just enough to feel modern without losing the "sharpness" requested. 

- **Containers & Cards:** 0.25rem (4px) corner radius.
- **Buttons & Inputs:** 0.25rem (4px) corner radius.
- **Special Elements:** Large section blocks may remain sharp (0px) to echo the logo's diagonal shear lines.

## Components

- **Buttons:** Primary buttons use the Orange (#F36D21) background with white text. Hover states should darken the orange slightly. Use "ghost" buttons (Slate outline) for secondary actions.
- **Input Fields:** Use 1px Slate Grey (#4A4D50) borders. On focus, the border transitions to Orange. Labels are always "Label-Bold" style for clarity.
- **Tracking Cards:** Use a left-accent border in Orange to indicate active shipments. Include data-rich rows with "Label-Sm" for metadata.
- **Status Chips:** Use high-contrast backgrounds (e.g., Sky Blue for "In Transit", Orange for "Urgent", Grey for "Delivered") with semi-bold text.
- **Data Tables:** High-density rows with light grey separators. Header cells should have a subtle grey background to distinguish from data rows.
- **Logistics Indicators:** Specialized icons for freight types (Reefer, Flatbed, Dry Van) should follow a consistent stroke weight of 2px, using the secondary Slate color.