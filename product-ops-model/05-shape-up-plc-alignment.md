# 05. Shape Up PLC Alignment (from Confluence Export)

## Purpose

Translate the current Shape Up PLC practices from Confluence exports into explicit, reusable standards for product teams.

## Source analyzed

- `Confluence-space-export-225937.html.zip` (Product Operations space).
- Relevant pages discovered:
  - `Pitch Template: [Title of your Target Opportunity here]`
  - `Pitch Template: [One Pager Title]`
  - `Customer Insight Framing`
  - `Product Opportunities Assessment`
  - GTM and release templates
  - Product and developer documentation guides

## Current Shape Up PLC patterns observed

### 1) Signal -> Insight -> Opportunity flow is explicit
- Teams distinguish:
  - signal (single feedback point),
  - insight (validated/repeated pattern),
  - opportunity (framed problem for exploration).
- This is a strong foundation for continuous discovery.

### 2) Canny is used as the insight system of record
- Required tagging is emphasized (customer, role, theme, keyword, time, etc.).
- "If it is not in Canny, it is anecdote" pattern is clear and useful.

### 3) Pitching includes Shape Up language and discipline
- Current pitch structure includes:
  - context,
  - problem statement,
  - proposed solution,
  - **appetite (fixed time, variable scope)**,
  - assumptions,
  - rabbit holes and risks,
  - expected outcomes and alignment.

### 4) Shift toward delivery-led one-pager execution
- The one-pager is optimized for execution clarity and dependencies.
- It intentionally reduces discovery overhead in later stages.

### 5) Strong GTM and release operationalization
- GTM strategy, launch plan, release plan, and release notes templates are present.
- Includes go/no-go checks, rollback, support/hypercare, and comms.

### 6) Documentation quality guides exist
- Guides for feature documentation and integration documentation are mature.
- AI prompt examples already appear in documentation workflows.

## Gaps to address for scale

1. **Stage gates need clearer entry/exit criteria**
   - Define exactly what "good enough" means before work advances.

2. **Discovery evidence recency must be measured**
   - Add explicit freshness checks (for example, evidence within 14 days for active opportunities).

3. **Appetite and delivery constraints need shared scoring**
   - Use consistent criteria for must-have vs nice-to-have vs out-of-scope.

4. **Cross-artifact traceability is not always guaranteed**
   - Ensure each one-pager links back to insight and opportunity sources.

5. **AI usage is present but not always standardized**
   - Require consistent evidence-integrity checks for AI-generated content.

## Recommended standard lifecycle (Shape Up + Continuous Discovery)

1. **Capture**: Canny insight capture with required tags.
2. **Frame**: Opportunity assessment with outcome metric and sizing.
3. **Shape**: Pitch one-pager with appetite, assumptions, and rabbit holes.
4. **Commit**: PRD-lite and execution plan.
5. **Launch**: GTM launch/release artifacts and go/no-go.
6. **Learn**: Post-launch review and portfolio learnings.

## Non-negotiable controls to adopt

- Every pitch includes appetite, explicit out-of-scope, and top risks.
- Every execution artifact links to at least one customer insight source.
- Every active initiative has a named primary KPI and decision owner.
- Every release has rollback and hypercare plans.
- Every AI-assisted artifact is human-reviewed before publication.

## Immediate implementation actions

1. Add a Canny insight capture template to the shared library.
2. Add a Shape Up pitch one-pager template to the shared library.
3. Train teams on signal -> insight -> opportunity quality checks.
4. Run monthly Product Ops audit on traceability and evidence quality.
5. Publish rule vs skill governance model for Cursor usage.
6. Add UI/backend checkpoint workflow and enforce at commitment stage.
