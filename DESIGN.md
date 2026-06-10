---
name: Grayscale Wireframe System
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#4c4546'
  inverse-surface: '#2f3131'
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
  secondary-container: '#e3e2e2'
  on-secondary-container: '#646464'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1a1c1c'
  on-tertiary-container: '#838484'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#e3e2e2'
  secondary-fixed-dim: '#c7c6c6'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#e3e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Inter
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The objective of this design system is to strip away visual noise and focus entirely on information architecture, hierarchy, and user flow. By utilizing a low-fidelity aesthetic, it prevents stakeholders from becoming distracted by aesthetics, focusing instead on the functional core of the product.

The style is **Minimalist** with a hint of **Architectural Brutalism**. It prioritizes structural clarity through varied stroke weights and a strict grayscale palette. There are no shadows, gradients, or decorative flourishes. Every element serves as a placeholder for future high-fidelity intent.

## Colors
The palette is strictly monochromatic. Black is reserved for primary actions, heavy borders, and high-level typography. Grays are used to differentiate secondary elements and background containers, while white serves as the base canvas.

- **Canvas:** #FFFFFF
- **Surface (Muted):** #F5F5F5
- **Lines (Standard):** #BDBDBD
- **Lines (Emphasis):** #000000
- **Text (Primary):** #000000
- **Text (Secondary):** #757575

## Typography
**Inter** is utilized for its exceptional legibility and neutral character. In this design system, hierarchy is communicated through size and weight rather than color. 

- **Headlines:** Bold and impactful to anchor sections.
- **Body:** Standardized at 16px for optimal readability.
- **Labels:** Used for buttons, inputs, and small metadata. Uppercase is encouraged for `label-sm` to create a technical, diagrammatic feel.

## Layout & Spacing
This design system employs an 8px square grid for all internal spacing. 

- **Desktop:** A 12-column fluid grid with 24px gutters.
- **Mobile:** A 4-column fluid grid with 16px gutters and 16px side margins.
- **Spacing Rhythm:** Use `md` (24px) for most component grouping and `lg` (48px) for section separation. 

Layouts should be structured to show the flow of information. Containers should use a 1px border (#BDBDBD) to define boundaries without adding visual weight.

## Elevation & Depth
Depth is created through **stacking and stroke weight**, not shadows. 

1.  **Level 0 (Background):** White (#FFFFFF).
2.  **Level 1 (Containers/Sections):** 1px border or light gray background (#F5F5F5).
3.  **Level 2 (Active Elements/Modals):** Defined by a 2px black border (#000000) to pull the element forward.

Avoid any use of backdrop blurs or transparency. If an element is "above" another (like a modal), it should have a thick 2px border and a solid white fill to obscure the elements behind it.

## Shapes
The shape language is strictly **Sharp (0px roundedness)**. This reinforces the blueprint/wireframe concept, making the interface feel like a technical drawing. All buttons, inputs, and containers must have square corners.

## Components

### Buttons
- **Primary:** 2px solid black border, bold text, no fill.
- **Secondary:** 1px solid gray (#BDBDBD) border, regular text.
- **State:** On hover or active, fill the button with a light gray (#F5F5F5) to indicate interaction.

### Input Fields
- **Container:** 1px solid gray (#BDBDBD) border with a label positioned above the field in `label-sm`.
- **Placeholder Text:** Rendered in light gray (#BDBDBD).

### Placeholders (Images/Icons)
- **Visual:** A box with a 1px border containing an "X" pattern (two diagonal lines connecting opposite corners). 
- **Ratio:** Maintain standard aspect ratios (16:9, 4:3, 1:1) to accurately represent content areas.

### Mobile Navigation
- **Top Bar:** 1px bottom border only. Centered title or left-aligned logo placeholder.
- **Bottom Tab Bar:** 1px top border. Use simple 24x24px placeholder boxes for icons with labels underneath.

### Cards
- **Style:** Thin 1px border (#BDBDBD). No padding between the image placeholder and the top of the card. Text content should have `md` (24px) padding.