# IGNIS — Autonomous Dual-Domain Predictive Sentinel

> **Next-Generation Autonomous Dual-Domain Predictive Sentinel for Frontline Firefighters & Industrial Hazardous Environments**  
> *Vishwakarma Awards National Finalist & Ashoka University Mentor Track Innovation*

---

## Overview

**IGNIS** is an ultra-ruggedized, spherical throwable sentinel engineered to enter structurally compromised, high-heat, and zero-visibility environments ahead of frontline firefighters and emergency response units. By fusing acoustic emission sensing with multi-spectral thermal radiometry and sub-gigahertz telemetry, IGNIS detects structural micro-fractures (predicting structural collapse) and flashover/thermal runaway conditions before human responders cross the threshold.

---

## Core Capabilities

- **Dual-Domain Predictive Sensing**: Fuses high-frequency piezoelectric acoustic emission signals with thermal radiometric data to identify structural failure mechanics and radiant flashover signatures in real time.
- **Spherical Self-Righting Shell**: Ballistic polycarbonate / carbon-fiber outer shell insulated with silica aerogel and Phase Change Materials (PCM) capable of withstanding extreme radiant heat (>600°C) and violent impacts.
- **Sub-GHz Long-Range Telemetry**: Robust penetration through reinforced concrete and steel infrastructure using localized 865–867 MHz LoRa / Sub-GHz mesh networks.
- **Frontline Alert Engine**: Simplified dual-alarm tactical output—structural integrity degradation and flashover proximity warnings—communicated via tactile telemetry and 520nm high-penetration optical strobes.

---

## System Architecture

```
┌────────────────────────────────────────────────────────────────────────┐
│                        IGNIS SENTINEL ARCHITECTURE                     │
├────────────────────────────────────────────────────────────────────────┤
│                                                                        │
│   [ Environmental Input ]                                              │
│         │                                                              │
│         ├─► Piezo Acoustic Transducer ──► Analog Front-End (DSP)       │
│         │                                       │                      │
│         └─► Multi-Spectral Radiometric IR ──────┤                      │
│                                                 ▼                      │
│                                       [ Dual-Core MCU / DSP ]          │
│                                       • Micro-fracture FFT / Wavelet   │
│                                       • Rate-of-Rise Thermal Predictor │
│                                                 │                      │
│                                                 ▼                      │
│                                       [ Sub-GHz Transceiver ]          │
│                                       (865–867 MHz WPC Compliant)       │
│                                                 │                      │
│                                                 ▼                      │
│                                 [ Incident Commander HUD / Base Node ] │
└────────────────────────────────────────────────────────────────────────┘
```

---

## Repository Contents

- **CAD Blueprints & Assemblies**: High-resolution exploded views, spherical sensor pod assemblies, and mechanical schematics.
- **Signal Processing & Flowcharts**: Acoustic front-end signal chain schematics, piezoelectric sensor conditioning, and system state machines.
- **Competition & Technical Reports**: Vishwakarma Awards documentation, system specifications, and verification data.

---

## Specifications

| Parameter | Specification |
| :--- | :--- |
| **Enclosure** | Spherical shock-damped shell with Silica Aerogel + PCM barrier |
| **Thermal Ceiling** | Up to 600°C ambient radiant exposure (transient) |
| **Compute Engine** | Low-power dual-core microcontroller with onboard hardware DSP |
| **Sensing Modalities** | Acoustic Emission (AE), Multi-zone Thermopile/Radiometer, IMU |
| **Telemetry** | Sub-GHz 865–867 MHz long-penetration mesh protocol |
| **Form Factor** | Throwable hand-held sphere (<550g) designed for bunker gloves |

---

## License

All rights reserved © 2026 Shreeprasandh K. Developed for the Vishwakarma Innovation Awards.
