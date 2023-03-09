---

layout: single 
classes: wide
entries_layout: grid
author_profile: true 

title: "Whole-body model predictive control"

excerpt: "
Whole-body Model Predictive Control (MPC) can  enable humanoid robots to perform complex, dynamic tasks such as walking, running, jumping, and manipulation. This is achieved by generating optimized motion trajectories that satisfy various constraints such as joint limits, torque limits, and contact stability.
"

---

Whole-body Model Predictive Control (MPC) can  enable humanoid robots to perform complex, dynamic tasks such as walking, running, jumping, and manipulation. This is achieved by generating optimized motion trajectories that satisfy various constraints such as joint limits, torque limits, and contact stability.

Recent research on MPC, such as [1,2], have focused on forward dynamics as they can be efficiently solved through differential dynamic programming. While optimal control using inverse dynamics provides numerical advantages such as coarse optimization, cheaper computation of derivatives, and a high convergence rate, implementing MPC with inverse dynamics presents new challenges. Our invited speakers will discuss these challenges and share their approaches to address them, including novel optimization problem formulation and exploiting the sparsity pattern to efficiently handle a large number of equality constraints.


[1] M. Neunert, M. Stäuble, M. Giftthaler, C. D. Bellicoso, J. Carius, C. Gehring, M. Hutter, and J. Buchli, “Whole-body nonlinear model predictive control through contacts for quadrupeds,” IEEE Robotics and Automation Letters, vol. 3, no. 3, pp. 1458–1465, 2018.

[2] C. Mastalli, W. Merkt, G. Xin, J. Shim, M. Mistry, I. Havoutis, and S. Vijayakumar, “Agile maneuvers in legged robots: a predictive control approach,” arXiv preprint arXiv:2203.07554, 2022.
