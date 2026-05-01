---
title: "UPIGAN, Unrolled Physics-Informed GAN for 3D Microscopy"
excerpt: "An unrolled GAN that bakes the SIM forward model and OTF directly into the network, producing higher-fidelity 3D super-resolution than baseline channel-attention GANs.<br/><img src='/images/auto-ball.jpg'>"
collection: portfolio
---

**Master's thesis · University of Memphis CIRL · 2021–2023.**

UPIGAN (Unrolled Physics-Informed GAN) reconstructs 3D super-resolved volumes from Structured Illumination Microscopy (SIM) acquisitions. Instead of asking a GAN to learn imaging physics from scratch, I unrolled a small number of optimization iterations of the SIM inverse problem into the network, making the **optical transfer function and SIM pattern model** differentiable parts of training.

**Why it matters.** SIM reconstruction is ill-posed and sensitive to noise / pattern mismatch. UPIGAN makes the physics non-negotiable while letting the network learn data-driven priors on top.

**Stack:** PyTorch, Keras, NumPy, MATLAB (for OTF and forward-model simulation), real SIM datasets from CIRL.

Presented at SPIE 2023 (Orlando), Frontiers in Optics / OPTICA 2023 (Boston), Gordon Research Conference 2022 (Maine), and the ECE 8th Annual Poster Competition (2nd place).
