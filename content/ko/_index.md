---
# Leave the homepage title empty to use the site title
title: "전북대 홍사강"
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
    design:
      css_class: dark
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: profile.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  # - block: slider
  #   content:
  #     slides:
  #       - title: 👋 Welcome to the group
  #         content: Take a look at what we're working on...
  #         align: center
  #         background:
  #           image:
  #             # Specify an image from `assets/media/`
  #             # or delete the image section to remove it
  #             filename: experiences.jpg
  #             filters:
  #               brightness: 0.7
  #           position: right
  #           color: '#666'
  #       - title: Lunch & Learn ☕️
  #         content: 'Share your knowledge with the group and explore exciting new topics together!'
  #         align: left
  #         background:
  #           image:
  #             # Specify an image from `assets/media/`
  #             # or delete the image section to remove it
  #             filename: projects.jpg
  #             filters:
  #               brightness: 0.7
  #           position: center
  #           color: '#555'
  #       - title: World-Class Semiconductor Lab
  #         content: 'Just opened last month!'
  #         align: right
  #         background:
  #           image:
  #             # Specify an image from `assets/media/`
  #             # or delete the image section to remove it
  #             filename: courses.jpg
  #             filters:
  #               brightness: 0.5
  #           position: center
  #           color: '#333'
  #         link:
  #           icon: graduation-cap
  #           icon_pack: fas
  #           text: Join Us
  #           url: ../contact/
  #   design:
  #     # Slide height is automatic unless you force a specific height (e.g. '400px')
  #     slide_height: ''
  #     # Make the slides full screen within the browser window?
  #     is_fullscreen: false
  #     # Automatically transition through slides?
  #     loop: false
  #     # Duration of transition between slides (in ms)
  #     interval: 2000
---
