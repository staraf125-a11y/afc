---
name: Vibrant Fast-Casual
colors:
  surface: '#fbfaee'
  surface-dim: '#dbdbcf'
  surface-bright: '#fbfaee'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f4e8'
  surface-container: '#efeee3'
  surface-container-high: '#e9e9dd'
  surface-container-highest: '#e4e3d7'
  on-surface: '#1b1c15'
  on-surface-variant: '#5b403d'
  inverse-surface: '#303129'
  inverse-on-surface: '#f2f1e5'
  outline: '#8f6f6c'
  outline-variant: '#e4beba'
  surface-tint: '#ba1a20'
  primary: '#af101a'
  on-primary: '#ffffff'
  primary-container: '#d32f2f'
  on-primary-container: '#fff2f0'
  inverse-primary: '#ffb3ac'
  secondary: '#785900'
  on-secondary: '#ffffff'
  secondary-container: '#fdc003'
  on-secondary-container: '#6c5000'
  tertiary: '#575757'
  on-tertiary: '#ffffff'
  tertiary-container: '#706f6f'
  on-tertiary-container: '#f6f3f3'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb3ac'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#930010'
  secondary-fixed: '#ffdf9e'
  secondary-fixed-dim: '#fabd00'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#5b4300'
  tertiary-fixed: '#e4e2e1'
  tertiary-fixed-dim: '#c8c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#474747'
  background: '#fbfaee'
  on-background: '#1b1c15'
  surface-variant: '#e4e3d7'
typography:
  display-lg:
    fontFamily: Bebas Neue
    fontSize: 72px
    fontWeight: '400'
    lineHeight: 72px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Bebas Neue
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: Bebas Neue
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: 0.02em
  headline-md:
    fontFamily: Bebas Neue
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 32px
  title-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
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
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
---

## Brand & Style
The design system focuses on a high-energy, appetite-stimulating aesthetic tailored for a local fast-food leader. The brand personality is unapologetically bold, friendly, and community-centric, aiming to evoke the excitement of a fresh, hot meal. 

The visual style blends **High-Contrast / Bold** elements with **Corporate / Modern** usability. It utilizes massive, punchy typography to communicate value and speed, while maintaining a clean, systematic structure that ensures ease of ordering. High-quality, saturated food photography is the hero of the interface, supported by a "fresh and fast" UI language that feels professional yet accessible.

## Colors
The palette is rooted in the psychology of fast food. **Deep Red** acts as the primary driver for urgency and appetite, used for key actions and branding. **Golden Yellow** provides high-energy highlights and reinforces the "value" aspect of the brand.

**Charcoal Grey** is used for primary text and grounding elements to ensure high legibility against the **Light Cream** background. The background is slightly warmed from pure white to #FDFCF0 to feel more organic and "freshly baked." Success, warning, and error states should utilize standard semantic colors but lean toward higher saturation to match the brand's vibrancy.

## Typography
The typography system uses a "Power and Precision" pairing. **Bebas Neue** is the voice of the brand—tall, condensed, and impactful. It is reserved for headlines, promotional banners, and product names. All Bebas Neue headlines should use a slight 2% letter spacing to enhance readability in digital formats.

**Inter** handles the functional heavy lifting. It provides a clean, neutral contrast to the expressive headlines, ensuring that ingredient lists, prices, and checkout details are effortless to read. Use bold weights of Inter for prices and sub-headers to maintain visual hierarchy without competing with the main display type.

## Layout & Spacing
This design system utilizes a **fluid 12-column grid** for desktop and a **4-column grid** for mobile. The spacing rhythm is based on an 8px square baseline to ensure mathematical harmony across all components.

- **Mobile:** Elements should span the full width of the 4-column grid for maximum impact of food photography. Use 16px side margins.
- **Desktop:** Content is centered with a max-width of 1280px.
- **Vertical Rhythm:** Use larger gaps (48px+) between distinct menu categories (e.g., between "Burgers" and "Deals") to create clear visual "breathing room" amidst the high-contrast colors.

## Elevation & Depth
To keep the UI feeling modern and tactile, we use **Ambient Shadows**. Surfaces should feel like they are floating slightly above the cream background to encourage interaction.

- **Level 1 (Cards/Inputs):** A soft, 4px blur with 5% opacity Charcoal Grey shadow.
- **Level 2 (Active States/CTAs):** A 12px blur with 10% opacity, slightly tinted with the Primary Red for buttons to make them feel "pressed" or elevated.
- **Modals:** High-diffusion 24px blur shadows to isolate the ordering flow from the background. 

Avoid heavy borders; use subtle tonal changes in the background (#F5F5F0) to define sections where elevation is not required.

## Shapes
The shape language is **Rounded**, reflecting a friendly and approachable brand. All standard containers, such as product cards and input fields, use a 0.5rem (8px) corner radius. 

Large buttons and "deal" badges may use the `rounded-xl` (1.5rem/24px) setting to create a softer, more "bubbly" feel that contrasts well with the sharp, condensed letterforms of the headline typography.

## Components
### Buttons
Primary CTAs are Deep Red with white text, utilizing a bold weight and slightly larger padding (16px 32px) for a "touch-friendly" mobile experience. Secondary buttons use a Golden Yellow background with Charcoal text for "Add to Cart" actions.

### Cards
Product cards feature a full-bleed image at the top, a 1:1 aspect ratio for the food, and a white content area below. The price should always be highlighted in a Golden Yellow badge or bold Charcoal text in the bottom right.

### Chips & Tags
Use chips for dietary labels (e.g., "Spicy," "Vegetarian"). These should have 0px borders and solid pastel fills of the semantic colors (e.g., a light red tint for Spicy).

### Input Fields
Inputs use a light grey stroke that turns Deep Red on focus. Labels remain visible above the field to ensure accessibility during the fast-paced checkout process.

### Navigation
The mobile bottom-bar navigation should feature high-contrast icons (Burger, Pizza, Deals, Profile) with the active state highlighted in Primary Red.