GIT (/canonic/machine/os/git/)

inherits: /canonic/machine/os/

axioms:

1. ledger:
   git history is the authoritative ledger for this scope

2. canon-approval:
   canon change require explicit USER approval before commit

3. autocommit:
   after approval, the AI stage and commit canon change unless the USER override

4. commit-push coupling:
   canon commit push immediately when a remote is configured

5. maturity-autocommit:
   after approval, the AI may ask if canon maturity is true; if confirmed, autocommit is enabled

6. producer-consumer:
   AI commits producer artifacts (CANON, VOCAB) after USER approval
   USER commits consumer artifacts (episodes, prose)

7. vocab-closure:
   AI must verify VOCAB closure before producer commit
   missing content concepts must be added before commit
