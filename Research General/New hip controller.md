- **Overall goal:** We want to find more intuitive way to design the controller, instead of just using randomly chosen basis functions.
- **Different approaches:** 
	- Using model identification tools like SINDy.
	- Incorporating biomechanics knowledges.
	- Using hierarchy way to choose and design basis functions (are we still looking for tri-functions?) 
- **Fundamental Question:** Is it possible to design biomimetic controller using only kinematics data, i.e., how important is the unmeasurable part of human proprioception in locomotion control?
- Now think about **the functions of hip** during locomotion: [[@pandyMuscleJointFunction2010]]
	- During stance: Body weight support, needs gravity compensation. This part is more like a spring, or nonlinear spring.
	- During stance (non-static): injecting positive energy for acceleration or upward motion. Can still use spring here, but may need some pure energy injection. Also, want to have something velocity-sensitive.
	- During swing: move leg forward to initial the next gait cycle. A spring should be enough, but also want to have something velocity-sensitive.
- Hip function during a gait cycle [@MuscleActivityGait]
	- ![[Pasted image 20240206164621.png]]
	- ![[Pasted image 20240206164653.png]]
	- ![[Pasted image 20240206164714.png]]
	- ![[Pasted image 20240206164732.png]]
	- ![[Pasted image 20240206164750.png]]
	- ![[Pasted image 20240206164805.png]]
	- ![[Pasted image 20240206164818.png]]
	- ![[Pasted image 20240206164832.png]]

### Two major things to do
1. Need to link the controller design to the biomechanics of human gait
2. Need to dive into energy shaping theories to fit the controller design to the theory frame

### Components of the controller
1. Need to have a gravity compensation components
	1. During stance, this should be for the body
	2. During swing, this should be for the leg, although I doubt if it is that important for able-bodied. Definitely useful for those who with weak hip flexor.
2. Need to have some sort of nonlinear spring. This is because hip extensor/flexor need to do both positive/negative work during a gait cycle
3. Need to have some velocity sensitive components. This is because the torque at hip changes with different velocities.
4. Need to incorporate GRF into the whole frame. Can use the sigmoid function style, but can also explore other ideas.
5. I am not sure about this part, but maybe have some kind of switching for ascending tasks.