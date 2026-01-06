# ONE — AI Workflow Engine

This repository contains **executable AI workflows** built as governed pipelines.

These workflows treat LLMs as components inside explicit structures — not as autonomous decision-makers.
Their purpose is to produce **traceable artifacts** under defined constraints.

---

## 🧭 What this repo is

The AI Workflow Engine provides reference implementations for:

- LLM-powered workflows designed as multi-step pipelines
- Explicit separation between inputs, processing, and outputs
- Artifact generation as a first-class outcome
- Validation and structure around every AI interaction

These workflows are designed to run, not just to illustrate patterns.

---

## 🧱 What lives in this repository

This repository includes:

- Runnable workflow definitions
- Structured input and context handling
- Artifact emission (reports, summaries, manifests, evidence packs)
- Boundaries that prevent uncontrolled prompt-only behaviour

Each workflow is designed so that:
- inputs are explicit,
- processing steps are visible,
- outputs can be inspected or reused.

---

## 🔍 Relationship to ONE

Within the broader ONE system:

- `system-skeletons` defines the allowed workflow shapes
- `contract-stack-examples` constrains how intelligence may be applied
- `ai-workflow-engine` executes workflows within those bounds
- `one-reference-system` inspects what was run and what was produced

This engine is where **intent becomes execution**, without abandoning governance.

---

## 📌 Concrete example

A typical workflow in this repository:

- Accepts a structured input (not a free-form prompt)
- Passes context through defined stages
- Invokes an LLM at constrained points
- Emits a concrete artifact (for example, a generated report or context pack)
- Leaves an evidence trail suitable for later inspection

The value is not the model’s cleverness, but the **reliability of the pipeline**.

---

## 🚧 Status & intent

These workflows are intentionally opinionated about structure, not outcomes.

They are expected to evolve as models change, but their **pipeline shape** remains stable.
Changes here are treated as execution refinements, not architectural shifts.

The goal is not autonomy.
The goal is **repeatable, inspectable AI work under load**.

---

*If contracts set the rules,  
this engine is how work gets done — carefully.*
---

## 📚 ONE — Repository Index

- **system-skeletons** → Structural blueprints and allowed system shapes  
- **contract-stack-examples** → Formal invariants and governance constraints  
- **one-reference-system** → System inspection and explainability anchor  
- **ai-workflow-engine** → Governed, artifact-producing execution pipelines  
- **system-diagnostics** → Mapping and drift-detection patterns  
- **ask-and-memory-patterns** → Grounded retrieval and answerability design

This index exists for orientation only.  
Each repository remains independently scoped and truth-aligned.
