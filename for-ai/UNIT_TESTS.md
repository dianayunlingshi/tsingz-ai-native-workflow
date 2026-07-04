# UNIT_TESTS

Target:
  tests/unit/

Purpose:
  Unit-level behavior specifications for isolated modules.

Read First:
  - tests/unit/README.md

Related:
  - interfaces/
  - src/

Depends On:
  - tests/README.md
  - interfaces/

Consumes:
  - module contracts
  - isolated expected behavior

Produces:
  - unit specifications

AI Goals:
  - Validate isolated behavior
  - Keep tests focused and small

Do Not:
  - Depend on unrelated modules
  - Test cross-module workflows here
