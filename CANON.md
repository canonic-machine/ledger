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
   series artifacts use `###-stub` naming
   the prefix is a three-digit numeric prefix
   series artifacts are ordered by the numeric prefix
   the stub is lowercase kebab-case
