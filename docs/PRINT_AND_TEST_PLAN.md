# Mila Animatronic Vision V1 — Print and Test Plan

**Status:** Proposed design and experiments; no validated physical build.

## Prototyping objectives

Prioritize repairability, accurate assembly, safe clearances, reliable movement, modular upgrades and straightforward access to electronics.

## Candidate printed parts

| Part group | Initial material to evaluate | Key test |
| --- | --- | --- |
| Internal frame, mounts | PETG | Rigidity, fasteners, heat tolerance |
| Face panels and shell | PLA or PETG | Surface finish, fit, replaceability |
| Eye gimbals and camera holders | PETG | Friction, clearances, repeatability |
| Eyelid and eyebrow linkages | PETG; alternatives if needed | Fatigue, smooth motion |
| Jaw pivots and brackets | PETG | Alignment, collisions |
| Electronics trays, cable guides | PLA or PETG | Access, strain relief |

Material choices are hypotheses, not proven selections.

## Mechanical test sequence

1. **Calibration samples:** check dimensions, holes, clearances and orientation-dependent strength.
2. **Single eye module:** verify camera fit, cable bending, pan/tilt range and physical limits.
3. **Lid and brow mechanisms:** verify linkage interference and cycle-to-cycle consistency.
4. **Jaw assembly:** check alignment, safe travel stops, vibration and clearance against face panels.
5. **Neck rig:** establish balance, torque needs, stability and safe cable routing.
6. **Integrated head:** log print times, failures, assembly fit, power behavior and redesigns.

## Proposed control chain

Mila PC (AI / interface) → ESP32-class controller → PCA9685-class PWM driver → servos.

Camera and lighting control will be planned separately. Before power testing, assess protected actuator power, grounding, wiring separation, motion limits, safe startup and emergency shutoff.

## Publishable evidence

- CAD revisions alongside clearly identified *real* print photographs.
- Print settings, material amounts and test conditions.
- Measurements of fit, tolerances, failures and redesigns.
- Video demonstrations **only after a mechanism actually works**.
- Selected generic mounts, print settings and assembly guidance where appropriate.

Dimensions and movement range estimates in concept images are not verified specifications.
