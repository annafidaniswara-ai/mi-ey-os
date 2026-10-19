# MI-EY OS — Project Control Document

**Document ID:** MI-EY-CTRL-001  
**Version:** 1.0  
**Status:** Initial baseline — owner review required  
**Last reviewed:** 2026-10-19  
**Repository:** https://github.com/annafidaniswara-ai/mi-ey-os  
**Default branch:** main

## 1. Purpose

This document is the operating control point for MI-EY OS. It records the project's purpose, source-of-truth rules, current verified status, governance, quality controls, and the next actionable work.

MI-EY OS is the Movement Intelligence Education Operating System: a child-centered movement-learning platform and knowledge architecture for ages 2–6. The first instructional framework focus is ages 2–4.

## 2. Product owner and decision rights

- **Product Owner:** project owner.
- **AI partner:** supports research, drafting, planning, analysis, and implementation where tools and permissions allow.
- **Human approval required:** product scope changes; publication of sensitive or consequential content; changes to access/security settings; destructive actions; and release decisions.
- **No false completion claims:** drafted content is not considered implemented until the artifact exists in the designated system and has been checked.

## 3. Source-of-truth rules

1. GitHub main is the source of truth for committed project documentation and code.
2. A GitHub commit SHA and visible file path are evidence of a repository change.
3. ChatGPT conversations are working context, not the canonical record of a decision unless the decision is recorded in the project documents.
4. Use the latest approved document; label unapproved work as Draft or Proposed.
5. Research claims must have traceable sources and a note describing limitations where material.
6. Never store passwords, API tokens, private keys, or unnecessary personal/child-identifying data in the repository.

## 4. Scope and planned modules

- docs/: vision, principles, architecture, decisions, project controls, and operating procedures.
- framework/: Developmental Competency Framework, beginning with ages 2–4.
- engine/: MI-EY Lesson Engine and session-generation rules.
- library/: Movement Experience Library.
- instructor/: Instructor Playbook and observation guidance.
- curriculum/: curriculum structure and progression.
- Additional technical implementation (application, APIs, database, authentication, and testing) is out of scope until the product architecture and requirements are reviewed and approved.

These are planned modules, not a claim that these directories or software components already exist.

## 5. Current verified repository baseline

Checked on 2026-10-19 through the connected GitHub integration:

- Repository: annafidaniswara-ai/mi-ey-os
- Visibility: public
- Default branch: main
- Repository access reports push permission.
- Root contents currently show only README.md.
- README.md describes MI-EY OS as a child-centered movement learning platform for ages 2–6 and marks the project status as Foundation phase.
- Current README blob SHA: 8c40f1855e5d17d96d0b1d724a60781a42019ed0.

**Important reconciliation:** the user's Phase 1 checklist is marked complete for their ChatGPT workspace and working documents. However, at the time of this live repository check, the remote GitHub root contains only README.md. The repository folder structure must therefore be treated as not yet present on remote main until verified after commits.

## 6. Delivery workflow

For each meaningful change:

1. State the objective and acceptance criteria.
2. Inspect the current file(s) and repository state before editing.
3. Draft the smallest useful change.
4. Check links, terminology, completeness, source quality, and safety.
5. Apply the change only through an available authorized tool or an explicitly user-operated step.
6. Verify the resulting file path and commit SHA.
7. Record the result, unresolved issues, and next action in the project log.

## 7. Quality gates

- **Content:** clear purpose, defined terms, age-appropriate language, and no unsupported developmental claims.
- **Evidence:** credible sources for scientific claims; distinguish evidence, interpretation, and design choice.
- **Safety:** child-centered, inclusive, non-diagnostic, and does not replace qualified clinical assessment.
- **Privacy:** use fictional/anonymous examples during early development.
- **Versioning:** each approved change is traceable; avoid broad, unrelated commits.
- **Implementation:** no module is marked complete without acceptance checks and a review record.

## 8. Initial success criteria

Phase 1 foundation is accepted when:
- project control and action-plan documents exist in the repository;
- the intended directory structure is documented and then verified on GitHub;
- project status and decisions can be updated consistently;
- each next task has an owner, priority, deliverable, and acceptance criteria;
- no credentials or unnecessary personal data are committed.

## 9. Open decisions

1. Confirm the canonical name and scope: MI-EY OS platform for ages 2–6, with first framework delivery for ages 2–4.
2. Approve the proposed directory structure.
3. Decide whether the next deliverable is repository documentation only or also a software architecture specification.
4. Approve evidence and citation standards for the Developmental Competency Framework.

## 10. Change log

- 2026-10-19 — Created initial project control baseline and documented live repository status.
