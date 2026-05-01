---
title: "Image Reconstruction for Structured Illumination Microscopy using an Unrolled GAN"
collection: publications
permalink: /publication/2023-05-image-reconstruction-sim-unrolled-gan
excerpt: "We unroll the SIM forward imaging model into the layers of a generative adversarial network, so the network learns to invert known optical physics rather than re-discover it. The result: sharper 3D reconstructions on real SIM datasets compared with baseline channel-attention GANs."
date: 2023-05-01
venue: "SPIE Defense + Commercial Sensing, Orlando, FL"
paperurl: "https://doi.org/10.1117/12.2663878"
citation: "<b>S. P. Dajkhosh</b>, M. Hossain, C. Preza. (2023). \"Image Reconstruction for Structured Illumination Microscopy using an Unrolled GAN.\" <i>Proc. SPIE Defense + Commercial Sensing</i>, Orlando, FL."
---

Structured Illumination Microscopy (SIM) reconstructs super-resolved images by combining several patterned-illumination acquisitions, but the inversion is ill-posed and sensitive to noise and illumination model mismatch. We propose an **unrolled GAN** for SIM reconstruction: we take the SIM forward model, illumination patterns, the optical transfer function, and detector response, and unroll a small number of optimization iterations into the layers of a generative adversarial network. The network's job is no longer to learn the physics from scratch, but to *steer* a known physical inversion using learned image priors.

Highlights:

- **Physics-in-the-loop:** the OTF and pattern model parameters are differentiable parts of the network, not a black box.
- **Better-conditioned training:** unrolled iterations regularize the GAN and reduce hallucinated content.
- **Validated on real SIM datasets** with both simulated ground truth and experimental acquisitions.

Presented at the **SPIE Conference**, Orlando, FL, May 2023.

Recommended citation: **S. P. Dajkhosh**, M. Hossain, C. Preza. (2023). "Image Reconstruction for Structured Illumination Microscopy using an Unrolled GAN." *SPIE Conference Proceedings*, Orlando, FL.
