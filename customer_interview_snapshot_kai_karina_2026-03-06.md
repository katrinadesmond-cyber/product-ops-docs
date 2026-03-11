# Customer Interview Snapshot (Teresa Torres Framework)

## Interview
- **Interviewee:** Kai Yao (Engineering)
- **Interviewer:** Karina Budaeva (Product)
- **Date:** 2026-03-06
- **Duration:** 31m 36s
- **Context:** Internal discovery interview on AI-assisted product development workflow, from data model generation to API/UI specs, testing, and Jira planning.

## 1) Memorable Quote
> "The build stuff is super fast. The communication stuff is the part that's slow." (8:22)

## 2) Quick Facts
- Project began under extreme time pressure, with limited product/design bandwidth at kickoff.
- Early discovery and implementation happened in parallel, with engineering filling product-definition gaps.
- Cursor/ChatGPT were used to generate initial data models, API specs, and UI field-spec documents.
- AI accelerated manual authoring (types, specs, tests), but did not eliminate need for alignment reviews.
- Automated unit test generation is fast; end-to-end/manual QA process remains largely unchanged.
- Team relies on repo-level Cursor rules (`.cursor/rules`) to enforce design-system and coding constraints.

## 3) Insights
1. **AI compresses document-production time but not decision-making time.**  
   Generation is quick; cross-functional review and alignment still take multiple rounds.

2. **Upstream context quality determines downstream rework.**  
   Missing product context early caused "shooting in the dark" and avoidable changes later.

3. **Specs are becoming machine-executable work instructions.**  
   Traditional ticket granularity for humans is often too fine/slow; AI can decompose a larger feature quickly.

4. **Testing economics changed for unit tests, not for QA completeness.**  
   Writing tests is cheaper, but coverage gaps still require manual QA and/or stronger end-to-end automation.

5. **Process boundaries are blurring.**  
   The distinction between PRD, engineering plan, and ticket decomposition is less rigid in AI-assisted workflows.

## 4) Opportunities (Needs, not solutions)
1. **Need a repeatable "context handoff"** from product/design into AI-ready specs before major build phases.
2. **Need clear governance for ticket granularity** (human-level outcome vs. AI-execution sub-tasks).
3. **Need stronger quality gates** so fast generation does not propagate bad assumptions across API/UI layers.
4. **Need scalable validation patterns** to complement rapid unit-test generation with reliable integration confidence.
5. **Need shared planning language** that keeps product, design, and engineering synchronized in high-velocity delivery.

---

## Interview Unpacked

### A) Story Arc (What happened)
1. **Kickoff under pressure:** tight deadlines reduced upfront planning.
2. **AI-assisted scaffolding:** initial data models/specs generated quickly, then iterated via review meetings.
3. **Parallelization:** UI/API implementation advanced while requirements were still being refined.
4. **Friction exposed:** communication and alignment became dominant bottlenecks.
5. **Emerging model:** higher-level tickets for humans, fine-grained decomposition delegated to AI.

### B) Evidence Highlights
- **Deadline pressure:** "Such a quick turnaround... there wasn't much of a different choice." (0:14-0:44)
- **Parallel discovery/build:** engineering-driven data-model-first approach before final designs. (0:44-1:42)
- **Spec acceleration:** AI used for data model, types, API spec, UI form field mapping. (4:39-8:22, 12:14-14:36)
- **Main bottleneck:** communication/alignment now slower than code generation. (3:01-3:09, 8:22)
- **Testing split:** unit test generation easy; manual QA still needed. (8:56-10:35)
- **Ticketing shift:** human tickets should trend higher-level; AI handles detailed execution steps. (29:08-30:29)

### C) Jobs-to-be-Done Signals
- **Functional job:** Convert high-level feature intent into correct API/UI artifacts quickly.
- **Risk-reduction job:** Catch assumption errors early before they spread through generated outputs.
- **Organizational job:** Keep role boundaries clear while enabling AI-native execution speed.

### D) Opportunity Statements (for OST/backlog)
- When projects start with partial context, teams need a way to **establish minimum viable product context early** so generated artifacts are directionally correct.
- When AI can generate end-to-end specs rapidly, teams need a way to **insert lightweight product/design checkpoints** so rework is reduced.
- When unit tests are cheap, teams need a way to **raise confidence at integration level** so release readiness improves.
- When AI decomposes features into micro-tasks, teams need a way to **track human-level outcomes** without losing execution transparency.

### E) Follow-up Questions to Validate
1. What is the minimum required product/design input before engineering starts AI-assisted build?
2. Which checkpoints produce the highest rework reduction per minute invested?
3. What ticket shape gives best visibility for PMs while still enabling AI task decomposition?
4. Which QA gaps most frequently escape generated unit tests in this workflow?

### F) Potential Experiments
- Introduce a "pre-build context checklist" (problem, constraints, acceptance criteria, references).
- Pilot dual-layer Jira model: outcome-level tickets + linked AI execution logs/artifacts.
- Add mandatory midpoint review for AI-generated API/UI specs before implementation.
- Prioritize one high-value flow for end-to-end test automation to reduce manual QA bottlenecks.
