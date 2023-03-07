---

layout: single 
classes: wide
entries_layout: grid
author_profile: true 

title: "Floating-base state estimation"

excerpt: "
By accurately estimating the floating-base state, an MPC controller can generate optimized motion trajectories that are feasible and safe for the robot to execute.
"

---

Humanoid robots are not rigidly attached to the environment, they can move freely in space, making it difficult to determine the precise location and orientations. By accurately estimating the floating-base state, an MPC controller can generate optimized motion trajectories that are feasible and safe for the robot to execute. This is especially important when the robot is subjected to external disturbances, such as contact with the environment or other objects, or when the robot is operating on uneven or unstructured terrain.

Floating-base state estimation remains an open research question for several reasons:

 * Noisy sensory data: The inertial measurement units (IMUs) suffer from significant drifts, and the vision data are blured due to task-purpose impacts, e.g., landing a supporting contact.

 * Nonlinear and coupled dynamics: The dynamics of the base and the limbs of the robot are tightly coupled, which means that errors in the estimation of one component can have a significant impact on the estimation of the others.

Addressing these challenges is critical for improving the accuracy and robustness of floating-base state estimation, and for enabling the development of effective control strategies for robotic systems.

 

