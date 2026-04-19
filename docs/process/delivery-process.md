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
5. Run retrospective at sprint/stage end.
6. Open sync PR per stage/increment.

## Quality & Governance (A-SPICE aligned intent)
- Requirements and scope are versioned in product docs.
- Work products are separated by concern (project/process/product/knowledge).
- Change impact is documented in traceability matrix before/after implementation.
- Retrospectives capture process and product improvements for the next cycle.

## Definition of Done
- Task acceptance criteria met.
- Backlog/task/traceability docs updated.
- Validation evidence recorded.
- Retrospective items captured (if sprint/stage end).
