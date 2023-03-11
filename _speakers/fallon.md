---
title: "Maurice Fallon"
excerpt: "Sensor fusion based legged robot perception, state estimation and exoskeleton navigation"
layout: single 
classes: wide

sidebar:
  - title: "Associate Professor"
    image: /docs/assets/images/speakers/fallon.jpg 
    image_alt: "logo"
    text: "[Oxford Robotics Institute](https://ori.ox.ac.uk/)"

toc: false 
collection: speakers
---


[Maurice Fallon](https://ori.ox.ac.uk/people/maurice-fallon/) (IEEE, Senior Member) is an Associate Professor in Engineering Science and a Royal Society University Research Fellow. He is also a Research Fellow of Wolfson College. He leads the [Dynamic Robot Systems Group](https://ori.ox.ac.uk/labs/drs/). You will find more information about his research on the DRS website.

He is the principal investigator on 3 large collaborative projects [ORCA](https://ori.ox.ac.uk/projects/orca-research-hub/), [MEMMO](https://ori.ox.ac.uk/projects/memmo-memory-of-motion/), [THING](https://ori.ox.ac.uk/projects/thing-eu-project/) and co-I on [RAIN](https://ori.ox.ac.uk/projects/rain-research-hub/).

His research is focused on probabilistic methods for localization and mapping. He has also made research contributions to state estimation for legged robots and is interested in dynamic motion planning and control. Of particular concern is developing methods which are robust in the most challenging situations by leveraging sensor fusion.


<center style="font-size:30px">
Sensor fusion based legged robot perception, state estimation and exoskeleton navigation
</center>



##### Abstract


Most legged robots are equipped with a high-frequency (>250 Hz) proprioceptive state estimator for control and local mapping purposes. These are typically implemented as nonlinear filters fusing high-frequency signals, such as kinematics and inertial measurement unit (IMU). In ideal conditions (i.e., high friction, rigid terrain, slow speeds), these estimators have a limited (yet unavoidable) drift that is acceptable for local mapping and control.

 

However, deformable terrain, leg flexibility, and foot slippage can degrade estimation performance up to the point where local terrain reconstruction is unusable and multistep trajectories cannot be executed, even over short ranges. This problem is more evident when a robot is moving dynamically and can be the limiting factor when crossing rough terrain. This estimate is also affected by modelling errors, such as inaccurate leg lengths or nonzero contact point size. In our work, we aim to fuse all four sensor modalities (IMU, kinematics, lidar, and camera) in a tightly coupled fashion, with particular focus on the proper integration of leg kinematics in presence of non-ideal contacts, when slippage or terrain deformation occurs.
 

