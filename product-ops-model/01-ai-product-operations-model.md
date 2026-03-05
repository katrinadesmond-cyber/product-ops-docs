# 01. AI Product Operations Model

## Purpose

Define a scalable operating model for product teams that use AI throughout the product development cycle while preserving continuous discovery, outcome focus, and responsible delivery.

## Scope

This model applies to:
- product managers;
- designers and researchers;
- engineers and data/ML practitioners;
- product operations and delivery leads;
- leadership stakeholders in planning and governance.

## Operating principles

1. **Outcomes over output**  
   Teams optimize for measurable customer and business outcomes.
2. **Continuous discovery is non-optional**  
   Discovery is an ongoing cadence, not a phase.
3. **AI assists, humans decide**  
   AI speeds synthesis, drafting, and analysis; humans own judgment.
4. **Standardize core artifacts, allow local flexibility**  
   Shared templates and minimum standards with room for team context.
5. **Instrument learning loops**  
   Every initiative has assumptions, experiments, and learning metrics.
6. **Responsible by design**  
   Privacy, security, ethics, and compliance are built in early.

## Product operations service model

### 1) Enablement
- Train teams on templates, discovery methods, and AI use patterns.
- Maintain playbooks, examples, and quality checklists.
- Coach teams during first 2-3 planning and discovery cycles.

### 2) Governance
- Run portfolio-level quality checks on artifacts.
- Monitor adoption of standards and discovery cadences.
- Escalate risks (strategy drift, weak evidence, compliance issues).

### 3) Insights and intelligence
- Aggregate learnings across teams (themes, customer patterns, failed bets).
- Track product health and experiment performance.
- Publish monthly insights briefs for leaders and teams.

## Roles and accountability (RACI summary)

| Capability | Product Team | Product Ops | Design/Research | Eng/Data/ML | Leadership |
|---|---|---|---|---|---|
| Opportunity framing | A/R | C | R | C | I |
| Discovery planning | A/R | C | R | C | I |
| Experiment design | A/R | C | R | R | I |
| PRD and delivery scope | A/R | C | C | R | I |
| Responsible AI review | C | C | C | A/R | I |
| Quarterly health review | R | A/R | C | C | I |

Legend: R = Responsible, A = Accountable, C = Consulted, I = Informed.

## Operating cadence

### Weekly
- Customer touchpoints and discovery synthesis.
- Decision log updates.
- Experiment progress review.

### Bi-weekly
- Opportunity-Solution Tree refresh.
- Cross-functional learning review.
- Backlog alignment based on evidence.

### Monthly
- Product Ops quality scan across artifacts.
- Insights briefing: wins, misses, and reusable patterns.

### Quarterly
- Portfolio health review and re-prioritization.
- Standards retrospective and framework updates.

## AI in the product development cycle

### Discover
- Use AI for interview summary clustering and theme extraction.
- Validate themes with raw evidence (quotes, recordings, notes).

### Define
- Use AI to draft opportunity statements, hypotheses, and success metrics.
- Require human validation before socialization.

### Develop
- Use AI to accelerate requirement refinement and edge-case generation.
- Keep traceability between assumptions, requirements, and experiments.

### Deliver and learn
- Use AI for telemetry analysis and anomaly detection.
- Convert results into explicit decisions: scale, iterate, pause, or stop.

## Minimum artifact stack per initiative

Each meaningful initiative should maintain:
1. Opportunity assessment.
2. Discovery brief.
3. Experiment cards (for key assumptions).
4. PRD-lite (or equivalent implementation brief).
5. Post-launch learning summary.

Templates for these artifacts are in `product-ops-model/templates/`.

## Definition of good product operations

A healthy team can:
- explain why an initiative matters in one sentence;
- show customer evidence from the last 30 days;
- list top assumptions and how they are being tested;
- map work items to outcome metrics;
- demonstrate decisions made from learnings, not opinions.
