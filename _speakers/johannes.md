---
title: "Johannes Englsberger"
excerpt: "Torque-based Dynamic Walking on Compliant and Uneven Terrain"
layout: single 
classes: wide
permalink: /johannes/

sidebar:
  - title: "Dr.-Ing."
    image: /docs/assets/images/speakers/johannes.jpg 
    image_alt: "logo"
    text: "DLR German Aerospace Center
	   Institute of Robotics and Mechatronics"


toc: false 
collection: speakers
---

[Johannes Englsberger](https://rmc.dlr.de/rm/en/staff/johannes.englsberger/) received his Dipl.-Ing. degree (equivalent to Masters) in mechanical engineering from the Technical University of Munich (TUM) in 2009. In 2010, he joined the German Aerospace Center (DLR), Institute of Robotics and Mechatronics, as a research scientist. In 2016, he received the Dr.-Ing. degree (equivalent to PhD) again from TUM. His PhD thesis "Combining reduced dynamics models and whole-body control for agile humanoid locomotion" received the Georges Giralt PhD Award 2017 for the best European thesis in robotics. In 2019, he was appointed team leader of DLR's legged locomotion group. In addition to his scientific career at DLR, he joined team IHMC (Florida Institute of Human and Machine Cognition, USA) as a visiting researcher and successfully participated in the DARPA Robotics Challenge (DRC). 

<center style="font-size:30px">
Centroidal Angular Momentum Approximation and Control for humanoid locomotion
</center>



##### Abstract
Humanoid and other legged locomotion is a challenging task due to its hybrid nature (contacting / non-contacting) and the many robot degrees of freedom (DoF) involved. A common approach is to reduce the dimensionality of the dynamic balancing problem by considering either just the 3D linear center of mass (CoM) dynamics, or the six-dimensional centroidal dynamics. Interestingly, the CoM dynamics is completely linear (Newton’s second law) and thus facilitates fully analytic solutions for multi-step gait previews. If Centroidal Angular Momentum (CAM) is neglected during gait planning, the center of pressure (CoP) is prone to deviate from its nominal position (e.g. in the foot centers), which can cause problems with balance. Therefore, the consideration of CAM in the planning process is very helpful for achieving highly dynamic locomotion, which includes both fast walking and running gaits. While for the CoM dynamics closed-form solutions exist, CAM is non-linear and non-holonomic, such that one has to work with approximations.

In this talk, I will present my group’s progress towards the integration of CAM in our planning and controls framework.

On the one hand side, our framework optimizes the reference motions (e.g. for walking and running) in two different, but complementary ways:

a) By modifying the CoM (or in our case: DCM) trajectories in a way such that gravity helps compensate required angular momentum changes through appropriate contact point offsets, while the CoP tracking is improved. This can be achieved both through offline pre-training / learning of the CAM matrix entries and / or through ILC-like online learning, such that CAM contributions can be approximated and integrated into our DCM-based gait generation framework.

b) By modifying and tracking certain DoF of the whole-body reference trajectories, such that some CAM objective is optimized. This yields smoother and more feasible gaits, and less excessive arm motions. 

On the other hand side, our framework contains reactive replanning and controls components. One example is push recovery – both during walking and stance –, where explicit angular momentum optimization (AMO) can be very helpful.

During my talk, I will also report about toe running of a simulated elastic humanoid robot, the advantages of a non-zero CAM reference, and finally about commonalities and differences between our proposed framework and MPC-based approaches.

 


