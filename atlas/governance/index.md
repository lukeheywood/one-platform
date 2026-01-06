# Governance

This section defines how ONE is constrained, stabilised, and kept coherent over time.

Governance in ONE exists to **prevent drift**, **block unsupported claims**, and **enforce discipline**
around what may be promoted, represented, or relied upon.

The System Atlas does **not** redefine governance.
It acts as a navigation and reference surface for governance that is defined elsewhere.

---

## Scope

Governance in ONE applies to all promoted system material, including:

- capabilities and workflows
- diagnostics and inspection surfaces
- documentation and public representations
- case studies and evidence-backed claims

No component, artifact, or narrative surface is exempt.

Governance constrains **what may exist publicly**, **what may advance**, and
**what must be withdrawn or revised**.

---

## Canonical governance artifacts

Governance rules are defined by a small set of **authoritative artifacts**.
These artifacts are **referenced**, not duplicated, by the System Atlas.

They include:

- **Governance overview**
  - Defines the purpose, scope, and limits of governance
  - Establishes why governance exists and what it constrains  
  → See: [`System Authority`](../authority/system-authority.md)

- **Contract stack**
  - Formal system contracts
  - Input/output definitions
  - Validation, abstention, and termination rules
  - Promotion gates and regression constraints  
  → See: [`/contracts`](../../contracts/)

- **Promotion rules**
  - Criteria for advancing material into the Atlas
  - Evidence and inspection requirements
  - Review and revision discipline  
  → See: [`PROMOTION_RULES.md`](../../contracts/PROMOTION_RULES.md)

- **Freeze declarations**
  - Explicitly frozen orientations, invariants, and semantics
  - Conditions under which freezes may be revised  
  → Maintained in canonical governance artifacts

Each artifact is authoritative within its declared scope.
If artifacts conflict, the more specific constraint prevails.

---

## Behaviour

Governance in ONE is **constraining, not advisory**.

- Unsupported behaviour is blocked, not tolerated
- Ambiguous outputs must abstain rather than infer
- Capabilities without evidence are not promoted
- Violations trigger review, not justification

Governance does not optimise outcomes.
It preserves system integrity under load.

---

## Relationship to authority

Governance operates under the **System Authority** defined in the Atlas.

- Authority defines ownership and accountability
- Governance defines constraints and enforcement
- Neither is delegated to models, tools, or automation

Where convenience conflicts with governance, governance prevails.

---

## Revision discipline

Governance artifacts may evolve only through:

- explicit revision,
- documented rationale,
- and promotion via the System Atlas.

Implicit change is prohibited.

Stability is preserved by intention, not convention.
