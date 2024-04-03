### Is it possible to distinguish the non-ascent/ascent tasks for hip using heel strike?

- For knee, this is possible, since from knee to ankle, it is rigid (and the distance doesn't change). This ensures the incline slope is the only variable that affects ankle joint center.

- For hip, this will be hard, since from hip to ankle there is still knee, so one can't tell whether it is ascending or non-ascending.
- Using knee joint center is also impossible, since KJC is also affected by the ankle angle.

- To conclude, this makes using GRF less meaningful, which is good since we want to get rid of GRF (also not passive)

### Why I want to find a new controller design

1. ~~For publication.~~
2. Want to find more intuitive controller design method (or basis functions)
	1. Is being intuitive meaningful? (yes, but no logical relationship between 2 and 3. Complicated things might be hard for HILO, but still possible for RL)
	2. In this case, we will need to have some types of simulation to reduce the time needed for online tuning.
3. Want to reduce the number of tunable parameters, so we can do HILO or RL things