# Staged Project Setup (MVP-first)

## Delivery Principle
- Build a **Minimal Valuable Product (MVP)** end-to-end first.
- Deliver in **increments (sprints)** with one sync PR per stage/increment.
- Keep each increment independently reviewable and traceable.

## Stage Plan

| Stage | Objective | Main Output | Sync Point |
|---|---|---|---|
| Stage 0 - Foundation | Create aligned system understanding and delivery structure | System understanding, PoC decisions, backlog, traceability setup | PR: `stage-0-foundation` |
| Stage 1 - MVP E2E | End-to-end vertical slice from Android service to browser status view | Running MVP with core telemetry flow | PR: `stage-1-mvp-e2e` |
| Stage 2 - Reliability & Security | Harden runtime behavior and transport/security controls | Improved resilience, permission handling, security checks | PR: `stage-2-hardening` |
| Stage 3 - Operational Readiness | Improve diagnostics, release readiness, and maintainability | Logging/diagnostics, release guidance, quality evidence | PR: `stage-3-operational-readiness` |

## Sprint Cadence per Stage
1. Sprint planning from prioritized backlog
2. Agent execution on scoped tasks
3. Daily progress updates in chronological log
4. End-of-sprint demo + retrospective
5. Stage sync PR with traceability updates
