# Explainability — Design Lens

Explainability is treated in ONE as a **design priority**, not an emergent property.

This document describes the *philosophy and intent* behind explainability decisions.
It does not assert that explainability is fully achieved or guaranteed in all system behaviour.

Evidence of explainability under real constraints is documented separately in the System Atlas.

---

## Design motivation

As systems grow in complexity, they often become:

- difficult to reason about without narrative reconstruction
- dependent on personal memory or undocumented context
- explainable only by the original builder

ONE was designed to resist these failure modes.

Explainability is prioritised not for transparency theater, but to ensure that:

- system behaviour can be reasoned about without execution
- understanding survives time gaps and personnel change
- claims can be inspected rather than justified

---

## Structural preference over narrative explanation

ONE favours **structural explainability** over retrospective explanation.

This means design decisions bias toward:

- explicit boundaries over implicit conventions
- inspectable artifacts over logs or dashboards
- deterministic representations over probabilistic explanations
- separation between runtime behaviour and explanatory surfaces

Narrative explanation is treated as fragile under load.
Structure is treated as durable.

---

## Limits and trade-offs

Explainability is intentionally scoped.

The system design accepts that:

- not all runtime behaviour can be exhaustively explained
- model internals remain opaque
- human judgment remains necessary at boundaries

Explainability is pursued where it can be **stabilised**, not where it would require invasive instrumentation or speculative claims.

---

## Relationship to promoted evidence

This document does not claim that ONE *is* explainable in all respects.

Demonstrations of explainability under real constraints are promoted, reviewed, and bounded in the **System Atlas case studies**.

This document exists to explain **why explainability matters**, not to prove that it has been achieved.

---

Status: Design philosophy. Non-authoritative.
