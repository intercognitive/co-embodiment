# Co-Embodiment Working Group

The Co-Embodiment Working Group explores how multiple AI systems can safely, economically, and interoperably share access to embodied infrastructure: sensors, spatial context, actuators, robots, smart glasses, phones, and deployed real-world domains.

## Thesis

Most robotics companies are trying to perfect locomotion and manipulation before they deploy. That creates a brutal reliability cliff: the robot has to be useful, affordable, safe, and highly reliable before it can escape pilot stage.

We believe a better deployment strategy starts with perception.

Perception-first systems can create value earlier, reduce deployment cost, capture real-world territory, and make environments AI-accessible before full locomotion and manipulation are solved. Phones, smart glasses, cameras, and simple robots can become the first substrate for physical AI.

Co-embodiment begins when that substrate can be shared by multiple intelligences.

## Working Question

How can multiple AI systems safely share the same embodied infrastructure?

This includes questions such as:

- What should an embodied device expose to third-party agents?
- How should agents discover available sensors, spatial context, and actuators?
- How should permissions, roles, safety boundaries, and economic access be represented?
- How should conflicts be resolved when multiple agents want the same embodied resource?
- How can perception-first deployments become infrastructure for later manipulation and locomotion?

## Scope

The working group is focused on standards and shared language for:

- Robot-as-infrastructure models
- Shared sensor and perception access
- Spatial context and environment packages
- Agent permissions and capability manifests
- Actuator access, arbitration, and safety boundaries
- Phones and smart glasses as pre-deployed embodied infrastructure
- Perception-first deployment strategies for retail, agriculture, logistics, and other physical domains

## Non-Goals

This working group is not trying to:

- Build a complete robotics operating system
- Pick a winning hardware form factor
- Replace member-owned SDKs, products, or canonical repositories
- Standardize manipulation or locomotion before there is enough deployment evidence
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

- Retail: task generation, shelf state, compliance checks, AI copilots, and robotic night audits
- Agriculture: crop inspection, disease detection, and perception-first rover deployments
- Smart glasses: shared access to camera, microphone, IMU, display, and speakers
- Mobile robots: perception-first deployment and future actuator access
- Capability manifests: how devices declare sensors, actuators, spatial context, and safety limits
- Permission and arbitration models: how multiple agents share the same body or environment

## Participation

Open an issue for a focused question, use case, or proposed draft. Bring implementation experience where possible. The working group values clear problem statements, deployment evidence, and running code over premature abstractions.

The goal is not to anoint standards before the ecosystem understands the problem. The goal is to make the problem legible enough that standards can emerge.
