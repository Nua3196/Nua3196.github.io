---
# Leave the homepage title empty to use the site title
title: "Jeonbuk National University Sakang Hong"
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    id: summary
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
    design:
      css_class: cloud
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: profile.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    id: project
    content:
      title: Projects
      filters:
        folders:
          - project
    design:
      view: community/custom_card
      columns: 1
  - block: resume-awards
    id: award
    content:
      title: Awards
      username: admin
  - block: collection
    id: etc
    content:
      title: Other experience
      filters:
        folders:
          - etc
    design:
      columns: 1
      view: card
  - block: resume-skills
    id: skils
    content:
      title: Pragramming Languages
      username: admin
    design:
      show_skill_percentage: false
      columns: '1'
  - block: resume-languages
    content:
      title: Languages
      username: admin
---