# Memory Architecture — Design Rationale

This document describes the **architectural intent and reasoning** behind memory design decisions in ONE.

It is not a full specification of current implementation, nor a guarantee of system behaviour.

Promoted architectural representations and inspectable memory behaviour are documented in the System Atlas.

---

## Design constraints

Memory architecture in ONE is shaped by several non-negotiable constraints:

- the system evolves continuously
- not all data can or should be retained
- human context degrades over time
- explainability must survive without live execution

These constraints rule out naive accumulation or purely model-internal memory strategies.

---

## Intentional separation of concerns

Memory in ONE is designed to separate:

- **storage** from **interpretation**
- **retrieval** from **authority**
- **representation** from **truth claims**

Embeddings and retrieval mechanisms are treated as *lenses*, not sources of authority.
Authority remains external and explicit.

---

## Preference for inspectable memory surfaces

Architectural decisions favour memory representations that can be:

- inspected without execution
- reasoned about without prompt context
- bounded by contracts and scope
- reviewed independently of the builder

This preference influences choices around:
- data lifecycle
- representation formats
- promotion and freezing discipline

---

## Avoided approaches

The architecture intentionally avoids:

- unbounded memory accumulation
- opaque model-internal state as the sole memory
- implicit context dependency
- memory that cannot be audited or constrained

These approaches may optimise short-term capability but degrade long-term coherence.

---

## Relationship to promoted architecture

This document explains *why* certain architectural patterns were chosen.

It does not assert that:
- all patterns are fully implemented
- all memory behaviour is stable
- all design goals are currently met

Authoritative architectural representations live in the System Atlas.

---

Status: Architectural rationale. Non-authoritative.
