# LEDGER

## 1. Purpose

Define the LEDGER scope as the authoritative, immutable record of state transitions for a CANONIC system.

---

## 2. Scope

- Applies to `/canonic/machine/os/ledger/`.
- Inherits from `/canonic/machine/os/`.

---

## 3. Constraints

### 3.1 Triad

The LEDGER scope **MUST** contain the following artifacts:

- `CANON.md`
- `VOCAB.md`
- `README.md`

Absence of any triad artifact renders the scope invalid.

---

### 3.2 Authority

The LEDGER is the sole authoritative record of state transitions for this scope.

A system state exists if and only if it is persisted in the LEDGER.

---

### 3.3 Immutability

Persisted LEDGER history **MUST NOT** be altered.

Corrections, reversals, and amendments **MUST** occur only through the creation of new persisted states.

---

### 3.4 Ordering

The LEDGER **MUST** preserve an authoritative ordering of persisted state transitions.

The ordering defines the execution history of the system.

---

### 3.5 Implementation independence

This specification defines the LEDGER as a semantic role.

Specific implementations (e.g., git) are non-normative and may vary without affecting validity.

---

## 4. Validation

A LEDGER scope is valid if and only if:

- The triad is present.
- Persisted history exists.
- History is append-only and ordered.

No assumptions are made about how states are proposed, approved, or persisted.

---

## 5. Consumption notes

- Protocols governing proposal, approval, automation, or agent behavior are defined in downstream MACHINE or AGENT scopes.
- This specification intentionally excludes workflow, tooling, and role assignment.

---

**This SPEC defines the LEDGER scope.**
**Validity is determined solely by persistence, immutability, and ordering of history.**

---
