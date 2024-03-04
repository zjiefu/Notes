---
Title: Stabilization of a class of underactuated mechanical systems via interconnection and damping assignment
Authors: R. Ortega, M.W. Spong, F. Gomez-Estern, G. Blankenstein
Year: 2002
---
***
### Abstract: 
In this paper, we consider the application of a new formulation of passivity-based control (PBC), known as interconnection and damping (IDA) assignment to the problem of stabilization of underactuated mechanical systems, which requires the modification of both the potential and the kinetic energies. Our main contribution is the characterization of a class of systems for which IDA-PBC yields a smooth asymptotically stabilizing controller with a guaranteed domain of attraction. The class is given in terms of solvability of certain partial differential equations. One important feature of IDA-PBC, stemming from its Hamiltonian (as opposed to the more classical Lagrangian) formulation, is that it provides new degrees of freedom for the solution of these equations. Using this additional freedom, we are able to show that the method of “controlled Lagrangians”—in its original formulation—may be viewed as a special case of our approach. As illustrations we design asymptotically stabilizing IDA-PBCs for the classical ball and beam system and a novel inertia wheel pendulum. For the former, we prove that for all initial conditions (except a set of zero measure) we drive the beam to the right orientation. Also, we define a domain of attraction for the zero equilibrium that ensures that the ball remains within the bar. For the inertia wheel, we prove that it is possible to swing up and balance the pendulum without switching between separately derived swing up and balance controllers and without measurement of velocities.
***
### Key takeaways:


***
### Reading Notes:
1. 2C energy shaping: "While the first row of the aforementioned equations is clearly satisfied" $\nabla_p H = M^{-1}M_d \nabla_p H_d = M^{-1} M_d M_d^{-1} p = M^{-1}p = \nabla_p H$  
2. In our paper, our control law is $u_{es} = (G^TG)^{-1}G^T [\nabla_q V - \nabla_q V_d + J_2(q)M^{-1}p] = (G^TG)^{-1}G^T [\nabla_q V - \nabla_q V_d + J_2(q)\dot{q}]$  So basically we just designed the $J_2(q)$ matrix in the form of all our sinusoidal basis. That's why we directly multiply them by $\dot{q}$.