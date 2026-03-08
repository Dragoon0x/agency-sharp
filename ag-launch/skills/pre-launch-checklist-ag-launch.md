---
id: pre-launch-checklist-ag-launch
name: Pre-Launch Checklist
domain: ag-launch
version: 1.0.0
---
# Pre-Launch Checklist
**Purpose:** Run a comprehensive pre-launch check that catches every category of issue — because the things that break in production are almost never the things you tested during development.

The pre-launch checklist is the agency's last line of defense. It's the systematic verification that everything works, across every browser, at every breakpoint, with real content, under real conditions. A 2-hour checklist prevents weeks of post-launch firefighting.

## The Checklist Categories
**Content:** All placeholder content replaced with final copy. No lorem ipsum. All images final and optimized. Legal pages present (privacy policy, terms). Contact information correct. Copyright year current.

**Functionality:** All forms submit and deliver to the correct destination. Payment processing tested with real transactions (then refunded). Search returns relevant results. Authentication works (login, signup, reset password, logout). All links work (no 404s — run a crawler).

**Performance:** Lighthouse score 90+ on key pages. Images lazy-loaded below the fold. Fonts loaded with font-display: swap. No render-blocking resources. Time to Interactive under 3 seconds on 3G.

**SEO:** Page titles and meta descriptions on every page. OG images for social sharing. Canonical URLs set. XML sitemap generated and submitted. Robots.txt configured. Structured data validated.

**Accessibility:** Keyboard navigation works on all interactive elements. Screen reader tested on key flows. Color contrast passes WCAG AA. Alt text on all images. Form labels associated with inputs.

**Infrastructure:** SSL certificate active and auto-renewing. Redirects from old URLs configured. 404 page designed. Analytics tracking verified. Error monitoring active. Backups configured.

## When to use
Every launch. No exceptions. The checklist should be a living document that grows with each post-launch issue discovered.
