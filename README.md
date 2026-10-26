# Pedro Henrique

### Mechanical Engineering | Robotics | Automation | Digital Twins | Physical AI

I am a Mechanical Engineering student at **UFTM**, working on robotics and studying how physical machines, communication, simulation and intelligent software fit together.

My long-term direction is to design and understand the physical system, model its virtual counterpart, connect both reliably, measure the difference, and then explore intelligent behavior.

[LinkedIn](https://www.linkedin.com/in/pedro-henrique-b75207227/) · [Public repositories](https://github.com/Pedronsjaja?tab=repositories)

## Current Focus

The diagram describes my learning and development direction. It is not an implemented end-to-end system.

```text
Physical system
      ↕
Sensors / actuators / embedded systems
      ↕
ROS 2 / DDS  ·  OPC UA / MQTT (planned study)
      ↕
Digital Twin synchronization (planned)
      ↕
Gazebo  ·  Isaac Sim / OpenUSD (future evaluation)
      ↕
AI / perception / planning / autonomous systems (research direction)
```

- **Building on:** Python actuator tooling, ROS 2/Gazebo simulation, mechanical CAD and telemetry.
- **Studying:** communication architectures, DDS QoS, latency, jitter, state consistency and physical/virtual synchronization.
- **Future experiments:** OPC UA/MQTT gateways, edge computing and Edge AI, sim-to-real, and autonomous behavior.
- **Secondary track:** CAD/CAE automation and traceable CAD-to-simulation workflows.

Physical AI is a long-term research direction here; no deployed learning-based controller is claimed.

## Selected Engineering Projects

| Project | Current evidence | Next step |
|---|---|---|
| [GAIA Humanoid Simulation](https://github.com/Pedronsjaja/gaia-humanoid-simulation) | ROS 2 Jazzy/Gazebo Harmonic package using the ROBOTIS OP3 reference model, joint control, camera and IMU; automated simulation checks | Identify a GAIA joint and plan Digital Twin integration. The fixed-base OP3 lab is not a complete GAIA Digital Twin. |
| [LX-225 / BusLinker Test Bench](https://github.com/Pedronsjaja/gaia-lx225-buslinker) | Python serial driver, position/voltage/temperature feedback, logging and mocked serial tests; velocity is estimated | A single-actuator physical/virtual experiment, starting with a documented ROS 2 interface |
| [GAIA Humanoid Structure](https://github.com/Pedronsjaja/gaia-humanoid-structure) | Mechanical CAD assets, mounting guidance and a model-data checklist | Identify masses, joint axes, limits and provenance before CAD → URDF/USD → simulation |
| [ROS 2 Environment](https://github.com/Pedronsjaja/gaia-ros2-ubuntu24) | Ubuntu 24.04/Jazzy setup and environment validation documentation | Record reproducible machine configurations for the experiments |

## Physical AI Digital Twin Lab — Documented / Planned

I am developing the architecture of [physical-ai-digital-twin-lab](https://github.com/Pedronsjaja/physical-ai-digital-twin-lab), an experimental laboratory for robotics, distributed communication and physical/virtual synchronization.

The first target is one virtual actuator, followed by an LX-225/BusLinker connection and a reproducible comparison of physical and virtual state. Architecture and experiment planning come before hardware integration, middleware benchmarks or AI. The repository contains architecture, a research roadmap and initial Issues; runtime implementation is planned.

## Team Contributions

- **GAIA Robotics:** team captain.
- **Valkiriaz — H2 Challenge:** vice-president, contributing to ROS 2, Digital Twin, telemetry and modeling work.
- **URASpace:** 3D modeling and physical rocket testing.

Team projects involve multiple contributors. These roles do not imply sole authorship or independent validation of every system.

## Supporting Work

[ESP32-S3 learning firmware](https://github.com/Pedronsjaja/Hacking-tico-com-Esp32-s3) ·
[GeekMagic PC telemetry](https://github.com/Pedronsjaja/geekmagic_pc_monitor) ·
[Leve11](https://github.com/Pedronsjaja/Leve11) ·
[GAIA portal contributions](https://github.com/Pedronsjaja/portal-gaia) ·
[GAIA website contributions](https://github.com/Pedronsjaja/gaiarobotica-new.github.io)

I aim to preserve raw data, document engineering decisions, and distinguish **implemented**, **experimental**, **documented** and **planned** work. Software tests, simulation and physical validation are separate kinds of evidence.
