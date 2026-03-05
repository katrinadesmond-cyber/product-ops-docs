# 07. Team Learnings and Priorities (Mar 2026)

## Why this document exists

Capture key learnings from product team interviews and convert them into clear product operations priorities, standards, and experiments.

## Key learnings from teams

### 1) Speed has improved, fundamentals are slipping
- AI-assisted delivery is making teams ship faster.
- A recurring risk is shipping the wrong things faster.
- Teams need stronger discovery and assumption-testing discipline.

### 2) Cursor needs deeper product/system context
- Current AI workflows do not consistently know:
  - backend system structures and constraints,
  - existing design system standards,
  - team delivery processes and operating patterns.
- Without this context, generated output tends to create net-new patterns rather than reuse internal foundations.

### 3) Design-to-dev handoff is still too manual
- Current process depends heavily on manual interpretation.
- Storybook code-connect and design system linkage are not yet established.
- This creates drift between design intent and implementation output.

### 4) Component ownership is distributed, not centralized
- No dedicated component team currently owns reusable UI primitives.
- Product teams create components in-flight for delivery needs.
- Reusability and generic design decisions are inconsistent.

### 5) Skills are not yet codified as a shared operating asset
- Valuable knowledge exists across Confluence and in individuals' heads.
- Teams need a shared skills repository to:
  - scale expertise,
  - reduce repetitive guidance overhead,
  - support teams without dedicated designers.

### 6) Rules vs skills are not clearly separated in practice
- Teams need explicit guidance on:
  - what a **rule** is (non-negotiable constraint),
  - what a **skill** is (reusable capability/playbook).
- Product Operations should own standards and governance for both.

### 7) Team workflows need explicit checkpoints/gates
- Brand Pages and similar teams surfaced the need for stage checkpoints.
- UI-heavy and backend-heavy workstreams need tailored gates.
- Gates should protect discovery quality without creating unnecessary drag.

## Most common traps observed

- Anchoring in solution space too early.
- HIPPO-driven decision cycles overriding evidence.
- Hype-driven urgency replacing customer problem clarity.
- Polished AI prototypes masking evidence gaps.

## Operating implications

1. **Discovery recommitment is essential**
   - Continuous discovery must be enforced in cadence and quality checks.

2. **Show-your-work must become a default behavior**
   - Teams should document evidence, assumptions, tradeoffs, and unknowns.

3. **Context infrastructure is now a product ops priority**
   - Backend, design system, and process knowledge should be codified for AI use.

4. **Governance must scale with AI acceleration**
   - Faster execution requires stronger pre-commit checkpoints and post-launch learning loops.

## Priority actions (next 90 days)

### Priority A: Codify knowledge into reusable skills
- Stand up a shared "skills repository" for product, design, and engineering workflows.
- Define contribution and review process.
- Add access/permission model for skill editing.

### Priority B: Build Cursor context packs
- Create source-verified context bundles for:
  - backend architecture and service boundaries,
  - design system foundations and component usage,
  - process standards and product lifecycle checkpoints.

### Priority C: Define rules vs skills governance
- Publish rule and skill definitions with examples.
- Clarify ownership:
  - Product Ops = standards and governance,
  - domain leads = technical/design content stewardship.

### Priority D: Implement checkpoint workflows
- Introduce stage gates for UI and backend pathways.
- Keep gates lightweight but non-optional for high-risk decisions.

### Priority E: Run design-to-dev experiments
- Test Storybook code-connect and design system integration assumptions.
- Evaluate toolchain constraints (for example, Figma limitations and alternatives).
- Measure impact on handoff speed, quality, and rework.

## Working definition: "Orchard"

For this framework, **Orchard** is defined as:

> A curated, shared library of reusable skills and context assets that can be used across teams and AI agents.

Core qualities of an Orchard:
- reusable across multiple initiatives;
- source-linked and versioned;
- governed with clear ownership;
- continuously improved from real delivery learnings.

## Success measures for these priorities

- Increase in initiatives with explicit evidence links and assumptions.
- Reduction in duplicate/one-off UI component creation.
- Improved design-to-dev handoff cycle time.
- Higher reuse rate of shared skills across teams.
- Reduced rework due to late discovery findings.
