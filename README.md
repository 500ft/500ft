# Mergen Ulziibayar

Mechanical engineering student at NYU building evidence-driven robotics and
mechanical systems: **Predict → Measure → Compare → Revise**.

My strongest work is organized around explicit acceptance gates, reproducible
analysis, and honest negative results—not just finished-looking demos. Where a
result is simulation-only or a measurement is still pending, the repository says
so.

## Flagship work

### [Soft Actuator Recalibration](https://github.com/500ft/soft-actuator-recalibration)

When should a soft robot recalibrate? A reproducible simulation study of
pressure–volume probes and pressure-only pose estimation. Across 2,000
actuator-split traces, P-V loop area tracks fatigue compliance drift at pooled
**r = 0.885**, and the deployed trigger has **no positive temporal lead**—a
limitation reported rather than tuned away. The archived v1.3 manuscript carries
a published correction notice for a methods overstatement; a corrected candidate
is under author review, with no DOI or arXiv identifier claimed.

### [Autonomous Racing Systems](https://github.com/500ft/autonomous-racing-systems)

F1TENTH-scale vehicle modeling, system identification, controls, ROS 2
telemetry, and LiDAR-mast structural design. The baseline mast **failed** its
≥200 Hz modal guard at **174.7 Hz**; the redesigned geometry clears it at
**285.5 Hz** in mesh-converged FEA, a 1.43× margin. A calibrated physical
compliance test is preregistered and measurement is pending.

### [Multirotor Recovery Dynamics](https://github.com/500ft/multirotor-recovery-dynamics)

Guarded micro-UAV release-to-recovery study. The robustness sweep recovers only
**4.0%** under placeholder torque; an assumed four-motor mixer *combined with a
revised controller* recovers 300/300 in the reported sweep—not an isolated
torque fix. The deciding 7.0 V bench gate is frozen at **0.020 N·m** with at
least **962/1,000** primary recovery trials; measurement is pending.

## Supporting projects

- [engineering-audit](https://github.com/500ft/engineering-audit) — CLI and benchmark suite that checks units, formulas, assumptions, and arithmetic in LLM-generated engineering calculations, with hash-verified capture provenance.
- [segmented-shroud-aeromechanics](https://github.com/500ft/segmented-shroud-aeromechanics) — measurement-first research design on segmented rotor-shroud defects and tip clearance.
- [uav-failsafe-composition](https://github.com/500ft/uav-failsafe-composition) — configuration-specific native UAV recovery after command loss, with falsifiable fleet-composition experiments.
- [sensor-enclosure-thermal-design](https://github.com/500ft/sensor-enclosure-thermal-design) — analytical thermal design and day/night test preparation for outdoor sensor enclosures.
- [informal-road-mapping](https://github.com/500ft/informal-road-mapping) — satellite screening for candidate informal-road corridors; synthetic tests, Mongolia validation pending.
- [Nomad](https://github.com/500ft/Nomad) — maps mechanical-engineering topics to ranked papers, researchers, and source-linked project ideas.

## Links

- [Portfolio](https://portfolio-omega-neon-53.vercel.app)
- [LinkedIn](https://www.linkedin.com/in/u-mergen/)
- [Email](mailto:mergen.ulzi@gmail.com)

Python · CAD/FEA · ROS 2 · controls · system identification · experimental design
