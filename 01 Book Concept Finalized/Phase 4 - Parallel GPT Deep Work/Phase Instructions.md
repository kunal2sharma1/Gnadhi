# Phase 4 — Parallel GPT Deep Work

## Objective
Use the three other ChatGPT Go accounts simultaneously for an extended, multi-round analysis of the checkpoint using the approved research context.

## Worker model

### GPT Worker 1 — Primary Analyst
Develop the strongest evidence-supported interpretation of the book concept. Build the core analysis, definitions, central question, and provisional thesis from the research.

### GPT Worker 2 — Independent Analyst
Work independently from Worker 1. Reach an independent interpretation of the concept and research. Identify patterns, alternative explanations, and ideas that Worker 1 may miss.

### GPT Worker 3 — Adversarial Analyst
Actively challenge the concept. Search for contradictions, overstatement, unsupported causal links, ideological conflation, alternative explanations, and evidence that could invalidate the emerging argument.

## Sub-phases

### 4.1 — Worker 1: Primary Analysis
**Assigned to:** GPT Worker 1

Complete a long-form analytical work cycle using the Master Research Context Pack. Continue through multiple increasingly difficult tasks when the user sends “continue.” Do not stop after a shallow summary.

**Output:** `04.1 Worker 1 Primary Analysis.md`

### 4.2 — Worker 2: Independent Analysis
**Assigned to:** GPT Worker 2

Independently analyze the same evidence with a different reasoning path. Do not simply imitate the likely conclusion of Worker 1.

**Output:** `04.2 Worker 2 Independent Analysis.md`

### 4.3 — Worker 3: Adversarial Analysis
**Assigned to:** GPT Worker 3

Try to break the developing concept using the same research context. Identify what survives and what fails.

**Output:** `04.3 Worker 3 Adversarial Analysis.md`

### 4.4 — Continued Deep Work Rounds
**Assigned to:** GPT Workers 1, 2, and 3 in parallel

After the first outputs are returned, the Product Manager may send a new prompt to each worker based on the checkpoint state. Each worker should continue from its own conversation and deepen the work rather than repeat earlier summaries.

Possible continued rounds include:
- refining the central question;
- comparing competing thesis formulations;
- testing evidence against the thesis;
- identifying missing research;
- improving conceptual definitions;
- challenging the other workers' likely conclusions without copying them;
- preparing a recommendation for the Product Manager.

**Outputs:** Additional numbered Markdown files as assigned by the Product Manager.

## Execution rule
All three workers begin their first work cycle at the same time. Their assignments are different. No worker should wait for another worker to finish before starting.

## Five-hour session strategy
The checkpoint should contain enough legitimate analytical work that the workers can continue productively across their available session. The goal is not to manufacture filler. Each continuation must introduce a new analytical layer or resolve a real remaining question.

## Context rule
Every worker receives a self-contained context pack and exact task prompt. The worker must not be expected to know the book from memory or access an unavailable previous conversation.

## Completion condition
The three workers have produced substantial, independent and adversarial analyses that give the Product Manager enough material to compare conclusions and identify the remaining gaps.

## Status
Not started
