---
layout: page
author: fedorov
title: "dicom-dump package for Atom"
teaser: "Explore DICOM content from a modern editor!"
comments: true
categories:
  - DICOM

header: no
image:
  title: atom-dicom_dump-demo.gif
  thumb: atom-dicom_dump-demo.gif
  homepage: atom-dicom_dump-demo.gif
  caption: Atom dicom-dump in action
  caption_url: https://atom.io/packages/dicom-dump
---

Those working with DICOM often (always!) need to be able to quickly view the content of DICOM data.

Several tools are available for this task, however some of the popular tools commonly used provide only the command line interface. It is often desirable to have a convenient search interface, or to be able to collapse sub-section of the DICOM hierarchy.

We have recently developed a plugin for the [Atom][1] editor (package, in the nomenclature of Atom) that provides a convenient interface within the editor to the output produced by the [DCMTK][2] DICOM dump tools. [Atom][1] is a an extensible, versatile, free open source modern editor brought to you by GitHub.

Once [dicom-dump package][5] is installed and properly configured with your local installation of DCMTK tools, you can open any DICOM file in Atom from command line, or by dropping the file into the editor window, and access the functionality demonstrated above. You can access both [dcmdump][3] (view the DICOM file dump at the attribute level) and [dsrdump][4] (view the DICOM file dump at the level of Structured Report content tree) command line tools of DCMTK using the interface of this package.

As always, the source code of this package is open and we welcome your contributions to further improving its functionality!

[1]: https://atom.io
[2]: http://dcmtk.org
[3]: http://support.dcmtk.org/docs/dcmdump.html
[4]: http://support.dcmtk.org/docs/dsrdump.html
[5]: https://atom.io/packages/dicom-dump
