# From conversation to companionship

PUPI's vision is a companion that is easy to approach, comfortable to talk to, and clear about
what it can do. The current mini-program is a place to develop and test that experience before
extending it into a physical device.

This is a development direction, not a delivery commitment. Progress depends on evidence at each stage.

## 1 Make the conversation worth returning to

Develop dialogue that responds to what a person actually says, acknowledges feelings without
pretending to diagnose them, and uses context only within the user's chosen boundaries.

**Evidence to seek:** repeatable dialogue evaluations for relevance, empathetic wording,
context consistency, appropriate boundaries, and recovery when the system misunderstands.

## 2 Complete the voice loop

Connect audio capture, speech recognition, AI dialogue, speech generation, and playback.
Make listening, thinking, speaking, interruption, and errors understandable to the user.

**Evidence to seek:** measured latency, transcription quality in defined conditions, successful
interruption and cancellation, and recovery after network or device failures. Current code
includes unfinished and simulated paths; these measurements have not yet been established.

## 3 Give the interaction a physical presence

Use the existing BLE and ESP32 work as a starting point for integration with a companion device.
Evaluate simple controls, clear status feedback, and an approachable form with hardware partners.

**Evidence to seek:** repeatable audio transfer and playback on actual hardware, understandable
pause/stop controls, and reliable reconnection. A finished companion robot is a future goal.

## 4 Learn from everyday use

Run a limited, consent-based usability study in a clearly defined setting. Observe whether people
understand the interface, feel in control, and find the interactions useful enough to revisit.

**Evidence to seek:** usability observations, reasons for disengagement, conversation feedback,
and failure reports. Engagement is not a substitute for evidence of emotional or health benefit.

## 5 Explore optional context carefully

Later research may explore user-authorized contextual or physiological signals to inform an
interaction. The current sensor dashboard uses simulated development data and does not validate
emotion recognition, brain-computer interaction, fall detection, or medical monitoring.

The goal is a useful companion experience whose claims grow with its evidence.
