# Customer Interview Snapshot (Teresa Torres Framework)

## Interview
- **Interviewee:** Ashwini R (Engineering)
- **Interviewer:** Karina Budaeva (Product)
- **Date:** 2026-03-09
- **Duration:** 28m 16s
- **Context:** Internal discovery interview on how Cursor is changing delivery speed, implementation quality, and team process for Brand Pages MVP.

## 1) Memorable Quote
> "With the help of cursor, things are moving too fast... we need a streamlined process to actually get things delivered." (19:05, 24:36)

## 2) Quick Facts
- Team is using Cursor heavily for implementation, planning, and architecture exploration.
- Cursor can generate large multi-file changes quickly, but debugging and traceability become hard when prompts are too broad.
- The team found better outcomes when prompts are constrained to small, incremental changes (2-3 files, small diff size).
- Early UI output diverged from design system until prompts explicitly referenced Orchard/internal component libraries.
- Current operating model is mostly Kanban-like and reactive; prioritization and scope visibility are weak.

## 3) Insights
1. **Speed shifted the bottleneck from coding to coordination.**  
   Build velocity increased, but requirement clarity, priority alignment, and review cadence did not keep up.

2. **Prompt quality is now a core delivery capability.**  
   Teams succeed when they provide concrete file references, data models, and design-system constraints.

3. **Large AI-generated changes reduce confidence.**  
   Broad prompts create too many edits and make debugging difficult; teams now prefer iterative prompt->review loops.

4. **Process artifacts still matter, but should be lighter and living.**  
   Ashwini supports using Jira, but as evolving tickets (day 1/day 2 updates) rather than heavy upfront specs.

5. **Planning horizon is missing.**  
   Team members can pick less critical work because backlog ordering and near-term focus are not explicit.

## 4) Opportunities (Needs, not solutions)
1. **Need to preserve velocity while restoring predictability** in what gets worked on each week.
2. **Need clear prompt-ready requirement inputs** so outputs match expected UX and architecture constraints.
3. **Need lightweight but durable visibility** into status, ownership, and priority across time zones.
4. **Need a reliable review loop** that catches mismatches early without slowing down implementation.
5. **Need integration-aware prioritization** so work sequencing aligns with partner teams (reporting/attribution/integration).

---

## Interview Unpacked

### A) Story Arc (What happened)
1. **Adoption:** Cursor enabled fast implementation and architecture discovery.
2. **Drift:** Initial outputs missed design consistency and process transparency.
3. **Adaptation:** Team learned to use stricter prompts, smaller changes, and references to internal libraries.
4. **Current pain:** Planning, prioritization, and communication lag behind build speed.
5. **Future need:** Phase 2 requires stronger cadence for backlog prioritization and daily/alternate-day review.

### B) Evidence Highlights
- **Small-batch prompting:** "Simple prompts... changes maximum of two to three files." (4:00-4:17)
- **Debugging risk:** "Development is very easy, but debugging... very difficult." (3:41-4:00)
- **Design fidelity requires constraints:** Reuse Orchard components; avoid generic CSS/HTML output. (8:51-10:10)
- **Process stress:** "Wild old West... people just pick up work." (21:37-21:46)
- **Desired rhythm:** Define focus weekly/biweekly; daily short alignment checks. (19:44-20:45, 22:51-23:30)

### C) Jobs-to-be-Done Signals
- **Functional job:** Deliver MVP and follow-on features quickly with acceptable quality.
- **Coordination job:** Keep team aligned on what to build next and why.
- **Emotional job:** Reduce stress caused by unclear priorities and fast-changing implementation.

### D) Opportunity Statements (for OST/backlog)
- When implementation speed spikes, teams need a way to **lock next-up priorities** so effort flows to highest-value work.
- When prompts generate broad changes, teams need a way to **constrain change scope** so debugging remains tractable.
- When requirements are discussed verbally, teams need a way to **capture prompt-ready acceptance criteria** so reviews are objective.
- When teams are distributed across time zones, teams need a way to **asynchronously clarify open questions** before coding starts.

### E) Follow-up Questions to Validate
1. What is the minimum artifact that gives Product confidence before coding starts?
2. Which change types should always require plan mode + review before agent mode?
3. What review cadence (daily vs. alternate-day) maximizes quality without reducing throughput?
4. How should backlog ordering be represented so engineers reliably pick highest-priority work?

### F) Potential Experiments
- Pilot a 2-week "priority lane" with explicit top-of-backlog commitment.
- Use a one-page prompt template for each new feature (context, references, constraints, acceptance checks).
- Require small-batch implementation (file/line guardrails) for UI changes.
- Run asynchronous "question handoff" protocol across time zones for unresolved requirements.
