---
name: Kinetic Logic
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
  on-surface-variant: '#434655'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#943700'
  on-tertiary: '#ffffff'
  tertiary-container: '#bc4800'
  on-tertiary-container: '#ffede6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb596'
  on-tertiary-fixed: '#360f00'
  on-tertiary-fixed-variant: '#7d2d00'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Hanken Grotesk
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  headline-md-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.2'
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
  lg: 48px
  xl: 80px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

The design system is rooted in **Modern Minimalism**, prioritizing clarity, intent, and high-functioning utility. It is designed for professional environments where efficiency and trust are paramount. The aesthetic avoids unnecessary decoration, instead using precise alignment and generous white space to guide the user’s focus toward primary actions.

The emotional response should be one of **calm competence**. By utilizing a structured layout and a disciplined color application, the interface feels reliable and high-end. The target audience includes enterprise users and professionals who require a frictionless, accessible, and sophisticated digital workspace.

## Colors

The palette is anchored by a deep **Indigo Primary**, symbolizing intelligence and stability. This color is reserved for the most critical interactive elements, such as primary buttons and active states. 

- **Primary (#2563EB):** Used for call-to-actions, focus states, and progress indicators.
- **Secondary (#0F172A):** A deep slate used for high-level headings and primary text to ensure maximum legibility.
- **Neutral (#64748B):** A balanced gray for secondary text, borders, and icons.
- **Surface (#FFFFFF):** Pure white is used for the main interaction containers (cards/inputs) to create a clear separation from the slightly tinted background.
- **Background (#F8FAFC):** A cool-toned neutral that reduces eye strain and provides a soft canvas for the UI components.

## Typography

This design system utilizes a dual-font strategy to balance character with utility. 

**Hanken Grotesk** is used for headlines. Its sharp, contemporary geometry provides a modern edge and establishes a clear information hierarchy. **Inter** is used for body copy and labels; it is highly optimized for screen legibility and provides a neutral, systematic feel that aids in long-form reading and data entry.

Tighten letter spacing on larger headings to maintain a cohesive visual block. Increase line height on body text to ensure maximum readability and a "breathing" layout.

## Layout & Spacing

The design system employs a **Fixed Grid** model for desktop to maintain a controlled, professional composition. Content is centered within a 1280px container using a 12-column grid.

- **Desktop:** 12 columns, 24px gutters, 80px side margins.
- **Tablet:** 8 columns, 24px gutters, 40px side margins.
- **Mobile:** 4 columns, 16px gutters, 20px side margins.

A strict 8px spatial scale is used for all internal component spacing and layout margins. Use "lg" (48px) and "xl" (80px) vertical spacing to separate major sections, creating a sense of openness and luxury. Components like login cards should be horizontally centered with a maximum width of 440px to ensure focus and ease of use.

## Elevation & Depth

This design system uses **Tonal Layers** and **Ambient Shadows** to define hierarchy. Depth is used sparingly to signify interactivity and importance.

- **Level 0 (Background):** The base layer using the `#F8FAFC` background color.
- **Level 1 (Surface):** White containers (cards/modals) that appear to sit flush with the background, defined by a 1px border in a light neutral (`#E2E8F0`).
- **Level 2 (Interaction):** When an element like a login card needs prominence, apply an extra-diffused ambient shadow: `0px 10px 25px -5px rgba(15, 23, 42, 0.05)`.
- **Level 3 (Overlay):** Used for dropdowns and tooltips, utilizing a slightly stronger shadow and a 1px border.

Avoid heavy blacks in shadows; always use a low-opacity tint of the Secondary (Slate) color to maintain a clean, airy feel.

## Shapes

The shape language is **Rounded**, reflecting a modern and approachable personality without becoming overly playful. 

- **Small elements (Inputs, Buttons):** Use `rounded` (0.5rem) to provide a soft but professional feel.
- **Large elements (Cards, Containers):** Use `rounded-lg` (1rem) or `rounded-xl` (1.5rem) to frame content elegantly.
- **Selection states:** Checkboxes and radio buttons should follow the 4px (`rounded-sm`) rule to maintain sharpness at small scales.

Consistency in corner radii is critical; avoid mixing sharp corners with rounded ones to maintain a unified system.

## Components

### Buttons
- **Primary:** Filled with Primary Indigo, white text, 0.5rem radius. Use a subtle scale-down effect (0.98) on click.
- **Secondary:** Transparent background with a 1px Slate-200 border. Transition to a light gray background on hover.

### Input Fields
- **Default:** White background, 1px Slate-200 border, 0.5rem radius.
- **Focus:** 1px Primary Indigo border with a 3px soft indigo outer glow (box-shadow).
- **Labels:** Use `label-md` in Secondary Slate, positioned 8px above the input.

### Login Card
- The central login component should have 48px of internal padding (`spacing.lg`).
- Use a Level 2 shadow to separate it from the background.
- Include a 1px border (`#E2E8F0`) for crispness.

### Feedback & Validation
- **Errors:** Use a soft red (#EF4444) for text and input borders.
- **Success:** Use a soft emerald (#10B981) for success states.
- Icons should be used alongside text for all validation messages to ensure accessibility.