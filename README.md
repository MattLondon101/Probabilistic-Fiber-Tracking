# Probabalistic-Fiber-Tracking
Probabalistic Fiber Tracking with DIPY (Diffusion Imaging in Python)

Probabilistic fiber tracking follows the trajectory of a possible pathway step by step starting at a seed, however, unlike deterministic tracking, the tracking direction at each point along the path is chosen at random from a distribution. The distribution at each point is different and depends on the observed diffusion data at that point. The distribution of tracking directions at each point can be represented as a probability mass function (PMF) if the possible tracking directions are restricted to discrete numbers of well distributed points on a sphere.

Prob_Fiber_Tracking.ipynb demonstrates this method with DIPY.
