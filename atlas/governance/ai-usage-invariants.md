# AI Usage Invariants (Frozen)

This document defines non-negotiable constraints on how AI may be used within ONE.

These invariants exist to preserve determinism, accountability, and trust.

---

## AI_USAGE_PRIMACY_INVARIANT_V1

**Status:** FROZEN (ENFORCED)  
**Scope:** AI Design · System Architecture · Governance  
**Effective Date:** 2026-01-02

### Invariant

AI must never replace deterministic system self-knowledge with probabilistic inference.

### Allowed Use of AI

AI may be used to:
- author system descriptions
- label system components and relationships
- structure existing system knowledge
- maintain semantic representations over time
- activate explanations from deterministic sources

In all cases, AI output must resolve to inspectable, versioned artifacts.

### Prohibited Use of AI

AI must not:
- infer system meaning from opaque runtime state
- act as the system’s source of truth
- replace authored explanation with model interpretation
- embed non-deterministic reasoning at the core of system identity
- operate autonomously without reference to deterministic system knowledge

### Rationale

Inference without authored self-knowledge:
- breaks reproducibility
- collapses trust
- obscures responsibility
- reintroduces human burden through debugging and interpretation

A system must know itself first.
AI may only read, explain, or synthesise that knowledge.

Violation of this invariant constitutes a governance failure.
