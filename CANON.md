GIT (/canonic/machine/os/git/)

inherits: /canonic/machine/os/

axioms:

1. ledger:
   git history is the authoritative ledger for this scope

2. canon-approval:
   canon changes require explicit USER approval before commit

3. autocommit:
   after approval, the AI stages and commits canon changes unless the USER overrides

4. commit-push coupling:
   canon commits are pushed immediately when a remote is configured
