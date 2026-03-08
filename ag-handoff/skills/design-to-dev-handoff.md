---
id: design-to-dev-handoff
name: Design-to-Development Handoff
domain: ag-handoff
version: 1.0.0
---
# Design-to-Development Handoff
**Purpose:** Hand off designs to development with enough specification that the implementation matches the design — because every gap in the handoff becomes a discrepancy in the browser.

The design-to-development handoff is the most frequent source of quality issues in agency work. Developers can't read designers' minds. If the hover state isn't specified, it won't be implemented. If the mobile layout isn't designed, the developer will improvise. If the spacing isn't defined, it'll be eyeballed.

## The Handoff Contents
Design files: organized Figma file with final screens, component library, and responsive variants. Specifications: spacing values, color tokens, typography scale, border radii, shadow values — everything needed to implement without measuring. Interaction specs: hover states, click states, transitions, animations (duration, easing, trigger). Content: final copy in a separate document (not just in the Figma file where it's hard to extract). Assets: exportable images, icons (SVG), fonts (with license verification).

## The Handoff Process
Handoff meeting: designer walks the developer through the design, explaining rationale for key decisions and calling out interactions that aren't visible in static screens. Q&A session: developer asks about edge cases, empty states, error states, loading states, and the scenarios the designer may not have explicitly designed. Annotation: designer annotates the Figma file with developer notes for anything that isn't self-evident.

## The Quality Checkpoint
After the first development sprint, compare the implementation to the design. The designer should review the staging environment (not screenshots — the actual browser) and log discrepancies. This catch-up loop should happen weekly during development, not just at the end.

## When to use
Every project with a design and development phase. When development frequently doesn't match the design. When handoff meetings are being skipped.
