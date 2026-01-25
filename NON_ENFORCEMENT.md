# Non-Enforcement Declaration

ORIGINSEAL is a **sealing primitive**, not an enforcement mechanism.

## What ORIGINSEAL does

- Seals origin data
- Outputs deterministic origin hash
- Returns exit code indicating success/failure of sealing

## What ORIGINSEAL does NOT do

- Validate content authenticity
- Enforce provenance rules
- Verify origin claims
- Make trust decisions
- Block or allow actions

## Enforcement responsibility

Enforcement is the responsibility of:
- The calling system (CICULLIS, MK10-PRO, etc.)
- The policy layer above ORIGINSEAL
- Human decision-makers

## Liability

ORIGINSEAL output indicates "this was sealed" — nothing more.
Sealing does not imply authenticity, correctness, or validity.
