---
name: Condo Management System
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#515f74'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3fd'
  on-secondary-container: '#57657b'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#191c1e'
  on-tertiary-container: '#818486'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#d5e3fd'
  secondary-fixed-dim: '#b9c7e0'
  on-secondary-fixed: '#0d1c2f'
  on-secondary-fixed-variant: '#3a485c'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-xl:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.25'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 0.5rem
  sm: 1rem
  md: 1.5rem
  lg: 2.5rem
  xl: 4rem
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 32px
---

## Brand & Style

The design system is built to convey reliability, administrative efficiency, and modern luxury. It targets property managers and residents who require a frictionless, high-trust environment to manage significant financial and logistical assets.

The visual style is **Minimalist-Corporate**. It prioritizes extreme clarity and breathing room to reduce the cognitive load of data-heavy management tasks. By utilizing a restrained color palette and generous whitespace, the system feels less like a utility and more like a premium service. The aesthetic is defined by "Soft Precision"—combining the mathematical rigor of a professional SaaS with welcoming, high-radius organic shapes.

## Colors

The palette is anchored in a professional "Deep Navy" used for primary actions and sidebar navigation to establish authority. "Crisp White" serves as the primary canvas, ensuring the interface feels airy and unobstructed.

*   **Primary:** Deep Navy (#0F172A) for text, primary buttons, and active states.
*   **Secondary:** Slate Blue-Grey (#334155) for secondary navigation and subheaders.
*   **Neutral/Grey Scale:** A range of soft greys from Slate-50 (#F8FAFC) for backgrounds to Slate-500 (#64748B) for helper text.
*   **Accents:** Highly functional use of Emerald for status approvals and Amber for pending maintenance requests.

## Typography

This design system utilizes a dual-font strategy to balance character with utility. 

**Manrope** is used for headlines and display text. Its slightly geometric yet refined letterforms provide a modern, high-end feel suitable for property titles and dashboard overviews. 

**Inter** is the workhorse for all body copy, data tables, and input labels. It is selected for its exceptional legibility at small sizes and its neutral, systematic appearance, which is critical for complex administrative workflows. Use `label-caps` for table headers and section categorizers to create a clear visual hierarchy.

## Layout & Spacing

The layout follows a **Fluid Grid** model with a max-width container of 1440px for desktop viewing. A 12-column system is utilized for the main content area, while a fixed 280px sidebar handles primary navigation on desktop.

Spacing is governed by an 8pt rhythm, ensuring consistent alignment across all components. For condominium management dashboards, prioritize wide margins and generous vertical padding within list items to prevent the data from feeling claustrophobic. On mobile devices, the system transitions to a single-column stack with the sidebar collapsing into a bottom-navigation bar or a "hamburger" menu for better reachability.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Ambient Shadows**. Instead of heavy borders, surfaces are differentiated by subtle shifts in background color (e.g., a white card on a soft grey background).

**Shadow Profile:**
*   **Level 1 (Cards/Inputs):** A very soft, diffused shadow with a 12px blur, 4px Y-offset, and 4% opacity of the Deep Navy primary color.
*   **Level 2 (Modals/Dropdowns):** A more pronounced shadow with a 24px blur and 8% opacity to pull the element significantly above the page surface.

Avoid using inner shadows or harsh black outlines. Focus on using light and depth to guide the user’s eye toward actionable elements.

## Shapes

The shape language is "Hyper-Rounded." This design system uses a standard radius of **0.5rem (8px)** for small elements like checkboxes and inputs, but scales up to **1rem (16px)** for primary containers and cards. 

Buttons should utilize a fully rounded (pill-style) radius for a friendlier, modern touch. This high-radius approach softens the "coldness" typically associated with management software, making the platform feel approachable for residents.

## Components

### Buttons
Primary buttons use the Deep Navy (#0F172A) background with White text and a 2px horizontal padding multiplier for a wide, confident look. Secondary buttons use a transparent background with a thin 1px Slate border.

### Clean Tables
Tables are the heart of this design system. They must be "borderless." Use a light grey background (#F8FAFC) for the header row and thin horizontal dividers (1px, #F1F5F9) between rows. Use alternating row stripes only for tables exceeding 20 rows.

### Cards
Cards are the primary container for dashboard widgets. They feature a white background, the Level 1 shadow profile, and a 16px corner radius. Padding inside cards should never be less than 24px.

### Inputs
Text fields use a soft grey background and a 1px border that darkens only on focus. The corner radius must match the standard component radius (8px).

### Thin Line Iconography
Icons must be 1.5px or 2px stroke weight. Avoid filled icons unless they represent an active/toggled state. This keeps the interface light and consistent with the minimalist aesthetic.

### Status Chips
Small, high-radius (pill) chips used for "Paid," "Pending," or "Overdue." These should use low-saturation background tints of the accent colors with high-saturation text for readability.