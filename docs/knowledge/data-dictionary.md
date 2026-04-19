# Data Dictionary (Starter)

This dictionary defines key terms used across business unit, project, program, and expert knowledge artifacts.

## Business Unit Terms
- **MVP (Minimum Viable Product)**: The smallest end-to-end product slice that delivers real user value and can be validated.
- **Value Slice**: A coherent scope unit that delivers measurable stakeholder/user value.
- **Hardening**: Work focused on reliability, security, compliance, and release readiness rather than net-new scope.

## Project Terms
- **Phase**: A major delivery period in the lifecycle with a clear objective and review checkpoint.
- **Increment**: A bounded delivery unit within or across phases, usually synchronized via one PR.
- **Sprint**: Short execution cycle in the feature-sprint phase, sized to roughly one day token budget and typically 1-2 sensible features/tasks.
- **DoD (Definition of Done)**: Minimum completion criteria required before accepting work; see `docs/process/delivery-process.md`.
- **Traceability Matrix**: Mapping of Feature -> Task -> Commit -> Impact Analysis -> Change Request/Decision.

## Program Terms
- **E2E (End-to-End)**: A slice that validates the full flow across all involved components/interfaces.
- **Infra E2E Slice**: Early end-to-end validation focused on infrastructure and runtime path viability.
- **Sync PR**: Coordination pull request used as an auditable integration/review point per increment.
- **CR (Change Request / Decision)**: Explicit record of change rationale and decision impact.
- **V-Model**: Development/assurance model linking definition work ("doing the right thing") with verification work ("doing it right").

## Expert Knowledge Terms
- **A-SPICE**: Automotive SPICE capability framework; requires evidence of capability, not fixed naming/partitioning of documents.
- **ADR (Architecture Decision Record)**: Structured record of architecture/process decisions, alternatives, rationale, and consequences.
- **C4 Model**: Architecture model using System Context, Container, Component, and (optional) Code views.
- **PoC (Proof of Concept)**: Targeted experiment to reduce uncertainty before broader implementation.
- **Assumption -> Step -> Observation -> Reaction/Decision Cycle**: Labbook-style evidence loop used in the progress log, including failures.
- **Heterogeneous Agent Handover**: Tool-agnostic context transfer so different agents can continue work without hidden assumptions.
