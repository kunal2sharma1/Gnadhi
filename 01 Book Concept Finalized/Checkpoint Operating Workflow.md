# Checkpoint 1 — Operating Workflow

## Working model
Checkpoint 1 is designed as a parallel production cycle, not a linear sequence of one task at a time.

### Layer 1 — Claude research
Seven Claude accounts receive seven tightly bounded research assignments. Each assignment must be narrow enough to finish within one normal free-session window. No Claude account is asked to “research Gandhi” broadly.

Each Claude account returns one Markdown Research Packet. These packets become persistent project material in GitHub.

### Layer 2 — GPT execution
After the research packets are reviewed, three other ChatGPT Go accounts work in parallel on different workstreams. They are expected to continue working through multiple rounds of analysis when the user sends “continue.”

This ChatGPT account acts as Product Manager and chief editor. It prepares context packs, assigns work, compares outputs, identifies gaps, and decides the next work.

### Layer 3 — Cross-review
The three GPT workers' outputs are compared. Contradictions, missing evidence, and weak reasoning are identified. Only targeted additional research is commissioned.

### Layer 4 — Final synthesis
The Product Manager consolidates the accepted work, records what changed, identifies what remains uncertain, and decides whether the checkpoint is complete.

## Resource rules

- Claude capacity is reserved for high-value, narrowly scoped research.
- GPT workers are not given duplicate assignments unless deliberate independent comparison is needed.
- No major conclusion is treated as true merely because multiple AI accounts repeat it.
- Important claims must be tied to research outputs and, where appropriate, original or scholarly sources.
- Every meaningful output must be saved as Markdown so another account can continue without the old conversation.

## Parallel rule
At the start of the GPT execution stage, all three worker accounts are assigned their work simultaneously. They can continue in their own conversations until they reach a stopping point or the user asks them to continue.

## Context rule
Each GPT prompt supplied by the Product Manager must contain or point to a self-contained context pack, the exact workstream objective, the current checkpoint status, the expected Markdown output, and the completion condition.

## Adaptation rule
The exact work inside later phases can change when new findings appear. The Product Manager may add, remove, split, or redesign sub-phases without changing the overall checkpoint objective.
