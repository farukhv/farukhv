# Mars Rover Edge AI — Case Study

> Public engineering summary of a private hackathon project. Secrets, API keys and private team material are intentionally excluded.

## Context

A Mars rover cannot treat every sensor reading and image as equally important. Communication delay and limited bandwidth make it valuable to analyze data locally before transmitting it to Earth.

## Concept

The prototype evaluates astrobiological sensor readings and camera images on the rover side, then prioritizes meaningful changes and possible anomalies.

```text
sensor / camera input
        │
        ▼
 local edge analysis
        │
   ┌────┴────┐
   │         │
minor      meaningful
change      event
   │         │
   ▼         ▼
store      compress / prioritize
locally        │
               ▼
          transmit to Earth
```

## Engineering highlights

- Python desktop prototype with separated domain and UI responsibilities
- sensor decision logic designed independently from the interface
- AI-assisted image anomaly/change analysis
- structured model output instead of fragile free-text parsing
- confidence thresholds before accepting AI detections
- image crop, resize and compression pipeline for bandwidth simulation
- background analysis so the UI remains responsive
- graceful behavior when AI services are unavailable

## What this project taught me

The interesting part was not simply adding an AI API. It was deciding **where AI belongs in the system**, how uncertain outputs should be handled, and how to keep the rest of the product useful when an external model is unavailable.

## Areas involved

`Python` · `Edge Computing` · `AI` · `Image Processing` · `System Design` · `Space Technology`

---

[← Back to profile](../README.md)
