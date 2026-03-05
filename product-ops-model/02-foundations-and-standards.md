# 02. Foundations and Standards

## Why standards matter

Standards reduce ambiguity, improve cross-team collaboration, and make scaling possible without sacrificing quality or discovery discipline.

## Foundational capabilities every team needs

1. **Problem framing**
   - Crisp problem statement.
   - Target segment and context clarity.
   - Baseline metric and impact expectation.

2. **Evidence-based decision making**
   - Continuous customer evidence capture.
   - Explicit assumptions and confidence levels.
   - Decision logs with rationale.

3. **Experimentation**
   - Hypothesis-driven tests.
   - Clear success/failure thresholds.
   - Learnings fed back into roadmap decisions.

4. **Responsible AI practice**
   - Data quality and privacy controls.
   - Risk analysis for bias, misuse, and failure modes.
   - Human oversight for high-impact decisions.

5. **Operational transparency**
   - Standard artifacts and naming.
   - Shared dashboards and health indicators.
   - Visible ownership and timelines.

## Non-negotiable standards

### Standard A: Every initiative starts with an opportunity
- Must include: customer problem, affected segment, expected outcome, strategic alignment.

### Standard B: Discovery evidence freshness
- At least one meaningful customer evidence input every 2 weeks for active initiatives.

### Standard C: Assumption tracking
- Top assumptions must be documented with confidence level and test plan.

### Standard D: Outcome metric ownership
- Every initiative must declare a primary outcome metric and owner.

### Standard E: Responsible AI gate
- AI-powered initiatives require a risk review before release.

### Standard F: Learning closure
- Post-launch or post-test summary is mandatory (what happened, why, what next).

### Standard G: Design system first for UI initiatives
- Teams must evaluate existing design system components before creating new UI patterns.
- New components require rationale, reuse intent, and ownership.

### Standard H: Rules and skills governance
- Every team should know which guidance is a non-negotiable rule vs reusable skill.
- Product Ops owns governance with domain leads as content stewards.

## Artifact quality criteria

### Opportunity artifact is high quality when it is:
- specific (not generic);
- evidence-backed (not opinion-only);
- connected to measurable impact;
- traceable to strategic goals.

### Discovery artifact is high quality when it is:
- continuous (not one-time);
- balanced (qualitative + quantitative);
- explicit on assumptions and unknowns;
- actionable for next decisions.

### Delivery artifact is high quality when it is:
- scoped around outcomes and user value;
- explicit about constraints and risks;
- linked to validation checkpoints.

## Naming and documentation conventions

Use this naming convention:

`[Team]-[Quarter]-[ArtifactType]-[InitiativeName]`

Examples:
- `Growth-Q2-Opportunity-ActivationDropoff`
- `Core-Q2-Experiment-OnboardingFriction`

Recommended artifact locations:
- Discovery and strategy docs in Confluence or docs repo.
- Experiment and outcome tracking in shared dashboarding tool.
- Decision log in a searchable central page.

## Review and governance checkpoints

### Stage 1: Intake / framing
- Opportunity artifact complete.
- Initial assumptions listed.

### Stage 2: Discovery
- Discovery brief complete.
- Evidence recency check passes.

### Stage 3: Solution commitment
- PRD-lite complete.
- Experiment plan for key unknowns defined.
- Responsible AI review completed if applicable.
- Track-specific checkpoints passed (UI or backend workflow gates).

### Stage 4: Learning and iteration
- Outcome tracking live.
- Post-launch learning summary published.

## Anti-patterns to avoid

- Starting delivery without clear opportunity framing.
- Treating discovery as a one-time kick-off.
- Using AI-generated artifacts without source validation.
- Measuring only shipped features, not customer outcomes.
- Skipping retrospective learning when results are poor.
- Anchoring too early in solution space.
- HIPPO-led decisions overriding evidence.
- Treating polished prototypes as proof of validated customer value.
