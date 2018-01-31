---
layout: page
title: "QuantitativeReporting: Interactive standardized annotation of DICOM data"
teaser: "3D Slicer extension for annotation of DICOM images with the support of standardized representation of the annotation results"
header:
  image_fullwidth: QuantitativeReporting.jpg
categories:
  - tool
---

# About

_QuantitativeReporting_ is an extension of 3D Slicer to support segmentation-based measurements with DICOM-based import and export of the results. The extension comes with a variety of plugins for loading DICOM Segmentations, Parametric Maps and Structured reports that follow DICOM SR TID1500 into 3D Slicer. This extension relies on _dcmqi_ to support the DICOM conversion tasks.

# Availability

**Installation**: _QuantitativeReporting_ can be installed as an extension to 3D Slicer via 3D Slicer _Extension manager_. Once installed, the DICOM plugins will be invoked automatically when you load DICOM series of types that are supported by the plugins (Segmentation image, Parametric map, or DICOM Structured Report that follows TID1500 template) from 3D Slicer DICOM Browser.

**Documentation**: [link](https://qiicr.gitbooks.io/quantitativereporting-guide/)

**Source code**: [link](https://github.com/QIICR/QuantitativeReporting)

# Publications

* Herz C, Fillion-Robin J-C, Onken M, et al. dcmqi: An Open Source Library for Standardized Communication of Quantitative Image Analysis Results Using DICOM. Cancer Res. American Association for Cancer Research; 2017;77(21):e87–e90 [link](http://dx.doi.org/10.1158/0008-5472.CAN-17-0336) - _This publication introduces dcmqi and discusses its relationship to DCMTK and 3D Slicer/QuantitativeReporting_.

# Grants support

* U24 CA180918
