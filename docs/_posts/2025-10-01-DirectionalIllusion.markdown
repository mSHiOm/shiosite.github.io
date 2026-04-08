---
layout: post
title:  "Directional-Aware Display"
date:   2025-04-22 00:00:00 +0900
categories: projects
image: /assets/images/chromotion.jpg
---

![]({{ page.image }})
<!-- ![](/assets/images/motionaware.jpg) -->

#### Title: Directionl-Aware Display

#### Main Contributor: Ryusuke Miyazaki

#### Abstract
We present Chromotion, a high-speed projection method that renders intended colors along the motion trajectories of moving objects. When an object moves across a high speed temporally multiplexed
frame sequence, its occlusion of the projected patterns can, through persistence of vision, produce motion dependent colors along its path. Chromotion exploits this phenomenon by decomposing each static image into a short sequence in which target color frames are interleaved with a single complementary color frame. This temporal design allows moving objects to sample the sequence so that the perceived color along their motion paths converges to the target color, while stationary regions still integrate to the original static color. We built a prototype and conducted a camera based technical evaluation together with a user evaluation. The results show that Chromotion reliably produces the target color on motion trajectories without degrading static color fidelity. Because the approach requires no body or gaze tracking and no decoding of embedded information, it scales to public settings and supports multiuser and multimodal interactions. We also discuss limitations, and outline application scenarios such as public, ambient displays that blend into the environment.

***

#### Citarion format

1. (Demo. Best Demo Award.) Ryusuke Miyazaki, Shio Miyafuji, and Hideki Koike. 2025. Be Smart-Phone Zombie!: Guidance Display for Texting While Walking Using Striped Pattern and High-Speed Projection. In Adjunct Proceedings of the 27th International Conference on Mobile Human-Computer Interaction (MobileHCI '25 Adjunct). Association for Computing Machinery, New York, NY, USA, Article 19, 1–5. [https://doi.org/10.1145/3737821.3748531](https://doi.org/10.1145/3737821.3748531) 

2. (Demo) Ryusuke Miyazaki, Shio Miyafuji, Kyeongwan Kim, and Hideki Koike. 2025. A Display Method Visible Only During Gaze Fixation on Moving Objects using High-Speed Projection and Striped Pattern. In Adjunct Proceedings of the 38th Annual ACM Symposium on User Interface Software and Technology (UIST Adjunct '25). Association for Computing Machinery, New York, NY, USA, Article 18, 1–3. [https://doi.org/10.1145/3746058.3759000](https://doi.org/10.1145/3746058.3759000)

3. (Poster) Ryusuke Miyazaki, Shio Miyafuji, and Hideki Koike. 2025. An Experiment on a High-Speed Image Projection Perceived Only During Smooth Pursuit using Striped Patterns. In Proceedings of the 2025 31st ACM Symposium on Virtual Reality Software and Technology (VRST '25). Association for Computing Machinery, New York, NY, USA, Article 118, 1–2. [https://doi.org/10.1145/3756884.3770537](https://doi.org/10.1145/3756884.3770537)
