# System Understanding Before Coding

## Problem Scope
Build a headless Android app that captures allowed local device/network status and streams status data to a browser endpoint in the same network, with clear consent and security boundaries.

## Baseline Architecture (initial)
1. Android foreground service for controlled data collection
2. Permission and runtime-state manager
3. Communication module (preferred: WebSocket)
4. Browser status UI with connection/health indicators
5. Logging and diagnostics flow

## Assumptions to Validate
- A headless/foreground model is acceptable for Android background restrictions.
- Metadata-only transfer is enough for MVP (no raw image/audio in MVP).
- Local-network trust model still requires transport hardening.

## Open Questions (do not guess)
1. Exact data payload contract (fields, frequency, retention)?
2. Required Android API level target?
3. Must browser UI run offline-only or can it rely on hosted assets?
4. Is encrypted transport mandatory in MVP or Stage 2?

## Proof of Concept (PoC) Gates
- PoC-1: foreground service lifecycle + reconnect behavior
- PoC-2: permission denial/revocation handling
- PoC-3: browser live update channel reliability

Only proceed to full implementation when PoC outcomes are documented and accepted.
