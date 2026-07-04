# Tsingz AI-Native Workflow Framework

> Build professional software for a world where AI is a first-class collaborator.

## Why

Traditional software was designed for human users.

Today, AI is becoming a core participant in professional work, yet most software still treats AI as an external assistant added on top of existing systems.

Tsingz AI-Native Workflow explores a different approach.

Instead of treating AI as a feature, we design software where humans and AI collaborate through structured workflows, explicit permissions, shared memory, and plug-and-play components.

## Vision

We believe the next generation of professional software should be:

- AI-native
- Human-in-the-loop
- Workflow-first
- Permission-aware
- Plug-and-play
- AI-friendly by design

AI should collaborate with professionals, not replace them.

## Tsingz Development Standard (TDS)

Tsingz follows the **Tsingz Development Standard (TDS)** — a documentation-first software engineering methodology designed for AI-native development.

Unlike traditional development where code gradually becomes the source of truth, TDS keeps architecture, documentation, interfaces, and tests as the primary project knowledge.

Every AI collaborator should understand the project before writing code.

The implementation should always follow the architecture, never redefine it.

## AI-Native Development

TDS organizes software into five first-class layers.

### 1. Documentation

Defines intent, architecture, design, business rules, and project knowledge.

### 2. Interfaces

Define contracts between modules.

Stable interfaces allow AI to work on isolated components without breaking the overall architecture.

### 3. Tests

Define expected behavior.

Tests become executable specifications rather than post-development validation.

Both unit tests and integration tests are considered first-class project artifacts.

### 4. Context for AI

Defines the attention layer for AI collaborators.

The `for-ai/` directory tells AI what to read first, where to focus, what each directory depends on, and which files must stay aligned.

The repository is treated as shared memory between humans and AI.

### 5. Implementation

Code is an implementation of the previous layers.

Implementation should remain replaceable.

The architecture should survive regardless of programming language, framework, or AI model.

## Core Principles

- Documentation First
- Architecture Before Code
- Interface Before Implementation
- Tests Define Behavior
- Context Guides AI Attention
- AI Reads Before It Writes
- Workflow First
- Human in the Loop
- Permission by Design
- Plug and Play
- AI Friendly

## Current Focus

The first implementation targets owner-operated professional software, including:

- Healthcare
- Legal
- Professional Services

These industries share a common challenge:

Highly specialized experts work across fragmented workflows with disconnected software.

## Repository Structure

```text
README.md
core-principles.md
ROADMAP.md

for-ai/
docs/
interfaces/
tests/
src/
examples/
scripts/
tds/
```

## Status

🚧 Early Architecture

The project is currently defining:

- Tsingz Development Standard (TDS)
- AI-Native Workflow Architecture
- AI collaboration context layer
- Interface Contracts
- Testing Strategy

Implementation will begin after the architecture is sufficiently defined.

## Long-Term Goal

Tsingz is not only a workflow framework.

It is an exploration of how professional software should be engineered in the AI era.

We believe software should no longer be designed only for humans.

Software should be designed for humans and AI working together.
