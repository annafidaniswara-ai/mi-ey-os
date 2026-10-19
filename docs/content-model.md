# MI-EY OS — Proposed Content Model

**Status: Draft — awaiting Product Owner review.**

## Purpose
Define a small, understandable content structure linking competencies, movement experiences, lessons, and curriculum without committing to a database or application stack.

## Modeling rules
1. Keep distinct concepts in distinct records and connect them with stable IDs.
2. Treat age bands as planning context, not universal milestone claims.
3. Separate observed behavior from interpretation and developmental conclusions.
4. Include status, version, and review ownership in each record.
5. Do not store identifiable child records in this public repository.
6. Validate proposed fields with instructors before treating them as final.

## Competency record
Suggested fields: competency_id; name; definition; domain; age_band_context; observable_indicators; examples_and_non_examples; adaptation_notes; evidence_notes; status; version; reviewer; review_date.

## Movement experience record
Suggested fields: experience_id; title; intention; competency_ids; age_readiness_context; duration_range; space; equipment; group_size; setup; instructions; adaptations; safety_checks; observation_cues; source_notes; status; version; reviewer; review_date.

## Lesson record
Suggested fields: lesson_id; learning_intention; competency_ids; experience_ids; duration_total; group_context; space; equipment; opening; main_experiences; closing; transition_notes; adaptation_plan; safety_review; observation_plan; reflection_prompts; assumptions; status; version; reviewer; review_date.

## Curriculum record
Suggested fields: curriculum_id; title; purpose; scope; competency_ids; lesson_ids; sequencing_rationale; adaptation_paths; review_evidence; status; version; reviewer; review_date.

## Relationship model
Program goals → competencies → movement experiences → lesson plan → instructor delivery → observations/reflection → reviewed revisions.

Curriculum organizes and sequences competencies and lessons without duplicating their definitions. A lesson can link to multiple competencies and experiences, and an experience can be reused in multiple lessons.

## Data quality rules
- IDs are stable and never reused for a different concept.
- Use observable language; avoid deficit labels and diagnostic conclusions.
- Record context; do not infer stable traits from one observation.
- Cite sources for research claims and identify design choices as such.
- Record safety checks and adaptations for each activity.
- Use fictional or anonymized examples.
- Never invent evidence, norms, or validation results.

## Open questions
1. Are these four record types sufficient for the first phase?
2. Which fields are essential versus optional for instructors?
3. Should observation records be kept outside this public repository with stronger privacy controls?
4. Which movement domains should the first ages 2–4 framework cover?
5. What review expertise is required before operational use?

## Acceptance criteria
An instructor should be able to understand the proposed record types, trace a lesson to competencies and experiences, identify safety/adaptation guidance, and distinguish draft from reviewed content. This model is not approved for production use until the Product Owner and relevant educators review it.
