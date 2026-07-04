# INTERFACES

Target:
  interfaces/

Purpose:
  Stable contracts between modules.

Read First:
  - interfaces/README.md
  - interfaces/workflow-interface.md
  - interfaces/api-conventions.md

Related:
  - docs/architecture.md
  - tests/unit/
  - src/

Depends On:
  - core-principles.md
  - docs/architecture.md

Consumes:
  - architecture
  - workflow model
  - permission model
  - plugin model

Produces:
  - module contracts
  - API conventions
  - compatibility boundaries

AI Goals:
  - Preserve compatibility
  - Avoid breaking contracts
  - Make contracts explicit

Do Not:
  - Rename public interfaces without updating docs and tests
  - Hide business logic in contracts
