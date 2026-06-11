# BSAI.md

Before Scaling with AI is a portable Markdown method for reporting how AI agents are likely to interpret project documents before AI-assisted work scales.

BSAI reports apparent document type, relative document scope, likely agent interpretation, evidence, confidence, ambiguity, and human decisions required.

BSAI does not recommend, authorize, approve, route, integrate, certify, or decide downstream use.

## Quickstart

### Option 1 — Use only `BSAI.md`

Use this path for a lightweight agent review with one portable method file.

1. Download `BSAI.md`.
2. Place `BSAI.md` where the AI agent can read it.
3. Give the AI agent the artifact or project document set under review.
4. Give the AI agent the surrounding project context: folder context, related documents, project boundaries, timeline, and known ambiguities.
5. Instruct the AI agent to read `BSAI.md` and produce a BSAI assessment.
6. End at `Human Decisions Required`.

Human-only review uses the same path: read `BSAI.md`, assess the artifact, and write the same assessment fields manually.

### Option 2 — Copy the full BSAI environment

Use this path for calibrated agent review inside a repository.

Copy these files into the repository:

```text
BSAI.md
templates/bsai-assessment-template.md
examples/aligned-feature-spec-assessment.md
examples/technical-spec-as-prd-assessment.md
examples/research-note-scope-risk-assessment.md
examples/design-note-overapplied-assessment.md
```

Then instruct the AI agent to:

1. Read `BSAI.md`.
2. Use `templates/bsai-assessment-template.md` as the output format.
3. Use `examples/aligned-feature-spec-assessment.md` for aligned type/scope calibration.
4. Use `examples/technical-spec-as-prd-assessment.md` for declared-type mismatch calibration.
5. Use `examples/research-note-scope-risk-assessment.md` for research-context scope-risk calibration.
6. Use `examples/design-note-overapplied-assessment.md` for over-applied design-note calibration.
7. Produce a BSAI assessment only.
8. End at `Human Decisions Required`.

## Use cases

Use `BSAI.md` before AI-assisted work relies on:

- planning notes;
- research notes;
- product requirements;
- specifications;
- design notes;
- architecture notes;
- implementation guidance;
- prompt packages;
- documentation folders.

Use `BSAI.md` when a document could be interpreted as stronger, broader, narrower, more authoritative, or more implementation-ready than its apparent type and relative scope support.

## BSAI assessment outputs

A BSAI assessment reports:

- declared document type;
- apparent document type;
- relative document scope;
- type mismatch;
- scope mismatch;
- likely AI interpretation;
- likely over-interpretation risk;
- likely under-interpretation risk;
- confidence;
- evidence;
- counter-evidence;
- ambiguity;
- human decisions required.

## Boundary

BSAI is not the decision.

BSAI is the warning label, interpretation report, and scope check before the decision.

A BSAI assessment does not approve artifacts, reject artifacts, authorize implementation, certify documents, recommend downstream use, select downstream tools, integrate with downstream workflows, replace human judgment, or decide what happens next.

## Repository documents

`BSAI.md` defines the portable method.

`README.md` provides quickstart instructions and repository navigation.

`templates/bsai-assessment-template.md` provides the reusable assessment output format.

`examples/aligned-feature-spec-assessment.md` shows an aligned assessment where declared type, apparent type, and relative scope align while human decision remains required.

`examples/technical-spec-as-prd-assessment.md` shows an apparent-type mismatch where a document labeled as a technical specification functions more like a product requirements document.

`examples/research-note-scope-risk-assessment.md` shows a scope-risk assessment where research context risks being treated as implementation authority.

`examples/design-note-overapplied-assessment.md` shows a scope mismatch where a narrow design note risks being applied beyond its apparent scope.

## About

BSAI.md is a portable Markdown method for reporting how AI agents are likely to interpret project documents before AI-assisted work scales.
