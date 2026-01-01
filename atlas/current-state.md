# Current State Snapshot (Public Repos)

**Snapshot date:** 2026-01-01  
**Source:** GitHub “text-only content export” (structure + contents for `.md/.txt/.json/.yml/.yaml`).

This snapshot exists to prevent drift between:
- what the repos look like publicly, and
- what they actually contain.

---

## Repo content state (as of 2026-01-01)

| Repo | State | Evidence (content surface) |
|---|---|---|
| `one-platform` | **Populated** | Atlas + Contracts + Codex + Case Studies present. |
| `contract-stack-examples` | **Mostly populated** | Multiple real docs; one obvious stub placeholder existed in export (`CONCEPTS.md` size ~1 byte). |
| `system-diagnostics` | **Scaffold + partial** | One substantive playbook; other docs were stubs (1 byte placeholders) in export. |
| `ask-and-memory-patterns` | **Light** | README only in export. |
| `system-skeletons` | **Scaffold** | README plus skeleton files that were stubs (1 byte placeholders) in export. |
| `ai-workflow-engine` | **Scaffold** | README plus workflow/example files that were stubs (1 byte placeholders) in export. |
| `one-reference-system` | **Scaffold** | README plus docs that were stubs (1 byte placeholders) in export. |
| `lukeheywood` (profile) | **Entry-only** | README only in export. |

---

## Interpretation rules (how to read this)

- **Populated**: usable content exists beyond the README; the repo can be evaluated by inspection.
- **Scaffold**: structure exists but most interior docs are placeholders; the repo is not yet an “exhibit”.
- **Light**: intentionally small; the README is the exhibit.

No repo is assumed to represent private/local runtime systems unless explicitly stated.

