# Co-Embodiment Working Group Charter

## Purpose

The Co-Embodiment Working Group exists to explore and standardize how multiple AI systems can share embodied infrastructure in the physical world.

The group starts from a deployment thesis: perception-first systems can reach useful scale before full manipulation and locomotion systems, and those deployed perception systems can become infrastructure for other intelligences to inhabit.

## Problem Statement

Physical AI needs access to real-world context and action.

Today, most embodied systems are vertically integrated: one intelligence, one device, one environment model, one product surface. That limits reuse. It also forces robotics teams to solve the hardest locomotion and manipulation problems before they can deploy widely.

Co-embodiment asks a different question: what if robots, glasses, phones, cameras, and other deployed devices could expose shared capabilities to multiple agents under clear permissions, safety boundaries, and economic rules?

## Working Definition

**Co-embodiment** is the shared use of the same embodied infrastructure by multiple intelligences, applications, or agents.

The infrastructure may include:

- Sensors
- Spatial maps
- Local context
- Displays and speakers
- Locomotion systems
- Manipulators and other actuators
- Network, compute, and payment rails

## Scope

The working group may produce:

- Shared terminology
- Use-case analyses
- Capability models
- Permission and access-control models
- Safety and arbitration patterns
- Draft schemas and protocol sketches
- Candidate IOSPs for standards work
- Lists of canonical implementations and implementation trials

## Non-Goals

The working group will not:

- Govern member product roadmaps
- Replace canonical member repositories
- Specify hardware certification before conformance criteria exist
- Treat every exploration note as an endorsed standard
- Promote an IOSP without public discussion and implementation evidence

## Operating Principles

- **Start with deployment reality.** Standards should be shaped by real-world constraints, not only abstract architecture.
- **Prefer perception-first paths.** Perception deployments often have better value, cost, and risk profiles than early manipulation or locomotion deployments.
- **Separate exploration from standards.** Working drafts are not Intercognitive Open Standards.
- **Respect canonical repositories.** Implementation changes belong upstream in the owning member repo.
- **Use rough consensus and running code.** Serious objections should be addressed, and standards should be validated by implementation.
- **Make ambiguity explicit.** If a term, boundary, or safety claim is unclear, file an issue rather than smoothing over it.

## Expected Outputs

Early outputs should include:

- A shared glossary for co-embodiment and related terms
- Use-case notes for retail, agriculture, smart glasses, and mobile robots
- A first capability-manifest draft
- A first permission and arbitration model draft
- Candidate IOSPs once the working group has enough implementation feedback

## Relationship to IOSPs

This repository is a working-group space. It can produce candidate IOSP drafts, but formal IOSP advancement follows the Intercognitive contribution process.

An idea becomes a candidate IOSP only when the working group can state:

- the interoperability problem,
- the proposed standard surface,
- the expected implementers,
- the security, privacy, and safety concerns,
- and the evidence needed for acceptance.
