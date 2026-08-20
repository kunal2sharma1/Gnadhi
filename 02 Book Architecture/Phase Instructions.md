# Checkpoint 2 — Phase Instructions

## Purpose

Build the manuscript-level architecture of *The Final Walk of Glory* from the completed Checkpoint 1 evidence and concept.

Checkpoint 2 is an architecture problem, not a writing problem.

## Operating Rule

### Parallel means genuinely parallel

Whenever three GPT workers are assigned in parallel:

- all three receive the same completed baseline;
- each has a different independent responsibility;
- none may read another worker's unfinished or newly created output;
- none may wait for another worker;
- none may make its work conditional on another worker's conclusion.

### Sequential means genuinely sequential

When reconciliation, synthesis or final decision requires the outputs of previous workers:

- the Product Manager handles the synthesis after all prerequisite files exist; or
- a later worker round is explicitly launched after the prerequisite output is complete.

Do not disguise a sequential dependency as parallel work.

## Phase 2.1 — Independent Architecture Models

### 2.1.1 — Historical Arc Design
**Assigned to:** GPT Worker 1

Determine the strongest historical/argumentative arc from Gandhi's final political period through the assassination, immediate post-assassination construction, later inheritance and selective contemporary epilogue.

Focus on:

- chronological engine;
- historical hinge;
- turning points;
- period boundaries;
- what must be established before and after the assassination;
- what can be omitted.

**Output:** `02.1 Historical Arc Design.md`

### 2.1.2 — Argument Architecture
**Assigned to:** GPT Worker 2

Independently design the major Parts and a provisional chapter sequence.

Focus on:

- what each Part must prove;
- what each chapter must accomplish;
- chapter sequence and dependencies;
- avoiding biography and controversy-catalogue structures;
- integrating Gandhi's critics into the argument;
- balancing assassination history with posthumous history.

**Output:** `02.2 Argument and Chapter Architecture.md`

### 2.1.3 — Case Study and Evidence Architecture
**Assigned to:** GPT Worker 3

Independently determine which historical cases are capable of carrying the book's major claims.

Focus on:

- essential case studies;
- supporting cases;
- excluded cases;
- claim-to-case mapping;
- primary-source burden;
- strongest counterarguments;
- modern case-selection criteria.

**Output:** `02.3 Case Study and Evidence Architecture.md`

## Phase 2.2 — Product Manager Architecture Reconciliation

### 2.2.1 — Cross-Worker Comparison
Compare the three independent architecture models.

Identify:

- convergence;
- contradictions;
- duplicated chapters/cases;
- missing mechanisms;
- overly broad sections;
- structural risks.

**Output:** `02.2.1 Cross-Worker Architecture Comparison.md`

### 2.2.2 — Master Architecture Draft
Build one provisional master architecture from the strongest elements.

The master must contain:

- Parts;
- chapter sequence;
- chapter objectives;
- core questions;
- evidence burden;
- major case studies;
- dependencies;
- transitions;
- provisional ending.

**Output:** `02.2.2 Master Book Architecture.md`

## Phase 2.3 — Architecture Stress Test

Use the completed master architecture as the common baseline.

All three GPT workers work in parallel again.

### Worker 1 — Historical Stress Test
Attack:

- chronology;
- causal transitions;
- historical overreach;
- weak period boundaries;
- presentism;
- whether the assassination remains central without dominating the book.

**Output:** `02.3.1 Worker 1 Historical Stress Test.md`

### Worker 2 — Reader/Argument Stress Test
Attack:

- chapter redundancy;
- pacing;
- unclear argumentative progression;
- chapter ordering;
- weak openings/endings;
- biography drift;
- political-polemic drift.

**Output:** `02.3.2 Worker 2 Reader and Argument Stress Test.md`

### Worker 3 — Evidence/Case Stress Test
Attack:

- unsupported chapters;
- weak case studies;
- insufficient primary evidence;
- ambiguous intent/effect claims;
- modern continuity overreach;
- cases that consume space without proving anything important.

**Output:** `02.3.3 Worker 3 Evidence and Case Stress Test.md`

## Phase 2.4 — Final Architecture Decision

### 2.4.1 — Stress-Test Reconciliation
**Assigned to:** Product Manager

Compare the three stress tests and revise the master architecture.

Record every major structural change and why it was made.

**Output:** `02.4.1 Final Architecture Revision.md`

### 2.4.2 — Architecture Decision
**Assigned to:** Product Manager

Lock the final architecture provisionally for the next checkpoint.

The decision must record:

- final Parts;
- final chapter sequence;
- chapter purpose;
- required evidence;
- selected case studies;
- exclusions;
- unresolved structural questions.

**Output:** `02.4.2 Architecture Decision.md`

## Phase 2.5 — Architecture Completion Review

### 2.5.1 — Completion Audit
Check the architecture against the Checkpoint 2 objective and completion standard.

**Output:** `02.5.1 Completion Audit.md`

### 2.5.2 — Next Checkpoint Design Brief
Define only the high-level objective and required outcomes of the next checkpoint. Do not prematurely design its detailed phases.

**Output:** `02.5.2 Next Checkpoint Design Brief.md`

### 2.5.3 — Formal Checkpoint Close
State whether Checkpoint 2 is complete, identify the authoritative architecture files, and define the exact starting context for the next checkpoint.

**Output:** `Checkpoint 2 Completion Review.md`

## Research Rule

Do not launch broad new historical research merely because a worker wants more context.

Architecture-level research is allowed only when:

- a factual issue changes chapter placement;
- a case-study decision depends on a disputed historical fact;
- a chapter cannot be responsibly included without targeted verification;
- or a structural claim depends on a historiographical distinction.

When research is needed, use ChatGPT web research and record the result in the relevant architecture file.

## Architecture Quality Rule

A good architecture must make it obvious:

1. why each chapter exists;
2. what evidence it must establish;
3. what question it advances;
4. what the reader should understand afterward;
5. why the next chapter follows.

If a chapter cannot answer those five questions, it does not belong in the architecture yet.

## Status

Phase 2.1 ready to begin.
