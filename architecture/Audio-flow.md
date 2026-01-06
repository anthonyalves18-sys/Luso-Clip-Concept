# Audio Flow

## Overview

Audio is streamed continuously from the wearable device to the smartphone in short, transient segments.

The system listens moment-to-moment and discards audio once translation is complete.

---

## Audio Segmentation

- Continuous audio sampling on device
- Silence detection used to identify phrase boundaries
- Typical phrase duration: 1.5–4 seconds
- Background noise below threshold ignored

Only completed speech segments are processed.

---

## Translation Trigger Rules

- Portuguese confidence exceeds threshold
- Speech segment exceeds minimum duration
- No overlapping or competing voices detected

If conditions are not met, audio is ignored.

---

## Output Strategy

Translated English audio is played through the phone speaker to avoid drawing attention to the wearable device and to preserve natural conversational dynamics.
