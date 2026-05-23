# Mobile Robots Use Case

Mobile robots can start as perception systems and later become shared infrastructure for action.

## Problem

Many robotics deployments stall because the robot must solve locomotion, manipulation, perception, safety, operations, and customer ROI at once. The reliability threshold for manipulation and autonomous locomotion can be punishing.

## Perception-First Opportunity

Mobile robots can begin with lower-risk tasks:

- Night audits
- Site scanning
- Inventory and shelf-state capture
- Security patrol observations
- Environmental monitoring
- Data collection for digital twins
- Staff task generation

Once deployed, a robot with sensors, compute, connectivity, maps, and perhaps latent actuation can become infrastructure that other agents use.

## Co-Embodiment Questions

- What should a mobile robot expose as shared capability?
- How should agents discover the robot and request perception tasks?
- How should the robot represent safety limits and restricted actions?
- How are conflicts resolved between navigation, observation, and future manipulation requests?
- How do phones and glasses pre-deploy spatial context before the robot arrives?
- What does it mean for a robot to be a platform for multiple intelligence providers?

## Standards Surfaces

Potential standard surfaces include:

- Robot capability manifest
- Spatial context package
- Agent task request schema
- Actuator permission and arbitration model
- Safety envelope representation
- Observation and action audit log
