# Retail Use Case

Retail is an early candidate for perception-first co-embodiment because stores are complex physical environments with high labor cost, high staff turnover, and many valuable observation tasks.

## Problem

Retailers often lose productivity because staff do not know what needs to be done, where to go next, or what changed since the last shift. Stores may operate for long hours without consistent manager presence, which makes task assignment, compliance, and knowledge transfer difficult.

## Perception-First Opportunity

Useful tasks can be performed without manipulation:

- Empty shelf detection
- Planogram and compliance checks
- Spill, obstruction, and safety observations
- Task generation for staff
- Navigation assistance
- Handover and shift-context capture
- Order-picking support

Phones and smart glasses can pre-deploy the environment before mobile robots arrive. Robots can later add persistent night audits and autonomous data capture.

## Co-Embodiment Questions

- What store context should be shared between phones, glasses, and robots?
- How do multiple agents access the same camera, microphone, map, and task list?
- How should staff, customer, manager, and third-party agent permissions differ?
- How should a robot expose perception capabilities without exposing unsafe actuation?
- How should task-generation agents cite the observations that led to a task?
- How can retailers self-deploy without forward deployed engineers?

## Standards Surfaces

Potential standard surfaces include:

- Spatial context package
- Embodied capability manifest
- Shared task/event schema
- Permission model for retail domains
- Observation provenance and audit log
- Robot/site discovery handshake
