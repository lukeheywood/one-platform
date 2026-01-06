# Diagnostics Index

This section describes how ONE evaluates **system coherence, drift, and failure modes**.

Diagnostics in ONE are designed to surface problems early, explicitly, and inspectably.
They do not attempt to optimise outcomes or mask uncertainty.

Diagnostics inform governance and promotion.
They do not override authority or contracts.

---

## Diagnostic intent

Diagnostics exist to answer concrete questions:

- Is the system behaving within its declared constraints?
- Are contracts being respected?
- Has behaviour drifted from promoted intent?
- Are explanations still structurally valid under load?
- Are failure modes understood and bounded?

Diagnostics are descriptive.
They do not decide correctness — they expose evidence.

---

## Diagnostic surfaces

Diagnostics within ONE operate across several surfaces:

### Structural diagnostics
Evaluate whether system structure remains intact.

- Presence of explicit contracts
- Clear ownership and authority boundaries
- Separation between exploration and execution
- Absence of implicit or emergent authority

---

### Behavioural diagnostics
Evaluate runtime or simulated behaviour against expectations.

- Validation and termination behaviour
- Retry and abstention behaviour
- Failure handling under ambiguity or partial input
- Boundary enforcement under load

---

### Coherence diagnostics
Evaluate alignment between:
- declared intent,
- implemented structure,
- and observed behaviour.

This includes detection of:
- silent capability expansion,
- implicit decision-making,
- undocumented assumptions,
- or narrative explanations unsupported by structure.

---

### Evidence diagnostics
Evaluate whether claims are supported.

- Availability of inspectable artifacts
- Traceability between claims and evidence
- Reproducibility of promoted behaviours
- Consistency across environments and runs

---

## Diagnostic outputs

Diagnostics produce **signals**, not conclusions.

Typical outputs include:
- pass / fail indicators
- constraint violations
- drift flags
- missing evidence markers
- abstention triggers

Interpretation of diagnostic outputs is governed by:
- contracts,
- promotion rules,
- and explicit review.

---

## Relationship to governance

Diagnostics are subordinate to governance.

- Diagnostics surface issues
- Governance determines response
- Authority remains external

No diagnostic process may:
- self-promote capabilities,
- override contracts,
- or justify unsupported behaviour.

---

## Scope boundary

Diagnostics in ONE do not:
- assign intelligence,
- infer intent,
- or optimise for success metrics.

They exist to preserve legibility and integrity under real-world constraints.
