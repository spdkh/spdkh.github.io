---
title: "UPIGAN & USR: Physics-Informed Deep Learning for 3D Super-Resolution Microscopy"
excerpt: "An unrolled, physics-informed GAN that bakes the SIM forward model and optical transfer function into the network, outperforming baseline channel-attention GANs on real 3D SIM data."
collection: portfolio
group: mine
order: 5
period: "Aug 2021 – Jul 2023"
role: "Project lead · M.Sc. thesis · led a sub-team of 3"
---

**M.Sc. thesis · Computational Imaging Research Lab (CIRL), University of Memphis · 2021–2023.**
**Role:** Project lead. This was my thesis project; I designed the method and led a sub-team of three, in collaboration with Dr. C. Van. Advisor: Dr. C. Preza.

**UPIGAN** (Unrolled Physics-Informed GAN) reconstructs 3D super-resolved volumes from Structured Illumination Microscopy (SIM) acquisitions. Instead of asking a GAN to learn imaging physics from scratch, I unrolled a few iterations of the SIM inverse problem into the network, so the **optical transfer function (OTF) and SIM illumination model** are differentiable parts of training.

- **Why it matters:** SIM reconstruction is ill-posed and sensitive to noise and pattern mismatch. UPIGAN keeps the physics fixed and lets the network learn data-driven priors on top.
- **Result:** outperformed baseline residual channel-attention GANs (caGAN) on real 3D SIM datasets.
- **Follow-up, USR:** *Unrolled Super-Resolution with Deep Priors*, which carries the same unrolled-optimization idea into a deep-prior formulation.
- **Groundwork:** re-implemented SRN and caGAN variants for SIM reconstruction, and built a MATLAB SIM simulation toolkit for generating training data.

**Stack:** TensorFlow / Keras, OpenCV, MATLAB (OTF and forward-model simulation), physics-guided deep learning, 3D image super-resolution.

**Outputs**
- SPIE Defense + Commercial Sensing 2023: *Image Reconstruction for Structured Illumination Microscopy using an Unrolled GAN* ([doi](https://doi.org/10.1117/12.2663878)).
- OPTICA / Frontiers in Optics 2023: *USR: Unrolled Super-Resolution with Deep Priors for SIM*.
- Gordon Research Conference poster, 2022.
- 2nd place, EECE 8th Annual Poster Competition, 2022.
