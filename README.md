# Co-Embodiment Working Group

The Co-Embodiment Working Group explores what needs to happen for robots and embodied devices to become discoverable, permissioned, and co-habitable infrastructure, so that multiple agents can safely share embodiment.

## Thesis

Most embodied systems are built as single-tenant products: one robot, one controlling application, one operator model, one environment integration, one intelligence stack. That makes robots difficult for third-party agents to discover, understand, trust, and inhabit.

Co-embodiment asks what common interfaces and rules are required for robots to become shared infrastructure.

A co-habitable robot should be able to describe where it is, what it can sense, what it can do, who may use it, what it costs, what safety limits apply, and how competing agent requests are resolved. Agents should be able to discover that robot, request a bounded embodiment session, use permitted capabilities, and leave behind an auditable record.

## Working Question

What needs to happen for robots to become discoverable and co-habitable infrastructure, so that multiple agents can share embodiment?

This includes questions such as:

- How should robots and embodied devices advertise their capabilities?
- How should agents discover available robots, sensors, spatial context, and actuators?
- How should an agent request, start, maintain, and end an embodiment session?
- How should permissions, roles, safety boundaries, economic access, and audit logs be represented?
- How should conflicts be resolved when multiple agents want the same embodied resource?
- What must be standardized so robots can be safely co-habited across vendors, agents, and domains?

## Scope

The working group is focused on standards and shared language for:

- Robot discovery and service advertisement
- Embodied capability manifests
- Embodiment session lifecycle
- Shared access to sensors, spatial context, displays, speakers, locomotion, and actuators
- Agent identity, authentication, authorization, and delegation
- Permission, pricing, metering, and settlement models
- Arbitration, priority, safety boundaries, and human override
- Observation, action, and decision audit logs
- Domain context packages for places where robots operate

## Non-Goals

This working group is not trying to:

- Build a complete robotics operating system
- Pick a winning hardware form factor
- Replace member-owned SDKs, products, or canonical repositories
- Standardize robot morphology, autonomy stack, or application behavior
- Certify products before conformance requirements exist

## How Work Progresses

The working group starts with public exploration and only graduates work into standards when the shape is clear.

```text
Discussion -> Issue -> Working draft -> Candidate IOSP -> implementation trial -> Accepted IOS
```

Intercognitive standards are proposed as **IOSPs: Intercognitive Open Standard Proposals**. See the organization [CONTRIBUTING.md](https://github.com/intercognitive/.github/blob/main/CONTRIBUTING.md) for the full IOSP process.

## Repository Map

```text
CHARTER.md         # Scope, operating model, outputs
GLOSSARY.md        # Shared terminology
CONTRIBUTING.md    # How to participate in this working group
use-cases/         # Domain-specific exploration notes
proposals/         # Working drafts before formal IOSPs
meetings/          # Notes and decisions
```

## Initial Exploration Areas

- Discovery: how agents find robots, places, services, and available embodiment surfaces
- Capability manifests: how robots declare sensors, actuators, spatial context, services, costs, and safety limits
- Embodiment sessions: how an agent requests, receives, uses, and releases shared embodiment
- Permission and arbitration models: how multiple agents share the same body, channel, or environment
- Safety and auditability: how limits, overrides, provenance, and logs are represented
- Domain examples: retail, agriculture, smart glasses, mobile robots, logistics, and industrial facilities

## Participation

Open an issue for a focused question, use case, or proposed draft. Bring implementation experience where possible. The working group values clear problem statements, deployment evidence, and running code over premature abstractions.

The goal is not to anoint standards before the ecosystem understands the problem. The goal is to make the problem legible enough that standards can emerge.
