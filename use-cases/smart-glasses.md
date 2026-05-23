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

## Co-Embodiment Questions

- How do multiple agents share camera and microphone access?
- How are proactive agents scheduled, muted, or interrupted?
- How does an agent request display or speaker output?
- How are private spaces, bystanders, and sensitive data protected?
- What is the manifest for available sensors and interaction channels?
- How does an agent request and release an embodiment session on the glasses?
- How does a user know which agent is currently observing or acting?

## Standards Surfaces

Potential standard surfaces include:

- Shared sensor access protocol
- Agent attention and interruption model
- Display and speaker arbitration model
- User permission and consent schema
- Embodied capability manifest for wearable devices
