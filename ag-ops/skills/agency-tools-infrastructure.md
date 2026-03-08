---
id: agency-tools-infrastructure
name: Agency Tools Infrastructure
domain: ag-ops
version: 1.0.0
---
# Agency Tools Infrastructure
**Purpose:** Build a tool stack that supports agency operations — project management, communication, design, development, billing, and the integrations that connect them.

Agency tools should serve the workflow, not create their own. The most common tool stack failure: too many tools, poorly integrated, each owned by a different person, with no shared source of truth. The result is information scattered across 15 platforms and nobody knows where anything is.

## The Core Stack
Project management: one tool for all project tracking (Linear, Asana, ClickUp — pick one, commit). Communication: Slack for internal, email for client (never mix these). Design: Figma (the industry standard for collaborative design). Development: GitHub (code), Vercel/Netlify (deployment). Billing: one invoicing tool that integrates with your accounting (FreshBooks, Xero, QuickBooks). Time tracking: one tool that integrates with project management (Harvest, Toggl, Clockify).

## The Integration Architecture
Every tool should connect to the project management hub. When a designer completes a deliverable, the PM tool updates automatically. When a client approves a milestone, the billing tool generates an invoice. When time is logged, it flows to both the project tracker and the billing system. Manual data transfer between tools is operational debt.

## The Client-Facing Stack
Clients need: a place to see project progress (PM tool with client view or a dedicated client portal), a place to give feedback (Figma comments for design, staging URLs for development), and a place to approve deliverables (avoid email chains — use structured approval in the PM tool or a dedicated tool like Frame.io).

## When to use
At agency founding — start with the right stack before habits form. When onboarding new team members takes too long because of tool complexity. When information is scattered and nobody can find things. When the tool budget is growing faster than the team.
