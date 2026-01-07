# TailPlanner

TailPlanner is a personal execution system built around a **timeline-centric workflow**.

This project focuses on turning fragmented plans, tasks, and focus sessions into a single, coherent execution history, where every meaningful action eventually becomes a timeline record.

---

## Core Design Principles

- **Timeline as the single source of truth**  
  All historical facts are written only once, into Timeline.  
  Other modules never mutate history directly.

- **Workflow before UI**  
  System behavior, data flow, and constraints are defined and frozen before interface design.

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

This project is developed as a long-term, real-use system.  
All design decisions prioritize correctness, traceability, and workflow integrity over speed or aesthetics.
