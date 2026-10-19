# MI-EY OS — Proposed Architecture

**Status: Draft — awaiting Product Owner review.**

## 1. Architectural approach

Begin with a documented knowledge architecture before committing to a specific application stack. The repository is the versioned home for specifications, content models, and later implementation artifacts. This document does not assert that an application, database, API, or authentication system already exists.

## 2. Proposed content layers

- **Governance (docs/):** vision, principles, decisions, project control, and quality procedures.
- **Competency model (framework/):** competency definitions, developmental considerations, observable indicators, and evidence notes. First focus: ages 2–4.
- **Lesson generation (engine/):** proposed rules connecting goals, constraints, activities, adaptations, and session structure.
- **Experience catalog (library/):** reusable movement experiences with setup, steps, adaptations, safety, and observation cues.
- **Instructor support (instructor/):** facilitation, observation, adaptation, and reflection guidance.
- **Curriculum (curriculum/):** sequencing and progression across experiences and age bands.

## 3. Conceptual flow

Program goals → competencies → movement experiences → lesson plan → instructor delivery → observations/reflection → reviewed improvement.

Curriculum organizes and sequences competencies and lessons. The proposed field-level model is documented in [content-model.md](content-model.md); the repeatable quality gate is in [quality-review-checklist.md](quality-review-checklist.md).

This is a proposed content workflow, not an implemented software pipeline.

## 4. Proposed records

The initial conceptual model separates four record types: competency, movement experience, lesson, and curriculum. Each uses stable IDs and includes status, version, and review ownership. Relationships should be explicit rather than duplicating definitions across documents.

The field lists are proposals and should be validated with instructors before becoming final schemas.

## 5. Technical decisions deferred

Do not choose frameworks, hosting, database, authentication, analytics, or AI APIs until requirements, data sensitivity, user roles, deployment constraints, and maintenance capacity are documented and approved.

## 6. Quality and security boundaries

- Public repository content must contain no credentials or identifiable child records.
- Any future private or child-related data needs a separate data-flow and access review before implementation.
- Generated content must be reviewed for developmental appropriateness, inclusion, safety, and evidence quality.
- Maintain explicit Draft / In review / Approved status. A commit does not equal approval.

## 7. Acceptance questions

- Do the proposed layers reflect the actual workflow of instructors?
- Are the four proposed record types sufficient and practical?
- Which content needs to be public, private, or restricted?
- What review roles and release gates are required?
