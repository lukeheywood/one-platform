# North Star — Semantic Orientation (Frozen)

This document defines the fixed design constraints that govern how AI is used,
how systems are structured, and how coherence is maintained in ONE.

These constraints are not aspirational.
They are enforced to reduce ambiguity, prevent drift, and ensure systems remain
explainable under real operational load.

---

## NORTH_STAR_SEMANTIC_ORIENTATION_V1

**Status:** FROZEN (CANONICAL)  
**Scope:** System Design · AI Usage · Representation  
**Effective Date:** 2026-01-02

### Canonical Statement

ONE is oriented around coherence.

Coherence is defined as a system’s ability to deterministically know and explain:
- what it is
- why it exists
- how it works
- what ran
- what changed
- what is assumed
- what is unknown

This self-knowledge must exist **before** AI is applied.

AI does not create coherence.
AI may only amplify a system that already knows itself.

### Implications

- System meaning must not live primarily in people.
- Explanation must not depend on memory, authority, or tribal knowledge.
- System truth must be inspectable, reproducible, and explicit.
- Capability is secondary to explainability.

This orientation governs all design, integration, and evaluation decisions in ONE.

Deviation from this orientation constitutes **coherence drift**.
