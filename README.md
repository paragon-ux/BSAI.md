# BSAI.md v1.0.2

Before Scaling with AI is a portable Markdown method for reporting how AI agents are likely to interpret one target project artifact before AI-assisted work scales.

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

1. Copy `BSAI.md`.
2. Copy `templates/bsai-assessment-template.md`.
3. Copy `examples/README.md`.
4. Copy the files in `examples/`.
5. Start a fresh session or fresh review context.
6. Read `BSAI.md`.
7. Use `templates/bsai-assessment-template.md` as the assessment output format.
8. Use `examples/README.md` and the example assessments for calibration.
9. End at `Human Decisions Required`.

For lightweight manual setup, `BSAI.md` can be used alone. For calibrated agent review, use `BSAI.md`, `templates/bsai-assessment-template.md`, `examples/README.md`, and the example assessments together.

## Repository contents

```text
BSAI.md
README.md
examples/
  README.md
  band-0-no-implementation-scope-assessment.md
  band-1-local-context-assessment.md
  band-2-design-note-overapplied-assessment.md
  band-3-feature-spec-assessment.md
  band-3-technical-spec-as-prd-assessment.md
  band-4-subsystem-architecture-assessment.md
  band-5-project-wide-product-brief-assessment.md
  unclear-confidence-conflicting-artifact-assessment.md
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
