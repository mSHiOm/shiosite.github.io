---
layout: post
title:  "Chromotion"
date:   2026-04-01 00:00:00 +0900
categories: projects
image: /assets/images/chromotion.jpg
---

![]({{ page.image }})
<!-- ![](/assets/images/chromotionApp.jpg) -->

#### Title: Chromotion: Controlling Motion-Induced Color on Object Motion Paths via High-Speed Temporal Additive Projection

#### Main Contributor: Shio Miyafuji, Arisa Kohtani

#### Abstract
We present Chromotion, a high-speed projection method that renders intended colors along the motion trajectories of moving objects. When an object moves across a high speed temporally multiplexed
frame sequence, its occlusion of the projected patterns can, through persistence of vision, produce motion dependent colors along its path. Chromotion exploits this phenomenon by decomposing each static image into a short sequence in which target color frames are interleaved with a single complementary color frame. This temporal design allows moving objects to sample the sequence so that the perceived color along their motion paths converges to the target color, while stationary regions still integrate to the original static color. We built a prototype and conducted a camera based technical evaluation together with a user evaluation. The results show that Chromotion reliably produces the target color on motion trajectories without degrading static color fidelity. Because the approach requires no body or gaze tracking and no decoding of embedded information, it scales to public settings and supports multiuser and multimodal interactions. We also discuss limitations, and outline application scenarios such as public, ambient displays that blend into the environment.

***

#### Citarion format
1. Shio Miyafuji, Arisa Kohtani, and Hideki Koike. 2026. Chromotion: Controlling Motion-Induced Color on Object Motion Paths via High-Speed Temporal Additive Projection. In Proceedings of the 2026 CHI Conference on Human Factors in Computing Systems (CHI ’26), April 13–17, 2026, Barcelona, Spain. ACM, New York, NY, USA, 15 pages. [https://doi.org/10.1145/3772318.3791975](https://doi.org/10.1145/3772318.3791975)
