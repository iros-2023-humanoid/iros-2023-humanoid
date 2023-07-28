---

layout: single 
classes: wide
entries_layout: grid
author_profile: true 

title: "Centroidal dynamics approximation"

excerpt: "
Centroidal dynamics approximation can significantly reduce the complexity of the model predictive control, enabling efficient computations for real-time predictive control.
"

---

Centroidal dynamics approximation (CDA) offers a solution to reduce the dimensionality of the model predictive control (MPC) problem. The classical approach approximates the motion of the robot’s center of mass (CoM) as a single point, which ignores the angular momemtum. CDA makes MPC easier and faster to solve. This can be particularly important for real-time control applications, where computation time is limited. However, CDA models, such as those in [4], capture the dynamic interactions between the robot’s linear motion and its angular momentum, which are critical for maintaining balance and stability [5]. By making MPC easier and faster to solve, CDA is particularly important for real-time control applications where computation time is limited.




[1] R. Schuller, G. Mesesan, J. Englsberger, J. Lee, and C. Ott, “Online centroidal angular momentum reference generation and motion optimization for humanoid push recovery,” IEEE Robotics and Automation Letters, vol. 6, no. 3, pp. 5689–5696, 2021. 

[2] G. Wiedebach, S. Bertrand, T. Wu, L. Fiorio, S. McCrory, R. Griffin, F. Nori, and J. Pratt, “Walking on partial footholds including line contacts with the humanoid robot atlas,” in IEEE-RAS 16th Inter. Conf. on Humanoid Robots, 2016, pp. 1312–1319. 

