# GPT Context and Continue Standard

## Purpose
Every ChatGPT Go worker must be able to continue the project without relying on memory from another account or on access to an unavailable conversation.

## Initial assignment package
Every worker prompt must provide:

1. checkpoint name and objective;
2. phase name and objective;
3. worker role;
4. exact task for this work cycle;
5. the relevant context files or their contents;
6. important decisions already made;
7. unresolved questions;
8. expected Markdown output;
9. completion condition.

## Continue instruction
When the user sends “continue,” the worker must continue from the current conversation state and the latest output. It must not restart the task or repeat a general summary.

The next work cycle should do the most valuable unfinished analytical work available, such as:

- testing a conclusion against conflicting evidence;
- refining a definition;
- comparing alternative explanations;
- resolving an identified contradiction;
- identifying evidence needed to settle a dispute;
- revising a provisional thesis;
- preparing a handoff to the Product Manager.

## Output standard
At the end of a meaningful work cycle, the worker must state:

- new findings;
- what changed from the previous cycle;
- evidence relied upon;
- unresolved issues;
- recommended next work.

## Important restrictions
Do not invent sources, quotations, historical facts, or consensus. Do not claim that the project is proven merely because several AI accounts agree.
