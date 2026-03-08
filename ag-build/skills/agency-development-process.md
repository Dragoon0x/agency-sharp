---
id: agency-development-process
name: Agency Development Process
domain: ag-build
version: 1.0.0
---
# Agency Development Process
**Purpose:** Run a development process that ships quality work on time within agency constraints — where the timeline is fixed, the client expects progress visibility, and the code needs to be maintainable by someone else after handoff.

Agency development is not startup development. You're building for handoff, not for iteration. The client (or their internal team, or another agency) will maintain this code after you leave. This means: clean architecture, documented decisions, no clever tricks that only you understand, and a codebase that a competent developer can pick up without a guided tour.

## The Sprint Structure
Week 1: Environment setup, architecture decisions, core layout and navigation. Week 2-3: Feature development, page-by-page build, CMS integration. Week 4: QA, bug fixes, client testing, performance optimization. Week 5: Launch prep, staging review, go-live. This is a 5-week sprint for a typical website project — adjust proportionally for larger or smaller scopes.

## The Quality Standards
Performance: Lighthouse score 90+ across all pages. Accessibility: WCAG AA compliance. Responsiveness: tested on real devices (not just browser simulators). Cross-browser: Chrome, Safari, Firefox, Edge (latest 2 versions). Code quality: consistent formatting (Prettier), no lint errors, meaningful commit messages, documented README with setup instructions.

## The Handoff Package
The delivered codebase must include: README with local setup instructions, environment variable documentation, CMS admin documentation, deployment instructions, and a brief architecture overview explaining key technical decisions. If the client can't run the project locally after reading the README, the handoff is incomplete.

## When to use
Every development project. When establishing engineering quality standards. When client handoffs are consistently rocky.
