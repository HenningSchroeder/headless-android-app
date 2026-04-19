# Product Backlog (Feature Level + Execution Task Level)

## Feature Backlog
| Feature ID | Feature | Phase Target | Priority | Status |
|---|---|---|---|---|
| F-001 | Secure metadata collection boundaries | Phase 3 | High | Planned |
| F-002 | Android headless service lifecycle | Phase 3 | High | Planned |
| F-003 | Live status transport to browser | Phase 3 | High | Planned |
| F-004 | Browser live status dashboard | Phase 4 | Medium | Planned |
| F-005 | Permission/restriction resilience | Phase 5 | High | Planned |
| F-006 | Diagnostics and operations support | Phase 5 | Medium | Planned |

## Execution Task Tracking
| Task ID | Feature ID | Task | Sprint | Status | Validation |
|---|---|---|---|---|---|
| T-001 | F-001 | Define allowed telemetry schema and exclusions | P1-S1 | Planned | Document review |
| T-002 | F-002 | Create foreground-service PoC | P1-S2 | Planned | PoC evidence |
| T-003 | F-003 | Implement transport PoC (WebSocket/SSE selection) | P2-S1 | Planned | PoC evidence |
| T-004 | F-004 | Define browser status UX and error states | P2-S2 | Planned | Design review |
| T-005 | F-002 | Implement MVP service lifecycle | P3-S1 | Planned | Integration test |
| T-006 | F-003 | Implement E2E status push | P3-S2 | Planned | E2E test |

Sprint policy: use the canonical sprint sizing rule in `docs/knowledge/data-dictionary.md` and document any sprint-specific tailoring explicitly.
