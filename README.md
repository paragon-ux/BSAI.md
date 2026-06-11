# BSAI.md v1.0.1

Before Scaling with AI is a portable Markdown method for reporting how AI agents are likely to interpret a target project artifact before AI-assisted work scales.

BSAI does not recommend, authorize, approve, integrate, route, certify, or decide. BSAI ends at `Human Decisions Required`.

## Core classifications

| Classification | What it reports | Review environment |
|---|---|---|
| `Apparent Document Type` | What the target artifact appears to function as | Fresh context, target artifact only |
| `Relative Document Scope` | How much of the project the target artifact appears to cover | Target artifact plus surrounding project context |

Classify `Apparent Document Type` before `Relative Document Scope`.

Use project context only after the type pass.

BSAI assesses one target artifact at a time. Project context supports scope classification; it does not turn BSAI into whole-project governance, source-of-truth selection, document ranking, or downstream approval.

## Quickstart

### Option 1: Download only `BSAI.md`

Use this path for a lightweight agent review.

1. Download `BSAI.md`.
2. Start a fresh session or fresh review context.
3. Provide the target artifact.
4. Ask the agent to classify `Apparent Document Type` from the target artifact alone.
5. Provide the surrounding project context.
6. Ask the agent to classify `Relative Document Scope`.
7. End at `Human Decisions Required`.

### Option 2: Copy the full BSAI environment

Use this path for calibrated agent review inside a repository.

1. Copy `BSAI.md`.
2. Copy `templates/bsai-assessment-template.md`.
3. Copy `examples/aligned-feature-spec-assessment.md`.
4. Copy `examples/technical-spec-as-prd-assessment.md`.
5. Copy `examples/research-note-scope-risk-assessment.md`.
6. Copy `examples/design-note-overapplied-assessment.md`.
7. Start a fresh session or fresh review context.
8. Have the agent use `BSAI.md`, fill `templates/bsai-assessment-template.md`, and calibrate against the examples.
9. End at `Human Decisions Required`.

## Repository contents

```text
BSAI.md
README.md
examples/
  aligned-feature-spec-assessment.md
  technical-spec-as-prd-assessment.md
  research-note-scope-risk-assessment.md
  design-note-overapplied-assessment.md
templates/
  bsai-assessment-template.md
```

## What BSAI reports

A BSAI assessment reports:

- declared type;
- apparent type;
- relative scope;
- type mismatch;
- scope mismatch;
- likely agent interpretation;
- likely over-interpretation risk;
- likely under-interpretation risk;
- confidence;
- evidence;
- counter-evidence;
- ambiguity;
- human decisions required.

## What BSAI does not do

BSAI does not:

- approve artifacts;
- reject artifacts;
- authorize implementation;
- certify documents;
- recommend downstream use;
- select downstream tools;
- integrate with downstream workflows;
- rank source-of-truth documents;
- resolve cross-document authority;
- replace human judgment;
- decide what happens next.

BSAI is not the decision.

BSAI is the warning label, interpretation report, and scope check before the decision.
