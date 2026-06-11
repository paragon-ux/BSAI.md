# BSAI.md

## Before Scaling with AI: Apparent Type, Relative Scope, and Human Decision

**Status:** Release 1.0
**Format:** Portable Markdown method
**Intended placement:** Repository root, documentation folder, project folder, prompt package, or review workspace
**Primary purpose:** Report likely AI interpretation of project artifacts before AI-assisted work scales

---

## 1. Identity

**BSAI** stands for **Before Scaling with AI**.

`BSAI.md` is a lightweight Markdown method for reviewing project artifacts before they guide AI-assisted work.

BSAI is not a coding-agent skill, automation framework, requirements standard, compliance system, certification process, software-development lifecycle, approval gate, routing system, or integration layer.

BSAI does not grant implementation authority.

BSAI exists because AI systems and coding agents infer document role, scope, and authority even when project owners do not intend those inferences. A document that calls itself a specification can function like a product brief. A research note can be treated as implementation guidance. A narrow design note can be over-applied to an entire project. A broad vision document can be converted into tasks, code, tests, or decisions without enough evidence.

BSAI makes those likely interpretations visible before scaling with AI.

The core identity is:

> **BSAI.md is a portable Markdown method for reporting apparent document type, relative document scope, likely agent interpretation, evidence, confidence, ambiguity, and human decisions required before AI-assisted work scales. It does not recommend, authorize, integrate, approve, or decide.**

---

## 2. Core Principle

BSAI does not decide what an artifact truly is.

BSAI does not decide what an artifact is authorized to govern.

BSAI does not decide whether an artifact guides implementation.

BSAI asks four questions:

1. **What does this artifact appear to be?**
2. **How much of the project does this artifact appear to cover?**
3. **How does an AI agent likely interpret or over-interpret it?**
4. **Where is human decision required before later AI-assisted use?**

BSAI treats document classification as **apparent and relative**, not absolute.

An artifact's declared label is evidence. It is not final authority.

An artifact's scope depends on surrounding project context. It is not always knowable from the artifact alone.

An artifact's authority is a human, team, or governance decision. BSAI exposes apparent authority and mismatch risk. It does not grant authority.

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

BSAI is not the decision layer.

---

## 4. Why BSAI Exists

Modern AI-assisted workflows turn written artifacts into execution inputs.

An artifact can influence:

- implementation tasks;
- code;
- tests;
- review criteria;
- architecture decisions;
- generated documentation;
- issue tickets;
- agent instructions;
- future project memory.

This changes the risk of vague, mislabeled, incomplete, or overextended project documents.

Before AI-assisted work scales, teams need a lightweight way to inspect how an artifact is likely to be interpreted.

BSAI provides that interpretation method.

BSAI is especially useful when a project contains multiple artifacts with overlapping, unclear, or misleading roles, such as:

- product briefs;
- PRDs;
- technical specifications;
- architecture notes;
- design documents;
- research notes;
- whitepapers;
- schemas;
- prompt packages;
- implementation plans;
- examples;
- roadmaps;
- standards drafts;
- agent instructions.

---

## 5. What BSAI Is

BSAI is:

- a Markdown-native review method;
- a pre-execution document interpretation aid;
- a way to make apparent document type explicit;
- a way to make relative document scope explicit;
- a way to identify type/scope mismatch;
- a way to surface likely agent misinterpretation;
- a way to document evidence, counter-evidence, ambiguity, and confidence;
- a way to identify where human decision is required before AI-assisted work continues.

BSAI works for:

- project owners;
- human reviewers;
- documentation maintainers;
- product teams;
- standards authors;
- coding agents;
- review agents;
- AI-assisted development workflows.

BSAI does not replace the human decision.

---

## 6. What BSAI Is Not

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

BSAI does not say:

> This artifact is definitively a specification.

It says:

> This artifact appears to function as a specification in this context.

BSAI does not say:

> This artifact governs the project.

It says:

> This artifact appears to cover this portion of the project relative to the surrounding artifact set.

BSAI does not say:

> This artifact is for implementation.

It says:

> An AI agent is likely to interpret this artifact in the following way; human decision is required before later AI-assisted use.

---

## 7. The Two Core Assessments

BSAI centers on two assessments:

1. **Apparent Document Type**
2. **Relative Document Scope**

These are not absolute classifications. They are reviewable interpretations.

### 7.1 Apparent Document Type

**Apparent Document Type** describes what kind of document an artifact appears to be, regardless of what it calls itself.

The guiding question is:

> What type of document does this artifact appear to function as?

Examples:

- A file titled `technical-spec.md` appears to function as a product requirements document.
- A file titled `research-paper.md` appears to function as a concept paper.
- A design document contains requirement-like statements.
- A PRD contains architecture decisions.
- A specification functions only as implementation guidance.
- A roadmap is mistaken for an execution plan.

Declared type matters only as evidence.

BSAI compares:

| Field | Meaning |
|---|---|
| Declared Type | What the artifact calls itself |
| Apparent Type | What the artifact appears to function as |
| Type Mismatch | Where declared type and apparent type diverge |

Apparent type is inferred from:

- title;
- file name;
- headings;
- structure;
- language;
- claims;
- evidence;
- level of specificity;
- acceptance criteria;
- implementation instructions;
- constraints;
- examples;
- intended reader;
- implied later use.

Apparent Document Type prevents type mismatch from remaining hidden.

An artifact is not treated as a specification merely because it calls itself one. A research note is not treated as binding requirements merely because it contains strong claims. A design note is not treated as a project-wide source of truth if it only supports one design decision.

### 7.2 Relative Document Scope

**Relative Document Scope** describes how much of the project an artifact appears to cover in relation to the surrounding artifact set.

The guiding question is:

> What portion of the project does this artifact appear to govern, describe, constrain, or inform relative to the other artifacts?

In BSAI, **govern** is descriptive, not prescriptive. It describes the portion of a project an artifact appears to govern, constrain, describe, or inform when interpreted by an AI system. It does not mean BSAI grants governing authority.

Relative Document Scope usually requires comparison against the surrounding project folder, artifact set, timeline, or documentation structure.

An artifact appears to cover one or more of these scopes:

- no implementation scope;
- background context only;
- one decision;
- one constraint;
- one feature;
- one workflow;
- one subsystem;
- one implementation area;
- one external interface;
- the whole project;
- an unclear or disputed scope.

Relative Document Scope prevents scope mismatch from remaining hidden.

A narrow design note is not treated as the source of truth for an entire product. A broad product brief is not treated as an implementation plan. A research note is not treated as a binding technical plan without human decision.

---

## 8. Scope Bands

BSAI avoids fake precision. It does not require exact percentages unless the project has already defined them.

Use coarse scope bands:

| Band | Scope | Description |
|---|---|---|
| 0 | No implementation scope | Background, notes, references, or context only |
| 1 | Local context | Narrow explanation, comment, or local rationale |
| 2 | Single decision or constraint | One decision, rule, assumption, or boundary |
| 3 | Feature or workflow | One feature, user flow, behavior group, or process |
| 4 | Subsystem or implementation area | One module, component, service, schema set, or technical area |
| 5 | Project-wide | Appears to describe, constrain, inform, or govern the project as a whole |
| ? | Unclear | Scope cannot be inferred with enough confidence |

Pair scope band with scope category.

Possible scope categories include:

- product scope;
- implementation scope;
- architecture scope;
- research scope;
- validation scope;
- interface scope;
- data scope;
- workflow scope;
- operational scope;
- governance scope;
- unknown or mixed scope.

---

## 9. Type and Scope Mismatch

BSAI is most useful when it detects mismatch.

Common mismatch patterns include:

| Pattern | Risk |
|---|---|
| Declared specification, apparent product brief | Agent over-implements vague intent |
| Declared research note, apparent design authority | Agent treats exploratory evidence as a binding plan |
| Declared technical spec, feature-level scope | Agent over-applies narrow details project-wide |
| Declared roadmap, apparent task plan | Agent converts aspirational sequence into execution steps |
| Declared architecture note, unclear authority | Agent treats one design option as the chosen design |
| Broad project brief, low implementation detail | Agent invents missing requirements |
| Detailed implementation note, narrow local scope | Agent applies a local solution globally |

BSAI reports mismatch. It does not resolve mismatch.

Resolution requires human decision.

---

## 10. Agent-Interpretation Risk

BSAI focuses on how an AI system is likely to interpret the artifact.

The assessment identifies likely risks such as:

- the agent treats the artifact as more authoritative than intended;
- the agent treats the artifact as broader than intended;
- the agent converts examples into requirements;
- the agent converts research claims into implementation decisions;
- the agent ignores missing acceptance criteria;
- the agent infers architecture from product language;
- the agent treats a draft as final;
- the agent merges conflicting artifacts without asking;
- the agent generates tasks from material that remains contextual;
- the agent implements unstated behavior to fill gaps.

The purpose is not to prevent all AI-assisted work.

The purpose is to force the interpretation problem into the open before scaling.

---

## 11. Confidence and Evidence

Every BSAI assessment includes confidence.

Use simple confidence levels:

| Confidence | Meaning |
|---|---|
| High | Strong internal and contextual evidence supports the assessment |
| Medium | The assessment is plausible but has meaningful ambiguity |
| Low | Evidence is weak, mixed, or dependent on unstated human intent |
| Unclear | The artifact cannot be assessed reliably without more context |

Every assessment includes:

- evidence;
- counter-evidence;
- ambiguity;
- required human decision.

BSAI does not hide uncertainty.

Uncertainty is part of the output.

---

## 12. BSAI Assessment Output

A BSAI assessment produces a report in this structure:

```markdown
# BSAI Assessment

## Artifact
- File:
- Declared Type:
- Project Context Reviewed:

## Apparent Document Type
- Apparent Type:
- Confidence:
- Evidence:
- Counter-Evidence:
- Type Mismatch:

## Relative Document Scope
- Scope Band:
- Scope Category:
- Confidence:
- Evidence:
- Counter-Evidence:
- Scope Mismatch:

## Likely Agent Interpretation
- Likely interpretation:
- Likely over-interpretation risk:
- Likely under-interpretation risk:
- Missing information the agent is likely to invent:

## Human Decision Required
- Does this artifact remain contextual?
- Does this artifact require revision?
- Does this artifact require splitting or merging?
- Does this artifact require conversion into a different artifact type?
- Does a human grant this artifact authority for later AI-assisted work?
- What limits require human definition before later AI-assisted use?

## BSAI Boundary Statement
BSAI does not grant implementation authority. This assessment only reports apparent document type, relative document scope, likely agent interpretation, evidence, confidence, ambiguity, and human decisions required.
```

---

## 13. How to Use BSAI.md

Use BSAI before asking an AI system to:

- interpret project documents;
- generate tasks from documents;
- generate code from documents;
- turn a prompt into a specification-like artifact;
- turn a specification-like artifact into an implementation plan;
- merge multiple project documents;
- infer requirements from research or notes;
- create later work packets from project artifacts;
- review whether a document is being interpreted beyond its apparent type or relative scope.

The simplest instruction is:

> Apply `BSAI.md` to the project artifacts. Report apparent document type, relative document scope, mismatch risk, likely agent interpretation, evidence, confidence, ambiguity, and human decisions required. Do not approve, reject, authorize, recommend, route, or decide later use.

---

## 14. BSAI Review Procedure

Use this procedure to complete a BSAI assessment.

### Step 1: Identify declared type

Ask:

> What does the artifact call itself?

Record title, filename, heading structure, and any explicit status claims.

### Step 2: Identify apparent type

Ask:

> What does the artifact appear to function as?

Compare structure, language, specificity, evidence, and implied use.

### Step 3: Identify relative scope

Ask:

> How much of the project does this artifact appear to cover relative to the surrounding artifact set?

Use a coarse scope band and scope category.

### Step 4: Identify mismatch

Ask:

> Where do declared type, apparent type, and relative scope diverge?

Report mismatch without resolving it.

### Step 5: Identify agent-interpretation risk

Ask:

> How is an AI agent likely to overuse, underuse, or misread this artifact?

Focus on apparent authority, scope expansion, and invented missing information.

### Step 6: Identify required human decision

Ask:

> What decision does a human need to make before this artifact influences later AI-assisted work?

BSAI stops here.

---

## 15. Portability

BSAI is intentionally a single Markdown method.

It fits in:

- a repository root;
- a documentation folder;
- an AI project folder;
- a prompt package;
- a standards draft folder;
- a planning workspace;
- a review checklist;
- an agent instruction bundle.

BSAI remains small enough to read, inspect, version, and modify.

If a project adds automation, scripts, agents, templates, or review tools can support BSAI assessments. The method itself remains understandable as Markdown.

BSAI remains independent of any specific later method, tool, standard, agent, or project.

---

## 16. Final Boundary

BSAI is not the decision.

BSAI is the warning label, interpretation report, and scope check before the decision.

It makes visible what an AI system otherwise assumes silently.

The final BSAI rule is:

> **Before scaling with AI, do not ask whether a document is important. Ask what it appears to be, how much it appears to cover, how an agent is likely to interpret it, and what human decision is required before later AI-assisted use.**
