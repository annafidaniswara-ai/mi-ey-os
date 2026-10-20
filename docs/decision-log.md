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
- **Status:** User-confirmed direction; formal document review pending
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

### DEC-004 — Product Owner review of ages 2–4 framework draft
- **Date:** 2026-10-20
- **Status:** Agreement recorded; educator and specialist review pending
- **Decision owner:** Product Owner
- **Context:** The Product Owner reviewed the proposed Developmental Competency Framework structure and competency dictionary.
- **Decision:** Proceed with the proposed structure for the next review stage: three core domains (locomotor, stability, object manipulation) plus integrative competencies; use observable indicators and flexible progression options rather than universal age deadlines.
- **Rationale:** This records the user's explicit agreement in the project conversation and enables the next validation activity.
- **Impact:** Framework structure, competency dictionary, review matrix, and instructor walkthroughs.
- **Review trigger:** Qualified educator, safety/inclusion, or research review identifies material issues; the Product Owner may revise the direction.
- **Approval boundary:** This decision confirms agreement with the proposed structure only. It does not mark the framework or dictionary Approved, and does not establish validation for operational or assessment use.

### DEC-005 — Proceed to structured human review
- **Date:** 2026-10-20
- **Status:** Approved to proceed with review preparation; framework approval remains pending
- **Decision owner:** Product Owner
- **Context:** After reviewing the competency review matrix and fictional instructor walkthroughs, the Product Owner said “berikutnya saya approve” and authorized the next step.
- **Decision:** Prepare a structured reviewer packet and proceed to solicit feedback from qualified human reviewers on instructor usability, development/inclusion, activity safety, and research-claim accuracy.
- **Rationale:** Separate the Product Owner's approval to proceed from specialist review and operational authorization.
- **Impact:** framework/reviewer-packet-2-4.md, framework/competency-review-matrix-2-4.md, framework/instructor-walkthroughs-2-4.md, and the next review cycle.
- **Review trigger:** Reviewer findings identify a critical safety, inclusion, privacy, evidence, or usability issue.
- **Approval boundary:** This approval does not assert that any external reviewer has already reviewed the documents. It does not approve the framework for operational use or mark framework documents Approved.
