# Delivery Process (Agent-First, Assessment-Ready)

## Agent-First Execution Model
- Human role: monitoring, guidance, acceptance decisions.
- Agent roles:
  - Copilot/Claude: implementation, documentation, validation, traceability updates.
  - Sub-agents: independent scoped tasks in parallel with clean context boundaries.
- Every task must include:
  1. Input scope
  2. Expected output
  3. Traceability IDs (feature/task)
  4. Validation evidence

## Workflow
1. Confirm or update system understanding.
2. Select sprint scope from prioritized backlog.
3. Execute tasks in parallel where independent.
4. Apply canonical process baseline requirements from `docs/knowledge/agent-and-technology-knowledge.md` (traceability updates, progress logging, retrospective cadence, and validation evidence), and record any project-specific tailoring here.
5. Open sync PR per phase/increment.

## Quality & Governance (A-SPICE aligned intent)
- Requirements and scope are versioned in product docs.
- Work products are separated by concern (project/process/product/knowledge).
- Change impact is documented in traceability matrix before/after implementation.
- Retrospectives capture process and product improvements for the next cycle.

## V-Model Alignment (tailored for this project)
- Left side (do the right thing): clarify scope, assumptions, architecture, and acceptance criteria before implementation.
- Right side (do it right): execute verification evidence per task and validate feature behavior against agreed use-cases.
- Pragmatic tailoring: keep artifacts lightweight and phase-appropriate; increase rigor at phase gates and release readiness.
- Traceability link: each planned feature/task should be verifiable and mapped to evidence in the progress log/traceability matrix.

## A-SPICE Tailoring (explicit and intentional)
A-SPICE requires capability evidence, not fixed document naming/partitioning. This setup is tailored to keep only evidence needed at the current maturity level.

### Included now (needed immediately)
- Bidirectional traceability for planned work and implemented change impact.
- Managed requirements/backlog with prioritized increments.
- Project monitoring via chronological progress and sprint/phase retrospectives.
- Verification evidence per task (defined in execution tracking).

### Deferred for now (not necessary at current phase maturity)
- Full organizational process asset library and broad role catalog: deferred until team scale requires it.
- Heavy-weight measurement baselines and statistical process control: deferred until stable implementation throughput exists.
- Formal supplier/dependency governance packages: deferred until external suppliers or critical third-party chains are introduced.

Deferrals are reviewed at each phase gate and promoted when project risk/complexity increases.

## Architecture & Decision Records
- Use ADRs for significant technical/process decisions and record context, options, decision, and consequences.
- Start from `docs/process/adr-template.md` and reference accepted ADRs from relevant backlog/tasks.
- Maintain C4 architecture views in `docs/product/architecture-c4.md` and update when architecture-relevant changes are introduced.
- Default diagram format: Markdown + Mermaid for agent portability; use PlantUML when it is a better fit for a specific diagram.

## Definition of Done (DoD)
- Task acceptance criteria met.
- Backlog/task/traceability docs updated.
- Validation evidence recorded.
- Retrospective items captured (if sprint/phase end).
