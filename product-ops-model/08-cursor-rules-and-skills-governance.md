# 08. Cursor Rules and Skills Governance

## Purpose

Define a clear operating model for **rules** and **skills** in Cursor so product teams can move fast without losing quality, consistency, and discovery rigor.

## Rule vs Skill (plain language)

| Type | Definition | Nature | Owner | Example |
|---|---|---|---|---|
| Rule | A non-negotiable standard or constraint that must be followed | Guardrail | Product Ops + domain governance leads | "Use existing design system components before creating new UI." |
| Skill | A reusable capability that helps teams execute a task better/faster | Enablement | Domain leads + Product Ops enablement | "Draft a Shape Up pitch from opportunity + evidence inputs." |

## Decision criteria: is it a rule or a skill?

Treat it as a **rule** when it:
- protects quality, compliance, safety, or integrity;
- should be consistently enforced across all teams;
- defines a pass/fail requirement at checkpoints.

Treat it as a **skill** when it:
- improves speed/quality of a repeatable task;
- can vary by context without breaking standards;
- benefits from examples, prompts, and iterative improvement.

## Recommended ownership model

### Product Operations (accountable)
- Rule framework and policy lifecycle.
- Skill quality bar and adoption metrics.
- Training and governance cadence.

### Engineering/Architecture leads (responsible for technical domains)
- Backend/system context quality.
- API, service boundary, and implementation standards.

### Design System/Design leads (responsible for design domains)
- Component guidance, tokens, patterns, and usage rules.
- Product design decision quality and coherence.

### Team leads (responsible for execution)
- Ensure teams apply rules in daily workflow.
- Propose new skills and report quality gaps.

## Minimum governance lifecycle

1. **Propose**
   - Submit new rule/skill proposal using standard template.

2. **Review**
   - Validate accuracy, scope, and overlap with existing assets.

3. **Approve**
   - Publish with owner, version, and effective date.

4. **Adopt**
   - Train teams and integrate into workflow checkpoints.

5. **Audit**
   - Monthly quality and usage review.

6. **Retire/Revise**
   - Deprecate stale assets and update based on learnings.

## Rule categories for product teams

1. **Discovery integrity rules**
   - Evidence freshness, source traceability, assumption testing.

2. **Design system reuse rules**
   - Prefer existing components before net-new implementation.
   - Require rationale for introducing a new reusable component.

3. **Delivery quality rules**
   - Explicit appetite, out-of-scope, dependencies, and risk checks.

4. **Responsible AI rules**
   - No fabricated evidence.
   - Human review required for high-impact content.

## Skill categories for product teams

1. Insight capture and synthesis skills.
2. Opportunity framing and prioritization skills.
3. Shape Up pitch and scope-shaping skills.
4. PRD-lite and execution planning skills.
5. Design decision recording and handoff skills.
6. Release/learning loop summarization skills.

## Permissions and contribution model (practical default)

- **View access**: all product, design, engineering, and ops team members.
- **Edit access**: designated maintainers per domain.
- **Approval rights**: Product Ops + domain owner pair.
- **Emergency updates**: temporary exception process with retroactive review.

## Quality checklist for publishing a rule

- [ ] Problem and risk are clearly stated.
- [ ] Scope is explicit (what this applies to).
- [ ] Rule is testable (pass/fail behavior defined).
- [ ] Owner and review cadence are assigned.
- [ ] Related skills/templates are linked.

## Quality checklist for publishing a skill

- [ ] Purpose and expected output are clear.
- [ ] Inputs are explicit and source-linked.
- [ ] Quality checks are included.
- [ ] Example usage is provided.
- [ ] Owner and update cadence are assigned.

## Implementation note: design-system-aware development

Given current pain points, adopt this default:

1. Before UI generation, Cursor should first reference design system context.
2. If no component exists, propose extension options and generic reuse potential.
3. Log design decisions in a reusable format for future teams.

This prevents repeated one-off patterns and improves handoff quality for teams without dedicated design coverage.
