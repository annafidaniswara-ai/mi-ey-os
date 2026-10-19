# MI-EY OS — Proposed Architecture

**Status: Draft — awaiting Product Owner review.**

## 1. Architectural approach

Begin with a documented knowledge architecture before committing to a specific application stack. The repository is the versioned home for approved specifications, content models, and later implementation artifacts. This document does not assert that an application, database, API, or authentication system already exists.

## 2. Proposed content layers

- **Governance (`docs/`):** vision, principles, decisions, architecture, quality and operating procedures.
- **Competency model (`framework/`):** competency definitions, developmental considerations, observable indicators, and evidence notes. First focus: ages 2–4.
- **Lesson generation (`engine/`):** rules connecting goals, constraints, activities, adaptations, and session structure.
- **Experience catalog (`library/`):** reusable movement experiences with setup, steps, adaptations, safety, and observation cues.
- **Instructor support (`instructor/`):** facilitation, observation, adaptation, and reflection guidance.
- **Curriculum (`curriculum/`):** sequencing and progression across experiences and age bands.

## 3. Conceptual flow

Program goals → competency framework → lesson intent → movement experience selection/adaptation → instructor delivery → observation/reflection → reviewed improvement.

The flow is a proposed content model, not an implemented software pipeline.

## 4. Suggested record fields

A movement experience may eventually include: unique ID, title, intended competency, suggested age/readiness, objectives, duration, space/equipment, setup, instructions, adaptations, safety considerations, observation cues, source/evidence notes, version, review status, and reviewer.

A competency may eventually include: ID, name, definition, domain, age-band context, observable indicators, examples/non-examples, adaptation notes, evidence references, and review status.

These fields are proposals and should be validated with real instructor workflows before being treated as final schemas.

## 5. Technical decisions deferred

Do not choose frameworks, hosting, database, authentication, analytics, or AI APIs until requirements, data sensitivity, user roles, deployment constraints, and maintenance capacity are documented and approved.

## 6. Quality and security boundaries

- Public repository content must contain no credentials or identifiable child records.
- Any future private or child-related data needs a separate data-flow and access review before implementation.
- Generated content must be reviewed for developmental appropriateness, inclusion, safety, and evidence quality.
- Maintain explicit Draft / In review / Approved status.

## 7. Acceptance questions

- Do the proposed layers reflect the actual workflow of instructors?
- Should competency content be maintained separately from curriculum sequencing?
- Which content needs to be public, private, or restricted?
- What review roles and release gates are required?
