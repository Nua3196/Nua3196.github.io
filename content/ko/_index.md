---
# Leave the homepage title empty to use the site title
title: "전북대 홍사강"
date: 2022-10-24
type: landing
show_date: false

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
      view: showcase
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
  - block: experience
    content:
      title: 학력 및 경험
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: 컴퓨터공학(재학)
          company: 전북대학교 컴퓨터인공지능학부
          company_url: 'https://csai.jbnu.ac.kr/csai/index.do'
          company_logo: jbnu
          location: 대한민국 전주
          date_start: '2022-03-01'
          date_end: ''
          description: |2-
              이수학점: 111.5  
              평점: 4.38/4.5
              
              수강과목:
              - 임베디드시스템
              - 운영체제
              - 인공지능
              - 암호론 등
        - title: 근로장학생
          company: 전북대학교 총동창회
          company_url: 'https://alumni.jbnu.ac.kr/alumni/index.do'
          company_logo: jbnu-alumni
          location: 대한민국 전주
          date_start: '2023-03-01'
          date_end: '2023-08-31'
          description: |2-
              수행업무:
              - 총동창회 홈페이지 관리
              - 사무보조
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
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

      - title: <span style="font-size:70%">기타 활동</span>
        content: <span style="font-size:70%">캠프, 교육 등 그동안 참여한 다양한 활동들입니다.</span>
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
---