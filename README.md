# TailPlanner

TailPlanner is a personal execution system designed to turn fragmented work into a single, reliable execution timeline.

This project focuses on turning fragmented plans, tasks, and focus sessions into a single, coherent execution history, where every meaningful action eventually becomes a timeline record.

---

## Core Design Principles

- **Workflow before UI**  
  System behavior, data flow, and constraints are defined and frozen before interface design.
  
- **Timeline as the single source of truth**  
  All historical facts are written only once, into Timeline.  
  Other modules never mutate history directly.

- **Deterministic execution, not intelligence**  
  TailPlanner does not provide recommendations, predictions, or AI summaries.  
  It exists to reflect what actually happened, not what should happen.

---

## System Scope

TailPlanner is composed of the following core modules:

- Lists
- Plans
- Todos
- Focus Sessions
- Timeline Records
- Reviews
- Notes

Each module exists only insofar as it contributes to a consistent and reconstructable execution timeline.

---

## Project Status

This repository represents the **formal development phase** of TailPlanner.

- System workflow and execution constraints are frozen
- Implementation follows a strict, phase-based order
- UI and visual polish are intentionally deferred

For detailed execution rules and MVP scope, see:

- `docs/WORKFLOW.md`

---

## Non-Goals

TailPlanner explicitly does not aim to be:

- A habit coaching system
- A productivity recommendation engine
- An AI-driven assistant
- A replacement for planning methodologies

It is a **record-first execution system**, not a guidance tool.

---

## Development Philosophy

TailPlanner is designed as a **cognitive control system**, not merely a task tracker.

Its primary goal is to reduce mental context switching and uncontrolled idea branching during real execution, by enforcing clear workflow boundaries and a stable execution rhythm.

### Key Design Intentions

- **Todo and Plan coexist within a single system**  
  To eliminate cross-app searching and fragmented state recovery during execution.

- **Workflow-first structure**  
  System behavior, data flow, and constraints are defined before UI, ensuring that every action has a clear and deterministic place in the execution flow, minimizing decision overhead.

- **Intentionally constrained multitask focusing**  
  Multitask focus is supported only for limited, high-relevance scenarios (e.g. 2–3 tightly related but operationally independent tasks), preventing uncontrolled attention drift while preserving necessary flexibility.

- **Focus sessions as continuity-preserving mechanisms**  
  Focus is treated as a way to reduce the cost of stopping, resuming, and re-entering work after short interruptions, rather than as a throughput optimization tool.

Overall, TailPlanner functions less as a productivity enhancer and more as an **execution boundary system** — prioritizing execution stability, traceability, and workflow integrity over speed, feature breadth, or visual polish.
