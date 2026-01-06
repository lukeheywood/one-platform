# Capability Registry

This registry enumerates the **promoted capabilities** within ONE.

Each entry represents a capability that is:
- stabilised and operational,
- governed by explicit constraints or contracts,
- and eligible to be referenced by other Atlas sections.

Capabilities not listed here are not promoted.

---

## CAP-001 — System Atlas

**Description**  
Canonical, public truth surface describing what exists within ONE, how it is structured, and where authority resides.

**Scope**
- Authoritative documentation of system state
- Promotion boundary for stabilised artifacts
- Navigation surface for architecture, governance, and case studies

**Constraints**
- Descriptive only; no runtime behaviour
- No duplication of implementation details
- Promotion required for inclusion

---

## CAP-002 — Governance & Contract Framework

**Description**  
Explicit contract structures governing AI workflow behaviour, including validation, termination, abstention, and promotion rules.

**Scope**
- Input/output contracts
- Guardrails and invariants
- Promotion and freeze discipline

**Constraints**
- Contracts must be inspectable
- Behaviour must fail closed rather than guess
- Authority remains external to models

---

## CAP-003 — Explainability Under Load

**Description**  
Workflow patterns that expose decision paths, assumptions, and failure modes when operating under real-world constraints.

**Scope**
- Deterministic explanation surfaces
- Evidence-backed evaluation
- Load and ambiguity handling

**Constraints**
- Explanations must be structural, not narrative
- Unsupported certainty is prohibited
- Evidence must be linkable

---

## CAP-004 — Workflow Skeletons

**Description**  
Reference workflow structures separating exploration from execution to prevent uncontrolled behaviour.

**Scope**
- Exploration vs execution split
- Retry, validation, and termination boundaries
- Integration-ready patterns

**Constraints**
- No implicit authority
- Execution paths must be bounded
- Exploration outputs must not auto-promote

---

## Registry governance

This registry is authoritative.

Entries are added, modified, or removed only through explicit promotion or revision recorded in the Atlas.
Deprecated capabilities are removed rather than retained for historical completeness.
