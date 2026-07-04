# Core Principles

This document is the primary source of truth for both human contributors and AI collaborators.

When conflicts arise between implementation and these principles, the principles take precedence.

## Foundational Principle

Architecture is the source of truth.

Code is one implementation.

## Repository as Shared Memory

The repository is the shared long-term memory between humans and AI collaborators.

Important project knowledge should live in versioned files, not only in conversation history.

## Documentation First

Documentation defines intent, architecture, design, and business rules.

AI collaborators should understand documentation before generating or modifying implementation.

## Interface Before Implementation

Interfaces define contracts.

Implementation must follow interfaces, not redefine them.

## Tests Define Behavior

Tests are executable specifications.

Behavior should be specified before implementation whenever possible.

## Context Guides AI Attention

The `for-ai/` directory guides AI collaborators toward the right files, dependencies, and attention focus.

AI should not read randomly or start from source code alone.

## AI Friendly

The system should be easy for AI to understand and maintain.

This means:

- clear module boundaries
- explicit interfaces
- simple data structures
- readable naming
- minimal hidden logic
- documented decisions

## Small Core, Flexible Edges

The core should stay small and stable.

Industry-specific features should live in plugins, workflows, adapters, or examples.

## Human in the Loop

AI assists.

Humans decide.

Professional judgment, accountability, and final approval remain with human participants.
