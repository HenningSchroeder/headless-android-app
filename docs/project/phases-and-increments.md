# Phase-Based Project Setup (MVP-first)

## Delivery Principle
- Build a **Minimum Viable Product (MVP)** end-to-end first.
- Deliver in **increments (sprints)** with one sync PR per phase/increment.
- Keep each increment independently reviewable and traceable.

## Phase Plan (industry-aligned, tailored)

| Phase | Objective | Main Output | Sync Point |
|---|---|---|---|
| Phase 1 - System Foundation | Baseline requirements, architecture understanding, and PoC gates | System understanding, PoC decisions, traceability baseline | PR: `phase-1-foundation` |
| Phase 2 - Infrastructure E2E Slice | Establish technical backbone and minimal end-to-end connection path | Infra E2E connectivity and basic observability | PR: `phase-2-infra-e2e` |
| Phase 3 - MVP E2E | Deliver first user-valuable end-to-end flow | Running MVP with accepted scope boundaries | PR: `phase-3-mvp-e2e` |
| Phase 4 - Feature Sprints | Add prioritized capabilities incrementally | Feature increments with validated acceptance criteria | PR: `phase-4-feature-sprints` |
| Phase 5 - Hardening & Readiness | Improve reliability, security, diagnostics, and release readiness | Hardened delivery evidence and go-live package | PR: `phase-5-readiness` |

## Phase Behavior Model
- **Phases 1-3 and 5 are stage-like**: primarily gate-driven and sequential (more waterfall-aligned).
- **Phase 4 is iterative**: it contains the looping agile feature sprints.

## Sprint Cadence per Phase
1. Sprint planning from prioritized backlog (limit sprint scope to 1 day of token budget and typically 1-2 sensible features)
2. Agent execution on scoped tasks
3. Daily progress updates in chronological log
4. End-of-sprint demo + retrospective
5. Phase/increment sync PR with traceability updates
