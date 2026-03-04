# AI-Assisted Shape Up Pitch Playbook

## Goal

Help PMs produce better Shape Up pitches faster, while keeping decision quality high and grounded in evidence.

This playbook is an **overlay** on your current pitch templates, not a replacement.

---

## 1) Minimum input pack (before using AI)

Prepare these inputs first:

- Customer insight evidence (quotes, counts, timestamps, sources)
- Opportunity context (segment affected, impact magnitude)
- Constraints (cycle appetite, dependencies, platform constraints)
- Existing artifacts (assessment docs, flows, sketches, prior decisions)
- Current template variant to use (full pitch or one-pager)

If evidence is missing, use AI to list **evidence gaps**, not to invent facts.

---

## 2) Prompt contract (standard for every AI call)

Use this instruction block at the top of each prompt:

```text
You are assisting with a Shape Up pitch.
Rules:
1) Use only the evidence provided.
2) Do not invent customer data, metrics, dependencies, or decisions.
3) If evidence is missing, state "evidence gap" and ask a targeted question.
4) Keep scope consistent with fixed time, variable scope.
5) Output concise bullets first, then a short narrative version.
```

---

## 3) Workflow (human + AI)

## Step 1: Build an evidence brief

**Human does:**
- Assemble raw notes and references.

**AI does:**
- Normalize into: problem signals, affected users, impact, confidence, unknowns.

**Output:**
- One-page evidence brief with citation links.

---

## Step 2: Draft the pitch skeleton

**Human does:**
- Select template variant (full vs one-pager), set appetite range.

**AI does:**
- Produce first-pass bullets for each required section.

**Output:**
- Skeleton with explicit "known" vs "assumed" labels.

---

## Step 3: Generate solution options before locking scope

**Human does:**
- Provide non-negotiables and constraints.

**AI does:**
- Propose 2-3 shape options:
  - Option A (minimal)
  - Option B (balanced)
  - Option C (higher impact, higher risk)

**Output:**
- Trade-off table (value, complexity, dependency load, risk).

---

## Step 4: Cut scope to appetite

**Human does:**
- Pick preferred option and enforce cycle boundaries.

**AI does:**
- Convert to:
  - Must-have
  - Nice-to-have
  - Out-of-scope
  - Follow-ups

**Output:**
- Appetite-aligned scope with clear cut-line.

---

## Step 5: Stress-test assumptions and rabbit holes

**Human does:**
- Add known technical and organizational constraints.

**AI does:**
- Create a red-team pass:
  - Top failure modes
  - Earliest warning signals
  - Mitigation actions + owners

**Output:**
- Risk register aligned to the pitch risk section.

---

## Step 6: Define measurable success

**Human does:**
- Confirm what can realistically be measured in cycle and post-release windows.

**AI does:**
- Draft metrics with:
  - baseline
  - target
  - measurement window
  - source of truth

**Output:**
- Measures of success section ready for review.

---

## Step 7: Prepare alignment package

**Human does:**
- Confirm stakeholders and review forum.

**AI does:**
- Generate:
  - 5-slide summary
  - anticipated Q&A
  - decision asks and fallback options

**Output:**
- Leadership-ready pitch narrative.

---

## Step 8: Run quality gate checklist

A pitch is "betting-ready" when all are true:

- Evidence is explicit and sourced
- Appetite and cut-line are clear
- Assumptions and dependencies have owners
- Risks include mitigations and triggers
- Success measures include baseline + target + timing
- Out-of-scope is explicit

---

## 4) Section-by-section AI guidance

| Template section | AI job | Human review focus |
|---|---|---|
| Background & Context | Summarize why now and who is affected | Strategic alignment and relevance |
| Problem Statement | Convert signals to crisp problem framing | Avoid solution bias |
| Show your work | Synthesize evidence and confidence levels | Source quality and recency |
| Outline Solution | Draft high-level shape and constraints | Feasibility and desirability |
| Appetite | Translate capacity into scope boundaries | Realistic commitment |
| Key Assumptions | Enumerate assumptions and test status | Missing critical unknowns |
| Measures of Success | Draft measurable criteria and windows | Instrumentation feasibility |
| Risks / Rabbit Holes | Identify derailers and mitigations | Practicality of mitigations |
| Gain Alignment | Build concise recap and stakeholder asks | Decision clarity |
| Appendix / Q&A | Summarize references and anticipated questions | Accuracy and completeness |

---

## 5) Reusable prompt starters

## A. Problem framing prompt

```text
Using the evidence below, draft:
1) a 3-bullet problem statement,
2) impacted customer segments,
3) quantified or directional business impact,
4) evidence gaps to validate next.

Evidence:
[paste notes, links, quotes]
```

## B. Appetite and scope prompt

```text
Given a fixed appetite of [X weeks], produce:
- must-have scope
- nice-to-have scope
- out-of-scope list
- top 3 trade-offs made and why
- dependencies that threaten delivery timing

Constraints:
[paste constraints]
```

## C. Risk red-team prompt

```text
Red-team this proposed pitch.
Return:
1) top 5 failure modes,
2) trigger signals for each,
3) mitigation action + owner,
4) residual risk score (low/medium/high).

Pitch draft:
[paste draft]
```

## D. Success metric prompt

```text
Define success measures for this pitch.
For each metric provide:
- metric name
- baseline
- target
- measurement window
- source of truth
- instrumentation owner

Pitch context:
[paste context]
```

---

## 6) Guardrails and anti-patterns

Do not use AI outputs if they:

- contain unsourced claims
- over-specify implementation details too early
- hide uncertainty behind confident wording
- produce broad outcomes without measurable indicators
- blur must-have vs nice-to-have scope

If any of these appear, run another pass with tighter constraints and explicit evidence references.

---

## 7) Suggested operating metrics for the pilot

Track for first 2 cycles:

- Median time to first complete pitch draft
- Number of revision rounds before review
- % pitches passing quality gate on first review
- PM-reported prep effort (hours)
- Bet acceptance rate

Use these metrics to decide whether to standardize or tune the AI workflow.
