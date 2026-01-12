# LEDGER

1. Purpose
   - Define the LEDGER machine scope and its intent.

2. Scope
   - Applies to /canonic/machine/os/ledger/.
   - Inherits from /canonic/machine/os/.

3. Constraints
   - The triad is required: CANON.md, VOCAB.md, README.md.
   - The LEDGER is the authoritative record for this scope.
   - Series artifacts follow the OS nomenclature rules.
   - Canon changes require explicit USER approval.
   - After approval, the AI stages and commits canon changes unless the USER overrides.
   - Canon commits are pushed immediately when a remote is configured.

4. Validation
   - Triad present.
   - LEDGER history exists and is readable.
   - Series artifacts match the `SPEC-###_stub` pattern.
   - Canon changes show approval and a coupled push when a remote exists.

5. Consumption notes
   - Instantiate from /canonic/templates.
   - Update the triad when this spec changes.
