# System Atlas — Overview

The System Atlas is the **canonical public representation of ONE**.

It exists to make the system **inspectable, bounded, and explainable** without requiring access to private data, runtime state, or personal context.

The Atlas does not describe everything that exists locally.
It describes only what has stabilised, been reviewed, and is safe to promote as a reference surface.

---

## What the Atlas is

The Atlas is:

- A **truth surface** describing the current, promoted state of ONE
- A **navigation map** across authority, orientation, capabilities, and evidence
- A **promotion boundary** separating stabilised work from experimentation
- A **review surface** for senior engineers, architects, and hiring managers

Everything included here is intentional, owned, and inspectable.

---

## What the Atlas is not

The Atlas is not:

- a runtime system
- a design notebook
- a roadmap or vision document
- a marketing surface
- a claim of autonomous intelligence

Unfinished, speculative, or private material is intentionally excluded.

---

## How the Atlas is structured

The Atlas is organised into the following sections:

- **Authority** — who owns truth and accountability
- **Orientation** — the fixed semantic constraints governing all design
- **Capabilities** — what exists today, what is experimental, and what is out of scope
- **Architecture** — how promoted components relate at a system level
- **Governance** — how drift is prevented and promotion is enforced
- **Diagnostics** — how coherence and failure are evaluated
- **Case Studies** — evidence-backed demonstrations under real-world constraints

Each section links to canonical artifacts rather than duplicating implementation detail.

---

## Promotion discipline

Inclusion in the Atlas requires that an artifact:

- has explicit scope and boundaries,
- does not rely on private or runtime-only context,
- can be inspected without execution,
- and remains stable under continued system evolution.

Artifacts that do not meet these criteria remain local or experimental.

---

## Intended audience

The Atlas is written for readers who evaluate systems rather than demos, including:

- senior engineers
- systems architects
- platform and infrastructure leads
- technical hiring managers

It assumes familiarity with production systems and real-world constraints.

---

## Status

The System Atlas is a living but governed surface.

Changes occur through explicit revision and promotion.
Implicit change is not permitted.

## Core Orientation (Frozen)

ONE is governed by a fixed semantic orientation: systems must be able to know and
explain themselves deterministically before AI is applied.

This orientation constrains system design, AI usage, and representation.
See [North Star — Semantic Orientation](./north-star.md).

