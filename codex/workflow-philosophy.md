# Workflow Philosophy

This document captures the **philosophy and assumptions** guiding workflow design in ONE.

It reflects how the system is *intended* to be used and shaped, not rules that are enforced.

Governance, validation, and enforcement live elsewhere.

---

## Human-first sequencing

ONE assumes that workflows exist to support human intent, not replace it.

Design choices favour:

- clarity over automation
- interruption over silent failure
- abstention over forced output
- legibility over optimisation

Workflows are treated as *assistive structures*, not autonomous agents.

---

## Explicit boundaries over implicit magic

Workflows are designed to expose:

- where decisions are made
- where uncertainty exists
- where authority stops

Implicit behaviour is considered a liability under load.
Explicit boundaries are preferred, even when they reduce convenience.

---

## Failure as a first-class condition

Workflow philosophy in ONE treats failure and uncertainty as normal states.

Design intent includes:

- safe termination paths
- explicit abstention
- graceful degradation
- refusal to infer beyond evidence

Success is not defined as uninterrupted execution.

---

## Anti-goals

Workflow design explicitly avoids:

- agentic self-extension
- silent retries or hidden reasoning
- optimisation that obscures intent
- autonomy without accountability

Where such behaviour appears attractive, it is treated with suspicion.

---

## Relationship to governance and contracts

This document does not override:

- promotion rules
- system boundaries
- validation or termination logic

Those constraints are defined in `/contracts` and referenced by the System Atlas.

This document explains *why* those constraints exist.

---

Status: Design philosophy. Non-authoritative.
