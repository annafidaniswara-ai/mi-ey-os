# MI-EY OS — Project Control Document

**Document ID:** MI-EY-CTRL-001  
**Version:** 1.1  
**Status:** Draft — awaiting Product Owner review  
**Last reviewed:** 2026-10-19  
**Repository:** https://github.com/annafidaniswara-ai/mi-ey-os  
**Default branch:** main

## 1. Purpose and scope

This document is the operating control point for MI-EY OS. It records the project's purpose, ownership, source-of-truth rules, verified repository state, quality controls, and next actions.

MI-EY OS is intended as a child-centered movement-learning platform and knowledge architecture for ages 2–6. The first Developmental Competency Framework deliverable focuses on ages 2–4.

## 2. Roles and decision rights

- **Product Owner:** owns scope, priorities, approval, and release decisions.
- **AI partner:** supports research, drafting, planning, analysis, and implementation where tools and permissions allow.
- **Human approval required:** approval of product scope and architecture; release of operational content; access/security changes; destructive actions; and decisions affecting child-related data.
- A GitHub commit proves that a file was saved; it does not mean the content has been approved.

## 3. Source-of-truth rules

1. GitHub main is the versioned source of truth for committed documentation and code.
2. A file path and commit SHA are evidence of a repository change.
3. ChatGPT conversations are working context; material decisions must be recorded in project documents.
4. All new documents remain Draft until the Product Owner reviews them.
5. Research claims need traceable sources; distinguish evidence, interpretation, and design decisions.
6. Never commit passwords, API tokens, private keys, or unnecessary identifying information about children.

## 4. Module boundaries (proposed)

- docs/: vision, principles, architecture, decision log, project control, and quality procedures.
- framework/: competency definitions and observable indicators, starting with ages 2–4.
- engine/: proposed rules for assembling lesson plans from goals, constraints, and experiences.
- library/: reusable movement experiences and their safety/adaptation guidance.
- instructor/: facilitation, observation, adaptation, and reflection guidance.
- curriculum/: sequencing and progression across the intended age range.

These are documented content boundaries. They do not imply that an application, database, API, or automated pipeline exists.

## 5. Verified repository baseline

Checked on 2026-10-19 through the connected GitHub integration:

- Repository: annafidaniswara-ai/mi-ey-os
- Visibility: public
- Default branch: main
- Root includes README.md, docs/, framework/, engine/, library/, instructor/, and curriculum/.
- The docs/ directory contains project control, action plan, vision, principles, architecture, decision log, content model, quality checklist, and documentation index.
- Each module directory currently has an entry-point README.md.
- Files were re-read from GitHub after creation. This is a documentation foundation, not a running software product.

## 6. Delivery workflow

For each meaningful change:

1. Define the objective and acceptance criteria.
2. Inspect current files and repository state before editing.
3. Draft the smallest useful change.
4. Check completeness, terminology, source quality, privacy, and safety.
5. Apply the change only through an authorized tool or an explicitly user-operated step.
6. Re-read the resulting file from GitHub and record the path and commit SHA.
7. Record unresolved issues and the next action.

## 7. Quality and safety gates

- **Content:** clear purpose, defined terms, and age-appropriate language.
- **Evidence:** cite credible sources for scientific claims; disclose material limitations.
- **Safety:** child-centered, inclusive, non-diagnostic, and not a substitute for qualified assessment.
- **Privacy:** use synthetic or anonymized examples during design and testing.
- **Versioning:** keep changes traceable and avoid unrelated edits in one change.
- **Approval:** no draft becomes an approved requirement without explicit human review.
- **Implementation:** do not mark a module complete without acceptance checks and a review record.

## 8. Success criteria for the documentation foundation

- Project-control and action-plan documents exist on the remote branch.
- The intended directory structure is visible on GitHub.
- Module boundaries and document statuses are explicit.
- Tasks have priorities, deliverables, and acceptance criteria.
- No credentials or unnecessary child-identifying data are committed.
- The Product Owner has reviewed and accepted the baseline.

## 9. Open review decisions

1. Confirm the primary user and first real-world use case.
2. Review the proposed content model for competencies and movement experiences.
3. Review evidence/citation and activity safety-review standards.
4. Decide which content, if any, should later be private rather than public.
5. Approve the architecture and documentation foundation before software implementation.

## 10. Change log

- 2026-10-19 — Version 1.0 created as initial project control baseline.
- 2026-10-19 — Version 1.1 reconciles the baseline with the verified GitHub tree and documents the content model and quality-review gate.
