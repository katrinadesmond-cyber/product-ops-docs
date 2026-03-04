# Product Operations Framework for Shape Up Teams

## Purpose

Create repeatable efficiency across the product development lifecycle so PMs spend less time on document rework and coordination overhead, and more time on high-quality decisions.

This framework is designed for teams using **Shape Up** and is aligned with your existing artifacts:

- Customer Insight Framing
- Product Opportunities Assessment
- Pitch Template (full and one-pager)
- GTM and release planning templates

---

## 1) Operating principles

1. **Evidence before opinion**  
   Every pitch claim should point to customer, market, or delivery evidence.
2. **Fixed time, variable scope**  
   Appetite is a hard constraint; scope flexes to protect cycle outcomes.
3. **Single source of truth by phase**  
   One artifact is canonical at each stage to reduce duplicate updates.
4. **AI for speed, humans for judgment**  
   AI drafts and stress-tests; PM/triad own decisions and trade-offs.
5. **Progressive fidelity**  
   Start lightweight, increase detail only when confidence and commitment rise.

---

## 2) Lifecycle operating model

| Phase | Goal | Primary artifact | AI leverage | Efficiency KPI | Exit criteria |
|---|---|---|---|---|---|
| 0. Portfolio intent | Clarify strategic focus and cycle constraints | Quarterly goals + capacity assumptions | Summarize themes and dependency risks | % work linked to strategic theme | Focus areas and appetite ranges agreed |
| 1. Insight intake | Convert raw feedback into usable signals | Customer Insight Framing | Cluster themes, detect repeats, draft insight summaries | Insight-to-theme tagging completeness | Top recurring problems prioritized |
| 2. Opportunity assessment | Decide if opportunity is worth shaping | Product Opportunities Assessment | Draft first-pass answers to the 10 core questions, identify evidence gaps | Time from insight to go/no-go | Clear go/no-go recommendation |
| 3. Shaping and pitching | Produce a bet-ready pitch | Pitch template (full or one-pager) | Draft sections, create alternatives, challenge assumptions, tighten scope | Pitch cycle time; rework rounds | Pitch meets quality gate and appetite |
| 4. Betting and commitment | Select and sequence bets | Betting table + cycle plan | Summarize trade-offs and dependency impacts | Decision lead time | Bet accepted/rejected with rationale |
| 5. Build and delivery | Execute with minimal thrash | Build scopes, delivery checkpoints | Generate risk watchlists, summarize blockers | Scope volatility; blocked days per cycle | Scope delivered within appetite |
| 6. Launch and GTM | Release with coordination clarity | GTM launch/release plans + release notes | Draft comms variants and readiness checklists | Launch readiness on-time rate | Launch checklist complete |
| 7. Learn and recycle | Close the loop for next shaping cycle | Post-launch learnings + insight updates | Summarize results vs expected outcomes | % bets with completed learning review | Learnings fed back into insight system |

---

## 3) Standard cadences (Product Ops)

### Weekly

- **Insight triage (30-45 min):** PM + Design + Research/Support
  - Review new signals
  - Merge duplicates
  - Promote validated patterns
- **Shaping standup (30 min):** PM triad + Product Ops
  - Track active pitch stage
  - Resolve dependency blockers early

### Fortnightly

- **Pitch clinic (60 min):**
  - Peer review 1-2 pitches using the shared rubric
  - Focus on appetite fit, assumptions, rabbit holes, success measures

### Per cycle

- **Betting prep review (60 min):**
  - Final confidence check on shortlisted pitches
- **Post-cycle learning review (45 min):**
  - Compare predicted vs actual outcomes
  - Feed insights back to phase 1

---

## 4) Roles and decision rights

| Decision area | PM | Design | Engineering | Data/Analytics | Product Ops | Leadership |
|---|---|---|---|---|---|---|
| Problem framing | A/R | C | C | C | C | I |
| Scope within appetite | A | C | R | C | C | I |
| Assumptions and risks | A | C | R | C | C | I |
| Success measures | A | C | C | R | C | I |
| Pitch quality gate | A | C | C | C | R | I |
| Bet selection | C | C | C | C | C | A/R |

Legend: **A** = Accountable, **R** = Responsible, **C** = Consulted, **I** = Informed

---

## 5) Product Ops quality gates

Before a pitch can enter betting, it must pass:

1. **Evidence gate**
   - Claims are sourced and recent
   - Customer segment and impact are explicit
2. **Scope gate**
   - Must-have, nice-to-have, and out-of-scope are explicit
   - Appetite is stated and defended
3. **Risk gate**
   - Top rabbit holes identified with mitigations
   - Dependencies and owners are explicit
4. **Outcome gate**
   - Success measures include baseline, target, and timing
5. **Alignment gate**
   - Key stakeholders named
   - Open questions tracked with owners

---

## 6) KPI set (efficiency + quality)

Track these at team and org level:

### Flow efficiency

- **Insight-to-pitch lead time** (days)
- **Pitch draft cycle time** (first draft to final)
- **Average pitch revision rounds** before betting

### Decision quality

- **Bet acceptance rate** (% pitches accepted)
- **Scope stability index** (planned vs delivered scope)
- **Risk realization rate** (% identified vs unplanned risks)

### Outcome quality

- **Success metric definition completeness** (% pitches with baseline + target + window)
- **Post-cycle learning completion rate**
- **Predicted vs actual outcome variance**

---

## 7) 60-day rollout plan

### Weeks 1-2: Foundation

- Align on lifecycle and cadences
- Agree pitch quality rubric
- Train PMs on AI prompt standards

### Weeks 3-4: Pilot

- Run AI-assisted pitching with 2-3 squads
- Measure pitch time saved and revision count
- Capture failure patterns (hallucination, over-scoping, vague metrics)

### Weeks 5-8: Scale

- Standardize template and prompt library
- Add lightweight quality checks in pitch clinic
- Publish monthly Product Ops scorecard

---

## 8) First focus area: AI-assisted pitch development

The first implementation priority is phase 3 (Shaping and Pitching), where most PM overhead and rework occurs.

Use:

- `docs/shape-up/ai-pitch-playbook.md` for operating workflow
- `docs/shape-up/templates/shape-up-pitch-template-ai-overlay.md` for authoring

This keeps your current template structure but adds repeatable AI acceleration and quality controls.
