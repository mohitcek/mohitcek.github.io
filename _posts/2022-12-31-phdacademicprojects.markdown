---
layout: post
title:  "Projects - JHU"
date:   2022-12-28 15:24:20 -0500
categories: jekyll update
---

# UQpy – Python toolbox 
(Jan 2018 – Present)
- UQpy (Uncertainty Quantification with Python) is a general-purpose Python toolbox for modeling uncertainty in physical and mathematical systems
- Developed modules with various methods for sampling techniques, surrogate modeling and sensitivity analysis
- Sequential learning algorithms based on the surrogate modeling are computationally more efficient for complex models, ran these models on Maryland Advanced Research Computing Center (MARCC) server using UQpy tools
- UQpy provides tools such as Refined Stratified Sampling (RSS), Gradient Enhanced-RSS (GE-RSS) and Adaptive Kriging – Monte Carlo Simulation (AKMCS) for sequential learning algorithm

# Large Scale Boundary Layer Wind Tunnel (BLWT) Experiments 
(Jan 2020 – Present)
- Developed a semi-automated framework to conduct high volume through-put experiments using wind tunnel facility at University of Florida
- Machine learning based framework sequentially guides the experiments by selecting next roughness terrain 
- Framework has been explored with various active learning functions to identify different roughness terrains which generates wind profile with similar second-order properties
- Various learning functions have been applied on large scale experimental model to improve surrogate fit and sensitivity analysis has been done based on Sobol Indices. 

# Adaptive Surrogate Model Construction for Efficient Global Sensitivity Analysis 
(July 2021 – Dec 2022)
- Developing an algorithm to tackle the Sensitivity Analysis in case of computationally expensive models by utilizing the characteristics of surrogates and Sobol Indices
- A proposed active learning function adaptively learns new samples based on complete available data and reduces the uncertainty in Sobol Indices 

# Study on Effects of Imperfections in Ship Grillage Structure using FEM model 
(Dec 2019 – Dec 2020)
- Main aim is to study the behavior of ship grillage in nonlinear region due to different types of imperfections (plate, web and flange imperfections)
- Redundant imperfections can be identified, using adaptive Sensitivity Analysis, and removed to improve the model
- GE-RSS method can reduce the uncertainty(variance) in the ultimate strength or other quantity of interest by adaptively learning samples using gradient estimates

# Gradient Enhanced-Refined Stratified Sampling using Voronoi Stratification 
(Aug 2018 – May 2019)
- Developed an efficient learning algorithm to extend the existing GE-RSS method in case of Voronoi stratification
- The algorithm aims at adaptively generate new samples to reduce the (uncertainty) output variance
- The critical aspect is to approximately compute the gradient at the centroid of each Voronoi cell using surrogate model and use it to identify the contribution of each cell to the output variance

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
