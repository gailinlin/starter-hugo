---
widget: slider
weight: 2
active: false
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 
      content: 
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: page1.png
    - title: 
      content: 
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: page2.png
    - title: 
      content: 
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: page3.png
      # link:
      #   icon: graduation-cap
      #   icon_pack: fas
      #   text: Join Us
      #   url: ../event/
---
