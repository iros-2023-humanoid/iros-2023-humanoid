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
Uneven terrain can unpredictably and shift the robot’s center of mass and instantaneously re-distribute the feet forces [1], [2]. Thus, it is challenging balance while moving, and poor control design can lead to instability or even falls. To achieve balance control over a prediction horizon, an effective combination of approximate model development, optimization, and efficient real-time computation implementation is required.

The state-of-the-art balance control design relies on accurate state feedback, precise linearized models, and whole-body coordination. Due to the nonlinear and time-varying dynamics of humanoid robots, balance control design relies on nonlinear model predictive control (NMPC) and nonlinear control methods, which can incorporate system constraints. 

However, several issues remain with NMPC, such as computation time, robustness, weight tuning, state estimation, and initial solution. These issues must be addressed to optimize the performance of NMPC in balance control.



[1] S. Samadi, J. Roux, A. Tanguy, S. Caron, and A. Kheddar, “Humanoid control under interchangeable fixed and sliding unilateral contacts,” IEEE Robotics and Automation Letters, vol. 6, no. 2, pp. 4032–4039, 2021.

[2] B. Henze, M. A. Roa, and C. Ott, “Passivity-based whole-body balancing for torque-controlled humanoid robots in multi-contact scenarios,” The International Journal of Robotics Research, vol. 35, no. 12, pp. 1522–1543, 2016.

