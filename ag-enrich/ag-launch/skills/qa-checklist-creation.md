---
id: qa-checklist-creation
name: Qa Checklist Creation
domain: ag-launch
version: 1.0.0
---
# Qa Checklist Creation
**Purpose:** Apply qa checklist creation with the rigor and specificity that profitable agency delivery demands — where client expectations, fixed budgets, and quality standards leave no room for guesswork.

## Why This Matters

Launch is a coordinated event, not just a deployment. It involves the client, the users, the team, DNS, monitoring, analytics, and the communication plan. A flawed launch undermines months of work. A clean launch builds trust that generates referrals.

For qa checklist creation specifically, the gap between doing this well and doing it poorly is the gap between a profitable project and a money-losing one. Agencies that systematize qa checklist creation deliver more consistently, scope more accurately, and retain clients longer than agencies that handle it ad-hoc.

## The Framework

The Post-Launch Report: What was delivered (deliverable list with links). Key metrics (performance scores, accessibility compliance). Issues discovered and resolved. Recommendations for next phase. Client satisfaction check-in.

## How to Apply This

**Step 1: Assess the current state.** Before changing anything, document how qa checklist creation is currently handled. What works? What breaks? Where does the team spend unnecessary time? The assessment reveals whether the problem is process, people, tools, or all three.

**Step 2: Define the standard.** What does good look like for qa checklist creation in this agency, for this project type, at this scale? The standard should be specific enough that two team members would independently produce similar outputs. If the standard is vague, the results will be inconsistent.

**Step 3: Build the system.** Create the templates, checklists, documentation, and workflows that make the standard repeatable. The system should be lightweight enough to actually use and comprehensive enough to catch the common failure modes.

**Step 4: Measure and improve.** Track whether the system is working. The key metrics for qa checklist creation: Launch day issues (target: 0 critical), time to detect post-launch issues, rollback frequency, client satisfaction with launch process, post-launch bug count. Review quarterly. Adjust based on what the data shows, not what feels right.

## Real-World Use Cases

**Early-stage agency (1-5 people):** At this scale, qa checklist creation is often handled by the founder directly. The priority is documenting what works before the team grows. Create a simple version — a one-page checklist or template — that captures the founder's judgment so it can be delegated.

**Growth-stage agency (5-20 people):** At this scale, qa checklist creation must be delegated and systematized. The founder can't be in every loop. Build the standard, train the team, and create quality checks that catch problems without creating bottlenecks. The goal is consistent output without the founder's involvement in every instance.

**Scaled agency (20+ people):** At this scale, qa checklist creation needs governance — who owns the standard, how it's updated, how new team members are trained, and how exceptions are handled. The system should be self-maintaining: documented enough that a new PM or lead can manage it without institutional knowledge from the founders.

## Common Mistakes

**Not communicating launch status to the client in real-time.** This is the most common failure mode and the one that costs the most in rework, client friction, and margin erosion.

**No pre-launch checklist — relying on memory instead of a systematic verification.** This usually happens when the agency is moving too fast to follow the process — which is exactly when the process matters most.

**No rollback plan — having no plan for what to do if the launch goes wrong.** This compounds over time. Each instance is small. The cumulative effect is significant.

## The Agency-Specific Dimension

Agency work has constraints that product teams and freelancers don't face. Multiple clients means qa checklist creation must work across different brands, industries, and stakeholder dynamics. Parallel projects mean the team handles qa checklist creation for 3-5 clients simultaneously. Fixed budgets mean there's no room for the process to be inefficient. External deadlines mean the timeline is real. These constraints make systematizing qa checklist creation not optional but essential.

## Metrics to Track

Launch day issues (target: 0 critical), time to detect post-launch issues, rollback frequency, client satisfaction with launch process, post-launch bug count

## When to use

When qa checklist creation is the current bottleneck in delivery or operations. When quality in this area is inconsistent across projects or team members. When the agency is scaling and needs qa checklist creation to work without the founder in the loop. When post-project retrospectives identify this as a recurring issue.


## Advanced Launch Execution

### The Launch Day Runbook
A minute-by-minute plan for launch day:

**T-60 min:** Team check-in. Everyone confirms they're online and have access to all systems. Monitoring dashboards open. Client communication channel active. Rollback procedure reviewed.

**T-0 (Deploy):** Code deployed to production. The designated deployer confirms successful deployment. PM sends "deployment complete, beginning verification" to the team channel.

**T+5 min:** Smoke test. Critical paths verified manually: homepage loads, navigation works, forms submit, payment processes (if applicable), authentication works, key content displays correctly. Each team member tests 2-3 paths and reports status.

**T+15 min:** Automated checks. Lighthouse run on key pages. Broken link checker. Analytics verification (events firing). Error monitoring check (no new errors). Performance check (Core Web Vitals).

**T+30 min:** Client notification. "The site is live. Here's the URL. We're monitoring performance and will send a full status report by end of day. Please test [specific things] and let us know if you see anything unexpected."

**T+2 hours:** First monitoring review. Error rates, page load times, user behavior (if analytics are configured), search console indexing. Any anomalies investigated immediately.

**T+4 hours:** Status update to client with initial metrics: uptime, performance scores, any issues found and resolved, any issues still being investigated.

**T+24 hours:** Comprehensive post-launch report: full Lighthouse scores, all issues found and their status, traffic and behavior data (if available), next steps.

### The Post-Launch Monitoring Protocol
Monitor these metrics for 7 days post-launch:

**Uptime** — should be 99.9%+. Any downtime in the first week is a reputation issue. Use an external monitor (UptimeRobot, Pingdom) — don't rely on your own infrastructure to tell you it's down.

**Error rates** — JavaScript errors (Sentry, Datadog), server errors (500s), 404s. Zero tolerance for 500s. 404s should be investigated — they indicate broken links or missing redirects.

**Performance** — track Core Web Vitals daily for the first week. LCP, FID, and CLS should remain stable or improve as caching warms. Any degradation needs immediate investigation.

**SEO** — verify Google Search Console shows no new errors. Check that old URLs are redirecting correctly (if migration). Verify sitemap is submitted and being crawled.

### Case Study: The Launch That Nearly Killed a $2M Relationship
An agency launched a major e-commerce redesign for a $2M/year client. The launch went technically smoothly — no errors, good performance, clean deployment. But nobody checked the payment flow on mobile Safari. On mobile Safari, the checkout button was hidden behind the keyboard on certain screen sizes. 30% of mobile purchases failed silently for 3 days before a customer reported it. Revenue loss: estimated $180K. The client nearly terminated the relationship. Post-mortem finding: the pre-launch checklist didn't include device-specific payment flow testing. The fix: every launch checklist now includes "test complete purchase flow on: Chrome desktop, Safari desktop, Chrome mobile, Safari mobile, Firefox." 5 tests that take 15 minutes and prevent catastrophic launch failures.



## The Agency Practitioner's Playbook

### Patterns That Recur Across Every Agency Domain

**Pattern 1: Process investment pays 10x.** Every hour invested in documenting and systematizing how the agency works saves 10 hours of ad-hoc problem-solving, onboarding confusion, and inconsistent quality. Process isn't bureaucracy — it's the operating system. The agencies that resist process stay small and stressed. The agencies that embrace it scale with sanity.

**Pattern 2: Client communication prevents 80% of problems.** The vast majority of client conflicts — about scope, quality, timeline, budget — trace back to communication gaps. A weekly status update in a consistent format prevents more client escalations than any amount of excellent work delivered silently. Overcommunication is almost never the problem. Undercommunication almost always is.

**Pattern 3: Quality costs less than rework.** Spending an extra 10% on quality (design review, code review, pre-launch checklist, content QA) prevents 50%+ of post-launch fixes, client complaints, and emergency patches. The math always favors investing in prevention over paying for repair. Yet most agencies underinvest in quality because the cost is visible and immediate while the savings are invisible and distributed.

**Pattern 4: Specialization beats generalism.** Agencies that specialize (by industry, by service, by technology, by company stage) charge more, win more, and deliver better than agencies that do everything for everyone. Specialization creates expertise, expertise creates efficiency, efficiency creates margin, and margin creates sustainability. The fear: "But we'll lose clients who need other things." The reality: you'll lose bad-fit clients and attract good-fit clients at higher rates.

### The Career Progression in Agency Work

**Junior (0-2 years):** Learn the craft. Execute tasks within a defined process. Develop skills in your discipline. Focus: quality of output.

**Mid (2-5 years):** Own deliverables end-to-end. Manage components of client relationships. Begin mentoring juniors. Focus: quality of process.

**Senior (5-8 years):** Own client relationships. Lead teams on complex projects. Contribute to agency strategy. Focus: quality of judgment.

**Lead/Director (8+ years):** Set standards for the discipline. Win and manage key accounts. Shape agency direction. Mentor seniors. Focus: quality of the system.

**Partner/Principal (10+ years):** Drive agency growth. Own the agency's market position. Build the team's capability. Focus: quality of the agency itself.

At every level, the shift is from doing the work to improving how the work gets done. The most valuable agency people aren't the best individual contributors — they're the people who make everyone else better.

### Mental Models for Agency Thinking

**The Service-Profit Chain:** Happy employees → better work → happy clients → referrals and retention → revenue → investment in employees → happier employees. The chain starts with employee experience, not client experience. Agencies that treat employees as fungible resources break the chain at the first link.

**The Trust Equation (Maister):** Trust = (Credibility + Reliability + Intimacy) / Self-Orientation. Credibility: do you know your stuff? Reliability: do you deliver what you promise? Intimacy: does the client feel safe with you? Self-Orientation: are you focused on the client's interests or your own? The denominator matters most — self-oriented agencies destroy trust regardless of how credible, reliable, or intimate they are.

**The Hedgehog Concept (Collins):** The intersection of: (1) What you're deeply passionate about, (2) What you can be best in the world at, and (3) What drives your economic engine. For agencies: passionate about a specific craft, best at a specific service for a specific audience, with an economic model that sustains the team. Agencies that operate outside the intersection are perpetually struggling. Agencies that find it are sustainable and growing.

### Metrics That Matter Across All Domains

Track these 5 meta-metrics regardless of your specific role:

1. **Client satisfaction trend** — are clients happier or less happy over the last 3 quarters?
2. **Team satisfaction trend** — is the team more or less engaged over the last 3 quarters?
3. **Revenue per employee** — is the agency getting more efficient or less?
4. **Repeat business rate** — are clients coming back? (Target: 60%+ of revenue from existing clients)
5. **Referral rate** — are clients sending new clients? (Target: 30%+ of new business from referrals)

If all 5 are trending positively, the agency is healthy regardless of what individual project metrics show. If any is trending negatively for 2+ quarters, there's a systemic issue that needs diagnosis.

## When to use

When this specific agency skill is the active constraint. When the current approach is producing inconsistent results. When scaling requires systematizing what currently lives in someone's head. When a post-project retrospective identifies this area as a recurring gap. When onboarding new team members who need to learn the agency's approach to this domain.

