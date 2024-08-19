# LiFCal.github.io
We propose LiFCal, a novel geometric online calibration pipeline for MLA-based light field cameras.
LiFCal accurately determines model parameters from a moving camera sequence without precise calibration targets, integrating arbitrary metric scaling constraints. It optimizes intrinsic parameters of the light field camera model, the 3D coordinates of a sparse set of scene points and camera poses in a single bundle adjustment defined directly on micro image points.

We show that LiFCal can reliably and repeatably calibrate a focused plenoptic camera using different input sequences, providing intrinsic camera parameters extremely close to state-of-the-art methods, while offering two main advantages: it can be applied in a target-free scene, and it is implemented online in a complete and continuous pipeline.

Furthermore, we demonstrate the quality of the obtained camera parameters in downstream tasks like depth estimation and SLAM.
