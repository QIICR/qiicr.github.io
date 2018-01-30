---
layout: page
title: "DWModeling: DWI MRI modeling"
teaser: "3D Slicer extension for diffusion MRI modeling"
comments: true
header:
  image_fullwidth: beacon.jpg
categories:
  - tool
---

# About

_DWModeling_ is module within the _SlicerProstate_ extension of 3D Slicer that implements fitting of various models to Diffusion Weighted MRI data. The module produces various (model-specific) voxel-wise parameter maps, and the accompanying diagnostic outputs to evaluate quality of the model fit. The module implements the following models:
* mono-exponential
* bi-exponential
* kurtosis
* gamma distribution
* stretched exponential

This extension can be used together with the [MultiVolume Explorer](https://www.slicer.org/wiki/Documentation/Nightly/Modules/MultiVolumeExplorer) module of 3D Slicer. _MultiVolume Explorer_ module allows to interactively visualize the signal curve at the individual pixels, and also examine the quality of model fit relative to the original data.

# Availability

**Installation**: _DWModeling_ can be accessed by installing the _SlicerProstate_ extension to 3D Slicer via 3D Slicer _Extension manager_.

**Documentation**: [link](https://www.slicer.org/wiki/Documentation/Nightly/Modules/DWModeling)

**Source code**: [link](https://github.com/SlicerProstate/SlicerProstate/tree/master/DWModeling)

# Publications

* Langkilde F, Kobus T, Fedorov A, et al. Evaluation of fitting models for prostate tissue characterization using extended-range b-factor diffusion-weighted imaging. Magn Reson Med. 2017; [link](http://dx.doi.org/10.1002/mrm.26831). - _Evaluation of various models, as implemented in DWModeling, applied to characterization of prostate cancer from DW MRI_
* Newitt DC, Malyarenko D, Chenevert TL, et al. Multisite concordance of apparent diffusion coefficient measurements across the NCI Quantitative Imaging Network. J Med Imaging (Bellingham). International Society for Optics and Photonics; 2018;5(1):011003 [link](http://dx.doi.org/10.1117/1.JMI.5.1.011003). - _Quantitative Imaging Network (QIN) evaluation of DW MRI modeling tools that included DWModeling_

# Grants support

* U24 CA180918
* U01 CA151261
* R01 CA160902
