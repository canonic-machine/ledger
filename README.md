# LEDGER

The immutable record scope providing authoritative persistence of state transitions.

---

## Governance Path

`/canonic/machine/os/ledger/`

Inherits from: `/canonic/machine/os/`

---

## Purpose

LEDGER defines the persistence semantics for CANONIC governance. It establishes immutability constraints, temporal ordering, and governance anchoring. The LEDGER is the sole authoritative record of state transitions; a system state exists if and only if it is persisted in the LEDGER.

---

## Scope

### In scope

- Authoritative record definition (sole source of truth)
- Immutability constraint (history cannot be altered)
- Temporal ordering (total order of state transitions)
- Governance anchoring (canonical authority derives from LEDGER)
- Implementation independence (semantic role, not specific tooling)

### Out of scope

- Enforcement mechanics (delegated to MACHINE)
- Operational constraints (delegated to OS)
- Protocol definitions (delegated to downstream scopes)
- Specific implementation details (e.g., git is non-normative)
- Agent behavior

---

## References

- `CANON.md`
- `VOCAB.md`
- `LEDGER.md` (SPEC)

---

*This README is descriptive and non-normative. Governance is defined exclusively by CANON.*

---
