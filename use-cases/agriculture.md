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

## Co-Embodiment Questions

- How should a farm domain expose maps, crop rows, sensor data, and inspection history?
- How should a rover, drone, phone, and fixed camera share observations?
- How should third-party agronomy agents request data or actions?
- What permissions are needed for observation versus chemical or mechanical action?
- How should confidence, provenance, and recommended interventions be represented?
- How should agents request embodiment sessions on rovers, drones, or fixed infrastructure?

## Standards Surfaces

Potential standard surfaces include:

- Field spatial context package
- Crop observation schema
- Embodied capability manifest for rovers and drones
- Permission model for inspection versus intervention
- Observation provenance and audit log
