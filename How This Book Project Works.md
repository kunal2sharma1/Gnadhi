# How This Book Project Works

## Purpose of This File

This file is the permanent operating guide for *The Final Walk of Glory*.

It explains how the project is organized, how ChatGPT and Claude accounts are used, how work is assigned, how information is preserved, and how each checkpoint is completed.

This file applies to the entire project unless a later checkpoint-specific instruction deliberately changes the workflow for a documented reason.

---

## 1. The Core Structure

The book is divided into **25 Checkpoints**.

Each checkpoint is a major milestone in building the book.

A checkpoint contains:

**Phases → Work assignments → Outputs → Review → Checkpoint completion**

The detailed phases and work inside a checkpoint are **not permanently fixed in advance**.

They are designed when that checkpoint begins, based on:

- what previous checkpoints established
- what remains unknown
- what research is required
- what contradictions have appeared
- what the book currently needs

At the end of every checkpoint, the findings determine how the next checkpoint should be designed.

---

# 2. The Four ChatGPT Accounts

There are four ChatGPT Go accounts available for the project, including this account.

### This ChatGPT account

**Role: Product Manager + Chief Editor + Workflow Controller**

This account is responsible for:

- understanding the overall book
- maintaining the project direction
- designing each checkpoint's workflow
- deciding what research is required
- assigning work to the other ChatGPT accounts
- deciding when Claude research is required
- comparing outputs from different agents
- identifying contradictions and gaps
- deciding what work should continue
- consolidating important findings
- approving checkpoint completion
- designing the high-level brief for the next checkpoint

This account does **not** need to perform every piece of execution itself.

Its main responsibility is to make sure the right work is being done in the right order by the right agent.

### Three other ChatGPT Go accounts

These are the **parallel execution workers**.

They should normally work simultaneously on different aspects of the same checkpoint.

Their exact roles can change from checkpoint to checkpoint, but typical roles are:

- Primary Analyst
- Independent Analyst
- Adversarial / Critical Analyst

The goal is not to make three accounts produce three copies of the same work.

They must receive **different objectives** so that their outputs can later be compared.

---

# 3. The Seven Claude Accounts

The seven Claude free accounts are used primarily for **targeted deep research**.

Claude is not treated as the permanent memory of the project.

Claude may not be able to access the repository or previous conversation reliably, so every Claude assignment must be self-contained.

The seven accounts are used as seven separate research opportunities.

For each checkpoint, the Product Manager decides what the seven most valuable research questions are.

The research assignments should be:

- narrow
- precise
- independently useful
- realistically completable within one free Claude session
- focused on evidence rather than broad essays

A Claude account should **not** be given a vague assignment such as:

> Research Gandhi in detail.

Instead, it should receive a bounded question such as:

> Establish the documented sequence of events surrounding a specific historical episode, identify the strongest primary and secondary sources, note disputed details, and separate established evidence from later interpretation.

The purpose is to obtain **seven complementary research packets**, not seven incomplete encyclopedias.

---

# 4. Claude Research Before GPT Execution

For a major checkpoint, the normal sequence is:

**Research planning → Seven Claude research assignments → Research packets → GPT execution**

Claude research should be completed before the main parallel GPT work begins whenever the checkpoint depends heavily on historical or external evidence.

The Product Manager decides whether all seven Claude slots are needed.

Some checkpoints may use all seven.

Some may use fewer if the evidence need is smaller.

Unused Claude capacity should not be filled with unnecessary research.

---

# 5. Claude Research Packet Standard

Every Claude research task must produce a structured Markdown research packet.

The packet should contain, where relevant:

### Research Question
The exact question assigned.

### Scope
What the research covers and what it deliberately excludes.

### Key Findings
The most important findings.

### Primary Evidence
Primary sources and what they establish.

### Secondary Evidence
Relevant scholarly or reputable secondary sources.

### Important Quotations
Only quotations that are important enough to verify and potentially use later.

### Competing Interpretations
Where historians or sources disagree.

### Disputed Points
Claims that are uncertain or contested.

### What We Can Safely Claim
Claims supported strongly enough for later consideration.

### What We Cannot Yet Claim
Claims that remain unsupported, uncertain, or overstated.

### Research Gaps
What still needs investigation.

### Sources
A usable list of sources for later verification.

### Handoff to GPT
A concise explanation of how the findings should be used in the next stage.

Claude should not write book chapters unless a later checkpoint explicitly assigns that task.

---

# 6. GitHub Is the Permanent Project Memory

GitHub is the central archive of the project.

Important work should not remain only inside an AI conversation.

When useful work is completed, it is converted into a readable Markdown document and placed in the repository.

The repository contains:

- checkpoint instructions
- phase instructions
- research packets
- analysis outputs
- important findings
- decisions
- unresolved questions
- final checkpoint reviews
- eventual manuscript material

The repository is therefore the project's **long-term memory**.

An AI account may disappear, hit a limit, or lose conversation context.

The project must still be able to continue from the files.

---

# 7. No Agent Is Expected to Remember the Project

This is a core rule.

A fresh ChatGPT or Claude conversation must never be expected to know what happened in earlier conversations.

Before assigning work, the Product Manager prepares a **self-contained context package**.

The context package should contain only the material required for that assignment.

It should normally include:

- the relevant checkpoint objective
- the relevant phase instructions
- previous approved outputs needed for context
- important decisions
- unresolved questions
- the exact task
- the expected output structure
- the completion condition

The worker should be able to perform the assignment using that package without needing access to an earlier conversation.

---

# 8. GPT Work Is Parallel, Not Sequential

The three execution ChatGPT accounts should normally start at approximately the same time.

They receive different assignments.

A typical parallel arrangement is:

### Worker 1 — Primary Analysis
Build the strongest evidence-based understanding of the checkpoint problem.

### Worker 2 — Independent Analysis
Approach the problem independently and reach conclusions without simply copying Worker 1.

### Worker 3 — Adversarial Analysis
Search for contradictions, unsupported assumptions, alternative explanations, weak logic, and evidence that could change the conclusion.

The exact roles may change for a particular checkpoint.

The principle remains the same:

**Different agents should produce different intellectual value.**

---

# 9. Use Long GPT Sessions Properly

The project is designed to make productive use of long ChatGPT sessions.

A worker should not be stopped after completing one small task when deeper useful work remains.

The worker can be given a **continue** instruction to move to the next defined stage of its assignment.

The continuation should build on the same conversation and the same approved context.

The goal is to use the available session deeply, not to restart repeatedly with the same information.

However, the project must never stretch work merely to consume time.

The objective is **maximum useful reasoning**, not maximum token consumption.

---

# 10. Each Worker Must Leave a Handoff

Every major worker output should be understandable to another agent.

Where appropriate, the output should include:

- what was completed
- what was established
- what remains uncertain
- important decisions
- important evidence
- contradictions found
- questions requiring further work
- recommended next step

This makes it possible to continue the work even if the original conversation ends.

---

# 11. Product Manager Review Between Major Stages

The Product Manager should not simply collect outputs and paste them together.

After major parallel work, this account reviews:

- agreements
- disagreements
- contradictions
- duplicated work
- unsupported claims
- research gaps
- stronger interpretations
- weaker interpretations
- new questions

The Product Manager then decides what happens next.

Possible next actions include:

- continue GPT analysis
- assign a new GPT task
- request targeted Claude research
- reject an argument
- merge compatible findings
- revise the checkpoint objective
- redesign the next phase

---

# 12. Claude Can Be Used Again After GPT Analysis

Claude research is not limited to the beginning of a checkpoint.

The normal pattern is:

**Initial Claude research → GPT analysis → identify gaps → targeted Claude research → GPT reconciliation**

The second Claude round should only happen when the GPT analysis exposes a genuine evidence gap.

The new Claude assignment must be even more precise than the first one.

For example:

> Verify whether this specific claim is supported by primary evidence and identify the strongest scholarly disagreement.

That is preferable to restarting a broad research task.

---

# 13. Evidence and Interpretation Must Stay Separate

This project deals with history and political ideology.

AI-generated interpretation must never automatically become historical fact.

The project should distinguish between:

**Established evidence**

**Reasonable interpretation**

**Author's hypothesis**

**Unresolved question**

**Disputed claim**

This distinction must be maintained throughout the research and manuscript process.

---

# 14. The Book's Thesis Is Always Provisional Until the Evidence Earns It

The project begins with the author's idea.

The research is allowed to challenge that idea.

The thesis can:

- become stronger
- become narrower
- change substantially
- split into multiple arguments
- or be rejected

We do not protect the original thesis simply because it is the reason the project started.

A stronger book is more important than preserving an early assumption.

---

# 15. Checkpoint Structure

The project contains 25 fixed checkpoints.

The **checkpoint objectives are fixed at the roadmap level**.

The detailed phases and sub-phases underneath them are adaptive.

A checkpoint normally follows this broad pattern:

**Checkpoint Start**

↓

**Research Planning**

↓

**Targeted Claude Research**

↓

**Research Consolidation**

↓

**Parallel GPT Work**

↓

**Cross-Worker Review**

↓

**Gap Identification**

↓

**Additional Targeted Research, if needed**

↓

**Final Synthesis**

↓

**Checkpoint Completion Review**

↓

**Design the Next Checkpoint**

This is the default pattern, not a rigid formula.

---

# 16. Checkpoint Completion Review

A checkpoint is not complete simply because the assigned conversations ended.

The Product Manager must determine whether the checkpoint objective was actually achieved.

The completion review should record:

### What We Established

### What We Disproved

### What Became More Likely

### What Remains Uncertain

### Important Evidence

### Important Contradictions

### Research Gaps

### Changes to the Book's Direction

### Lessons for the Next Checkpoint

### High-Level Objective for the Next Checkpoint

The exact next phases and sub-phases are designed only after this review.

---

# 17. Parallel Work Does Not Mean Uncontrolled Work

Parallel execution is useful only when the workers have clearly different jobs.

We should avoid:

- three workers writing the same answer
- seven Claude accounts researching the same broad topic
- repeating the same research because context was lost
- generating large amounts of text without a defined purpose
- allowing an agent to invent missing context

Every assignment should answer:

**Why this task?**

**Why this agent?**

**What exactly should it produce?**

**What will the next agent do with the output?**

---

# 18. Writing Style for the Project

The final book should be readable, serious, historically responsible, and intellectually direct.

The writing should not sound like an AI-generated report.

The book should preserve the author's central ideas while improving grammar, structure, clarity, and presentation.

AI may improve the expression of an idea, but it must not silently change the author's intended meaning.

Historical claims must be supported before they are presented as fact.

---

# 19. The Author's Role

The author is responsible for the intellectual direction of the book.

The author should provide:

- ideas
- questions
- interpretations
- observations
- disagreements
- desired arguments
- decisions about what the book should ultimately say

Grammar and imperfect writing are not a blocker.

Raw thoughts can be supplied in ordinary language and later transformed into structured prose.

The author remains the final decision-maker on the book's meaning and direction.

---

# 20. The Final Operating Principle

The project should behave like a small research and editorial team built from multiple AI sessions.

**Claude = targeted research capability**

**Other ChatGPT accounts = parallel analytical workers**

**This ChatGPT account = Product Manager, workflow controller and chief editor**

**GitHub = permanent project memory**

**Author = intellectual owner and final decision-maker**

The objective is not to make AI produce a book as quickly as possible.

The objective is to use multiple AI systems intelligently so that the final book is:

- well researched
- evidence-driven
- critically tested
- coherent
- readable
- intellectually honest
- and genuinely the author's book.
