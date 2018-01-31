---
layout: page
title: "PETLiverUptakeMeasurement: Automated measurement of liver uptake PET"
teaser: "3D Slicer extension automated measurement of liver uptake PET scans"
comments: true
header:
  image_fullwidth: beacon.jpg
categories:
  - tool
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/XJRUHFgBODI?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

# About

_PETLiverUptakeMeasurement_ is an extension of 3D Slicer that allows automated measurement of liver uptake in SUV normalized whole-body FDG-18 PET scans and export to DICOM. The extension provides the automated algorithm, a GUI module for providing additonal input, and functionality to export quantification results to DICOM SEG and SR files.

# Availability

**Installation**: _PETLiverUptakeMeasurement_ can be installed as an extension to 3D Slicer via 3D Slicer _Extension manager_. In addition to the GUI module, the extension includes a command line interface module, _PETLiverUptakeMeasurementCLI_, which can be used in batch mode.

**Documentation**: [link](https://www.slicer.org/wiki/Documentation/Nightly/Extensions/PETLiverUptakeMeasurement)

**Source code**: [link](https://github.com/QIICR/PETLiverUptakeMeasurement)

# Publications

* Bauer C, Sun S, Sun W, et al. Automated measurement of uptake in cerebellum, liver, and aortic arch in full-body FDG PET/CT scans. Med Phys. 2012;39(6):3112-3123 [link](http://dx.doi.org/10.1118/1.4711815) - _This publication describes in detail the algorithm implemented in the module, and its evaluation in a clinical dataset_.

* Fedorov A, Clunie D, Ulrich E, et al. DICOM for quantitative imaging biomarker development: a standards based approach to sharing clinical data and structured PET/CT analysis results in head and neck cancer research. PeerJ. 2016;4:e2057 [link](http://dx.doi.org/10.7717/peerj.2057) - _This publication describes the dataset that includes segmentations produced using the PETTumorSegmentation tool_.

# Grants support

* U01 CA140206
* U24 CA180918
