# Promotion Rules

Promotion is the act of moving material into the **System Atlas** as a stable public reference.

Promoted material is treated as:

- inspectable without execution
- bounded in scope
- safe to discuss with third parties
- stable under ongoing system evolution

Promotion is not a reward.
It is a safety gate.

---

## What can be promoted

Eligible:

- capability descriptions with explicit limits
- governance surfaces and contracts
- architecture summaries (non-executable)
- diagnostics / inspection surfaces (bounded)
- case studies with evidence-backed constraints and trade-offs

Not eligible:

- runtime code
- private data, logs, prompts, tokens, or internal traces
- speculative designs or “future intent”
- model-generated claims without deterministic structure

---

## Promotion criteria (must pass)

An artifact may be promoted only if it satisfies all of the following:

1. **Explicit scope**
   - states what it covers and what it does not

2. **No private dependencies**
   - understandable without private context, runtime state, or hidden inputs

3. **Inspectable**
   - a reviewer can reason about it by reading it (no execution required)

4. **Non-claiming**
   - does not assert capabilities beyond what is shown or bounded

5. **Stable phrasing**
   - avoids language that will drift with iteration (“soon”, “will”, “next”)

6. **Clear ownership**
   - the artifact is authored and accountable (not “the system says”)

---

## Required sections (for promoted narratives / case studies)

If the artifact is explanatory (e.g., a case study), it must include:

- observed problem / failure mode
- constraints and stakes
- why naive approaches failed
- design decision(s)
- trade-offs and exclusions
- what this enables / what it does not

---

## Demotion / withdrawal

If an artifact becomes incorrect, misleading, or unbounded, it must be:

- revised explicitly, or
- withdrawn from promoted status

Stale public truth is worse than missing truth.

---

## Change control

Promotion rule changes must be:

- explicit
- reviewed
- applied consistently

If enforcement is unclear, promotion pauses until clarified.
