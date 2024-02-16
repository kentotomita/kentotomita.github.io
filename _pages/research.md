---
layout: splash
title: "Research Projects"
permalink: /research/
author_profile: true
excerpt: "List of research projects"
intro: 
  - excerpt: ''
feature_row:
  - image_path: '../images/cislunar-ip.png'
    alt: "Skyplot"
    title: "Multi-Spacecraft Predictive Sensor Tasking for Cislunar Space Situational Awareness"
    excerpt: ''

    This paper delves into the predictive sensor tasking algorithm for the multi-observer, multi-target sensor setting, leveraging the Extended Information Filter (EIF). Conventional predictive formulations suffer from the curse of dimensionality due to the dependence of the performance metric on the target-observer assignment history. This paper exploits the EIF's additive structure of measurement information to break the dependence and devises an efficient linear integer programming formulation. We further investigate the resulting formulation to study how the cislunar dynamics expands and shrinks the measurement information, and discuss when the information gain is maximized in relation to the observation space and the uncertainty deformation caused by the dynamics. We numerically demonstrate that the predictive sensor tasking algorithm outperforms the myopic algorithm in two different metrics, depending on the formulation.
    
    url: /research/cislunar_ip/
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row" type="left" %}