---
title: 'BrainSMASH'
date: 2020-10-06
authors: ['admin']
layout: post
categories: ['Software','Data Analysis']
tags: ['Software','Data Analysis']
---
BrainSMASH is a Python-based framework for quantifying the significance of a brain map’s spatial topography in studies of large-scale brain organization. BrainSMASH was designed to generate synthetic brain maps with spatial autocorrelation (SA) matched to the SA of a target brain map. 

SA is a prominent and ubiquitous property of brain maps that violates the assumptions of independence/exchangeability that underlie many conventional statistical tests. Controlling for this property is therefore necessary to disambiguate meaningful topographic relationships from chance associations. To this end, BrainSMASH instantiates a generative null model for simulating surrogate brain maps, constrained by empirical data, that preserve the SA of cortical (surface-based), subcortical (volumetric), parcellated, and dense brain maps.

BrainSMASH requires only two inputs: a brain map of interest, and a matrix of pairwise distances between elements of the brain map. How these inputs are derived is left to user discretion, though additional support has been provided for investigators working with HCP-compliant neuroimaging files. Specifically, BrainSMASH includes routines to generate two-dimensional Euclidean and geodesic distance matrices from surface geometry (GIFTI) files, and subcortical Euclidean distance matrices from CIFTI-format neuroimaging files.

Detailed documentation for BrainSMASH can be found at https://brainsmash.readthedocs.io/.
## Project Author(s)
Joshua B. Burt; Markus Helmer; Maxwell Shinn; Alan Anticevic; John D. Murray
## Project Links
https://github.com/murraylab/brainsmash
***
This post was automatically generated by
Joshua B. Burt
***