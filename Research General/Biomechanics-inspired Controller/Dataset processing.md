
### How to organize the dataset:

- Level1: Data
- Level2: LG, RA, RD, need to add SA and SD
- Level3: angle (hip), velocity (hip), global thigh, GRF, torque
- Level4: left, right sides
- Level5: each side is a 150 x n x 10 array, dim1- gait percentage, dim2 - number of tasks, dim3 - number of subject.

### Current stage
Finished parsing the data for all tasks except STS. Need to do sanity check. Also need to normalize the GRF data of LG, RA, RD