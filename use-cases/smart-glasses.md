# Smart Glasses Use Case

Smart glasses are a useful co-embodiment domain because multiple agents may need to share the same user-worn sensors and output channels.

## Problem

Users will want many AI agents in the physical world, but those agents need shared access to the same embodied context: camera, microphone, IMU, display, speakers, location, and user state.

If every agent owns its own isolated pipeline, the platform becomes fragmented, unsafe, and difficult to reason about.

## Shared Embodiment Opportunity

Smart glasses can provide:

- First-person visual context
- Audio context
- IMU and head-pose context
- Hands-free display and audio output
- User-mediated permissions
- Real-time task support

The standards question is how these channels become discoverable and co-habitable without allowing agents to overwhelm the user, violate privacy, or fight over scarce output surfaces.

## Core Scenario

A worker is wearing smart glasses in a warehouse. Intelligence provider X has an agent using the glasses for pick-path guidance: reading shelf labels, confirming item locations, and presenting turn-by-turn instructions.

Another intelligence provider, Y, wants to use the same glasses to solve safety coaching tasks. Provider Y should not need to own the glasses, replace provider X, or rebuild the wearable integration. It should be able to discover the available camera, microphone, IMU, display, and speaker capabilities, request an authorized embodiment session, receive only permitted context, and surface warnings without disrupting critical pick-path guidance.

This is the co-embodiment problem for smart glasses: how can one worn device become a shared embodied interface for multiple task-specific agents?

## Co-Embodiment Questions

- How do multiple agents share camera and microphone access?
- How are proactive agents scheduled, muted, or interrupted?
- How does an agent request display or speaker output?
- How are private spaces, bystanders, and sensitive data protected?
- What is the manifest for available sensors and interaction channels?
- How does an agent request and release an embodiment session on the glasses?
- How does a user know which agent is currently observing or acting?
- How should provider Y discover that glasses currently used by provider X can support a safety-coaching embodiment session?
- How should the glasses arbitrate between pick-path instructions, safety warnings, notifications, and human override?
- What must be logged when one agent observes or speaks through a wearable normally used by another agent?

## Standards Surfaces

Potential standard surfaces include:

- Shared sensor access protocol
- Agent attention and interruption model
- Display and speaker arbitration model
- User permission and consent schema
- Embodied capability manifest for wearable devices
- Embodiment session request and lease model
- Observation and interaction audit log
