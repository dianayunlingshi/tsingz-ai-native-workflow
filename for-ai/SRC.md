# SRC

Target:
  src/

Purpose:
  Implementation of documented architecture, interfaces, and tests.

Read First:
  - src/README.md

Related:
  - docs/
  - interfaces/
  - tests/

Depends On:
  - core-principles.md
  - docs/
  - interfaces/
  - tests/

Consumes:
  - documentation
  - interfaces
  - tests

Produces:
  - implementation

AI Goals:
  - Implement documented behavior
  - Keep code replaceable
  - Preserve module boundaries

Do Not:
  - Redefine architecture in code
  - Create hidden contracts
  - Modify behavior without tests
