# Mobile Robots Use Case

Mobile robots are a core co-embodiment domain because they combine sensors, spatial context, compute, connectivity, locomotion, and sometimes manipulation in one shared body.

## Problem

Many robots are built as closed systems controlled by a single application or operator. That makes it hard for outside agents to discover the robot, understand its available capabilities, request bounded access, or safely share the body with other agents.

## Shared Embodiment Opportunity

Mobile robots may expose several shared capability classes:

- sensor streams,
- site maps and spatial context,
- onboard compute and network access,
- navigation or repositioning,
- displays, speakers, lights, or other interaction channels,
- manipulation or other actuators when present.

The standards question is how a robot describes these capabilities, grants access to them, arbitrates competing requests, and maintains a safety envelope.

## Core Scenario

A facility already has a mobile robot operating overnight. Intelligence provider X has taught the robot to perform security patrol tasks: follow routes, inspect doors, detect anomalies, and alert staff.

Another intelligence provider, Y, wants to use the same robot to solve inventory audit tasks. Provider Y should not need to own the robot, replace provider X, or rebuild the facility integration. It should be able to discover the robot, inspect its capability manifest, request an authorized embodiment session, use permitted cameras and navigation, avoid interfering with safety or patrol duties, and leave an auditable record of its inventory observations.

This is the co-embodiment problem for mobile robots: how can one mobile body become shared infrastructure for multiple operational intelligences?

## Co-Embodiment Questions

- What should a mobile robot expose as shared capability?
- How should agents discover the robot and request embodiment sessions?
- How should the robot represent safety limits and restricted actions?
- How are conflicts resolved between navigation, observation, and future manipulation requests?
- What does it mean for a robot to be a platform for multiple intelligence providers?
- How should provider Y discover that a robot currently used by provider X is available for an inventory embodiment session?
- How should the robot arbitrate between security patrol, inventory audit, navigation, charging, and safety-critical requests?
- What must be logged when one intelligence provider inhabits a robot normally operated by another provider?

## Standards Surfaces

Potential standard surfaces include:

- Robot capability manifest
- Spatial context package
- Embodiment session request and lease model
- Agent task request schema
- Actuator permission and arbitration model
- Safety envelope representation
- Observation and action audit log
