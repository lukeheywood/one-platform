# Naming Conventions

These conventions exist to keep ONE’s public surfaces **inspectable** and **low-ambiguity** as the repository grows.

They are not aesthetic rules.
They are anti-drift constraints.

---

## Scope

Applies to:

- repositories
- top-level directories
- promoted artifacts in the System Atlas
- contracts and reference surfaces

Does not apply to private/local runtime systems.

---

## Canonical terms

Use these terms consistently:

- **ONE** — the system (authored, governed)
- **System Atlas** — public, promoted, non-executable truth surface
- **Engine** — executable runtime component (local/private unless explicitly published)
- **Contract** — deterministic constraint on behaviour, inputs/outputs, validation, boundaries
- **Promotion** — moving material into the Atlas as stable public reference
- **Capability** — a declared function/surface with explicit scope and limits
- **Diagnostics** — inspection surfaces and failure-mode evaluation

Avoid inventing new synonyms unless necessary.

---

## File and directory naming

- Prefer **kebab-case** for folders and general markdown files:
  - `system-authority.md`
  - `explainability-under-load.md`

- Use **UPPER_SNAKE_CASE** for contract documents that act like “rules”:
  - `PROMOTION_RULES.md`
  - `SYSTEM_BOUNDARIES.md`
  - `NAMING_CONVENTIONS.md`

- Use `index.md` only as a **navigation surface** for a directory.

---

## Titles and headings

- Titles should describe **what the file is**, not what it aspires to be.
- Avoid “vision” language in canonical surfaces.
- Prefer stable nouns:
  - “System Boundaries”
  - “Promotion Rules”
  - “Capability Registry”

---

## Prohibited patterns

- Ambiguous labels: `final.md`, `new.md`, `misc.md`
- Future-claim titles: `roadmap.md`, `coming-soon.md`
- Authority leakage: files implying the system “decides”, “knows”, or “self-updates”

---

## Revision discipline

If a naming rule changes:

- update this file explicitly
- describe the rationale
- apply the change consistently (no half-migrations)

Naming is a governance surface.
Drift here creates drift everywhere.
