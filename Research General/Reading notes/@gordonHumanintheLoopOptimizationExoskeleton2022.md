---
Title: Human-in-the-Loop Optimization of Exoskeleton Assistance Via Online Simulation of Metabolic Cost
Authors: Daniel F. N. Gordon, Christopher McGreavy, Andreas Christou, Sethu Vijayakumar
Year: 2022
---
***
### Abstract: 
Many assistive robotic devices have been developed to augment or assist human locomotion. Despite advancements in design and control algorithms, this task remains challenging. Human walking strategies are unique and complex, and assistance strategies based on the dynamics of unassisted locomotion typically offer only modest reductions to the metabolic cost of walking. Recently, human-in-the-loop (HIL) methodologies have been used to identify subject-specific assistive strategies, which offer significant improvements to energy savings. However, current implementations suffer from long measurement times, necessitating the use of low-dimensional control parameterizations, and possibly requiring multiday collection protocols to avoid subject fatigue. We present a HIL methodology, which optimizes the assistive torques provided by a powered hip exoskeleton. Using musculoskeletal modeling, we are able to evaluate simulated metabolic rate online. We applied our methodology to identify assistive torque profiles for seven subjects walking on a treadmill, and found greater reductions to metabolic cost when compared to generic or off-the-shelf controllers. In a secondary investigation, we directly compare simulated and measured metabolic rate for three subjects experiencing a range of assistance levels. The time investment required to identify assistance strategies via our protocol is significantly lower when compared to existing protocols relying on calorimetry. In the future, frameworks such as these could be used to enable shorter HIL protocols or exploit more complex control parameterizations for greater energy savings.
***
### Key takeaways:
1. In this paper, human kinematics data is collected online, fed into a pipeline to Opensim and estimate the metabolic cost, instead of direct measurement of metabolic cost. This reduced the time of each trail (less than 2 mins).

***
### Questions:
1. Is there anyway to utilize existing dataset to do something, i.e., do not need to measure kinematics real-time. 