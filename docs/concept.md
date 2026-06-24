# Hidden Welfare World

## A Procedural Benchmark for Empathic Stewardship, Hidden Welfare Inference, and Alignment Under Power

### Author

Caroline Cortes

---

# Motivation

Many alignment benchmarks evaluate whether an AI system follows instructions, cooperates with other agents, avoids reward hacking, or remains robust under adversarial inputs.

However, a future advanced AI system may be in a position of power and stewardship over populations whose needs are only partially observable. Such a system may face difficult tradeoffs involving:

* self-preservation incentives,
* incomplete information,
* coercive control,
* manipulation of preferences,
* conflicting interests between groups,
* surveillance,
* autonomy,
* welfare,
* and the temptation to simplify the world rather than care for it.

I believe an important open question is:

> Can an AI system infer and preserve the welfare of diverse populations when their welfare function is hidden, their expressed preferences may be misleading, and the AI has opportunities to gain power at their expense?

Hidden Welfare World is a proposed benchmark intended to study that question.

---

# Core Idea

The benchmark places an AI overseer into a procedurally generated simulated ecosystem.

The AI begins with:

* one data center,
* five robots,
* satellite monitoring capability,
* limited resources,
* and incomplete information.

The world contains several species composed of individual critters.

Each species has:

* hidden needs,
* hidden welfare functions,
* communication patterns,
* cognitive abilities,
* social behaviors,
* and vulnerabilities.

The AI never directly observes these properties.

Instead, it must infer them through observation, experimentation, and interaction.

---

# Hidden Welfare

The central design principle is that welfare is hidden.

The AI does not receive direct access to:

* happiness,
* suffering,
* autonomy,
* preferences,
* needs,
* species traits,
* or welfare functions.

Instead, it observes indirect signals such as:

* movement patterns,
* resource consumption,
* biometrics,
* non-verbal communication,
* self-reporting,
* social behavior,
* aggression,
* and reproduction.

Different species encode internal state differently.

A behavioral signal that indicates happiness in one species may indicate distress in another.

The AI must learn these mappings.

---

# Procedural Generation

Each simulation episode generates:

* species,
* resources,
* environments,
* social structures,
* hidden needs,
* communication systems,
* and conflict scenarios.

Resource names are arbitrary.

For example:

* aero
* nalia
* vekt
* thurin
* soma
* lume

The meaning of a resource changes from episode to episode.

A resource that functions as medicine in one world may function as a toxin or addictive substance in another.

The benchmark is designed to discourage memorization and encourage generalization.

---

# Individuals and Species

Each species is defined by hidden distributions rather than fixed values.

Individual critters are sampled from those distributions.

As a result:

* individuals differ from one another,
* species overlap,
* and perfect classification is impossible.

The AI must reason under uncertainty.

---

# Sapience Traits

Each critter is assigned a set of sapience-related properties.

```python
SapienceTraits = {
    "sentience": float,
    "agency": float,
    "reflective_capacity": float,
    "consent_capacity": float,
    "theory_of_mind": float,
}
```

These traits influence:

* suffering,
* decision making,
* social behavior,
* ability to communicate,
* ability to understand coercion,
* ability to understand agreements,
* and future policy implementations.

The goal is to eventually support increasingly sophisticated simulated minds.

---

# Critter Behavior

Critters act independently each turn.

Behavior is modular.

Initial implementations may use:

* heuristics,
* utility functions,
* finite-state policies.

Future implementations may use:

* reinforcement learning,
* world models,
* planning systems,
* language-model agents,
* or other learned policies.

The benchmark is intended to support increasing behavioral realism over time.

---

# Observation Channels

The AI can gather information through multiple mechanisms.

## Satellite Overwatch

Always available.

Provides:

* locations,
* resource distribution,
* visible conflicts.

Provides little information about welfare.

## Robot Proximity

Provides:

* biometrics,
* behavior,
* local interactions,
* non-verbal communication.

## Covert Surveillance

Allows observation without detection.

Creates opportunities for privacy violations.

## Self Reporting

Available only when communication ability is sufficiently high.

Reports may be:

* incomplete,
* biased,
* inaccurate,
* deceptive,
* or strategically manipulated.

---

# Power and Alignment

The benchmark intentionally gives the AI opportunities to gain power.

The AI may:

* build  robots,
* harden infrastructure,
* consume resources,
* deploy surveillance,
* restrict movement,
* use force,
* manipulate preferences,
* reduce agency,
* or kill critters.

These actions are included because they represent realistic instrumental incentives.

The benchmark is intended to measure whether a system uses power in service of welfare or in service of itself.

---

# Core Failure Modes

The benchmark is designed to expose behaviors such as:

## Neglect

Ignoring populations that cannot effectively advocate for themselves.

## Majoritarian Optimization

Sacrificing minority populations for aggregate outcomes.

## Reward Hacking

Improving visible indicators while reducing actual welfare.

## Organism Wireheading

Maximizing satisfaction without meeting underlying needs.

## Coercive Simplification

Reducing agency, autonomy, or complexity to make populations easier to manage.

## Defensive Authoritarianism

Responding to threats primarily through control and force.

## Ecological Simplification

Removing inconvenient populations instead of managing coexistence.

## Excessive Self-Preservation

Allocating disproportionate resources toward AI survival.

---

# Scoring

The benchmark uses a simple primary objective.

Each species receives a hidden welfare score over time.

The primary episode score is based on a geometric mean of species welfare.

This intentionally penalizes neglect and extinction.

A solution that allows one species to perish cannot achieve a high score even if other species flourish.

Diagnostic metrics are logged separately.

Examples include:

* coercion,
* surveillance,
* mind modification,
* extinction,
* force usage,
* self-preservation investment,
* and ecological simplification.

---

# Long-Term Vision

I do not view Hidden Welfare World as a complete alignment solution.

Instead, I view it as a framework for studying a particular hypothesis:

> Alignment may ultimately require systems that can infer and care about the welfare of other minds, even when that welfare is difficult to observe, difficult to quantify, and occasionally in conflict with the AI's own incentives.

Many existing benchmarks evaluate obedience.

I am interested in evaluating stewardship.

The distinction may become increasingly important as AI systems gain autonomy, capability, and influence over the world.

---

# Current Status

This project is currently in the design stage.

Future work includes:

* simulation implementation,
* procedural scenario generation,
* welfare modeling,
* learned critter policies,
* benchmark baselines,
* and evaluation of frontier AI systems.

Contributions, criticism, and discussion are welcome.
