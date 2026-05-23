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

## Co-Embodiment Questions

- What should a mobile robot expose as shared capability?
- How should agents discover the robot and request embodiment sessions?
- How should the robot represent safety limits and restricted actions?
- How are conflicts resolved between navigation, observation, and future manipulation requests?
- What does it mean for a robot to be a platform for multiple intelligence providers?

## Standards Surfaces

Potential standard surfaces include:

- Robot capability manifest
- Spatial context package
- Agent task request schema
- Actuator permission and arbitration model
- Safety envelope representation
- Observation and action audit log
