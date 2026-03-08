---
id: multi-agent-workflow-design
name: Multi-Agent Workflow Design
domain: ag-orchestrate
version: 1.0.0
---
# Multi-Agent Workflow Design
**Purpose:** Design workflows where multiple AI agents collaborate on complex projects — the orchestration layer that turns individual specialists into a functioning team.

Individual agents are commodities. The value is in the system that coordinates them. A frontend agent and a backend agent working independently produce fragmented work. The same agents with a defined handoff protocol, shared context, and quality gates produce integrated work. The orchestration design is the difference.

## The Workflow Architecture
Define: which agents are involved, what each one produces, what each one needs from others, what order they execute in, and what quality checks happen between them. This is the project's production architecture — the blueprint for how work flows through the system.

## The Context Protocol
Agents lose context between sessions. The orchestration system must maintain context: project brief (persistent), decisions made (cumulative), current state (updated), and next steps (clear). This context document is the shared memory of the project — every agent reads it before starting work and updates it when finishing.

## The Handoff Format
Define a standard handoff format: what was done, what decisions were made, what's left for the next agent, what risks or issues were identified. Structured handoffs (not free-text summaries) prevent information loss and ensure the receiving agent has everything needed to continue.

## The Quality Gates
Between every handoff, a quality check: does the output meet the specification? Does it maintain consistency with previous work? Are there conflicts with other agents' outputs? Quality gates catch problems before they compound.

## When to use
Any project involving more than one agent or role. When agents are producing work that doesn't integrate well. When projects feel fragmented despite individual quality. When scaling agent-powered delivery.
