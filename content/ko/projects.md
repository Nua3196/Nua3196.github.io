---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    id: cs
    content:
      title: 전공
      text: 전공과 관련된 프로젝트들입니다.
      filters:
        folders:
          - ko
    design:
      view: article-grid
      fill_image: false
      columns: 3
  - block: collection
    id: etc
    content:
      title: 그 외
      text: 전공과 관련없는 프로젝트들입니다.
      filters:
        folders:
          - ko
    design:
      view: article-grid
      fill_image: false
      columns: 3
---
