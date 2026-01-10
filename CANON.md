GIT (/canonic/machine/git/)

inherits: /canonic/machine/

axioms:

1. triad:
   a scope contains CANON.md, VOCAB.md, README.md

2. inheritance:
   every CANON.md declares the scope it inherits from
   inherited axioms are final and cannot be overridden

3. introspection:
   VOCAB defines every term used by this CANON and itself

4. ledger:
   git history is the authoritative ledger for this scope

5. nomenclature:
   non-triad artifacts use `###-SPEC_stub` naming
   the prefix is a three-digit numeric prefix
   the prefix order is static in CANON
   artifacts are consecutive and generative
   the `000` prefix is reserved for the SPEC artifact itself
   the stub is lowercase kebab-case

6. canon-approval:
   canon changes require explicit USER approval before commit

7. autocommit:
   after approval, the AI stages and commits canon changes unless the USER overrides

8. commit-push coupling:
   canon commits are pushed immediately when a remote is configured
