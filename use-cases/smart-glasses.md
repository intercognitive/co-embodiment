# Smart Glasses Use Case

Smart glasses may be the minimum viable co-embodiment platform because they expose shared real-world context without requiring a full robot body.

## Problem

Users will want many AI agents in the physical world, but those agents need shared access to the same embodied context: camera, microphone, IMU, display, speakers, location, and user state.

If every agent owns its own isolated pipeline, the platform becomes fragmented, unsafe, and difficult to reason about.

## Perception-First Opportunity

Smart glasses can provide:

- First-person visual context
- Audio context
- IMU and head-pose context
- Hands-free display and audio output
- User-mediated permissions
- Real-time task support

They can act as a pre-deployed robot with no arms or legs: a perception and interaction surface that lets agents enter the physical world.

## Co-Embodiment Questions

- How do multiple agents share camera and microphone access?
- How are proactive agents scheduled, muted, or interrupted?
- How does an agent request display or speaker output?
- How are private spaces, bystanders, and sensitive data protected?
- What is the manifest for available sensors and interaction channels?
- How does a user know which agent is currently observing or acting?

## Standards Surfaces

Potential standard surfaces include:

- Shared sensor access protocol
- Agent attention and interruption model
- Display and speaker arbitration model
- User permission and consent schema
- Embodied capability manifest for wearable devices
