# Agriculture Use Case

Agriculture is an early candidate for perception-first deployment because crop health observations can create large value while keeping deployment risk comparatively low.

## Problem

Permanent crop operations can lose significant yield to disease, pests, irrigation problems, and other environmental conditions. Many high-value tasks are observation problems before they are manipulation problems.

## Perception-First Opportunity

Useful tasks can be performed through observation:

- Crop disease detection
- Growth-stage monitoring
- Pest and stress detection
- Yield forecasting
- Irrigation and microclimate observations
- Targeted inspection with cameras, phones, drones, or rovers

A rover may later carry manipulators, sprayers, or other tools, but the first territory-capturing deployment can be perception.

## Co-Embodiment Questions

- How should a farm domain expose maps, crop rows, sensor data, and inspection history?
- How should a rover, drone, phone, and fixed camera share observations?
- How should third-party agronomy agents request data or actions?
- What permissions are needed for observation versus chemical or mechanical action?
- How should confidence, provenance, and recommended interventions be represented?

## Standards Surfaces

Potential standard surfaces include:

- Field spatial context package
- Crop observation schema
- Embodied capability manifest for rovers and drones
- Permission model for inspection versus intervention
- Observation provenance and audit log
