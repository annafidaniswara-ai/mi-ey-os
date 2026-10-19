# MI-EY OS — Phase 1 Action Plan

**Plan ID:** MI-EY-PLAN-001  
**Version:** 1.3  
**Status:** Draft — awaiting Product Owner review  
**Updated:** 2026-10-19  
**Owner:** Product Owner

## Goal

Establish a reliable, auditable documentation foundation and validate the proposed content model before expanding into the detailed ages 2–4 framework or software implementation.

## Confirmed direction

The intended platform scope is ages 2–6. The first Developmental Competency Framework deliverable focuses on ages 2–4 and starts with locomotor movement, stability, and object manipulation. The primary daily user is a movement instructor/educator. No real child data is to be stored in this public repository; use fictional or anonymized examples. New documents remain Draft until reviewed by the Product Owner.

## Work items

| ID | Priority | Task | Deliverable | Status |
|---|---|---|---|---|
| P1-01 | P0 | Project control | docs/project-control.md | Updated; owner review pending |
| P1-02 | P0 | Action plan | docs/action-plan.md | Updated; owner review pending |
| P1-03 | P0 | Documentation skeleton | docs/README.md, vision.md, principles.md, architecture.md | Present; review pending |
| P1-04 | P1 | Module entry points | README files in framework, engine, library, instructor, curriculum | Present; review pending |
| P1-05 | P1 | Decision log | docs/decision-log.md | Platform scope and draft governance recorded; review pending |
| P1-06 | P0 | Verify remote state | GitHub paths and commit metadata | Verify after current writes |
| P1-07 | P0 | Product Owner review | Review checklist and unresolved-decision list | Awaiting review |
| P1-08 | P1 | Content model | docs/content-model.md | Draft; review pending |
| P1-09 | P1 | Quality review checklist | docs/quality-review-checklist.md | Draft; review pending |
| P1-10 | P1 | Validate model with fictional scenario | docs/design-validation-example.md | Created; Draft; educator review pending |

## Execution order

1. Reconcile the documentation with actual remote state.
2. Maintain a proposed content model for competencies, movement experiences, lessons, and curriculum.
3. Use a fictional example to test stable IDs, traceability, observable wording, adaptations, safety, evidence boundaries, and privacy.
4. Re-read changed files from GitHub and verify paths and blob SHAs.
5. Ask the Product Owner and relevant educators to review the architecture, content model, and quality gates.
6. Resolve review findings before beginning the detailed ages 2–4 Developmental Competency Framework.

## Acceptance criteria

- Foundation files exist on the remote default branch and can be re-read.
- Documents remain Draft until reviewed.
- Proposed schemas are labeled as proposals, not final technical contracts.
- Example competencies link consistently to a movement experience and lesson.
- Observable cues do not claim to diagnose or establish universal age norms.
- Child safety, inclusion, evidence quality, privacy, and human review are addressed.
- No credentials or real child-identifying data are committed.
- The Product Owner can clearly identify what requires approval.

## Risks and mitigations

- **Remote state drift:** re-check GitHub after every write.
- **Premature technical commitment:** defer stack, database, API, and authentication choices until requirements are approved.
- **Unsupported developmental claims:** require traceable evidence and qualified review.
- **Draft mistaken for policy:** preserve explicit status labels.
- **Sensitive data exposure:** use fictional examples and do not store real child records in this public repository.
- **Overly complex content model:** test the proposed fields with instructors before finalizing them.

## Definition of done

The documentation foundation is ready for Product Owner review when baseline files exist remotely, the content model and quality checklist are present, a fictional validation example demonstrates traceability, remote state is verified, and unresolved decisions are visible. It is not formally approved until the Product Owner says so.
