---
layout: page
title: "DSC_MRI_Analysis: DSC MRI Modeling"
teaser: "3D Slicer extension for dynamic susceptibility MRI modeling"
comments: true
header:
  image_fullwidth: beacon.jpg
categories:
  - tool
---

# About

_DSC_MRI_Analysis_ is an extension of 3D Slicer that implements fitting of various models to Dynamic Susceptibility MRI data. The module produces various (model-specific) voxel-wise parameter maps, and the accompanying diagnostic outputs to evaluate quality of the model fit. The module produces the following parameter maps:
* _K2_: leakage map
* _RCBV_: Relative Cerebral Blood Volume (rCBV) map
* _RCBF_: Relative Cerebral Blood Flow (rCBF) map
* _MTT_: Mean Transit Time (MTT) map

This extension can be used together with the [MultiVolume Explorer](https://www.slicer.org/wiki/Documentation/Nightly/Modules/MultiVolumeExplorer) module of 3D Slicer. _MultiVolume Explorer_ module allows to interactively visualize the signal curve at the individual pixels, and also examine the quality of model fit relative to the original data.

# Availability

**Installation**: _DSC_MRI_Analysis_ can be accessed by installing the _DSC_MRI_Analysis_ extension to 3D Slicer via 3D Slicer _Extension manager_.

**Documentation**: [link](https://www.slicer.org/wiki/Documentation/Nightly/Modules/DSC_MRI_Analysis)

**Source code**: [link](https://github.com/QIICR/DSC_Analysis)

# Publications

N/A

# Grants support

* U01 CA154601
* U24 CA180918
