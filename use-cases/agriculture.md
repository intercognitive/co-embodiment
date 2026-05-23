# Agriculture Use Case

Agriculture is a useful co-embodiment domain because farms may contain rovers, drones, fixed sensors, maps, agronomy systems, and third-party agents that need to share context and capabilities.

## Problem

Permanent crop operations can lose significant yield to disease, pests, irrigation problems, and other environmental conditions. Many devices and agents may observe, interpret, recommend, or act on the same field context.

## Shared Embodiment Opportunity

Several embodied surfaces may need to cooperate in the same field:

- rovers and drones,
- fixed cameras and environmental sensors,
- phones and tablets used by field workers,
- field maps, crop rows, and agronomy records,
- third-party agents that need bounded access to observations or interventions.

The standards question is how these systems discover one another, share field context, and expose capabilities under different permissions for inspection, recommendation, and action.

## Core Scenario

A grower already has a rover operating in a vineyard. Intelligence provider X has taught the rover to perform crop-health scouting: follow rows, capture close-up imagery, identify disease pressure, and produce inspection reports.

Another intelligence provider, Y, wants to use the same rover to solve irrigation optimization tasks. Provider Y should not need to own the rover, replace provider X, or rebuild the farm integration. It should be able to discover the rover, understand its sensors and route capabilities, request an authorized embodiment session, access permitted field context, collect the observations it needs, and leave an auditable record of its recommendations.

This is the co-embodiment problem in agriculture: how can one field robot become shared infrastructure for multiple agronomic intelligences?

## Co-Embodiment Questions

- How should a farm domain expose maps, crop rows, sensor data, and inspection history?
- How should a rover, drone, phone, and fixed camera share observations?
- How should third-party agronomy agents request data or actions?
- What permissions are needed for observation versus chemical or mechanical action?
- How should confidence, provenance, and recommended interventions be represented?
- How should agents request embodiment sessions on rovers, drones, or fixed infrastructure?
- How should provider Y discover that a rover currently used by provider X is available for an irrigation embodiment session?
- How should the rover arbitrate between crop scouting, irrigation inspection, routing, battery constraints, and safety-critical requests?
- What must be logged when one agronomy provider inhabits a rover normally operated by another provider?

## Standards Surfaces

Potential standard surfaces include:

- Field spatial context package
- Crop observation schema
- Embodied capability manifest for rovers and drones
- Embodiment session request and lease model
- Permission model for inspection versus intervention
- Arbitration model for competing field tasks
- Observation provenance and audit log
