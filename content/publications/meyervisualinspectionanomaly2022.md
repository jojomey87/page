---
title: "Visual inspection via anomaly detection by automated uncertainty propagation"
date: 2022-05-01
author_list: "Johannes Meyer, Matthias Hartrumpf, Thomas Längle, Jürgen Beyerer"
venue: "Unconventional Optical Imaging III"
publication_type: "Conference paper"
doi_url: "https://doi.org/10.1117/12.2621146"
draft: false
---

[→ Full text / DOI](https://doi.org/10.1117/12.2621146)

## Abstract

The visual quality inspection of test objects having a complex geometry is a challenging task for automated artificial vision systems. Even for systems where the illumination and image acquisition setups are specifically tailored with respect to the properties of the test object, captured images often show unwanted signal components, e.g., surface reflections, which complicate the detection of present material defects. One way to mitigate this problem is to have an expert define image regions by hand which are excluded from the automated defect detection. Besides being a time-consuming procedure, this also results in the system being blind at the respective regions. Another approach is based on acquiring image value statistics (e.g., mean value and standard deviation) for every pixel of an image series captured from a set of defect-free test objects. This information can then be exploited during the inspection process by comparing image values with respect to the previously calculated statistics. Pixels whose image values lie outside the distribution for the defect-free case might indicate a material defect. Unfortunately, the calculated statistics are invalidated as soon as further preprocessing steps like smoothing or edge detection are applied. The statistics would have to be recalculated by applying the respective preprocessing steps to the images of the defect-free test objects. To resolve this drawback, this contribution presents a novel approach capable of adequately updating the calculated statistics with respect to the chain of required image processing steps. This is achieved by interpreting the statistics as uncertainties and by propagating them through the single processing steps via Gaussian uncertainty propagation. The required gradients are obtained via automated differentiation of the image processing steps. The effectiveness of the proposed approach is demonstrated by means of empirical experiments.
