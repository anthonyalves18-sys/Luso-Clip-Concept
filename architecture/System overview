# System Overview

## Overview

LusoClip is designed as a hybrid system consisting of a lightweight wearable device and a companion mobile application.

The wearable focuses exclusively on audio capture and transmission, while all computationally intensive tasks are handled by the smartphone.

---

## Component Responsibilities

### Wearable Device
- Continuous microphone capture
- Short rolling audio buffer
- Bluetooth audio streaming
- No language detection
- No persistent storage
- No audio playback

### Mobile Application
- Language detection
- Portuguese speech-to-text
- Portuguese → English translation
- English text-to-speech
- Audio playback through phone speaker
- Live transcript display

---

## Architectural Rationale

This separation reduces hardware complexity, lowers power consumption on the wearable, and allows translation logic to improve independently of the physical device.

The device behaves as a passive relay rather than an active recording system.
