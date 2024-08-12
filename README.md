# ApparentHorizon

Horizon finding is a non-trivial problem in numerical relativity. One can distinguish between the event horizon and the apparent horizon. The event horizon is a global property of spacetime, and therefore requires knowledge about the entire spacetime and its evolution in order to find it. The apparent horizon, on the other hand, is a local property and can be evaluated on a single timeslice.

This project aims to develop an algorithm which is able to locate the apparent horizon from a particular metric. Currently its input consists of the ADM 3+1 components: the lapse function alpha, the shift vector beta and the conformal factor psi. The algorithm solves for a scalar function h(theta, phi), the horizon function, which gives the radial distance of the horizon from a certain origin for each direction (theta, phi) on the unit sphere. The horizon function can be found by solving the expansion equation, which is in general a non-linear partial differential equation for h.

## References

The solving procedure is provided by the paper by [H. K. Hui, L. M. Lin (2024)](arXiv:2404.16511v1).
