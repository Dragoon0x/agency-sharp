---
id: image-optimization-engineering
name: Image Optimization Engineering
domain: ag-engineering-playbook
version: 1.0.0
---
# Image Optimization Engineering
**Purpose:** Apply image optimization engineering with the rigor and specificity that profitable agency delivery demands — where client expectations, fixed budgets, and quality standards leave no room for guesswork.

## Why This Matters

Agency engineering must balance craft with pragmatism. The code needs to be good enough to be maintainable, performant, and accessible — but it doesn't need to be over-engineered for a scale the client may never reach. The engineering playbook defines the quality standards, architecture patterns, and development practices that apply to every project.

For image optimization engineering specifically, the gap between doing this well and doing it poorly is the gap between a profitable project and a money-losing one. Agencies that systematize image optimization engineering deliver more consistently, scope more accurately, and retain clients longer than agencies that handle it ad-hoc.

## The Framework

The Security Baseline: HTTPS everywhere. Security headers (CSP, HSTS, X-Frame-Options). Input sanitization on all user inputs. Parameterized database queries (no SQL injection). Environment variables for secrets (never committed). Dependencies audited monthly (npm audit, Snyk).

## How to Apply This

**Step 1: Assess the current state.** Before changing anything, document how image optimization engineering is currently handled. What works? What breaks? Where does the team spend unnecessary time? The assessment reveals whether the problem is process, people, tools, or all three.

**Step 2: Define the standard.** What does good look like for image optimization engineering in this agency, for this project type, at this scale? The standard should be specific enough that two team members would independently produce similar outputs. If the standard is vague, the results will be inconsistent.

**Step 3: Build the system.** Create the templates, checklists, documentation, and workflows that make the standard repeatable. The system should be lightweight enough to actually use and comprehensive enough to catch the common failure modes.

**Step 4: Measure and improve.** Track whether the system is working. The key metrics for image optimization engineering: Lighthouse scores (target: 90+ per category), TypeScript coverage, test coverage (target: 60%+ for critical paths), build time, bundle size, deployment frequency, post-deployment error rate. Review quarterly. Adjust based on what the data shows, not what feels right.

## Real-World Use Cases

**Early-stage agency (1-5 people):** At this scale, image optimization engineering is often handled by the founder directly. The priority is documenting what works before the team grows. Create a simple version — a one-page checklist or template — that captures the founder's judgment so it can be delegated.

**Growth-stage agency (5-20 people):** At this scale, image optimization engineering must be delegated and systematized. The founder can't be in every loop. Build the standard, train the team, and create quality checks that catch problems without creating bottlenecks. The goal is consistent output without the founder's involvement in every instance.

**Scaled agency (20+ people):** At this scale, image optimization engineering needs governance — who owns the standard, how it's updated, how new team members are trained, and how exceptions are handled. The system should be self-maintaining: documented enough that a new PM or lead can manage it without institutional knowledge from the founders.

## Common Mistakes

**No performance budget — shipping sites that score 40 on Lighthouse.** This is the most common failure mode and the one that costs the most in rework, client friction, and margin erosion.

**No TypeScript — losing type safety that catches bugs before production.** This usually happens when the agency is moving too fast to follow the process — which is exactly when the process matters most.

**No testing — shipping code that works on the dev machine but breaks in edge cases.** This compounds over time. Each instance is small. The cumulative effect is significant.

## The Agency-Specific Dimension

Agency work has constraints that product teams and freelancers don't face. Multiple clients means image optimization engineering must work across different brands, industries, and stakeholder dynamics. Parallel projects mean the team handles image optimization engineering for 3-5 clients simultaneously. Fixed budgets mean there's no room for the process to be inefficient. External deadlines mean the timeline is real. These constraints make systematizing image optimization engineering not optional but essential.

## Metrics to Track

Lighthouse scores (target: 90+ per category), TypeScript coverage, test coverage (target: 60%+ for critical paths), build time, bundle size, deployment frequency, post-deployment error rate

## When to use

When image optimization engineering is the current bottleneck in delivery or operations. When quality in this area is inconsistent across projects or team members. When the agency is scaling and needs image optimization engineering to work without the founder in the loop. When post-project retrospectives identify this as a recurring issue.

