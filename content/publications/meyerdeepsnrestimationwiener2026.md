---
title: "Deep SNR-estimation for Wiener filter-based non-blind image deconvolution"
date: 2026-05-01
author_list: "Johannes Meyer, Lukas Dippon, Christian Kludt, Chia-Wei Chen et al."
venue: "Signal, Image and Video Processing"
publication_type: "Journal article"
doi_url: "https://doi.org/10.1007/s11760-026-05360-z"
draft: false
---

[→ Full text / DOI](https://doi.org/10.1007/s11760-026-05360-z)

## Abstract

Abstract We introduce a data-driven approach for enhancing Wiener filter-based non-blind image deconvolution by accurately estimating the spatial frequency-dependent signal-to-noise ratio (SNR) from a single degraded observation. Our method leverages a U-Net architecture trained on synthetic data with diverse point spread functions (PSFs) and noise levels to predict SNR maps, which are subsequently integrated into the classical Wiener filtering pipeline. Unlike heuristic SNR assumptions, our learned estimator adapts to varying degradations and noise conditions, enabling substantial improvements in peak signal-to-noise ratio (PSNR) and structural similarity (SSIM) compared to existing state-of-the-art deconvolution methods such as DWDN+. Experiments on the Sun benchmark dataset, challenging coded aperture kernels, and real captured images demonstrate that our method yields high-quality reconstructions with minimal artifacts while maintaining low computational cost, achieving a fivefold speedup over DWDN+. This work bridges classical filtering and modern deep learning, offering a simple, lightweight, and effective solution for real-time image restoration in computational imaging systems.
