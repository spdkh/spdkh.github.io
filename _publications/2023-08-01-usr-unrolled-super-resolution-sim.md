---
title: "USR: Unrolled Super-Resolution with Deep Priors for Structured Illumination Microscopy"
collection: publications
permalink: /publication/2023-08-usr-unrolled-super-resolution-sim
excerpt: "USR (Unrolled Super-Resolution) plugs deep image priors into the SIM inversion via algorithm unrolling, combining the data fidelity guarantees of model-based reconstruction with the expressive priors of modern deep networks."
date: 2023-08-01
venue: "OPTICA / Frontiers in Optics, Boston, MA"
citation: "<b>S. P. Dajkhosh</b>, M. Hossain, C. Preza. (2023). \"USR: Unrolled Super-Resolution with Deep Priors for Structured Illumination Microscopy.\" <i>OPTICA</i>, Boston, MA."
---

A natural extension of our unrolled-GAN approach to SIM: **USR** (Unrolled Super-Resolution) replaces the GAN component with explicit *deep image priors* learned from clean microscopy data. The unrolled iterations give us a clean separation between

- a **data-consistency step** that uses the SIM forward model and the OTF directly, and
- a **prior step** in which a learned denoiser refines the current iterate.

This decoupling makes the model easier to train, easier to debug, and more robust to mismatched illumination patterns than end-to-end black-box networks.

Presented at **OPTICA / Frontiers in Optics**, Boston, MA, August 2023.

Recommended citation: **S. P. Dajkhosh**, M. Hossain, C. Preza. (2023). "USR: Unrolled Super-Resolution with Deep Priors for Structured Illumination Microscopy." *OPTICA*, Boston, MA.
