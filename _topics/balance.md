---

layout: single 
classes: wide
entries_layout: grid
author_profile: true 

title: "Balance control on uneven terrain"

excerpt: "
Uneven terrain can unpredictably and shift the robot’s center of mass and instantaneously re-distribute the feet forces. Thus, it is challenging balance while moving, and poor control design can lead to instability or even falls. 
"

---
Walking on uneven terrain can significantly affect a robot's balance, leading to unpredictable shifts in the center of mass and foot forces distribution [1], [2]. To ensure stability and prevent falls, designing effective balance control systems for uneven terrain is critical. Achieving balance control over a prediction horizon requires a combination of accurate modeling, optimization, and real-time implementation.

The current state-of-the-art in balance control design relies on precise state feedback, accurate linearized models, and whole-body coordination. Given the nonlinear and time-varying dynamics of humanoid robots, nonlinear model predictive control (NMPC) and other nonlinear control techniques are necessary to incorporate system constraints.

However, several challenges remain in using NMPC for balance control, including long computation times, sensitivity to weight tuning, robustness, state estimation, and initial solution. These challenges must be addressed to improve the performance of NMPC and other control techniques for balance control on uneven terrain.


[1] S. Samadi, J. Roux, A. Tanguy, S. Caron, and A. Kheddar, “Humanoid control under interchangeable fixed and sliding unilateral contacts,” IEEE Robotics and Automation Letters, vol. 6, no. 2, pp. 4032–4039, 2021.

[2] B. Henze, M. A. Roa, and C. Ott, “Passivity-based whole-body balancing for torque-controlled humanoid robots in multi-contact scenarios,” The International Journal of Robotics Research, vol. 35, no. 12, pp. 1522–1543, 2016.

