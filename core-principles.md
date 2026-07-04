# Core Principles

## Purpose

This document defines the core principles of Tsingz AI-Native Workflow.

It is written for both humans and AI collaborators.

Tsingz treats documentation as long-term project memory.  
AI should be able to read, understand, and follow these principles when designing, generating, reviewing, or modifying the system.

## Philosophy

Traditional software was designed around human users.

Tsingz is designed for a world where humans and AI work together as collaborators inside structured workflows.

AI is not an external assistant added on top of software.

AI is a first-class participant in the software architecture.

## Principles

### 1. Workflow First

Every meaningful action belongs to a workflow.

A workflow defines context, responsibility, state, permission, and next steps.

### 2. Human in the Loop

AI assists.  
Humans decide.

Professional judgment, accountability, and final approval remain with human participants.

### 3. Permission by Design

Data sharing must be explicit.

Participants should know what data is used, who can access it, and for what purpose.

### 4. Plug and Play

Capabilities should be built as independent modules or plugins.

The system should be composed, extended, and replaced without rewriting the whole application.

### 5. AI Friendly

The system should be easy for AI to understand and maintain.

This means:

- clear module boundaries
- explicit interfaces
- simple data structures
- readable naming
- minimal hidden logic
- documented decisions

### 6. Small Core, Flexible Edges

The core should stay small and stable.

Industry-specific features should live in plugins, workflows, or adapters.

## Long-Term Vision

Tsingz aims to build AI-native workflow infrastructure for professional software.

The goal is not to replace professionals, but to help humans and AI collaborate inside systems that are structured, auditable, permission-aware, and easy to evolve.
