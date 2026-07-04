# TESTS

Target:
  tests/

Purpose:
  Behavioral specifications for the system.

Read First:
  - tests/README.md
  - tests/unit/README.md
  - tests/integration/README.md

Related:
  - interfaces/
  - src/
  - docs/detailed-design.md

Depends On:
  - core-principles.md
  - interfaces/

Consumes:
  - interfaces
  - design docs
  - expected behavior

Produces:
  - executable specifications
  - regression protection

AI Goals:
  - Treat tests as specifications
  - Keep unit and integration concerns separate

Do Not:
  - Treat tests as afterthought
  - Change implementation without updating expected behavior
