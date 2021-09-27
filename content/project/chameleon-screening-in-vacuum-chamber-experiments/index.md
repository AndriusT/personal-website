---
title: Chameleon Screening in Vacuum Chamber Experiments
date: 2021-09-18T22:25:48.222Z
draft: false
featured: true
tags:
  - Modified Gravity
categories:
  - Modified Gravity
external_link: https://andrius-tamosiunas.netlify.app/project/chameleon-screening-in-vacuum-chamber-experiments/
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
One of the most baffling facts about the Universe is that its composition is dominated by the non-baryonic matter and energy. Namely, dark energy and dark matter constitute around 68 and 26 percent of the total mass-energy budget ([Planck Collaboration, 2018](https://arxiv.org/abs/1807.06209)). And despite the endless stream of data coming from current cosmological surveys, measuring properties of dark energy and dark matter, the nature of the elusive components of the Universe remains as deep as ever. When it comes to dark energy, the following branches of solutions seem to dominate the landscape of theories: 

* The accelerated expansion is due to intrinsic property of space-time vacuum that is accounted by an additional term in Einstein field equations known as the cosmological constant;
* The Universe expands due to a new form of energy that can be described, for instance, as a dynamical scalar field (e.g. Quintessence);
* The Universe accelerates due to certain properties of gravity, which are not reflected or misunderstood in our currently best theory of gravity, General Relativity (GR). 

The list above is by no means exhaustive -- there are dozens of possible explanations for the observed accelerated expansion of the Universe. Nonetheless, they generally consist of either introducing a new form of energy to the mass-energy budget of the Universe or modifying the known laws of gravity. My work primarily consists of studying various modifications of GR and developing tests to constrain these different theories. This short overview introduces some of the theories that I study and briefly lays out some of the ways how these models could be tested.

There exists a large family of modified gravity theories, each with different phenomenology and predictions. However, the majority of models are also well-constrained or straight up ruled out by the currently available observational constraints. A prime example of the importance of observational constraints in the theoretical model building is the GW170817 event. GW170817 refers to the  binary neutron star merger detected by LIGO in August, 2017. For the first time astronomers were able to detect both the gravitational wave signal of the merger along with the electromagnetic counterpart. Such a measurement is of great significance as it allows us to measure the speed of gravitational waves and different theories of gravity predict different speeds of gravitational waves. With the tight constraints on gravitational waves, dozens of modified gravity theories were ruled out overnight. Combing this with the other observational constraint, such as those from the solar system observations leads to a landscape of theories that are tightly constrained. In other words, any new theory has to abide by the stringent gravitational wave speed constraints, while also not deviating from the GR predictions in the solar system. In addition, any phenomenologically interesting theory must also satisfy a plethora of cosmological constraints, ranging from the cosmic microwave background (CMB) measurements to the history of structure formation constraints. This makes building new theories that deviate from GR in any significant way extremelly difficult. 

An important class of modified gravity models in the context described above, is scalar-tensor gravity that possesses a screening mechanism. Specifically, this refers to a model with an scalar field introduced. The potential is then chosen such that modified gravity effects do no manifest in high density regions such as the solar system. This can be done by a number of different mechanisms, but the one we focus one here is the so called chameleon mechanism. In the chameleon mechanism the potential is chosen such that the effective mass of the field grows in the vicinity of high density regions leading to the fifth force being supressed. 

Modified gravity theories such as the chameleon are described by non-linear equations of motion, which generally cannot be solved analytically for arbitrary density distributions. In this project we tackle this problem by employing a numerical technique known as the finite element method (FEM). This powerful approach allows us to model modified gravity effects in a variety of contexts. For instance, the equations can be solved numerically to model vacuum chamber experiments that look for evidence of a chameleon fifth force. Similarly, complicated modified gravity effects in astrophysical systems, such as cosmic voids and galaxy clusters, can also be modelled. The produced numerical results can then act as a powerful tool for designing future experimental and observational searches for modified gravity.

Chameleon gravity can be described by the following action:

$$S = \int \mathrm{d}x^{4}\sqrt{-g}\bigg(\frac{M\_{Pl}^{2}}{2} R - \frac{1}{2} \phi^{,\mu} \phi\_{,\mu} - V(\phi) - \frac{\mathcal{L}\_{m}\left(\varphi\_{m,}  \tilde{g}\_{\mu \nu}\right)}{\sqrt{-g}} \bigg),$$

with $\phi$ as the scalar field, $\mathcal{L}_{m}$ as the matter Lagrangian and $V(\phi)$ as the potential. Varying the outlined action w.r.t. the scalar field $\phi$, we obtain the equation of motion:

$$
\square \phi=V\_{, \phi}- \frac{\beta}{M\_{Pl}} T\_{\mu \nu} \tilde{g}^{\mu \nu}.
$$

Here we used the definition of the energy momentum tensor: 

$$T_{\mu \nu}=\frac{2}{\sqrt{-\tilde{g}}} \frac{\partial \mathcal{L}_{m}}{\partial \tilde{g}^{\mu \nu}}.$$

A typical potential choice in this model is the following:

$$
V(\phi)=\Lambda^{4}\left(1+\frac{\Lambda^{n}}{\phi^{n}}\right),
$$

with $\Lambda$ as the energy scale often set to the dark energy scale (2.4 meV) and $n$ as some integer. In addition, if we assume that the field does not vary in time and use the fact that $T_{\mu \nu} \tilde{g}^{\mu \nu} \approx-\rho$, the equation of motion can be simplified to: 

$$
\nabla^{2} \phi=-\frac{n \Lambda^{n+4}}{\phi^{n+1}}+\frac{\beta \rho}{M\_{Pl}}.
$$

Our goal is to solve this equation for different density $\rho$ distributions. For most complex density distributions this is not possible to do analytically. 

 




