# MI-EY OS — Phase 1 Action Plan

**Plan ID:** MI-EY-PLAN-001  
**Version:** 1.0  
**Status:** Proposed execution plan  
**Created:** 2026-10-19  
**Owner:** Product Owner

## Goal

Establish a reliable, auditable documentation foundation for MI-EY OS before expanding into instructional framework design or software implementation.

## Current state

A live GitHub check on 2026-10-19 confirmed that the public repository annafidaniswara-ai/mi-ey-os uses main as its default branch and currently has only README.md at the root. The connected GitHub integration reports push permission. Do not assume planned folders exist until they are visible on GitHub.

## Work items

| ID | Priority | Task | Deliverable | Acceptance criteria | Status |
|---|---|---|---|---|---|
| P1-01 | P0 | Establish project control | docs/project-control.md | Purpose, ownership, source-of-truth, baseline, quality gates, and open decisions are recorded | In progress |
| P1-02 | P0 | Establish action plan | docs/action-plan.md | Tasks have priorities, outputs, and acceptance criteria | In progress |
| P1-03 | P0 | Define repository documentation skeleton | docs/README.md, docs/vision.md, docs/principles.md, docs/architecture.md | Each document has a clear purpose and is explicitly marked draft until approved | Not started |
| P1-04 | P1 | Add module entry points | framework/README.md, engine/README.md, curriculum/README.md, instructor/README.md, library/README.md | Each entry point describes scope, planned inputs/outputs, and current status | Not started |
| P1-05 | P1 | Record decision log | docs/decision-log.md | Decisions include ID, date, status, rationale, owner, and impact | Not started |
| P1-06 | P1 | Verify remote state | GitHub root listing and commit metadata | All expected files are visible on main; each change has a verifiable commit SHA | Not started |
| P1-07 | P1 | Review Phase 1 | Review checklist and unresolved-decision list | Product Owner can approve foundation or identify required changes | Not started |

## Recommended execution order

1. Create the project control and action-plan documents.
2. Re-read both files from GitHub and verify the resulting commits.
3. Create the documentation skeleton and module entry points in small, reviewable changes.
4. Add the decision log and capture decisions without silently converting proposals into approved requirements.
5. Review the complete remote tree and README.
6. Ask the Product Owner to approve the baseline before writing detailed product architecture or implementation code.

## Definition of done

Phase 1 is done when all planned foundation files exist on the remote default branch, their contents have been reviewed, no secrets or unnecessary child-identifying data are present, and the Product Owner has accepted the scope and open decisions.

## Risks and mitigations

- **Assuming local progress equals remote progress:** verify GitHub paths and commit SHAs after each write.
- **Scope creep into application code too early:** finish and approve documentation architecture first.
- **Unverified research claims:** keep claims sourced and label gaps.
- **Sensitive data exposure:** use synthetic or anonymized examples; do not commit credentials.
- **Unapproved decisions becoming requirements:** label proposals and obtain owner approval.

## Next action

Complete P1-01 and P1-02, verify them on GitHub, then proceed with P1-03. The architecture document should remain a draft until the Product Owner approves the scope and module boundaries.
