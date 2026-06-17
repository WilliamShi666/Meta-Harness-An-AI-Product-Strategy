# Meta-Harness: Harness Generation, Verification & Evolution Platform for the Agent Era

> **Meta-Harness 产品战略计划书**
>
> A product strategy document on building the "production line generator" for the AI Agent era.
>
> 📖 **[中文版战略介绍与 Extract →](README_CN.md)**

## Repository Contents

| File | Description |
|------|-------------|
| `Meta-Harness-Strategy-Text.pdf` | Full text version of the strategy document (~534 KB) |
| `Meta-Harness-Strategy-Deck.pdf` | Slide/presentation version of the strategy document (~13 MB) |

---

## Executive Summary

**Meta-Harness** is a Harness generation, verification, and evolution platform for the Agent era. Its core thesis: the bottleneck for AI Agents is not model capability, but the lack of a **Harness** — a structured work system that integrates models into real production workflows.

Coding Agents were the first to break through, not simply because models can write code, but because software engineering naturally provides a complete working environment: repos, tests, CI, diffs, code review, rollback, etc. When a model enters this environment, it transforms from a "question-answering assistant" into an "executing agent embedded in a production pipeline."

However, in education, HR, sales, operations, consulting, content creation, data analysis, SMB management, and many other industries, such structured harnesses don't yet exist. Many potential users don't need an agent — they need a way to organize their domain knowledge, tools, processes, memory, quality standards, and verification mechanisms into a sustainable AI work system.

**Meta-Harness is designed to solve exactly this problem: enable AI to automatically generate small, task- and domain-specific Harnesses.**

---

## What is a "Harness"?

A **Harness** is not a prompt. It is a **complete task execution system** built around a model, including:

- **Roles** — agent identity and responsibilities
- **Commands & Tool Permissions** — what the agent can do
- **Memory Strategy** — how context and knowledge are retained
- **Workflows** — step-by-step execution processes
- **Rubric** — quality evaluation criteria
- **Hard Validator** — deterministic verification (tests, schema checks, etc.)
- **Eval Cases** — benchmark cases for performance assessment
- **Artifacts** — structured output templates
- **Controlled Evolution** — versioned improvement from real-world trace data

---

## The Four Layers of the Agent Ecosystem

| Layer | Definition | Examples |
|-------|-----------|----------|
| **Skill** | Individual capability module | A single tool or API call |
| **Small Harness** | Domain-specific work system | GStack, custom agent workflows |
| **Big Harness** | Complete agent product or runtime | Claude Code, Cursor, Devin |
| **Meta-Harness** | Platform that generates, verifies, and evolves Harnesses | **This project** |

Projects like GStack have already proven that small harnesses significantly expand an agent's productive boundary. But they still rely on a handful of experts who understand both the domain and how to operate tools like Claude Code, Codex, or OpenCode — iterating with agent assistance to refine the harness. Ordinary domain experts, even if they deeply understand their industry, cannot easily create a runnable, verifiable, evolvable harness on their own.

---

## Product Opportunity

Meta-Harness's product opportunity is to **productize** the individual capability of "expert-driven, agent-assisted harness generation" into a **platform capability** accessible to ordinary users, domain experts, and enterprise teams.

Users describe their goal → the system generates:
1. **Domain blueprint** — what the problem space looks like
2. **Role structure** — what agents are needed
3. **Workflows** — execution processes
4. **Tool permissions** — what actions are allowed
5. **Evaluation standards** — rubrics + validators
6. **Output templates** — artifact schemas

After real-world execution, the system improves harnesses based on:
- Execution traces
- Validator failures
- User corrections
- Expert feedback

**Versioned, auditable, reproducible.**

---

## Strategic Value for Model Companies

For model companies, Meta-Harness is more than an application-layer tool — it is a **strategic entry point from the model/API layer into the workflow layer**.

If model companies remain at the API layer, user relationships, task data, industry know-how, and enterprise workflows will be captured by upstream agent products. Meta-Harness allows model companies to define:

- Pack standards
- Runtime
- Eval frameworks
- Registry
- Evolution loop

…becoming the **work-system infrastructure** of the Agent era.

---

## Product Roadmap

1. **CLI & Developer Preview** — Validate Pack Schema, Runtime, Validator, Trace, and cost curves
2. **Harness Studio** — Natural language + visual interface for non-technical users to create small harnesses
3. **Harness Registry** — Official, community, and certified packs discoverable, installable, forkable, reusable, and improvable
4. **Big Harness Composer** — Componentized generation of complete agent product systems

---

## Core Moats

Five competitive barriers:

1. **Demand-to-blueprint**: translating vague requirements into clear domain blueprints
2. **Runnable & verifiable**: generating small harnesses that actually execute and validate
3. **Cost efficiency**: compressing multi-agent workflow costs to daily-usable levels
4. **Safe evolution**: improving harnesses from real-world trace data without regressions
5. **Data and ecosystem flywheel**: connecting experts, developers, enterprises, and model companies

---

## Vision

**Meta-Harness could become the "production line generator" of the Agent era.**

- Models provide intelligence
- Agents provide execution
- Harnesses provide work systems
- Meta-Harness provides the method for generating work systems

If this method holds, every industry could experience its own "Claude Code moment": education, HR, consulting, data analysis, content production, enterprise operations, and personal learning — all equipped with verified, continuously evolving, low-cost AI work systems.

At that point, economic growth would come not just from "existing employees getting more efficient," but from **"more individuals and small organizations gaining access to capabilities previously reserved for expert teams and large corporations."**

---

> **The fundamental value of Meta-Harness is not enabling AI to do a few more tasks — it's enabling every industry to generate its own AI work system.**
