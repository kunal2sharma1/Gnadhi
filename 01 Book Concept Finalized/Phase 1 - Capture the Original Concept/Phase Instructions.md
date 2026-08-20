# Phase 1 — Capture the Original Concept

## Objective
Capture the author’s original idea for *The Final Walk of Glory* exactly as the starting point for the project, before research, criticism, or rewriting changes it.

## What this phase must accomplish
Create a reliable record of the author’s own thinking. Grammar, wording, and structure can be imperfect. The priority is preserving the idea, the motivation behind it, the intended argument, the emotional effect, and the questions the author wants the book to investigate.

This phase does not prove the historical thesis. It separates the author’s current idea from facts that will later need evidence.

## Sub-phases

### Sub-phase 1.1 — Capture the Author's Raw Idea
**Assigned to:** This ChatGPT account — Product Manager

**Work:** Work directly with the author to capture the complete concept in the author’s natural language. Clarify the intended subject, why the book matters, what the author thinks is happening, what “The Final Walk of Glory” means, and what the author wants the reader to understand.

**Output:** `01.1 Author Concept Record.md`

### Sub-phase 1.2 — Independent Concept Interpretation
**Assigned to:** ChatGPT Go execution account

**Work:** Give the execution account a self-contained context package containing the phase objective and the completed 01.1 record. Ask it to explain what it believes the book is trying to investigate, identify the strongest ideas, identify ambiguities, and identify assumptions that must later be tested. It must not rewrite the author's idea into a different thesis.

**Output:** `01.2 Independent Concept Interpretation.md`

### Sub-phase 1.3 — Product Manager Consolidation
**Assigned to:** This ChatGPT account — Product Manager

**Work:** Compare the author’s raw concept with the independent interpretation. Preserve the author’s meaning, resolve misunderstandings, identify differences, and produce the official concept summary for the next phase.

**Output:** `01.3 Concept Summary.md`

## Execution rule for all sub-phases
The execution account will not be expected to remember previous chats. The prompt must explicitly provide the phase file, the required previous output, the exact objective, and the expected Markdown output. The agent must treat the supplied files as its complete context for the task.

## Handoff rule
Every completed sub-phase must produce a Markdown file that another ChatGPT account can understand without access to the previous conversation. The output must include the work completed, important decisions, uncertainties, and anything the next agent needs to know.

## Completion condition
The author’s original concept is documented, independently interpreted, compared, and consolidated into a clear concept summary.

## Next phase dependency
Phase 2 must use the approved Phase 1 outputs as its context. The Product Manager will prepare the exact context package and assignment prompt for each Phase 2 sub-phase.

## Status
Not started
