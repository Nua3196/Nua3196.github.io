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
      - title: 프로젝트
        content: 수업, 대회 등 다양한 상황에서 진행한 프로젝트들입니다.
        align: center
        background:
          image:
            filename: projects.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          # icon: user
          # icon_pack: fas
          # text: <span style="font-size:60%">Join Us</span>
          # text-color: '#000'
          # url: /experiences

      - title: 학력 및 경력
        content: 학부 이수 현황 및 기타 경력을 소개합니다.
        align: center
        background:
          image:
            filename: experiences.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: 캠프 및 교육
        content: 그동안 참여한 다양한 활동들입니다.
        align: center
        background:
          image:
            filename: explore.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: 대회
        content: 소정의 성과들을 기록해두었습니다.
        align: center
        background:
          image:
            filename: contests.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: 여가
        content: 제가 즐거움을 위해 하는 것들입니다.
        align: center
        background:
          image:
            filename: others.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000
      
  - block: collection
    id: project
    content:
      title: 프로젝트
      filters:
        folders:
          - project
    design:
      view: card
      columns: 2
  # - block: resume-awards
  #   id: award
  #   content:
  #     title: 대회
  #     username: admin
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
  # - block: resume-skills
  #   id: skils
  #   content:
  #     title: 프로그래밍 언어
  #     username: admin
  #   design:
  #     show_skill_percentage: false
  #     columns: '1'
  # - block: resume-languages
  #   content:
  #     title: 언어
  #     username: admin
---