---
# Leave the homepage title empty to use the site title
title: "전북대 홍사강"
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: custom-biography
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
  - block: slider
    content:
      slides:
      - title: <span style="font-size:70%">프로젝트</span>
        content: <span style="font-size:70%">수업, 대회 등 다양한 상황에서 진행한 프로젝트들입니다.</span>
        align: center
        background:
          image:
            filename: projects.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#000'

      - title: <span style="font-size:70%">학력 및 경력</span>
        content: <span style="font-size:70%">학부 이수 현황 및 기타 경력을 소개합니다.</span>
        align: center
        background:
          image:
            filename: experiences.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#000'

      - title: <span style="font-size:70%">캠프 및 교육</span>
        content: <span style="font-size:70%">그동안 참여한 다양한 활동들입니다.</span>
        align: center
        background:
          image:
            filename: explore.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#000'

      - title: <span style="font-size:70%">대회</span>
        content: <span style="font-size:70%">소정의 성과들을 기록해두었습니다.</span>
        align: center
        background:
          image:
            filename: contests.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#000'

      - title: <span style="font-size:70%">여가</span>
        content: <span style="font-size:70%">제가 즐거움을 위해 하는 것들입니다.</span>
        align: center
        background:
          image:
            filename: others.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#000'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '250px'
      # slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 7000

  - block: custom-three-collection
    id: goal
    content:
      title: 지향점
      filters:
        folders:
          - goal
    design:
      view: custom-three-card
      columns: '1'
  - block: collection
    id: strength
    content:
      title: 강점
      filters:
        folders:
          - strength
    design:
      columns: '1'
      view: compact
  - block: collection
    id: weakness
    content:
      title: 약점
      filters:
        folders:
          - weakness
    design:
      columns: '1'
      view: card
---