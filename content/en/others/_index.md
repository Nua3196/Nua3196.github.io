---
# Leave the homepage title empty to use the site title
title: "Others"
date: 2022-10-24
type: landing


design:
  # Default section spacing
  spacing: "6rem"
  # background:
  #   image:
  #     # Add your image background to `assets/media/`.
  #     filename: profile.jpg
  #     filters:
  #       brightness: 0.1
  #     size: cover
  #     position: center
  #     parallax: false

sections:
  - block: markdown
    id: knitpurl
    content:
      title: 'Knitting'
      subtitle: ''
      text: |-
        quite good at knitting, but beginner at crocheting!
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: 'Travel'
      subtitle: ''
      text: |-
        Travel during semesters when there is a day without class. I went to Suncheon and Gwangyang last semester. I also actively participate in sending trips.
      # Coordinates to display a map - set your map provider in `params.yaml`
      coordinates:
        latitude: '34.9284391'
        longitude: '127.4982691'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  - block: markdown
    id: reading
    content:
      title: 'Reading'
      subtitle: ''
      text: |-
        Now it has become too rare to be called a hobby.
    design:
      columns: '1'
---