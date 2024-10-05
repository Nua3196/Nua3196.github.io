---
title: 'Experience'
date: 2024-10-05
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    id: timeline
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  - block: resume-skills
    id: skils
    content:
      align: center
      title: Programming Languages
      username: admin
    design:
      show_skill_percentage: false
  - block: resume-awards
    id: award
    content:
      title: Awards
      username: admin
  - block: collection
    id: etc
    content:
      title: Etc
      filters:
        folders:
          - etc
    design:
      columns: '3'
      view: card
  - block: resume-languages
    content:
      title: Languages
      username: admin
---
