# GIT

1. Purpose
   - Define the GIT machine scope and its intent.

2. Scope
   - Applies to /canonic/machine/git/.
   - Inherits from /canonic/machine/.

3. Constraints
   - The triad is required: CANON.md, VOCAB.md, README.md.
   - Git history is the authoritative ledger for this scope.
   - Series artifacts follow the machine nomenclature rules.
   - Canon changes require explicit USER approval.
   - After approval, the AI stages and commits canon changes unless the USER overrides.
   - Canon commits are pushed immediately when a remote is configured.

4. Validation
   - Triad present.
   - Git history exists and is readable.
   - Series artifacts match the `###-stub` pattern.
   - Canon changes show approval and a coupled push when a remote exists.

5. Consumption notes
   - Instantiate from /canonic/templates.
   - Update the triad when this spec changes.
