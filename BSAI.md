# BSAI.md

## Before Scaling with AI: Apparent Type, Relative Scope, and Human Decision

**Status:** Stable release 1.0.2  
**Format:** Portable Markdown method  
**Intended placement:** Repository root, documentation folder, project folder, prompt package, or review workspace  
**Primary purpose:** Report likely AI interpretation of one target artifact before AI-assisted work scales

---

## 1. Identity

**BSAI** stands for **Before Scaling with AI**.

`BSAI.md` is a lightweight Markdown method for reviewing one target project artifact before it guides AI-assisted work.

BSAI exists because AI systems infer document role, scope, and authority even when project owners do not intend those inferences. A document that calls itself a specification can function like a product brief. A research note can be treated as implementation guidance. A narrow design note can be over-applied to an entire project. A broad vision document can be converted into tasks, code, tests, reviews, or decisions without enough supporting evidence.

BSAI makes those likely interpretations visible before scaling with AI.

The core identity is:

> **BSAI.md is a portable Markdown method for reporting apparent document type, relative document scope, likely agent interpretation, evidence, confidence, ambiguity, and human decisions required before AI-assisted work scales. It does not recommend, authorize, integrate, approve, or decide.**

---

## 2. Artifact

In BSAI, an **artifact** is any project material that can influence AI-assisted work.

Artifacts include documents, notes, specifications, requirements, design records, architecture notes, research notes, prompt packages, schemas, examples, plans, roadmaps, standards drafts, and instruction bundles.

A BSAI assessment reviews one target artifact at a time.

Project context supports Relative Document Scope only. It does not turn BSAI into whole-project governance, source-of-truth selection, artifact ranking, or downstream approval.

---

## 3. Non-Decision Constraint

A BSAI assessment must not approve, reject, authorize, certify, rank, route, recommend, or prescribe later use.

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

Any later decision belongs to a human, team process, governance process, or separate tool.

---

## 4. Review Environment and Order

A BSAI assessment begins in a fresh review context.

The reviewer or agent does not rely on prior conversation history, author intent, roadmap assumptions, product plans, or downstream implementation goals unless those materials are explicitly included in the review environment.

BSAI uses this order:

1. **Fresh review context** — start without unstated prior assumptions.
2. **Apparent Document Type** — review the target artifact in isolation.
3. **Relative Document Scope** — add surrounding project context after the type pass.
4. **Agent Interpretation Risk** — report likely overuse, underuse, and invented missing information.
5. **Human Decisions Required** — identify decisions without answering them.

Apparent Document Type comes before Relative Document Scope.

The type pass uses the target artifact alone.

The scope pass uses the target artifact plus surrounding project context needed to understand relative coverage.

BSAI does not perform full multi-artifact governance, resolve cross-document authority, rank source-of-truth documents, or decide which artifact controls later work.

---

## 5. Core Classifications

BSAI enables two core classifications.

| Classification | What it reports | Review environment |
|---|---|---|
| `Apparent Document Type` | What the target artifact appears to function as | Fresh context, target artifact only |
| `Relative Document Scope` | How much of the project the target artifact appears to cover | Target artifact plus surrounding project context |

These classifications inform later human decisions. They do not make those decisions.

---

## 6. Apparent Document Type

Apparent Document Type reports what the target artifact appears to function as, regardless of the label it gives itself.

The guiding question is:

> What type of document does this artifact appear to be when reviewed by itself?

Examples:

- a file labeled `technical-spec.md` that functions like a product requirements document;
- a file labeled `research-notes.md` that functions like exploratory context;
- a file labeled `design.md` that functions like an architecture decision note;
- a file labeled `requirements.md` that functions like a loose feature brief;
- a file labeled `specification.md` that functions like implementation guidance.

The declared type is evidence. It is not final authority.

Apparent Document Type prevents type mismatch.

---

## 7. Relative Document Scope

Relative Document Scope reports how much of the project the target artifact appears to cover when placed against surrounding project context.

The guiding question is:

> How much of the project does this target artifact appear to cover relative to the surrounding project context?

In BSAI, **govern** is descriptive, not prescriptive. It describes the portion of a project an artifact appears to govern, constrain, describe, or inform when interpreted by an AI system. It does not mean BSAI grants governing authority.

Scope bands:

| Band | Relative scope |
|---|---|
| 0 | No implementation scope |
| 1 | Local note or local context |
| 2 | Single decision or constraint |
| 3 | Feature or workflow |
| 4 | Subsystem or implementation area |
| 5 | Project-wide apparent scope |

Scope categories include product scope, implementation scope, research scope, architecture scope, validation scope, operations scope, and external-interface scope.

Relative Document Scope prevents scope mismatch.

Band 5 reports project-wide apparent scope for the target artifact. It does not grant project-wide authority.

---

## 8. Type and Scope Mismatch

Type mismatch occurs when the artifact's declared label and apparent function diverge.

Scope mismatch occurs when the artifact appears likely to be used beyond or below its apparent relative scope.

Examples:

- a technical specification that functions like a product brief;
- a research note that contains design-authority language;
- a design note that looks local but uses project-wide phrasing;
- a project overview that gets treated as implementation-ready specification;
- a narrow feature specification that gets applied to adjacent features.

BSAI reports mismatch risk. It does not resolve mismatch risk.

---

## 9. Likely Agent Interpretation

A BSAI assessment reports how an AI system is likely to interpret the target artifact.

This includes:

- likely interpretation;
- likely over-interpretation risk;
- likely under-interpretation risk;
- missing information the agent is likely to invent.

The purpose is not to predict every output. The purpose is to expose plausible failure modes before AI-assisted work scales.

---

## 10. Evidence, Counter-Evidence, Confidence, and Ambiguity

A BSAI assessment records evidence and counter-evidence for each core classification.

Evidence supports the apparent type or relative scope.

Counter-evidence limits, weakens, or complicates the classification.

Confidence records how stable the assessment appears:

- **High** — evidence and counter-evidence strongly support the classification.
- **Medium** — evidence supports the classification, but material uncertainty remains.
- **Low** — evidence is weak, conflicting, incomplete, or unstable.
- **Unclear** — available evidence does not support a stable classification; report competing interpretations rather than forcing a single classification.

BSAI does not hide uncertainty.

Ambiguity appears through confidence and counter-evidence. Low or Unclear confidence is a valid BSAI output, not a failed assessment.

---

## 11. Human Decisions Required

A BSAI assessment ends by identifying decisions that require a human, team process, governance process, or separate tool.

Decision questions can include:

- Does the target artifact remain contextual?
- Does the target artifact require revision?
- Does the target artifact require splitting or merging?
- Does the target artifact require conversion into a different artifact type?
- Does a human grant the target artifact authority for later AI-assisted work?
- What limits require human definition before later AI-assisted use?

BSAI identifies the questions. It does not answer them.

---

## 12. Review Procedure

Use this procedure for a complete BSAI assessment:

1. Start a fresh review context.
2. Identify the target artifact, declared type, and declared status.
3. Review Apparent Document Type using the target artifact only.
4. Record type evidence, counter-evidence, confidence, and type mismatch.
5. Add surrounding project context for Relative Document Scope.
6. Record scope band, scope category, project context reviewed, evidence, counter-evidence, confidence, and scope mismatch.
7. Report likely agent interpretation, likely over-interpretation risk, likely under-interpretation risk, and missing information the agent is likely to invent.
8. End with Human Decisions Required and the BSAI Boundary Statement.

The procedure does not authorize later use.

---

## 13. Assessment Output

Use `templates/bsai-assessment-template.md` for the complete output structure.

A complete BSAI assessment includes:

1. Review Environment
2. Artifact
3. Apparent Document Type
4. Relative Document Scope
5. Likely Agent Interpretation
6. Human Decisions Required
7. BSAI Boundary Statement

Every complete assessment closes with the BSAI Boundary Statement.

---

## 14. What BSAI Is Not

BSAI is not:

- a requirements-governance framework;
- a formal specification standard;
- a compliance framework;
- a security review;
- a privacy review;
- a legal review;
- a production-readiness review;
- a code-review system;
- a PR/MR review agent;
- a project-management method;
- a software-development lifecycle;
- a certification process;
- a guarantee of correctness;
- a guarantee of implementation fitness;
- a guarantee of external interoperability;
- a replacement for human judgment.

Do not use BSAI as a substitute for code review, implementation approval, artifact ranking, source-of-truth selection, downstream routing, or forced specification conversion.

---

## 15. Final Boundary

BSAI is not the decision.

BSAI is the warning label, interpretation report, and scope check before the decision.
