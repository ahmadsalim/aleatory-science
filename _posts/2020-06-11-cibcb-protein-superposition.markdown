---
title: A Probabilistic Programming Approach to Protein Structure Superposition
subtitle:  Lys Sanz Moreta,  Ahmad Salim Al-Sibahi,  Douglas Theobald, William Bullock, Basile Nicolas Rommes, Andreas Manoukian,  Thomas Hamelryck (CIBCB 2019)
layout: default
modal-id: 2
date: 2020-06-11
img: 2019-cibcb-protein-superposition.pdf
thumbnail: 2019-cibcb-protein-superposition.pdf
alt: CIBCB
project-date: July 2019
description: Optimal superposition of protein structures or other biological molecules is crucial for understanding their structure, function, dynamics and evolution. Here, we investigate the use of probabilistic programming to superimpose protein structures guided by a Bayesian model. Our model THESEUS-PP is based on the THESEUS model, a probabilistic model of protein superposition based on rotation, translation and perturbation of an underlying, latent mean structure. The model was implemented in the probabilistic programming language Pyro. Unlike conventional methods that minimize the sum of the squared distances, THESEUS takes into account correlated atom positions and heteroscedasticity (ie. atom positions can feature different variances). THESEUS performs maximum likelihood estimation using iterative expectation-maximization. In contrast, THESEUS-PP allows automated maximum a-posteriori (MAP) estimation using suitable priors over rotation, translation, variances and latent mean structure. The results indicate that probabilistic programming is a powerful new paradigm for the formulation of Bayesian probabilistic models concerning biomolecular structure. Specifically, we envision the use of the THESEUS-PP model as a suitable error model or likelihood in Bayesian protein structure prediction using deep probabilistic programming.

---
