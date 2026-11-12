# Mila — Animatronic Vision V1

**A modular 3D-printed animatronic desktop head for a primarily local AI assistant.**

**Status:** Design concept; Mila software is under active development. The physical head has **not** yet been built or validated.

**Application:** Snapmaker Innovation Fund Phase 2 — **U1 Hardware Sponsorship**  
**Category:** Other · **Originality:** Original New Idea · **Core software:** Closed source

![Mila Animatronic Vision V1 design concept](assets/mila-animatronic-vision-v1-concept.png)

> **Concept illustration, not a photo of a finished prototype.** Parts, dimensions, materials and motion ranges shown in the concept are design targets requiring verification.

## The concept

Mila is an independent AI-assistant project based in the Netherlands. Its long-term goal is to combine primarily local AI software with a physical, expressive desktop presence.

**Animatronic Vision V1** is the proposed first physical version: a roughly **33 cm tall** modular mechanical head with two camera-equipped eyes, independently moving eyelids and eyebrows, an articulated jaw for future speech animation and a pan/tilt neck. A printed internal frame would carry mechanisms, while replaceable face panels provide access for maintenance and redesign. The exact size and assembly will be established through CAD and print tests.

## Planned mechanisms

| Subsystem | Intended function | Printed parts to develop |
| --- | --- | --- |
| Camera eyes | Independent eye pan/tilt, ice-blue LED-ring accents | Eye shells, gimbals, lens and camera holders |
| Eyelids | Controlled blinking | Hinges, lids, linkage brackets |
| Eyebrows | Expressive movement | Brow panels and linkages |
| Jaw | Opening and closing; future lip-sync | Jaw shells, pivots and couplers |
| Neck | Pan and tilt | Supports, joints and cable channels |
| Face housing | Modular, repairable construction | Removable panels, access covers and frame |

**Proposed electronics, subject to tests:** an ESP32-class controller, a PCA9685-class servo driver, approximately 8–12 servos, two camera modules, LED rings and a separate computer running Mila. These are not verified final specifications.

## Why the Snapmaker U1?

Building a moving animatronic face requires repeated print-and-test cycles, accurate alignment of moving parts and rapid replacement of failed or improved components. The U1 would be used for:

- Prototyping compact eye gimbals, eyelid linkages, jaw pivots, servo mounts and neck brackets.
- Testing fit, tolerances, strength and assembly of closely interacting printed parts.
- Producing modular facial panels and exploring multi-color/toolchanging workflows for mechanical and decorative details.
- Iterating repairable components and shareable print practices for other makers.

The goal is to evaluate real print performance rather than assume the mechanisms will work on the first attempt.

## Development roadmap

1. **CAD:** determine clearances, dimensions, load limits and an initial bill of materials.
2. **Modular frame:** print the structural skeleton and removable face panels; test fitting and access.
3. **Facial movement:** build and test eye, eyelid, eyebrow and jaw mechanisms individually.
4. **Neck and electronics:** test balance, safe motion limits, protected power and cable routing.
5. **Integration:** connect verified hardware to Mila's local software using user-controlled commands.
6. **Documentation:** publish progress photos, actual tests, failures, revisions and useful print settings.

[Detailed print and test plan](docs/PRINT_AND_TEST_PLAN.md)

## What exists today?

The **software is being developed**, but this public repository is **a concept presentation and proposed hardware roadmap**, not a finished robot, verified hardware demonstration or open-source release of Mila's AI system.

The physical animatronic is **not built yet**. Concept artwork depicts a design intention, not proof of a functioning prototype. Working functionality will only be claimed after testing.

## Community contribution

I aim to share design decisions, print settings, tolerance measurements, assembly observations, photographs of real prototypes and selected non-proprietary printable designs when appropriate. Technical failures and redesigns will be documented too.

The core AI software remains **closed source**. This repository intentionally contains **no private Mila code, credentials or secrets**, and does not grant an open-source license to the project.

## Snapmaker application

- **Project:** Mila — Animatronic Vision V1
- **Location:** Netherlands
- **Support requested:** Snapmaker U1 Hardware Sponsorship
- **Project category:** Other
- **Source model:** Closed Source
- **Originality:** Original New Idea

[Full Snapmaker project summary](docs/SNAPMAKER_PROJECT_SUMMARY.md)

---
*Built as a concept-led independent maker project, with honest public documentation of future physical validation.*
