---
layout: splash
title: "Research Projects"
permalink: /research/
author_profile: true
excerpt: "Selected research and enginnering projects"
intro: 
  - excerpt: ''
feature_row:
  - image_path: '../images/ocams_tag-bicnet-nko.gif'
    alt: "Skyplot"
    title: "Hazard Detection and Avoidance for Autonomous Spacecraft Landing"
    excerpt: ''<br><br>

    Hazard Detection and Avoidance (HD&A) plays a pivotal role in enhancing the flexibility and diversity of mission designs and executions in planetary science and interplanetary development endeavors. HD&A encompasses two principal functionalities (i) hazard detection (HD) and (ii) hazard avoidance guidance, both of which are addressed and enhanced in this research. For the HD algorithm, a novel framework and formulation are introduced, leveraging machine learning and Gaussian random fields for improved efficiency and precision. Regarding hazard avoidance guidance, this research initiates by precisely defining and formulating this emergent challenge, subsequently presenting a set of solution frameworks tailored for this unique perception-aware guidance problem.<br><br>

    **Related Publication:** Bayesian Deep Learning for Segmentation for Autonomous Safe Planetary Landing, *AIAA JSR*, 2022 [[Paper](https://arc.aiaa.org/doi/full/10.2514/1.A35104)]
    
  - image_path: '../images/cislunar-ip.png'
    alt: "Skyplot"
    title: "Multi-Spacecraft Predictive Sensor Tasking for Cislunar Space Situational Awareness"
    excerpt: ''<br><br>

    This paper delves into the predictive sensor tasking algorithm for the multi-observer, multi-target sensor setting, leveraging the Extended Information Filter (EIF). Conventional predictive formulations suffer from the curse of dimensionality due to the dependence of the performance metric on the target-observer assignment history. This paper exploits the EIF's additive structure of measurement information to break the dependence and devises an efficient linear integer programming formulation. We further investigate the resulting formulation to study how the cislunar dynamics expands and shrinks the measurement information, and discuss when the information gain is maximized in relation to the observation space and the uncertainty deformation caused by the dynamics. We numerically demonstrate that the predictive sensor tasking algorithm outperforms the myopic algorithm in two different metrics, depending on the formulation.

    **Related Publication:** Multi-Spacecraft Predictive Sensor Tasking for Cislunar Space Situational Awareness, *AMOS Conference, 2022 [[Paper](https://arxiv.org/abs/2310.04894)]

---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row" type="left" %}