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
4. Update traceability matrix (Feature -> Task -> Commit -> Impact/CR).
5. Run retrospective at sprint/phase end.
6. Open sync PR per phase/increment.

## Quality & Governance (A-SPICE aligned intent)
- Requirements and scope are versioned in product docs.
- Work products are separated by concern (project/process/product/knowledge).
- Change impact is documented in traceability matrix before/after implementation.
- Retrospectives capture process and product improvements for the next cycle.

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

## Definition of Done
- Task acceptance criteria met.
- Backlog/task/traceability docs updated.
- Validation evidence recorded.
- Retrospective items captured (if sprint/phase end).
