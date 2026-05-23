# Retail Use Case

Retail is a useful co-embodiment domain because stores contain many people, devices, tasks, maps, policies, and services that multiple agents may need to share.

## Problem

Retailers often lose productivity because staff do not know what needs to be done, where to go next, or what changed since the last shift. Stores may operate for long hours without consistent manager presence, which makes task assignment, compliance, and knowledge transfer difficult.

## Shared Embodiment Opportunity

Several embodied surfaces may need to cooperate in the same store:

- phones and smart glasses carried by staff,
- fixed cameras and shelf sensors,
- mobile robots and cleaning machines,
- task systems, maps, and AI copilots,
- third-party agents that need bounded access to store context.

The standards question is how these surfaces become discoverable and co-habitable without every integration becoming custom.

## Core Scenario

A retailer already has a semi-humanoid robot in the store. Intelligence provider X has taught the robot to perform order-picking tasks: navigate to products, identify shelf locations, collect items, and hand them off.

Another intelligence provider, Y, wants to use the same robot to solve restocking tasks. Provider Y should not need to own the robot, replace provider X, or rebuild the whole store integration. It should be able to discover the robot, understand its available capabilities, request an authorized embodiment session, use permitted sensors and actuators, respect the robot's safety envelope, and leave an auditable record of what it did.

This is the co-embodiment problem in retail: how can one embodied robot become shared infrastructure for multiple task-specific intelligences?

## Co-Embodiment Questions

- What store context should be shared between phones, glasses, and robots?
- How do multiple agents access the same camera, microphone, map, and task list?
- How should staff, customer, manager, and third-party agent permissions differ?
- How should a robot expose available capabilities without exposing unsafe actuation?
- How should provider Y discover that a robot currently used by provider X is available for a restocking embodiment session?
- How should the robot arbitrate between order-picking, restocking, navigation, and safety-critical requests?
- What must be logged when one intelligence provider inhabits a robot normally operated by another provider?
- How should task-generation agents cite the observations that led to a task?
- How should an agent request a bounded embodiment session in a retail domain?

## Standards Surfaces

Potential standard surfaces include:

- Spatial context package
- Embodied capability manifest
- Embodiment session request and lease model
- Shared task/event schema
- Permission model for retail domains
- Arbitration model for competing robot tasks
- Observation provenance and audit log
- Robot/site discovery handshake
