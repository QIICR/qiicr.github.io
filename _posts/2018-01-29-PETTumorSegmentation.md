---
layout: page
title: "PETTumorSegmentation: Semi-automatic segmentation of tumors in PET"
teaser: "3D Slicer extension for \"just enough interaction\" segmentation"
comments: true
header:
  image_fullwidth: beacon.jpg
categories:
  - tool
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/k1GbJliipuc?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

# About

_PETTumorSegmentation_ is an extension of 3D Slicer that provides "just enough interaction" tools for automated segmentation of metabolically active regions in Positron Emission Tomography (PET) images. The extension provides segmentation tools implemented as "effects" for the 3D Slicer _Segment Editor_ and legacy _Editor_ modules. As such, these tools can be used in combination with the other automated and manual segmentation approaches already available in those modules. These effects are also available within the _Quantitative Reporting_ module of 3D Slicer.

# Availability

**Installation**: _PETTumorSegmentation_ can be installed as an extension to 3D Slicer via 3D Slicer _Extension manager_.

**Documentation**: [link](https://www.slicer.org/wiki/Documentation/Nightly/Extensions/PETTumorSegmentation)

**Source code**: [link](https://github.com/QIICR/PETTumorSegmentation)

# Publications

* Beichel RR, Van Tol M, Ulrich EJ, et al. Semiautomated segmentation of head and neck cancers in 18F-FDG PET scans: A just-enough-interaction approach. Med Phys. 2016;43(6):2948–2964 [link](http://dx.doi.org/10.1118/1.4948679) - _This publication describes in detail the algorithm implemented in the module, and its evaluation in a clinical dataset_.

* Fedorov A, Clunie D, Ulrich E, et al. DICOM for quantitative imaging biomarker development: a standards based approach to sharing clinical data and structured PET/CT analysis results in head and neck cancer research. PeerJ. 2016;4:e2057 [link](http://dx.doi.org/10.7717/peerj.2057) - _This publication describes the dataset that includes segmentations produced using the PETTumorSegmentation tool_.

* Beichel RR, Smith BJ, Bauer C, et al. Multi-site quality and variability analysis of 3D FDG PET segmentations based on phantom and clinical image data. Med Phys. 2017;44(2):479–496http://dx.doi.org/10.1002/mp.12041. - _This publication applied the PETTumorSegmentationTool in the context of a community challenge organized by the NCI Quantitative Imaging Network (QIN)_

# Grants support

* U01 CA140206
* U24 CA180918
