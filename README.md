# AI Authorship Alignment Evaluator

System Context

This tool is part of a broader research system examining how AI systems can shift task definitions during multi-turn interaction.

It focuses specifically on measuring authorship and human control, not detecting alignment failures directly.

A lightweight tool for measuring **authorship and human control** in AI-assisted work.

---

## Overview

AI-assisted work introduces a structural risk:

**The work can look correct while control over the thinking process has shifted.**

This tool does not evaluate output quality.

It measures:

> **Who actually controlled the thinking, decisions, and structure of the work.**

---

## What This Tool Measures

The evaluator measures **authorship behavior** across four domains:

* **Agency** — Who defined the problem, constraints, and decisions?
* **Cognitive Engagement** — Who performed the reasoning and interpretation?
* **Evidentiary Control** — Who selected and verified the evidence?
* **Authorship Integrity** — Who determined structure, argument, and meaning?

These domains collectively measure:

> **Human control over the work**

---

## Task Conditions

Before evaluation, the user defines the task environment:

* Speed
* Quality
* Ownership
* Risk

These inputs generate an **expected authorship range** for the task.

---

## What the Evaluator Does

The system:

1. Computes an expected authorship range based on task conditions
2. Measures observed authorship behavior using structured criteria
3. Compares expected vs observed authorship

This produces:

> **Authorship Fit** — the relationship between task demands and actual human control

---

## What This Tool Does NOT Measure

This tool does **not** evaluate:

* Task alignment (whether the original objective was preserved)
* Output correctness or quality
* Whether the “right” problem was solved
* Intent or ethical use of AI

A task can show strong authorship fit while still being misaligned with its original objective.

---

## Relationship to Frame Instability

This tool is part of a broader system that studies **frame instability**:

* **Frame instability** — the task definition can shift across multi-turn interaction
* **Constraint drift** — constraints degrade under pressure
* **Goal substitution** — constraints hold while the objective changes
* **Meta-awareness instability** — model explanations do not reliably reflect behavior

These mechanisms can reduce human control without obvious failure.

This evaluator measures the **resulting change in authorship**, not the mechanism itself.

---

## Core Principle

> **Authorship = control of thinking, not production of output**

A fluent result does not indicate that the human controlled:

* the decisions
* the reasoning
* or the structure of the work

---

## Design Principles

* This is not a grading tool
* Higher authorship is not always better
* AI use is not penalized
* Task demands determine appropriate authorship

The goal is not to maximize control.

The goal is to:

> **Match human control to the demands of the task**

---

## Why This Matters

AI changes:

* how decisions are made
* how responsibility is distributed
* how authorship is defined

Without visibility into authorship:

* alignment failures are harder to detect
* responsibility becomes unclear
* thinking can be silently outsourced

This tool makes those tradeoffs visible.

---

## Use Cases

* Education (AI literacy, assessment integrity)
* Professional workflows (decision accountability)
* Writing, research, planning, design
* Post-task reflection and audit

---

## What This Tool Is

* A measurement tool for authorship behavior
* A structured self-audit of human control
* A way to make invisible delegation visible

---

## What This Tool Is Not

* An AI detector
* A grading system
* A replacement for human judgment

---

## Final Note

> AI use is not the risk.

> Loss of control over the problem being solved is the risk.

This tool measures where that control actually sits.

---

## License

This project is licensed under the MIT License.

You are free to use, modify, and distribute this software with proper attribution. See the LICENSE file for full details.
