---
title: "Image Reconstruction for Structured Illumination Microscopy Using an Unrolled GAN"
collection: publications
permalink: /publication/2023-05-01-spie2023-unrolled-gan
published: false
excerpt: 'UPIGAN: an unrolled, physics-informed generative adversarial network for 3D SIM reconstruction that embeds the optical transfer function and SIM forward model directly into the network architecture.'
date: 2023-05-01
venue: 'SPIE Defense + Commercial Sensing, Orlando, FL'
paperurl: 'https://doi.org/10.1117/12.2663878'
citation: 'Dajkhosh, S. P., Hossain, M., &amp; Preza, C. (2023). &quot;Image Reconstruction for Structured Illumination Microscopy Using an Unrolled GAN.&quot; <i>Proc. SPIE Defense + Commercial Sensing</i>, Orlando, FL.'
---

We introduce UPIGAN (Unrolled Physics-Informed GAN), a generative adversarial network for 3D image reconstruction in Structured Illumination Microscopy (SIM). Unlike purely data-driven approaches, UPIGAN bakes the SIM forward model and optical transfer function (OTF) directly into an unrolled network architecture, enabling the generator to learn the inverse of known optics rather than re-discovering physical priors from data alone. The unrolled design yields an interpretable, physics-constrained reconstruction pipeline. Evaluated on real 3D SIM datasets, UPIGAN produces higher-fidelity reconstructions than baseline channel-attention GAN variants, with better preservation of fine structural detail and reduced reconstruction artifacts.
