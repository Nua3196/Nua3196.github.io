---
# Leave the homepage title empty to use the site title
title: "전북대 홍사강"
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  # - block: resume-biography-3
  #   id: summary
  #   content:
  #     # Choose a user profile to display (a folder name within `content/authors/`)
  #     username: admin
  #     text: ""
  #   design:
  #     css_class: cloud
  #     background:
  #       image:
  #         # Add your image background to `assets/media/`.
  #         filename: profile.jpg
  #         filters:
  #           brightness: 1.0
  #         size: cover
  #         position: center
  #         parallax: false
  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">Recruit</span>
        content: <span style="font-size:70%">Interested in MacsLAB?</span>
        align: center
        background:
          image:
            filename: profile.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">Join Us</span>
          text-color: '#000'
          url: contact

      - title: <span style="font-size:70%">AI</span>
        content: <span style="font-size:70%">의료/항공우주/컨텐츠 등 특성화 분야에 적용 가능한 AI 기술 개발<span style="font-size:70%">
        align: center
        background:
          image:
            filename: profile.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Healthcare</span>
        content: <span style="font-size:70%">의료 및 헬스케어 분야에 적용 가능한 AI 기술 개발</span>
        align: center
        background:
          image:
            filename: profile.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Mathematics</span>
        content: <span style="font-size:70%">AI와 관련된 수학 및 최적화 이론 연구</span>
        align: center
        background:
          image:
            filename: profile.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">기반 기술을 활용한 Full-Stack 어플리케이션 개발</span>
        align: center
        background:
          image:
            filename: profile.jpg
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