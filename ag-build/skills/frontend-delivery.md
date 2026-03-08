---
id: frontend-delivery
name: Frontend Development Delivery
domain: ag-build
version: 1.0.0
---
# Frontend Development Delivery
**Purpose:** Deliver frontend code that matches the design, performs well, and is maintainable — the specific frontend engineering craft that agency work demands.

Frontend is where design meets reality. The gap between a Figma design and a browser implementation is where most agency quality issues live. Pixel-perfect is the wrong goal — responsive, accessible, performant, and faithful to the design intent is the right goal.

## The Framework Decision
Next.js for most agency websites (SSG for marketing sites, SSR for dynamic content). React for web applications. Astro for content-heavy sites where performance is the priority. The framework should be chosen based on project needs, not team preference. Document the rationale so the client understands why.

## The CSS Architecture
Tailwind CSS for rapid development with consistent spacing and color. CSS Modules or styled-components for component isolation. Never write global CSS beyond base resets and typography. The CSS should be scannable — another developer should understand the styling approach in 5 minutes.

## The Component Architecture
Build components that match the design system: atomic (buttons, inputs, badges), molecular (cards, form groups, navigation items), and page-level (hero sections, feature grids, testimonial carousels). Each component should be self-contained, documented, and reusable. Use Storybook for component documentation if the project warrants it.

## When to use
Every frontend project. When establishing frontend quality standards. When the gap between design and implementation is consistently too wide.
