---
Title: Dynamic movement primitives in robotics A tutorial survey - Matteo Saveriano, Fares J Abu-Dakka, Aljaž Kramberger, Luka Peternel, 2023
Authors: 
Year:
---
***
### Abstract: 

Biological systems, including human beings, have the innate ability to perform complex tasks in a versatile and agile manner. Researchers in sensorimotor control have aimed to comprehend and formally define this innate characteristic. The idea, supported by several experimental findings, that biological systems are able to combine and adapt basic units of motion into complex tasks finally leads to the formulation of the motor primitives’theory. In this respect, Dynamic Movement Primitives (DMPs) represent an elegant mathematical formulation of the motor primitives as stable dynamical systems and are well suited to generate motor commands for artificial systems like robots. In the last decades, DMPs have inspired researchers in different robotic fields including imitation and reinforcement learning, optimal control, physical interaction, and human–robot co-working, resulting in a considerable amount of published papers. The goal of this tutorial survey is two-fold. On one side, we present the existing DMP formulations in rigorous mathematical terms and discuss the advantages and limitations of each approach as well as practical implementation details. In the tutorial vein, we also search for existing implementations of presented approaches and release several others. On the other side, we provide a systematic and comprehensive review of existing literature and categorize state-of-the-art work on DMP. The paper concludes with a discussion on the limitations of DMPs and an outline of possible research directions.
***
### Reading notes:

#### 2.1.1 Classical DMP
Three equations (1)-(3). $\alpha_z, \beta_z$ terms are determined. $f(x)$ is the forced term to be learned. (3) is a phase dynamics (still not sure why need it)

##### 2.1.1.1 Learning the forcing term
Regression problem, finding the weights that minimize the error.







---
### Key takeaways:
