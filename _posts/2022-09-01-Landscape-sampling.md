---
layout: "post"
title: "Examining the relationship between sampling strategy, sample density, and interpolation strategy on mapping accuracy"
author: "Ira Parsons"
categories: research
tags: [research, sampling, landscapes]
image: samplingloc.png
---
Obtaining accurate and precise maps of landscape features often requires intensive spatial sampling and interpolation. 
The data required to generate reliable interpolated maps varies with sampling density and landscape heterogeneity. 
However, there has been no rigorous examination of sampling density relative to landscape characteristics and interpolation methods. Our objective was to characterize the 3-way relationship among sampling density, interpolation method, and landscape heterogeneity on interpolation accuracy and precision in simulated and in situ landscapes. We simulated landscapes of variable heterogeneity and sampled at increasing densities using gridded and random strategies. We applied three local interpolation methods (i.e., Inverse Distance Weighting, Universal Kriging, and Nearest Neighbor) to the sampled data and estimated accuracy (slope and intercept) and precision (R2) between interpolated surfaces and the original surface. Finally, we applied these analyses to in situ data using a normalized difference vegetation index raster collected from pasture with various resolutions. In our simulations, all interpolation methods and sampling strategies yielded similar accuracy and precision except in the case of Universal Kriging with random sampling. Additionally, low heterogeneity and increasing sample density improved both accuracy and precision, with cross-validation slopes and R2 values approaching optimal values. In situ analysis demonstrated that heterogeneity decreased with resolution. Nearest Neighbor under both sampling strategies and Universal Kriging using the gridded sampling strategy had the highest accuracy and precision. Decreased heterogeneity and increased sampling density improved accuracy and precision for all combinations of interpolation method and sampling strategies. Heterogeneity of the  landscape is a major influence on the accuracy and precision of interpolated maps. There is a need to create structured tools to aid in determining sampling design most appropriate for interpolation methods across landscapes of various heterogeneity. 

![Sampling locations](assets/img/samplingloc.png)

Reference: [Parsons et al., 2022](https://link.springer.com/10.1007/s10980-022-01523-8)