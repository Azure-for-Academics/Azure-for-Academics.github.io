---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: head.png
widget1:
  title: "About"
  url: '/info/'
  #image: widget-1-302x182.jpg
  text: 'This site contains materials on Microsoft Azure that can be useful in teaching, both for faculty, students and individual learners. The content here has been created and maintained by <a href="https://developer.microsoft.com/advocates/">Microsoft Cloud Advocates</a>, together with University Relations team, and has been used in a number of top universities worldwide.'
widget2:
  title: "Quickstart Videos"
  url: '/quickstart/'
  text: 'Introductory videos are 30 min long videos that introduce you to the concept of a cloud, show how Microsoft Azure can be used to create resources, and go into more details on Azure Machine Learning. Those videos can be easily distributed to students for self-study.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="/images/azure_intro_video.png" alt=""/></a>'
widget3:
  title: "Azure Syllabus"
  url: '/courses/'
  image: syllabus.png
  text: 'Introductory syllabus on Azure consists of three modules that introduce you to Azure platform (and walk you through creating an Azure account), to Machine Learning on Azure, and to working with Data (including relational and non-relational data). Those courses are accompanied by office hours, where you can ask further questions on your specific projects.'
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
callforaction:
  url: /courses/
  text: Start Learning ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3RRirPGDWbE" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
