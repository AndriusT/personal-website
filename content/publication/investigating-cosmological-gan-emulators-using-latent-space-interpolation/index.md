---
title: Investigating Cosmological GAN Emulators Using Latent Space Interpolation
publication_types:
  - "2"
authors:
  - Andrius Tamosiunas
  - Hans A. Winther
  - Kazuya Koyama
  - David J. Bacon
  - Robert C. Nichol
  - Ben Mawdsley
doi: 10.1093/mnras/stab1879
publication: In MNRAS
abstract: Generative adversarial networks (GANs) have been recently applied as a
  novel emulation technique for large scale structure simulations. Recent
  results show that GANs can be used as a fast, efficient and computationally
  cheap emulator for producing novel weak lensing convergence maps as well as
  cosmic web data in 2-D and 3-D. However, like any algorithm, the GAN approach
  comes with a set of limitations, such as an unstable training procedure and
  the inherent randomness of the produced outputs. In this work we employ a
  number of techniques commonly used in the machine learning literature to
  address the mentioned limitations. In particular, we train a GAN to produce
  both weak lensing convergence maps and dark matter overdensity field data for
  multiple redshifts, cosmological parameters and modified gravity models. In
  addition, we train a GAN using the newest Illustris data to emulate dark
  matter, gas and internal energy distribution data simultaneously. Finally, we
  apply the technique of latent space interpolation to control which outputs the
  algorithm produces. Our results indicate a 1-20% difference between the power
  spectra of the GAN-produced and the training data samples depending on the
  dataset used and whether Gaussian smoothing was applied. Finally, recent
  research on generative models suggests that such algorithms can be treated as
  mappings from a lower-dimensional input (latent) space to a higher dimensional
  (data) manifold. We explore such a theoretical description as a tool for
  better understanding the latent space interpolation procedure
draft: false
featured: true
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-08-09T22:25:35.047Z
---
