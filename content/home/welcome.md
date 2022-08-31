
widget: slider
headless: true 
weight: 1 # Order that this section will appear.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '400px'
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Monir Lab
      content: 'Microbial ecology and evolution at University of Miami Rosenstiel'
      align: center
      background:
        position: center
        color: '#666'
        brightness: 0.7
        media: floridakey.jpg
        fit: cover
    - title: Giant Viruses
      content:
      align: center
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: giantvirus.jpeg
        fit: cover
    - title: Phytoplankton
      content:
      align: center
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: phyto.jpg
        fit: cover
    - title: University of Miami Rosenstiel School
      content: 'Check out the world-class campus on the Virginia Key'
      align: center
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: rsmas.jpg
        fit: cover
      link:
        text: Learn more
        url: 'https://www.earth.miami.edu/'
