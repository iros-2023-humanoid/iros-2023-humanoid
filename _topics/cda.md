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

Centroidal dynamics approximation (CDA) is a powerful tool for reducing the dimensionality of the model predictive control (MPC) problem. The classical approach to MPC simplifies the robot's motion by approximating the center of mass (CoM) as a single point. This method, however, overlooks the angular momentum, a critical factor in maintaining balance and stability.

On the other hand, CDA effectively captures the dynamic interactions between the robot's linear motion and its angular momentum [2]. This makes MPC less complex and quicker to solve, providing a significant advantage in real-time control applications where computation time is limited.

The effective implementation of CDA has been demonstrated in the work of R. Schuller et al. [1], who used online centroidal angular momentum reference generation and motion optimization for humanoid push recovery. Moreover, G. Wiedebach et al. [2] have applied CDA in managing walking on partial footholds, including line contacts, with the humanoid robot Atlas.

Our workshop will further exploit the benefits of CDA for the efficient control of legged robots, enhancing their ability to dynamically interact with their environment, maintain balance, and adapt to on-purpose impacts.



[1] R. Schuller, G. Mesesan, J. Englsberger, J. Lee, and C. Ott, “Online centroidal angular momentum reference generation and motion optimization for humanoid push recovery,” IEEE Robotics and Automation Letters, vol. 6, no. 3, pp. 5689–5696, 2021. 

[2] G. Wiedebach, S. Bertrand, T. Wu, L. Fiorio, S. McCrory, R. Griffin, F. Nori, and J. Pratt, “Walking on partial footholds including line contacts with the humanoid robot atlas,” in IEEE-RAS 16th Inter. Conf. on Humanoid Robots, 2016, pp. 1312–1319. 

