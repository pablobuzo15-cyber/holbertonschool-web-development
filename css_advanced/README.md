# SmileSchool — CSS Advanced Project

This phase focuses entirely on applying **HTML + CSS** (no frameworks) to bring the static markup from _0x02 – HTML, advanced_ to life.

## Goals

- Reproduce the Figma as a webpage.
- Demonstrate modern CSS layout, typography, and asset management without external libraries.

## Page Sections

- Hero with call-to-action
- “Learn from the pros”
- Testimonial block
- “Most popular tutorials” cards
- Free-membership benefits
- FAQ
- Footer with social links

## Project Structure

## Assets

All project assets are stored in the `images/` folder, including backgrounds, instructor photos, tutorial previews, star ratings, and social icons.

**Fonts**

- `Source Sans Pro` — primary text
  Imported via Google Fonts in the `<head>` tag.

## Implementation Notes

- **Flexbox** is used for section and card alignment, replacing Figma’s exported absolute positioning.
- Clean, **semantic class names** (`.hero`, `.pros`, `.tutorials`, `.membership`, `.faq`) keep the CSS readable and maintainable.
- Spacing and hierarchy were reproduced through logical margins, paddings, and gaps to match the Figma file.
- Decimal pixel values from Figma were preserved.
- Built **only with HTML and CSS**, no frameworks or libraries.
