# Apparent Horizon

Horizon finding is a non-trivial problem in numerical relativity. One can distinguish between the event horizon and the apparent horizon. The event horizon is a global property of spacetime, and therefore requires knowledge about the entire spacetime and its evolution in order to find it. The apparent horizon, on the other hand, is a local property and can be evaluated on a single timeslice.

This project aims to develop an algorithm which is able to locate the apparent horizon from a particular metric. Currently its input consists of the ADM 3+1 components: the lapse function alpha, the shift vector beta and the conformal factor psi. The algorithm solves for a scalar function h(theta, phi), the horizon function, which gives the radial distance of the horizon from a certain origin for each direction (theta, phi) on the unit sphere. The horizon function can be found by solving the expansion equation, which is in general a non-linear partial differential equation for h.

# Contents

This GitHub contains the documents that have been developed over the course of the project. The summary of what has been done can be found in the pdf-file "Horizon_finder_project_Summary". This file serves as a guide through the different steps and explains which Jupyter notebooks belong to the different attempts at solving. The Jupyter notebooks can be found in the according folder.

## References

The solving procedure is inspired by the paper by [H. K. Hui, L. M. Lin (2024)](https://arxiv.org/abs/2404.16511).
