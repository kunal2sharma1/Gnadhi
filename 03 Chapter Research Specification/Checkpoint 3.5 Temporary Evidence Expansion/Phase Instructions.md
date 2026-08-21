# Phase Instructions — Checkpoint 3.5

## Worker Model

Use exactly three GPT workers in parallel.

Each worker has ten tasks.

The tasks inside a worker are sequential because each task can reuse that worker's previous findings.

The three workers themselves are parallel because their information goals are deliberately different.

## Execution Rule

The command sent to each worker should instruct it to execute the entire packet continuously.

The worker must not ask the user for permission between tasks.

After completing a task, it should:

- write durable findings to the specified research file or append to the worker master report;
- record sources and confidence;
- identify unresolved questions;
- immediately continue to the next task.

## Full-Capacity Rule

"Full capacity" means deeper verification and synthesis, not repetitive verbosity.

Workers should prioritize:

1. primary sources;
2. authoritative archives;
3. serious scholarship;
4. direct comparisons;
5. counterevidence;
6. durable research notes.

## Source Discipline

Every major finding should record:

- claim;
- source;
- source type;
- what the source actually establishes;
- what it does not establish;
- confidence;
- unresolved issue.

Do not treat search snippets as evidence.

Do not convert an actor's claim into historical fact.

Do not treat similarity as continuity.

## Output Discipline

Each worker should maintain one master report rather than create ten disconnected files.

Recommended location:

`03 Chapter Research Specification/Checkpoint 3.5 Temporary Evidence Expansion/Worker Outputs/`

Each master report should contain ten clearly numbered task sections.

## Red-Team Hold

No worker may alter:

- Checkpoint 1 decision files;
- Checkpoint 2 architecture decision files;
- Checkpoint 3 master research specification;
- the unfinished red-team log.

If a finding appears to require architectural change, record it under:

`Potential Structural Implication`

and continue researching.

## Stop Rule

If the worker reaches a platform limit:

- save all completed work;
- record the last completed task;
- record the exact next task;
- commit;
- stop.

If the worker has remaining capacity after Task 10, it should deepen the weakest unresolved areas rather than invent an eleventh unrelated task.
