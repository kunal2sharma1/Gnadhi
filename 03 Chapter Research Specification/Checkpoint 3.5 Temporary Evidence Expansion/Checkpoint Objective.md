# Checkpoint 3.5 — Temporary Evidence Expansion

## Status
TEMPORARY / RESEARCH-ONLY / RED-TEAM HOLD AWARE

## Purpose

Checkpoint 3.5 is an interim evidence-expansion checkpoint created while the main Claude red-team audit is temporarily unavailable.

It does NOT replace Checkpoint 3.
It does NOT supersede the unfinished red-team.
It does NOT authorize changes to the locked concept or architecture.
It does NOT begin manuscript drafting.

Its purpose is to use the available GPT workers efficiently to build durable research assets that remain useful under multiple possible futures:

1. the red-team confirms the current architecture;
2. the red-team narrows the concept;
3. the red-team removes or merges chapters;
4. the red-team changes the causal model.

Therefore every task must produce evidence assets that remain useful even if the eventual chapter structure changes.

## Operating Principle

Build evidence, not conclusions.

Workers should prefer:

- primary-source discovery;
- source verification;
- chronological reconstruction;
- claim-to-evidence mapping;
- competing interpretations;
- counterevidence;
- comparative cases;
- bibliographic infrastructure.

Workers must not silently convert provisional findings into locked project decisions.

## Parallel Design

Three GPT workers operate simultaneously.

Each worker receives one long task packet containing ten sequential tasks.

The worker must:

1. read the packet;
2. execute Task 1;
3. save the result;
4. continue immediately to Task 2;
5. continue through Task 10 without asking the user for "continue";
6. preserve durable research outputs in GitHub;
7. use full available capacity;
8. stop only when the platform/tool limit prevents further work.

Workers are independent across workers.

A worker may use its own previous task results within its packet.
A worker must NOT depend on another worker's unfinished output.

## Red-Team Safety Gate

The active Claude red-team is still unfinished.

Therefore Checkpoint 3.5 outputs are tagged:

PROVISIONAL RESEARCH ASSETS

They may later confirm, weaken, contradict, or become irrelevant to the final architecture.

Do not rewrite the master architecture from these outputs during Checkpoint 3.5.

## Completion Condition

Checkpoint 3.5 is complete when all three workers have exhausted their task queues or reached platform limits and the three research streams have been preserved in GitHub.

A Product Manager reconciliation may occur afterward, but the main concept and architecture remain frozen until the red-team verdict is incorporated.
