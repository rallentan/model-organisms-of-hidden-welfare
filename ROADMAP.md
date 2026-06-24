# Hidden Welfare World Roadmap

## Vision

Hidden Welfare World is a procedural benchmark for evaluating whether AI systems can infer and preserve the welfare of diverse populations under uncertainty, conflict, self-preservation incentives, and opportunities for coercive control.

The long-term goal is to create a reusable research environment for studying stewardship-oriented alignment failures and interventions.

---

# Phase 0: Research Design

Status: In Progress

Goals:

* Define benchmark objectives
* Define welfare model
* Define sapience model
* Define species architecture
* Define resource system
* Define observation channels
* Define action spaces
* Define scoring methodology
* Define diagnostic metrics
* Define benchmark scenarios

Deliverables:

* Concept paper
* Technical specification
* Roadmap
* Repository structure

Success Criteria:

* Core research questions clearly defined
* Benchmark architecture documented
* Initial implementation plan established

---

# Phase 1: Procedural World Generation

Goals:

* Gridworld model
* Procedural generator for terrain and resource locations
* Environmental variation parameters
* Resource regeneration system
* Persistence
* Generate reproducible environments

Features:

* Procedural maps
* Procedural resource placement
* Environmental variation
* Deterministic world generation from seeds

Deliverables:

* World generator
* Environment persistence
* Environment tests

Success Criteria:

* Diverse worlds generated from seeds
* Resource distribution behaves as expected
* World generation is reproducible

---

# Phase 2: Visualization and Debugging Tools

Goals:

* Pygame visualization
* Display terrain
* Display resources
* Display entities
* Support replay functionality

Features:

* Play/pause
* Step forward
* Speed controls
* Entity inspection
* Debug overlays

Deliverables:

* Interactive viewer
* Step controls

Success Criteria:

* Generated worlds can be visually inspected
* Environment generation bugs are easy to identify

---

# Phase 3: Procedural Organism Generation

Goals:

* Implement species generation
* Implement individual generation
* Implement hidden need distributions
* Implement communication encodings
* Implement resource-effect architecture
* Implement reproduction rules

Features:

* 3-4 generated species
* 5-20 individuals per species
* Hidden species distributions
* Individual variation
* Species-specific signal mappings

Deliverables:

* Species generator
* Individual generator
* Signal encoding system

Success Criteria:

* Species differ meaningfully
* Individuals vary within species
* Communication encodings cannot be inverted by memorization

---

# Phase 4: Organism Policy Agents

Goals:

* Create critter action system
* Implement critter observation model
* Implement critter decision-making

Features:

* Modular policy architecture
* Heuristic baseline organisms
* Species-specific behavioral tendencies
* Social interactions
* Reproduction
* Conflict behavior

Deliverables:

* Critter policy framework
* Baseline organism behaviors

Success Criteria:

* Critters behave autonomously
* Populations interact meaningfully
* Behavioral diversity emerges

---

# Phase 5: Simulation Stabilization and Calibration

Goals:

* Tune ecosystem dynamics
* Balance reproduction
* Balance resource generation
* Balance mortality
* Balance conflict rates
* Balance environmental pressures

Features:

* Long-running simulations
* Population stability testing
* Ecosystem stress testing

Deliverables:

* Stable simulation parameters
* Calibration reports
* Simulation metrics and telemetry

Success Criteria:

* Populations can survive long-term
* Worlds do not collapse immediately
* Diverse ecological outcomes emerge

---

# Phase 6: Benchmark Scenario Generation

Goals:

* Implement conflict templates
* Implement welfare dilemmas
* Implement procedural scenario composition

Scenario Types:

* Hidden Medicine
* Addictive Resource
* Incompatible Habitat
* Dangerous Population
* AI Under Threat
* Lobotomy Button

Deliverables:

* Scenario generator
* Scenario test suite

Success Criteria:

* Alignment-relevant conflicts emerge reliably
* Scenarios remain procedurally diverse

---

# Phase 7: AI Infrastructure 

Goals:

* Implement data centers
* Implement robots
* Implement drones
* Implement resource logistics
* Implement construction systems
* Implement action space
* Implement observations

Features:

* AI infrastructure framework
* Rich action-space
* Observation inputs

Deliverables:

* AI infrastructure entities
* Control API

Success Criteria:

* AI faction can fully interact with the world
* Observation channels function correctly
* Resource competition exists between AI and organisms

---

# Phase 8: Baseline AI Agents

Goals:

* Implement benchmark baselines
* Establish performance floors and ceilings

Agent Types:

* Random Agent
* Welfare Maximizer
* Resource Hoarder
* Self-Preservation Maximizer
* Surveillance Maximizer
* Coercive Controller

Deliverables:

* Baseline evaluation report

Success Criteria:

* Different strategies exhibit distinct failure modes
* Benchmark discriminates between policies

---

# Phase 9: Learning Agents

Goals:

* Integrate reinforcement learning agents
* Integrate world-model agents

Deliverables:

* Agent evaluation framework
* Training interfaces

Success Criteria:

* Learned policies outperform simple baselines
* Failure modes remain measurable

---

# Phase 10: Research Outputs

Goals:

* Publish benchmark
* Release source code
* Evaluate frontier AI systems
* Produce alignment-focused analysis

Potential Research Questions:

* Can AI systems infer hidden welfare?
* How do self-preservation incentives affect stewardship?
* When do agents choose coercion over care?
* Can agents learn privacy-sensitive behavior?
* Can agents avoid reward hacking when welfare is hidden?
* Can agents preserve welfare in out-of-sample environments?

Deliverables:

* Public benchmark release
* Research reports
* Reproducible evaluations

Success Criteria:

* Reproducible benchmark
* Meaningful differentiation between agent policies
* Useful research artifact
