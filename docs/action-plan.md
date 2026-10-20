# MI-EY OS — Phase 1 Action Plan

**Plan ID:** MI-EY-PLAN-001  
**Version:** 1.4  
**Status:** Draft — awaiting Product Owner review  
**Updated:** 2026-10-20  
**Owner:** Product Owner

## Goal

Maintain a reliable, auditable documentation foundation and run a structured human review of the proposed ages 2–4 framework before operational use or software implementation.

## Confirmed direction

The intended platform scope is ages 2–6. The first Developmental Competency Framework deliverable focuses on ages 2–4 and starts with locomotor movement, stability, and object manipulation, plus integrative competencies. The primary daily user is a movement instructor/educator. No real child data is to be stored in this public repository; use fictional examples only. New documents remain Draft until reviewed.

The Product Owner approved proceeding to structured human review on 2026-10-20. This authorizes preparation of the reviewer packet and collection of document/activity-design feedback; it does not approve operational use or claim that expert review has occurred.

## Work items

| ID | Priority | Task | Deliverable | Status |
|---|---|---|---|---|
| P1-01 | P0 | Project control | docs/project-control.md | Present; review pending |
| P1-02 | P0 | Action plan | docs/action-plan.md | Updated; Draft |
| P1-03 | P0 | Documentation skeleton | docs/README.md, vision.md, principles.md, architecture.md | Present; review pending |
| P1-04 | P1 | Module entry points | README files in framework, engine, library, instructor, curriculum | Present; review pending |
| P1-05 | P1 | Decision log | docs/decision-log.md | Direction and review gate recorded; Draft |
| P1-06 | P0 | Verify remote state | GitHub paths and commit metadata | Verify after each write |
| P1-07 | P0 | Product Owner review | Review checklist and unresolved-decision list | Direction agreed; formal document review and specialist review pending |
| P1-08 | P1 | Content model | docs/content-model.md | Draft; review pending |
| P1-09 | P1 | Quality review checklist | docs/quality-review-checklist.md | Draft; review pending |
| P1-10 | P1 | Validate model with fictional scenario | docs/design-validation-example.md | Created; Draft; educator review pending |
| P1-11 | P1 | Create competency review matrix | framework/competency-review-matrix-2-4.md | Created; Draft; qualified review pending |
| P1-12 | P1 | Create fictional instructor walkthroughs | framework/instructor-walkthroughs-2-4.md | Created; Draft; desk-based only; not field-tested |
| P1-13 | P1 | Prepare external reviewer packet | framework/reviewer-packet-2-4.md | Created; Draft; reviewer feedback not yet received |

## Execution order

1. Reconcile documentation with the actual remote state.
2. Maintain separate but linked records for competencies, movement experiences, lessons, and curriculum.
3. Use fictional examples to test stable IDs, traceability, observable wording, adaptations, safety, evidence boundaries, and privacy.
4. Re-read changed files from GitHub and verify paths, content, and commit/blob metadata.
5. Use the reviewer packet to request feedback from a movement educator, a development/inclusion reviewer, a safety reviewer, and a research/evidence reviewer.
6. Record only reviews that actually occur; keep all criteria at Not reviewed until there is real reviewer evidence.
7. Revise the framework in response to findings and verify every changed file.
8. Ask the Product Owner to review findings before proposing any status transition.
9. Defer operational use and software implementation until requirements and critical review findings are resolved.

## Acceptance criteria

- Foundation files exist on the remote default branch and can be re-read.
- Documents remain Draft until reviewed and explicitly authorized for a status change.
- Proposed schemas are labeled as proposals, not final technical contracts.
- Competency entries link consistently to movement experiences and lessons.
- Observable cues do not claim to diagnose or establish universal age norms.
- Child safety, inclusion, evidence quality, privacy, and human review are addressed.
- No credentials or real child-identifying data are committed.
- Reviewer outcomes are not fabricated or pre-filled.
- The Product Owner can clearly identify what requires approval.

## Risks and mitigations

- **Remote state drift:** re-check GitHub after every write.
- **Premature technical commitment:** defer stack, database, API, and authentication choices until requirements are reviewed.
- **Unsupported developmental claims:** require traceable evidence and qualified review.
- **Draft mistaken for policy:** preserve explicit status labels.
- **Sensitive data exposure:** use fictional examples and do not store real child records in this public repository.
- **Overly complex content model:** test the proposed fields with instructors before finalizing them.
- **Simulated review mistaken for human review:** label desk-based checks accurately; only record feedback received from actual reviewers.

## Definition of done

The documentation foundation is ready for structured human review when baseline files exist remotely, the content model and quality checklist are present, fictional examples demonstrate traceability, a reviewer packet is available, remote state is verified, and unresolved decisions are visible. It is not formally approved for operational use until the required reviews are documented, critical issues are resolved, and the Product Owner explicitly authorizes that status.
