---
layout: page
title: Research
permalink: /research/
---

## Visuo–Tactile Sensing for Robust Contact Perception
<!-- Optional hero image -->
<!-- <img src="{{ site.baseurl }}/assets/img/projects/visuotactile_hero.jpg" alt="Visuo-tactile sensor" width="900"> -->

I am building a </strong>new visuo–tactile</strong> stack that renders frames completely black before touch—eliminating ambient-light artifacts—and, upon contact, simultaneously captures both </strong>tactile</strong> deformation and overlaid </strong>color/text</strong> from the object. This design stays reliable on very </strong>soft/low-stiffness</strong> materials (e.g., water droplets, facial cream, thin plastic film) where prior sensors degrade. A lightweight cv2 pipeline (ROI/contours and feature extraction) turns raw frames into stable contact patches, and a VLM uses color cues to sort resistors by code with <strong>82%</strong> end-to-end accuracy. I led the sensor design, software pipeline, and robustness evaluation.

---

## <a href="https://linchangyi1.github.io/LocoTouch/">LocoTouch: Learning Dynamic Quadrupedal Transport with Tactile Sensing</a>
<!-- Optional hero image -->
<!-- <img src="{{ site.baseurl }}/assets/img/projects/locotouch_hero.jpg" alt="LocoTouch quadruped" width="900"> -->

We target safe transport of unsecured objects by making the robot “feel” load motion through a <strong>221-taxel</strong> piezoresistive back pad and react accordingly. I designed and fabricated the array, improved manufacturing repeatability/yield and the low-noise PCB, and co-developed a tactile-aware policy using a <strong>teacher–student pipeline (PPO → DAgger)</strong> with <strong>PD</strong> tracking for hardware stability. The student policy consumes tactile + proprioceptive signals and achieves <strong>zero-shot</strong> sim-to-real transport across long distances and varied terrain. Contributions include sensing bring-up and calibration, evaluation/ablations, and real-robot trials.

---

## Vine-Robot Anchors for Mars Rover Locks & Drilling
<!-- Optional hero image -->
<!-- <img src="{{ site.baseurl }}/assets/img/projects/vinerobot_anchor.jpg" alt="Vine-robot anchor" width="900"> -->

At UCSB’s Hawkes Lab, I designed compliant vine-robot mechanisms that act as temporary “locks” to steady rover tooling on sand–pebble–dust (Mars-regolith analog) surfaces. I built a <strong>3 × 3 × 2 m</strong> granular testbed with Raspberry-Pi sensing/control and CV evaluation, modeled rover–vine interaction, and developed a controller stack with <strong>LQI</strong> pose regulation (integrators on x–y–yaw) and <strong>MRAC</strong> adaptation to handle wind gusts and soil/contact changes. We validated station-keeping under varying friction and lateral loads, showing improved robustness versus LQI alone.
