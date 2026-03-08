---
id: parallel-vs-sequential
name: Parallel vs Sequential Execution
domain: ag-orchestrate
version: 1.0.0
---
# Parallel vs Sequential Execution
**Purpose:** Decide which tasks run in parallel and which must run sequentially — maximizing speed without creating integration problems.

Not everything can be parallelized. Design must follow strategy. Development must follow design. But within phases, many tasks can run simultaneously: while the designer works on the homepage, the developer sets up the CMS. While the content agent writes copy, the designer creates the visual system. The skill is identifying true dependencies vs assumed dependencies.

## The Dependency Map
For each task, ask: what does this task need as input? If the input already exists, the task can start. If the input comes from another task that's in progress, this task must wait. Map every task-to-task dependency. The tasks with no upstream dependencies can run first. Tasks that depend only on completed work can run in parallel.

## The Integration Points
Parallel work must converge. Define integration points: moments where independently produced work comes together and must be verified for consistency. After the designer and content agent work in parallel, their outputs must be integrated before development begins. The integration point is where misalignment is caught.

## The Speed vs Quality Tradeoff
Maximum parallelism maximizes speed. But it also maximizes the risk of misalignment — parallel agents can drift in different directions. The tradeoff: more parallelism = faster delivery but higher integration risk. More sequential work = slower delivery but higher consistency. Choose based on timeline pressure vs quality requirements.

## When to use
During project planning — designing the execution schedule. When projects are taking too long and parallelism could help. When parallel work is producing integration problems.
