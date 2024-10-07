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
      title: 프로젝트
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 3
  - block: resume-awards
    id: award
    content:
      title: 대회
      username: admin
  - block: collection
    id: etc
    content:
      title: 기타 활동
      filters:
        folders:
          - etc
    design:
      columns: 1
      view: card
  - block: resume-skills
    id: skils
    content:
      title: 프로그래밍 언어
      username: admin
    design:
      show_skill_percentage: false
      columns: '1'
  - block: resume-languages
    content:
      title: 언어
      username: admin
---

{{< carousel items="1" height="500" unit="px" duration="7000" >}}