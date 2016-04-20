---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage

header:
  image_fullwidth: nk_olpc_france_1_large_1600x900.jpg

widget1:
  title: "Des XOs à Saint-Ouen"
  url: '/saint-ouen/'
  image: saint-ouen-img3890_300x180.jpg
  text: 'Des élèves du primaire à Saint-Ouen utilisent des XOs et Sugar'

widget2:
  title: "Sugarizer : Sugar en HTML5"
  url: '/sugarizer/'
  image: sugar_animation_300x180-1.jpg
  text: 'Découvrez Sugarizer, la version de Sugar qui tourne dans votre navigateur'

widget3:
  title: "Des XOs à Madagascar"
  url: '/nosy-komba/'
  image: nk2014_1-300x180.jpg
  text: 'Description du projet Nosy Komba'

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
  url: https://www.helloasso.com/don/associations/olpc-france
  text: Soutenez nos actions !
  style: alert

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
