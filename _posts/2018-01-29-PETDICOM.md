---
layout: page
title: "PETDICOM: PET normalization"
teaser: "3D Slicer extension for Standard Uptake Value calculation"
comments: true
header:
  image_fullwidth: beacon.jpg
categories:
  - tool
---

# About

_PETDICOM_ is an extension of 3D Slicer that implements calculation of the Standard Uptake Value (SUV) correction for Positron Emission Tomography (PET) images. The SUV approaches implemented include:
* SUV body weight
* SUV lean body mass
* SUV body surface area
* SUV ideal body weight

The extension contains three modules:
* _SUVFactorCalculatorCLI_: a command line interface module that generates SUV factors and stores the result as a DICOM Real World Value Mapping (RWVM) object
* _DICOMPETSUVPlugin_ and _DICOMRWVMPlugin_: DICOM plugins that implement loading and automatic calculation of SUV for PET DICOM series, and loading of the DICOM RWVM objects, respectively.

# Availability

**Installation**: _DICOMPET_ can be installed as an extension to 3D Slicer via 3D Slicer _Extension manager_. Once installed, the DICOM plugins will be invoked automatically when you load PET series from 3D Slicer DICOM Browser. You can also run the _SUVFactorCalculatorCLI_ in the batch mode using the command line interface.

**Documentation**: [link](https://www.slicer.org/wiki/Documentation/Nightly/Extensions/PETDICOM)

**Source code**: [link](https://github.com/QIICR/Slicer-PETDICOMExtension)

# Publications

* Fedorov A, Clunie D, Ulrich E, et al. DICOM for quantitative imaging biomarker development: a standards based approach to sharing clinical data and structured PET/CT analysis results in head and neck cancer research. PeerJ. 2016;4:e2057 [link](http://dx.doi.org/10.7717/peerj.2057). - _dataset discussed in this paper contains DICOM RWVM objects generated using DICOMPET extension_

# Grants support

* U01 CA140206
* U24 CA180918
