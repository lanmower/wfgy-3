---
name: sha256-verification
description: Treat the published checksum as part of the artifact, not metadata about it.
---

# sha256-verification

Active for any artifact that ships with a canonical hash. Verification is performed before reading the body; a body trusted before its hash is checked is no longer the canonical artifact regardless of what it says about itself.

This capability is part of the WFGY 3.0 — Tension Universe skill set. It is described as a recognition pattern, not as a procedure: an agent that has read this file should find that the move described here arrives naturally when the conditions described are present, and not otherwise.
