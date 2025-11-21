---
layout: page
title: Course Projects
permalink: /course-projects/
---

## Adaptive Warehouse Navigation System
<!-- Optional hero image -->
<!-- <img src="{{ site.baseurl }}/assets/img/projects/warehouse_nav.jpg" alt="Warehouse robot navigating aisles" width="900"> -->

This project targets safer autonomy in dynamic warehouse aisles, where layouts and obstacles change frequently. I built a real-time perception stack that combines <strong>YOLOv8</strong> detection with <strong>BLIP-2</strong> vision–language reasoning to filter obstacles and interpret scene cues. To harden the system, I generated synthetic scenes via diffusion and applied Prompt-to-Prompt edits to vary shelf layouts and obstacle density. Planning uses a lightweight grid heuristic constrained by the model’s semantic hints, yielding efficient, collision-free trajectories across diverse layouts. The result is a planner that behaves conservatively near people/objects while maintaining throughput. My role covered the full pipeline: dataset curation and augmentation, perception integration, and planner design/evaluation.  

---

## AudioGen — Audio-Driven Music Generation (MusicGen + CLAP)
<!-- Optional hero image -->
<!-- <img src="{{ site.baseurl }}/assets/img/projects/audiogen.jpg" alt="AudioGen controllable music generation" width="900"> -->

Creators need controllable audio generation that follows real-world sounds without collapsing diversity. I trained an <strong>audio→text</strong> labeler (using the MusicCaps vocabulary) to steer a pretrained <strong>MusicGen</strong> model toward target styles and instrumentation, then orchestrated batched generation and metrics over <strong>900+</strong> clips. Quantitative evaluation used <strong>CLAP</strong> similarity and Fréchet Audio Distance to track alignment versus novelty. Conditioning improved stylistic match while preserving variety, and the pipeline made prompt formatting and evaluation replicable end-to-end. I implemented data curation, classifier training, prompt construction, the generation harness, and the metrics suite.
