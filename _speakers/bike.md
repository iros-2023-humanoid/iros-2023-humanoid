---
title: "Bike Zhang"
excerpt: "Learning Humanoid Locomotion via Transformer"
layout: single 
classes: wide
permalink: /bike/

sidebar:
  - title: "Ph.D"
    image: /docs/assets/images/speakers/bike.jpeg
    image_alt: "logo"
    text: "University of California, Berkeley"

toc: false 
collection: speakers
---
Bike Zhang is a PhD student at UC Berkeley, advised by Professor [Koushil Sreenath](https://me.berkeley.edu/people/koushil-sreenath/). His research focuses on the intersection between control theory and machine learning, with the aim of endowing robots with greater agility, safety, and intelligence.


<center style="font-size:30px">
Learning Humanoid Locomotion with Transformers
</center>



##### Abstract
In this talk, I will introduce a sim-to-real learning-based approach for real-world humanoid locomotion. Our controller is a causal Transformer trained by autoregressive prediction of future actions from the history of observations and actions. We hypothesize that the observation-action history contains useful information about the world that a powerful Transformer model can use to adapt its behavior in-context, without updating its weights. This policy is trained with large-scale model-free reinforcement learning on an ensemble of randomized environments in simulation and deployed to the real world in a zero-shot fashion. The learned controller is evaluated in high-fidelity simulation and successfully deployed to a real Digit humanoid robot.



