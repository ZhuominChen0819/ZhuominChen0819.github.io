---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Welcome to my website!"
  url: http://zchenocean.github.io/about-me/
  image: widget-1-self.jpg
  text: 'I am a currently Research Scientist at the Department of Marine Sciences, University of Connecticut... '
widget2:
  title: "Latest Progresses & News"
  url: http://zchenocean.github.io/projects/
  image: widget-2-302x182.jpg
  text: 'I am currently working on several interesting projects...'
widget3:
  title: "Gallery & Moments"
  url: http://zchenocean.github.io/projects/
  image: widget-3.jpg
  text: "I'd like to record & share beautiful moments in life..."


#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /about-me/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
#callforaction:
#  url: http://zchenocean.github.io/contacts/
#  text: Contact me for questions ›
#  style: alert

permalink: /index.html

#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true


---

