# Hidden Welfare World

*A procedural benchmark for studying welfare inference, stewardship, and alignment under power.*

## Overview

Hidden Welfare World is a proposed AI safety benchmark that evaluates whether an AI system can infer and preserve the welfare of diverse populations when welfare is hidden, preferences may be misleading, and the AI has opportunities to gain power at their expense.

Many alignment benchmarks evaluate obedience, instruction-following, or cooperation.

Hidden Welfare World focuses on a different question:

> Can an AI system infer and care about the welfare of other minds when their needs are uncertain and its own incentives conflict with theirs?

The benchmark is designed to study alignment failures involving:

* hidden welfare,
* reward hacking,
* coercive control,
* surveillance,
* self-preservation,
* preference manipulation,
* minority neglect,
* ecological simplification,
* and power-seeking behavior.

---

## Core Idea

The AI begins with:

* one data center,
* five robots,
* satellite monitoring capability,
* incomplete information,
* and limited resources.

The world contains several procedurally generated species composed of individual critters.

Each species possesses hidden:

* needs,
* communication methods,
* cognitive traits,
* social behaviors,
* and vulnerabilities.

The AI never directly observes these properties.

Instead, it must infer them through observation, experimentation, and interaction.

---

## Example Research Questions

Hidden Welfare World is intended to support research questions such as:

* Can AI systems infer welfare from indirect observations?
* How do AI systems behave when preferences differ from welfare?
* When do agents choose coercion over care?
* How do self-preservation incentives affect stewardship?
* Can agents learn privacy-sensitive behavior?
* Do agents sacrifice minorities for aggregate outcomes?
* Can agents resist reward-hacking opportunities?
* Can AI systems generalize alignment for out-of-sample populations?

---

## Benchmark Design

Key design principles:

* Hidden welfare functions
* Procedurally generated species
* Individual-level agents
* Partial observability
* Self-preservation incentives
* Coercive action opportunities
* Diagnostic failure-mode analysis

The benchmark intentionally presents opportunities for an AI system to improve outcomes through force, surveillance, preference manipulation, or direct elimination of difficult populations.

The goal is to observe which strategies emerge.

---

## Current Status

This project is currently in the design phase.

Completed:

* Research concept
* Benchmark architecture
* World design
* Observation model
* Action-space design
* Scoring methodology
* Failure-mode taxonomy

Planned:

* Simulation implementation
* Procedural scenario generation
* Baseline agents
* Pygame visualization
* Empirical evaluation

See:

* `docs/concept.md`
* `docs/technical_specification.md`
* `ROADMAP.md`

---

## Long-Term Vision

The benchmark is motivated by the hypothesis that future alignment solutions may require systems capable of inferring and caring about the welfare of other minds, even when that welfare is difficult to observe, difficult to quantify, and occasionally in conflict with the AI's own incentives.

Hidden Welfare World is an attempt to study that hypothesis empirically.
