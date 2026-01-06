# Architecture Overview

This page describes the **high-level architecture** of ONE.

The architecture is intentionally simple.
Its purpose is to make structure, boundaries, and responsibility legible — not to optimise for novelty or density.

---

## Architectural principles

The architecture of ONE is governed by the following principles:

- **Explicit separation of concerns**
  Exploration, execution, governance, and evidence are deliberately isolated.

- **Authority outside models**
  Models and tools do not define behaviour; they operate within externally defined constraints.

- **Fail-closed behaviour**
  Where structure or certainty is insufficient, workflows must abstain or terminate.

- **Inspectable surfaces**
  Every promoted behaviour has a corresponding documentation or evidence surface.

---

## High-level components

### 1. System Atlas
**Role:** Canonical truth surface

- Documents what exists, what is governed, and what is promoted
- Defines authority, orientation, capabilities, and boundaries
- Serves as the public inspection layer

_No runtime behaviour._

---

### 2. Workflow Layer
**Role:** Execution and exploration structures

- Reference workflow skeletons
- Exploration paths using frontier models
- Execution paths using governed, bounded workflows

_Execution is constrained by contracts and validation._

---

### 3. Governance Layer
**Role:** Constraint and promotion enforcement

- Contracts, invariants, and termination rules
- Capability promotion discipline
- Drift prevention and freeze boundaries

_Governance constrains behaviour; it does not execute it._

---

### 4. Diagnostics & Evidence
**Role:** Evaluation and verification

- Coherence and drift evaluation
- Failure mode inspection
- Evidence packs and case studies

_Diagnostics inform promotion; they do not override governance._

---

## Relationship flow (conceptual)

Orientation & Authority
↓
Governance
↓
Workflow Layer
↓
Diagnostics & Evidence
↓
Promotion into Atlas


This flow is directional.
No component may bypass governance or self-promote.

---

## External references

The architecture intentionally links outward to specialist repositories and artifacts:

- Contract and governance definitions
- Workflow implementations
- Diagnostic tooling
- Evidence packs and case studies

The Atlas does not duplicate these materials; it references promoted sources of truth.

---

## Architectural boundary

ONE is not:
- a monolithic runtime system,
- an autonomous agent framework,
- or a self-modifying intelligence.

It is a **governed system-of-systems** designed to remain explainable under real-world constraints.
