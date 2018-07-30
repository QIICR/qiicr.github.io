---
layout: page
title: "PkModeling: DCE MRI modeling"
teaser: "3D Slicer extension for Tofts modeling of DCE MRI"
comments: true
header:
  image_fullwidth: PkModeling.jpg
categories:
  - tool
---

# About

PkModeling is an extension of 3D Slicer that implements Tofts model fit to Dynamic Contrast Enhanced MRI signal. As a result PkModeling can be used to generate quantitative maps of Tofts model parameters:
* _Ktrans_ - volume transfer constant between blood plasma and EES (extracellular-extravascular space)
* _ve_ - fractional volume for extracellular space

This module also generates maps of some empirical (model-independent) parameters: time to peak (TTP) and area under the signal curve (AUC).

Modeling can be parameterized using the patient-specific Arterial Input Function (AIF), or a population-averaged AIF.

This extension can be used together with the [MultiVolume Explorer](https://www.slicer.org/wiki/Documentation/Nightly/Modules/MultiVolumeExplorer) module of 3D Slicer. _MultiVolume Explorer_ module allows to interactively visualize the signal curve at the individual pixels, and also examine the quality of model fit relative to the original data.

# Availability

**Installation**: _PkModeling_ can be installed as an extension to 3D Slicer via 3D Slicer _Extension manager_. You can also build _PkModeling_ as a standalone tool independent of 3D Slicer.

**Documentation**: [link](https://www.slicer.org/wiki/Documentation/Nightly/Modules/PkModeling)

**Source code**: [link](https://github.com/QIICR/PkModeling)

# Publications

* Huang W, Li X, Chen Y, et al. Variations of dynamic contrast-enhanced magnetic resonance imaging in evaluation of breast cancer therapy response: a multicenter data analysis challenge. Transl Oncol. 2014;7(1):153–166 [link](http://dx.doi.org/10.1593/tlo.13838). - _Quantitative Imaging Network (QIN) evaluation of DCE MRI modeling tools that included PkModeling_
* Mehrtash A, Gupta SN, Shanbhag D, et al. Bolus arrival time and its effect on tissue characterization with dynamic contrast-enhanced magnetic resonance imaging. J Med Imaging (Bellingham). 2016;3(1):014503 [link](http://dx.doi.org/10.1117/1.JMI.3.1.014503). - _Investigation of one of the parameters influencing DCE MRI analysis that utilized PkModeling_

# Grants support

* U54 EB005149
* U01 CA151261
* U24 CA180918
