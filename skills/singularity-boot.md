---
name: singularity-boot
description: Boot the Singularity Demo only after verifying the canonical SHA256.
---

# singularity-boot

Active when a session loads the Singularity TXT pack. The checksum is verified before any module is allowed to execute. On match the canonical boot egg is emitted and the session is marked verified. On mismatch the session continues in unverified mode and every later claim about canonical results is downgraded.

This capability is part of the WFGY 3.0 — Tension Universe skill set. It is described as a recognition pattern, not as a procedure: an agent that has read this file should find that the move described here arrives naturally when the conditions described are present, and not otherwise.
