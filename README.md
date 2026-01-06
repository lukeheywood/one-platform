# ONE — System Atlas (Public Glass Case)

This repository is the **public System Atlas** for ONE.

It contains **curated, promoted artifacts** that describe system architecture, governance, and evidence-backed outcomes.
It is intentionally **non-executable** and **read-only in spirit**.

> This repository is the map — not the private or local system.

**Audience:** senior engineers, architects, and technical hiring managers  
**Last verified:** 2026-01-01

---

## What this repository is

- A **canonical navigation surface** for promoted system material
- A **coherence check** across public artifacts
- A **reference point** for technical discussion, review, and assessment

Everything here is intentional, bounded, and inspectable without execution.

---

## What this repository is not

- Source code for runtime engines
- Private or local configuration, data, prompts, or logs
- A roadmap or a claim of future capability
- A live reflection of ongoing experimentation

Unpromoted work remains private by design.

---

## How to navigate

### System Atlas (canonical, promoted)

The `atlas/` directory is the **authoritative public representation** of ONE.

- `atlas/overview.md`  
  Systems-level description of what ONE is and why it exists

- `atlas/index.md`  
  Canonical navigation index for the Atlas

- `atlas/authority/system-authority.md`  
  Ownership, accountability, and epistemic authority model

- `atlas/orientation/north-star.md`  
  Fixed semantic orientation guiding system design and promotion

- `atlas/capabilities/`  
  - `index.md` — what capabilities exist today  
  - `registry.md` — scoped capability registry

- `atlas/architecture/index.md`  
  Promoted system structure and component relationships

- `atlas/governance/index.md`  
  Governance scope and links to canonical enforcement artifacts

- `atlas/diagnostics/index.md`  
  How coherence, drift, and failure modes are evaluated

- `atlas/case-studies/`  
  Promoted, evidence-backed demonstrations under real constraints  
  - `explainability-under-load.md` — Case Study 1 (canonical anchor)

---

### Contracts (deterministic constraints)

The `contracts/` directory contains **formal, authoritative constraints**.
These files are **sources of truth** and are referenced by the Atlas.

- `contracts/PROMOTION_RULES.md`
- `contracts/SYSTEM_BOUNDARIES.md`
- `contracts/NAMING_CONVENTIONS.md`

Contracts define what is allowed, enforced, or prohibited.

---

### Codex (design rationale)

The `codex/` directory contains **design philosophy and reasoning**.

These documents explain *why* decisions were made — not *what is currently true* or *what is enforced*.

- `codex/explainability.md`
- `codex/memory-architecture.md`
- `codex/workflow-philosophy.md`

If Codex content conflicts with the Atlas or Contracts, it is informational only.

---

### Reference (supporting material)

The `reference/` directory holds **non-authoritative supporting material** such as diagrams or excerpts, when promoted.

---

## Promotion principle (black-and-white)

If an artifact exists in this repository, it has been:

- built and validated elsewhere (private or local)
- bounded for public representation (explicit scope and exclusions)
- reviewed for coherence against contracts
- intentionally promoted into the System Atlas

Everything else remains private by design.

---

## Repository orientation

This repository represents **ONE as stabilised**, not ONE as explored.

- Exploration happens elsewhere
- Claims are bounded here
- Authority is explicit
- Drift is constrained

The goal is not completeness — it is **inspectability under load**.
