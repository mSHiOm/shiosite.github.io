---
layout: post
title:  "MR Microsurgery Training"
date:   2023-01-30 00:28:00 +0900
categories: projects
image: /assets/images/microsurgery.jpg
---

![]({{ page.image }})

#### Main Contributors: Mikihito Matsuura,Yuka Tashiro

#### Abstract
This paper proposes the basis of a microscopic suture practice support system aimed to reduce the time required for neurosurgeons to practice microscopic gauze suturing. The system detects instruments in real-time from the video of the microscope camera and provides an immediate analysis. After practitioners have completed practicing, they can immediately view their results. We introduce a sequential image dataset in which the surgery phases, as well as the bounding boxes of surgical instruments, are annotated. A YOLO V4 network is fine-tuned with the proposed dataset and achieves an accuracy of approximately 94%. We also propose a tool for a phase estimation after each suturing using a Dynamic Programming based algorithm from the tracking data, which allows us to estimate the phase of the previous practice session with about 83 % accuracy. This is used for an application to detect and provide feedback on points of concern. This proposal augments the practitioners’ acquisition of skills, allowing them to immediately reflect on their most recent practice session, rather than repeating aimlessly.


***

#### Citarion format
1. Yuka Tashiro, Shio Miyafuji, Dong-Hyun Hwang,  Satoshi Kiyofuji, Taichi Kin, Takeo Igarashi, and Hideki Koike. 2023. GAuze-MIcrosuture-FICATION: Gamification in Microsuture training with real-time feedback. (Accepted to Augmented Humans 2023. It will be presented in March 2023.)

1. Yuka Tashiro, Mikihito Matsuura, Dong-Hyun Hwang, Shio Miyafuji, Satoshi Kiyofuji, Taichi Kin, Takeo Igarashi, and Hideki Koike. 2022. Introducing a Concept of Gamification to Microscopic Suturing Training. In Augmented Humans 2022 (AHs 2022). Association for Computing Machinery, New York, NY, USA, 294–297. [https://doi.org/10.1145/3519391.3524026](https://doi.org/10.1145/3519391.3524026)

1. Mikihito Matsuura, Shio Miyafuji, Erwin Wu, Satoshi Kiyofuji, Taichi Kin, Takeo Igarashi, and Hideki Koike. 2021. CV-Based Analysis for Microscopic Gauze Suturing Training. In Augmented Humans Conference 2021 (AHs'21). Association for Computing Machinery, New York, NY, USA, 169–173. [https://doi.org/10.1145/3458709.3458991](https://doi.org/10.1145/3458709.3458991)