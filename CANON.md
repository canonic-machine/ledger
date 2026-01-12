# LEDGER (/canonic/machine/os/ledger)

inherits: /canonic/machine/os/

---

## Axioms

### 1. Authoritative record

The LEDGER is the sole authoritative record of state transitions for this scope.

A system state exists if and only if it is persisted in the LEDGER.

---

### 2. Immutability

Persisted LEDGER history **MUST NOT** be altered.

Corrections, reversals, and amendments **MUST** occur only through the creation of new states.

---

### 3. Temporal ordering

The LEDGER **MUST** preserve a total order of persisted state transitions.

The order of persistence defines the authoritative execution history.

---

### 4. Governance anchoring

Canonical artifacts derive authority exclusively from the LEDGER.

Artifacts not persisted in the LEDGER have no canonical standing.

---

### 5. Implementation independence

This CANON defines the LEDGER as a semantic role.

Specific implementations (e.g., git) are non-normative and may vary without affecting validity.

---

**This CANON defines validity for the LEDGER scope.**
**Protocols, automation, and agent behavior are defined in downstream MACHINE and AGENT layers.**

---
