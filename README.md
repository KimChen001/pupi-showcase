<div align="center">

# PUPI

### A familiar voice. A warmer connection.

**Conversational companionship for everyday life.**

A WeChat mini-program exploring emotional companionship, gentle daily engagement,
and a path toward voice-enabled companion devices.

[Explore the demo](DEMO.md) · [See the vision](ROADMAP.md) · [中文介绍](README.zh-CN.md)

**Interface demonstrated · Voice and device integration in development**

</div>

## A companion people can approach

PUPI starts with a simple idea: people should be able to ask for company in an ordinary,
comfortable way. A familiar character, an accessible conversation screen, and small daily
activities create different ways to begin an interaction.

The current software brings these ideas into a native WeChat mini-program. The longer-term
vision is to carry that conversational experience into a small companion device: something
that can listen, respond, and make everyday moments feel more connected.

## Inside the current experience

<table>
  <tr><th>A familiar starting point</th><th>An invitation to talk</th><th>A little daily engagement</th></tr>
  <tr>
    <td><img src="assets/01-home.png" width="260" alt="Actual PUPI mini-program home screen with a companion character and demonstration activity cards"></td>
    <td><img src="assets/02-conversation.png" width="260" alt="Actual PUPI conversation interface with voice and keyboard entry controls"></td>
    <td><img src="assets/03-training.png" width="260" alt="Actual PUPI training interface with daily activity tracking and exercise entry points"></td>
  </tr>
</table>

*Screens captured from the running project in WeChat Developer Tools on November 2, 2026.
Health and device values shown are simulated development data. The screenshots demonstrate
the interface; they do not establish connected-device performance or health outcomes.*

### Talk and be heard

The conversation screen offers a press-to-talk entry, keyboard input, a simplified mode,
and shortcuts for relaxation, breathing, and family contact. The source includes Coze
conversation and workflow integrations, contextual prompts, and fallback responses.
These give the project a concrete software base for exploring empathetic dialogue.

### Make room for everyday engagement

The mini-program includes an activity hub with memory and attention exercises, breathing-related
interaction, and local progress tracking. These are interaction and engagement features;
their therapeutic or cognitive effects have not been established.

### Connect conversation to a physical companion

The project includes BLE communication modules, audio buffering and conversion utilities,
an Express backend, a cloud-function proxy, and ESP32 microphone/speaker firmware code.
They outline the connection between the mini-program and a voice-enabled device.
The complete device-to-speech-recognition-to-reply-playback loop still needs integration
and hardware validation.

## Development focus

This portfolio presents Zhixin Chen's work on PUPI's software and interaction layer:

- Native mini-program interfaces for conversation, daily activities, and device-facing workflows.
- AI conversation and workflow integration, including context handling and fallback behavior.
- BLE/audio integration code and an ESP32 firmware starting point for physical interaction.
- Translating companionship scenarios into software flows that can be demonstrated and evaluated.

## What exists, and what comes next

| Area | Current evidence | Next step |
| --- | --- | --- |
| Mini-program experience | Home, conversation, and activity screens observed in the running developer-tool session | Device testing and accessibility review |
| AI dialogue | Conversation/workflow client code and contextual response logic are present | Repeatable evaluation of empathy, relevance, consistency, and safe responses |
| Voice interaction | Voice controls, recognition-related code, audio utilities, and backend scaffolding are present | Replace simulated paths and validate the complete speech pipeline |
| Physical integration | BLE handlers and ESP32 microphone/speaker firmware code are present | Test transfer reliability, playback, interruption, and recovery on hardware |
| Physiological context | Dashboard and simulated sensor-data paths are present | Optional research integration with consent and independently validated sensing |
| Companion robotics | Software-to-device integration concept | Co-develop a physical companion experience with hardware partners |

## A path toward companion robotics

PUPI is being shaped around capabilities relevant to older-adult companion robots and small,
approachable emotional-companion devices: supportive dialogue, voice interaction, visible
device states, and simple ways to pause or leave an interaction.

The opportunity is to connect those software capabilities with a physical presence. The next
stage is a measured progression: improve the conversation, complete the voice loop, integrate
a device, and evaluate the experience with users. [Read the roadmap.](ROADMAP.md)

## Engineering foundation

**Native WeChat mini-program · JavaScript · WXML/WXSS · Coze integrations · Node.js/Express · BLE · ESP32/I2S**

This repository contains presentation material and selected screenshots. Application source,
runtime credentials, and internal development notes are maintained in a separate private repository.
No clinical validation, production hardware deployment, or university partnership is claimed here.

---

Project portfolio: [Zhixin Chen](https://github.com/KimChen001)
