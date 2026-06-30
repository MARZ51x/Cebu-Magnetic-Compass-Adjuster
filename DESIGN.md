---
name: Nautical Precision
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#44474e'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#495f84'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#001b3d'
  on-primary-container: '#6f84ac'
  inverse-primary: '#b1c7f2'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#000001'
  on-tertiary: '#ffffff'
  tertiary-container: '#111c2d'
  on-tertiary-container: '#798499'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b1c7f2'
  on-primary-fixed: '#001b3d'
  on-primary-fixed-variant: '#31476b'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#d8e3fa'
  tertiary-fixed-dim: '#bcc7dd'
  on-tertiary-fixed: '#111c2c'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-xl:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Source Serif 4
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Source Serif 4
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Hanken Grotesk
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
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  unit: 8px
---

## Brand & Style

The brand personality is rooted in unwavering accuracy, maritime heritage, and technical mastery. As a specialized service for magnetic compass adjustment, the UI must project an image of absolute reliability—evoking the same confidence as a perfectly calibrated instrument. The target audience includes ship owners, captains, and maritime authorities who value safety, certification, and professional rigor.

The design style is **Corporate / Modern** with a **Tactile** edge. It utilizes clean, structured layouts to reflect precision, while incorporating subtle physical metaphors—such as hair-line strokes and metallic finishes—that reference compass needles and brass instruments. The interface prioritizes clarity and whitespace to simulate the open horizon, ensuring that information is never cluttered and always "true north."

## Colors

The palette is a sophisticated blend of traditional maritime tones and high-end technical finishes:

- **Deep Navy (#001B3D):** The primary anchor. It represents the depths of the ocean and the authority of a certified professional. Used for navigation, headers, and primary actions.
- **Polished Brass (#C5A059):** The secondary accent. Inspired by the physical components of a binnacle, this color is used sparingly for highlights, icons, and CTA borders to evoke a premium, "instrument-grade" quality.
- **Slate Grey (#4A5568):** A utilitarian tertiary tone used for secondary text and structural borders, providing a grounded, industrial feel.
- **Crisp White & Sky (#F8FAFC):** The background canvas. It ensures maximum legibility and creates the generous whitespace necessary for a "precise" aesthetic.

## Typography

The typographic strategy balances modern engineering with historical certification.

- **Headings & Labels:** **Hanken Grotesk** provides a sharp, contemporary feel. Its geometric precision mimics technical drawings. Labels are often set in uppercase with increased letter spacing to resemble stamped serial numbers or technical markings.
- **Body Text:** **Source Serif 4** is used for all long-form content and certificates. It evokes the feeling of official maritime documents and traditional logs, ensuring high legibility while adding a layer of established trust.

For mobile devices, `headline-xl` should scale down to `32px` to maintain visual balance on smaller screens.

## Layout & Spacing

This design system employs a **Fixed Grid** model on desktop to enforce a sense of order and containment. 

- **Grid:** A 12-column grid with 24px gutters. Content is centered within a 1280px max-width container.
- **Rhythm:** An 8px linear scale governs all padding and margins. Vertical rhythm is generous; use double spacing (16px or 32px) between sections to reflect "open seas" and clarity.
- **Responsive Behavior:** On tablet, the grid shifts to 8 columns. On mobile, it moves to a single column with 20px side margins. Large imagery should maintain a 16:9 or 3:2 aspect ratio to feel like professional photography.

## Elevation & Depth

To maintain a "precision instrument" feel, depth is achieved through **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows.

- **Surfaces:** Use subtle shifts in background color (e.g., White to Light Grey) to define different functional areas.
- **Outlines:** Cards and input fields use a 1px solid border in Slate Grey at low opacity (20%).
- **Shadows:** Only used for the highest level of elevation (e.g., active modals). These should be "Ambient Shadows"—extremely diffused, with a slight Deep Navy tint to keep the shadow feeling like a natural part of the environment.
- **Accents:** A "Brass" top-border (2px) can be used on primary cards to denote "Certified" or "Primary" information.

## Shapes

The shape language is **Soft (0.25rem)**. 

While the brand is focused on precision, perfectly sharp corners can feel overly aggressive or "cheap." A very slight radius (4px) provides a professional, machined finish—similar to the rounded edges of high-quality nautical hardware. 

- **Buttons:** Use the standard 4px radius. 
- **Containers:** Large cards may use `rounded-lg` (8px) for a more modern structural feel.
- **Icons:** Should feature consistent stroke weights (1.5px or 2px) with slightly rounded terminals.

## Components

- **Buttons:** Primary buttons are Deep Navy with white text. Secondary buttons use a transparent background with a Polished Brass border and text. All buttons should have a hover state that subtly increases the border-weight or brightness.
- **Input Fields:** Use a Slate Grey outline. When focused, the border changes to Polished Brass. Labels are always placed above the field in `label-md` Hanken Grotesk.
- **Cards:** White backgrounds with a very thin (1px) Slate Grey border. For "Adjustment Reports" or "Certificates," add a subtle watermark-style background element of a compass rose.
- **Status Chips:** Used for "Certified," "Pending," or "Expired." These use high-contrast text on a very pale background of the status color (e.g., Green for Certified, Brass for Pending).
- **Data Tables:** Used for compass deviation cards. Rows should have ample padding and alternate subtle background tints for readability. Vertical lines should be avoided; use horizontal rules only to maintain a clean "ledger" look.