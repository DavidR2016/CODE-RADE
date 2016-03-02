---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
  title: Project CODE-RADE

widget1:
  title: "Overview of the project"
  url: '/overview/'
  image: unsplash_9-302x182.jpg
  text: 'Not sure what this is all about or how you even got here ? Read this first'
widget2:
  title: "Quick Demo"
  url: 'demo/'
  text: 'Seeing is believing'
  video: '<a href="#" data-reveal-id="videoModal"><video src="https://oar.sci-gaia.eu/record/99/files/Sci-GaIA-OAR-video-tutorial.mp4?subformat=master" width="302" height="182" alt=""/></a>'
widget3:
  title: "Tools"
  url: ''
  image:
  text:
permalink: /index.html
---
<div id="header-home">
    <div class="row">
        <div class="small-12 columns">
        </div><!-- /.medium-4.columns -->
    </div><!-- /.row -->
</div><!-- /#header-home -->

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>