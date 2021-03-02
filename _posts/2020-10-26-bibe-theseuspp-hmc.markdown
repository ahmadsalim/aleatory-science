---
title: Bayesian protein superposition using Hamiltonian Monte Carlo
subtitle: Lys Sanz Moreta, Ahmad Salim Al-Sibahi, Thomas Hamelryck (BIBE 2020)
layout: default
modal-id: 2
date: 2020-10-26
img: 2020-bibe-theseuspp-hmc.pdf
thumbnail: 2020-bibe-theseuspp-hmc.pdf
alt: BIBE
project-date: October 2020
description: Optimally superimposing protein structures is essential to study their structure, function, dynamics and evolution. We present THESEUS NUTS (No U-Turn Sampler), a Bayesian version of the THESEUS model [1] -[3] which relies on maximum likelihood estimation. The probabilistic model interprets each protein as a rotated and translated noisy observation of a latent mean structure. Unlike conventional methods [4], THESEUS takes into account the differences in correlations between the atoms in the structure. This paper extends the previous THESEUS MAP (Maximum A Posteriori) model, [5] to full Bayesian inference by making use of the iterative NUTS [6], a Hamiltonian Monte Carlo method. The model delivers consistent results and is computationally efficient thanks to its implementation in the probabilistic programming language NumpPyro [7], [8] which in turn relies upon JAX [9], a system for high-performance machine learning.

---
