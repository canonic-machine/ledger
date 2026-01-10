# VOCAB (/canonic/machine/git/)

## Core terms

### GIT
The git machine scope.

### git
The version control system used as the ledger.

### USER
The human governor who authorizes canon changes.

### AI
The agent that proposes and applies canon changes after approval.

### CANON
The axioms for a scope.

### VOCAB
The terms for a scope; it defines the terms used by CANON and itself.

### README
The README for a scope.

### scope
The area governed by a CANON and its triad.

### triad
The required governance artifacts for a scope: CANON.md, VOCAB.md, README.md.

### CANON.md
The CANON file for a scope.

### VOCAB.md
The VOCAB file for a scope.

### README.md
The README file for a scope.

### axioms
The CANON statements for a scope.

### inheritance
The declared linkage from a scope to its parent scope.

### inherits
The declared parent scope for a CANON.

### declares
To state an inheritance linkage in CANON.

### contains
To hold governance artifacts within a scope.

### inherited
Axioms taken from a parent scope.

### final
The property that inherited axioms cannot be overridden.

### cannot
A statement of prohibition.

### overridden
A final axiom that is replaced in a downstream scope.

### introspection
The requirement that VOCAB defines terms used by CANON and itself.

### defines
To state meanings in VOCAB.

### term
A word or phrase used by CANON that must be defined in VOCAB.

### used
Employed in CANON statements.

### every
Without exception.

### itself
The same artifact referring to itself.

### ledger
The authoritative record of changes for this scope.

### history
The ordered record of commits in a repository.

### repository
The git store for a scope.

### commit
A recorded change in git history.

### signal
A non-authoritative output describing evaluation.

### series
A set of related artifacts ordered by a numeric prefix.

### artifact
A file or record governed by a scope.

### non-triad artifact
An artifact not in the triad.

### upper case
Letters in A to Z.

### lower case
Letters in a to z.

### SPEC
The spec identifier in a series name.

### spec artifact
The specification artifact for a series.

### order
The numeric arrangement of a series.

### static
Fixed and not changing.

### consecutive
Without gaps in numeric order.

### generative
Created in sequence as artifacts are produced.

### reserved
Kept aside for a specific use.

### govern
To set constraints for a scope.

### governed
Constrained by a governing scope.

### episodes
Governed session records in a scope.

### templates
Governed template artifacts in a scope.

### PROTOCOLS
The protocols artifact for a scope.

### canon change
A modification to a scope's canon artifacts.

### canon-approval
The explicit USER permission required before a canon change is committed.

### autocommit
Automated commit by the AI after canon approval, unless the USER overrides it.

### commit-push coupling
Requirement that a canon commit is pushed immediately when a remote is configured.

### remote
A configured git endpoint for pushing commits.

### override
An explicit USER instruction to prevent autocommit.

### nomenclature
The naming rule applied to a series.

### prefix
The numeric lead segment of a series name.

### three-digit
A numeric prefix padded to three digits.

### numeric
Composed of digits.

### stub
The descriptive tail segment of a series name.

### lowercase
Letters in a to z.

### kebab-case
Lowercase words separated by hyphens.

### ordered
Arranged by the numeric prefix.

End of VOCAB.
