# BSAI Examples

These examples calibrate BSAI assessments across Relative Document Scope Bands 0–5 and one Unclear-confidence case.

Each example reviews one target artifact. Project context appears only in the Relative Document Scope pass.

Use examples after reading `BSAI.md` and before completing `templates/bsai-assessment-template.md`.

## Scope bands

| Band | Example file | Purpose |
|---|---|---|
| 0 | `band-0-no-implementation-scope-assessment.md` | Research or reference material with no apparent implementation scope. |
| 1 | `band-1-local-context-assessment.md` | Local note or setup context with limited project effect. |
| 2 | `band-2-design-note-overapplied-assessment.md` | Single design decision or constraint with over-application risk. |
| 3 | `band-3-feature-spec-assessment.md` | Aligned feature or workflow artifact. |
| 3 | `band-3-technical-spec-as-prd-assessment.md` | Declared technical specification that functions like a feature-level PRD. |
| 4 | `band-4-subsystem-architecture-assessment.md` | Subsystem or implementation-area artifact. |
| 5 | `band-5-project-wide-product-brief-assessment.md` | Project-wide apparent scope without BSAI-granted project-wide authority. |

## Confidence calibration

| Example file | Purpose |
|---|---|
| `unclear-confidence-conflicting-artifact-assessment.md` | Conflicting type and scope signals where forcing a single classification creates false-positive risk. |

## Use

For calibrated review:

1. Read `BSAI.md`.
2. Review `templates/bsai-assessment-template.md`.
3. Select the example whose apparent outcome most closely resembles the target artifact.
4. Compare the target artifact against the example structure.
5. Complete `templates/bsai-assessment-template.md`.
6. End at `Human Decisions Required`.

The examples are not approval models. They show how to report apparent type, relative scope, likely agent interpretation, evidence, confidence, counter-evidence, ambiguity, and human decisions required.
