---
name: Academic Precision
colors:
  surface: '#fbf9fb'
  surface-dim: '#dbd9dc'
  surface-bright: '#fbf9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f6'
  surface-container: '#efedf0'
  surface-container-high: '#e9e7ea'
  surface-container-highest: '#e4e2e5'
  on-surface: '#1b1b1e'
  on-surface-variant: '#44474d'
  inverse-surface: '#303033'
  inverse-on-surface: '#f2f0f3'
  outline: '#75777e'
  outline-variant: '#c5c6ce'
  surface-tint: '#4e5f7e'
  primary: '#031632'
  on-primary: '#ffffff'
  primary-container: '#1a2b48'
  on-primary-container: '#8293b5'
  inverse-primary: '#b6c7eb'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#211400'
  on-tertiary: '#ffffff'
  tertiary-container: '#3c2700'
  on-tertiary-container: '#ad8d5b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#b6c7eb'
  on-primary-fixed: '#081b38'
  on-primary-fixed-variant: '#374765'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#ffdead'
  tertiary-fixed-dim: '#e5c18a'
  on-tertiary-fixed: '#281900'
  on-tertiary-fixed-variant: '#5b4217'
  background: '#fbf9fb'
  on-background: '#1b1b1e'
  surface-variant: '#e4e2e5'
typography:
  display:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  3xl: 64px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  max-width: 1280px
---

## Brand & Style

This design system is built for the focused, high-performance environment of modern academia. The brand personality is **reliable, organized, and empowering**, acting as a silent partner in a student's academic journey. 

The aesthetic follows a **Corporate / Modern** direction with a focus on high-information density handled through **Minimalism**. By prioritizing whitespace and a structured grid, the system reduces cognitive load, allowing students to navigate complex schedules and task lists without friction. The visual tone is scholarly yet contemporary, avoiding the stuffiness of traditional institutions in favor of a clean, digital-first interface that emphasizes clarity and accessibility.

## Colors

The color palette is engineered for high contrast and professional clarity, meeting WCAG AA standards. 

- **Primary (Deep Navy):** Used for navigation headers, primary branding, and high-level headings to establish authority and grounding.
- **Accent (Vibrant Blue):** Reserved for primary actions, links, and active states to guide the eye toward progress.
- **Secondary (Soft Slate):** Applied to supporting text, icons, and metadata to create a clear visual hierarchy against the primary content.
- **Semantic Colors:** Green and Red are used sparingly for success states and urgent alerts, ensuring critical status cues are immediately recognizable.
- **Neutral/Surface:** A "Crisp White" surface sits atop a slightly off-white "Slate-50" background to create subtle container definition without heavy borders.

## Typography

The design system utilizes **Inter** for its exceptional legibility and systematic weight distribution. The type scale is intentionally generous to ensure readability during long study sessions.

- **Headlines:** Use Bold (700) or SemiBold (600) weights in Deep Navy to provide strong structural anchors.
- **Body Text:** Primarily uses the Regular (400) weight in Slate-800 for optimal contrast. Body-md is the default for most paragraph content.
- **Labels:** Use SemiBold (600) and Medium (500) weights to differentiate UI controls and metadata from general content.
- **Mobile scaling:** Display and Large Headlines scale down significantly on mobile to maintain layout integrity while preserving the high-contrast hierarchy.

## Layout & Spacing

The layout is built on a **12-column fluid grid** for desktop and a **4-column fluid grid** for mobile. 

- **Spacing Rhythm:** A strict 8px-based (4px base unit) spatial system ensures consistency across all components.
- **Margins:** Use 48px margins on desktop to allow the content to "breathe" and 16px on mobile to maximize screen real estate.
- **Gutter:** A consistent 24px gutter provides clear separation between card-based modules.
- **Safe Areas:** Interactive elements should maintain a minimum touch target area of 44x44px, regardless of the visual size of the icon or label.

## Elevation & Depth

Visual hierarchy is established through a **Tonal Layering** approach combined with **Ambient Shadows**. This creates a clear distinction between the workspace (background) and the active tasks (cards).

- **Level 0 (Background):** Slate-50 (#F8FAFC) is used for the base application canvas.
- **Level 1 (Cards/Surfaces):** Pure white surfaces with a soft, diffused shadow (Offset: 0, 2px; Blur: 4px; Opacity: 0.05). This is the default state for task cards and content blocks.
- **Level 2 (Hover/Active):** Slightly more pronounced shadow (Offset: 0, 8px; Blur: 16px; Opacity: 0.08) to indicate interactivity.
- **Overlays (Modals):** High-elevation shadows with a semi-transparent backdrop blur (8px) to focus the user’s attention on the specific action required.
- **Focus Indicators:** All interactive elements must show a 2px solid Accent Blue outline with a 2px offset when navigated via keyboard.

## Shapes

The shape language is **Structured and Friendly**. 

- **Standard Radius:** A base of 8px (`rounded-md` equivalent) is used for cards, input fields, and primary buttons. This provides a modern, approachable feel while maintaining professional discipline.
- **Large Radius:** 16px is used for larger containers or marketing-style sections.
- **Pill Shape:** Used exclusively for Status Chips (e.g., "In Progress", "Completed") and Tab indicators to distinguish them from actionable buttons.

## Components

- **Buttons:** Primary buttons use the Accent Blue background with white text. Secondary buttons use a slate border or ghost style. All buttons feature an 8px corner radius and a clear transition state on hover.
- **Cards:** The central unit of the system. Cards must have a 1px border (#E2E8F0) and a Level 1 shadow. Content within cards follows the 16px (md) internal padding rule.
- **Input Fields:** Use a 1px Slate-300 border that transforms to 2px Accent Blue on focus. Labels sit clearly above the field in Label-md typography.
- **Chips/Badges:** Pill-shaped with low-opacity background tints of the semantic colors (e.g., 10% Success Green background with 100% Success Green text).
- **Lists:** Clean, unbordered rows with 1px horizontal dividers. Use generous vertical padding (12px) for list items to ensure clarity.
- **Progress Bars:** Use a 4px height with a Slate-200 track and an Accent Blue fill, featuring rounded ends for a polished finish.