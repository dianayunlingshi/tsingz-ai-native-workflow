# INTEGRATION_TESTS

Target:
  tests/integration/

Purpose:
  Cross-module behavior specifications.

Read First:
  - tests/integration/README.md

Related:
  - interfaces/
  - src/
  - docs/architecture.md

Depends On:
  - tests/README.md
  - interfaces/

Consumes:
  - module contracts
  - workflow behavior
  - plugin interactions

Produces:
  - integration specifications

AI Goals:
  - Validate collaboration across modules
  - Test workflow boundaries

Do Not:
  - Duplicate unit tests
  - Ignore documented workflow boundaries
