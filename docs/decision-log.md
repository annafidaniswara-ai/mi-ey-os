# MI-EY OS — Decision Log

**Status: Draft — awaiting Product Owner review.**

Use this log for material product, content, governance, and technical decisions. Keep proposals separate from approved decisions.

## Decision record template

### DEC-000 — Short title
- **Date:** YYYY-MM-DD
- **Status:** Proposed / Approved / Rejected / Superseded
- **Decision owner:** Product Owner or named delegate
- **Context:** What needs to be decided and why?
- **Options considered:** List credible alternatives.
- **Decision:** State the selected option, or write “Pending”.
- **Rationale:** Evidence, constraints, and trade-offs.
- **Impact:** Documents, modules, users, data, and operations affected.
- **Review trigger:** What new evidence or condition should reopen this decision?

## Initial records

### DEC-001 — Platform age scope
- **Date:** 2026-10-19
- **Status:** User-confirmed direction; awaiting formal document review
- **Decision owner:** Product Owner
- **Decision:** Intended platform scope is ages 2–6; first Developmental Competency Framework deliverable focuses on ages 2–4.
- **Rationale:** Establish a broad platform direction while starting with a bounded first deliverable.
- **Impact:** Vision, architecture, curriculum, and framework planning.

### DEC-002 — Documentation approval state
- **Date:** 2026-10-19
- **Status:** User-confirmed governance rule
- **Decision owner:** Product Owner
- **Decision:** New documents remain Draft until reviewed.
- **Rationale:** GitHub commit status is not product approval.
- **Impact:** All project documentation and generated content.

### DEC-003 — Proposed content model
- **Date:** 2026-10-19
- **Status:** Proposed; Product Owner review required
- **Decision owner:** Product Owner
- **Context:** Keep competencies, curriculum sequencing, lesson design, and movement experiences connected but separately maintainable.
- **Options considered:** One combined catalog, or separate content records linked by stable IDs.
- **Proposed decision:** Use separate competency, movement-experience, lesson, and curriculum records linked by stable IDs; keep the first version in Markdown until instructor workflows validate the fields.
- **Rationale:** Supports reuse and traceability without prematurely choosing a database or application stack.
- **Impact:** Framework, engine, library, curriculum, and future technical architecture.
- **Review trigger:** Instructor testing shows the model is too complex or does not support actual planning workflows.
