---
layout: page
title: "Medical Imaging Webapp Software"
teaser: "Kickoff meeting hosted at Stanford Medical School March 28, 2016."
comments: true
categories:
  - web
  - outreach
---


As blogged about by [other participants][1] there was a meeting held at Stanford Medical School on the topic of common
technologies and possible community development around in the field of medical imaging software.  Several QIICR investigators attended and the
event in person including Ron Kikinis, David Clunie, and me, Steve Pieper, while Andrey Fedorov and Jayashree Kalpathy-Cramer attended via
google hangout.  A [google document][2] was used to organize and document the meeting.

Everyone will have their own conclusions but here are some things that stood out in my mind from the QIICR perspective:
 * A range of [ITCR][3] groups were well represented and each group had a clear focus with interest in collaborating and no overlaps of responsibility.
 * It was a nice chance to review the new approach that David Clunie and Daniel Rubin are taking to harmonize the [AIM][4] and DICOM SR approaches
 and to implement a good solution using the [TID 1500][5] approach.  While we didn't have time to work on this project
 in detail, we looked at it from the perspective of webapps that would make use of data reported in
 that manner.
 * Among the various groups represented there were some interesting differences of perspective on the utility of, for example,
 performing 3D rendering on a browser vs remotely rendering on servers.  Some of the exact implementations will need to
 be tested before specific architectures can be fixed.  Also we may be revisiting some of these issues from
 time to time as the technology develops.  For now the XTK effort will be looking at 3D (WebGL) operations while
 the Cornerstone and OHIF efforts will focus on 2D in the browser and 3D operations provided by servers.  Both
 groups can learn from the overall experience.
 * DICOM technologies are still at the center of the medical imaging world and QIICR's implementations
 of SEG, SR, RWVM, etc. provide a valuable reference for anyone working to organize and operate on
 sophisticated clinical experiment datasets.

I'm looking forward to the upcoming discussions to see where this leads.

Any interested parties should get in touch about participating in this community effort.
We are planning a week-long hackfest meeting in Boston May 23-27, 2016.  An [initial draft of
an organizing document][6] is open for comment.



[1]: https://blog.kitware.com/gabfest-meeting-building-the-medical-imaging-web-app-software-community/
[2]: https://goo.gl/Llnkfy
[3]: http://itcr.nci.nih.gov/
[4]: http://www.ncbi.nlm.nih.gov/pubmed/22745220
[5]: http://dicom.nema.org/medical/dicom/current/output/html/part16.html#sect_TID_1500
[6]: https://docs.google.com/document/d/1BIQHLheqYhsfeHhCTVtid5bZMVywlo1UmeK6-ZmHeq8/edit?usp=sharing
