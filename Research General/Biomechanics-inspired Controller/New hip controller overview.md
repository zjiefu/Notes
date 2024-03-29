
The scope of new hip exoskeleton controller: find a way to incorporate biomechanics-inspired basis functions, and integrate the basis into the IDA-PBC framework.
- Biomechanics-inspired basis: [[New hip controller biomechanics]]
	- Solve the problem of hard to find intuitive/physically meaningful basis functions, since they are now biomechanics-inspired
	- Potentially reduce the number of tunable parameters, which allows human-in-the-loop optimization
- IDA-PBC side: [[New hip controller mathematics]]
	- Hopefully extend/refine the requirement of basis functions selection, especially the "integrable". **For this section check the integrable NN papers**
	- Need to think about how to incorporate the "memory" part, i.e., the information of last step
	- Better evaluate the effect of power leak, and potential effects on the system behavior? (Something done by others)


### Some new thoughts

Read a paper on HRI with energy shaping, and it used energy surface idea. Not sure if this is also applicable to our controller. Want to find a simple way to parameterize this energy surface.