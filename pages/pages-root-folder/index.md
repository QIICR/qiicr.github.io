---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: chicago-lakeside.jpg
widget1:
  title: "Open software"
  url: 'https://github.com/QIICR'
  text: 'We are developing open source imaging informatics tools based on <a href="http://slicer.org">3D Slicer</a> to support research workflows of the <a href="http://imaging.cancer.gov/programsandresources/specializedinitiatives/qin">NCI Quantitative Imaging Network</a>.'
  video: '<a href="#" data-reveal-id="slicerVideo"><img src="http://qiicr.org/images/slicer-youtube.jpg"  width="302" height="182" alt=""/></a>'

widget2:
  title: "Open standards"
  url: 'https://peerj.com/articles/2057/'
  image: peerj-graphical-abstract.jpg
  text: 'We aim to support interoperable exchange of quantitative image analysis results using <a href="http://dicom.nema.org/Dicom/about-DICOM.html">Digital Imaging and Communications in Medicine (DICOM) standard</a>.'

widget3:
  title: "Open science"
  url: '/about.html'
  text: 'Our ultimate goal is to support open and reproducible science in quantitative imaging biomarker development for cancer imaging research.'
  video: '<a href="#" data-reveal-id="qiicrVideo"><img src="http://qiicr.org/images/qiicr-demo-youtube.png"  width="302" height="182" alt=""/></a>'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="slicerVideo" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/ikK5uDEmihU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="qiicrVideo" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/wK2TGyVQjzs" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>


