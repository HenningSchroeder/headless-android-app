# Expertise / Skills / Technology & Tool Knowledge

## Agent Collaboration Knowledge
- Keep tasks small and context-clean for parallel agent execution.
- Always include feature/task IDs in task prompts and commit messages.
- Use one sync PR per phase/increment to preserve auditability.
- Treat agent-local memory as non-authoritative/ephemeral; persist shared project knowledge in repository docs.
- Keep handover notes tool-agnostic so heterogeneous agents (Copilot, Claude, OpenCode, PI, etc.) can continue work without hidden context.

## Technical Knowledge Baseline
- Target system: Android app (headless/foreground service) + browser client.
- Preferred real-time update mechanism: WebSocket (SSE as fallback candidate).
- Security principle: minimum data collection, explicit consent, transport hardening.

## Process Knowledge
- Canonical process baseline requirements for all increments:
  - Update traceability matrix for planned work and implemented change impact.
  - Update chronological progress log in every increment.
  - Use progress log entries to capture assumption -> step -> observation -> reaction/decision cycles, including failed attempts.
  - Run retrospective at sprint and phase boundaries.
  - Ensure verification/validation evidence is captured per task.
- Call out outdated/unfounded/suboptimal assumptions and propose alternatives.
- Project/process docs should reference this baseline and only add explicit tailoring where needed.
