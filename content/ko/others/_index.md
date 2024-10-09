---
# Leave the homepage title empty to use the site title
title: "여가"
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: profile.jpg
      filters:
        brightness: 0.1
      size: cover
      position: center
      parallax: false

sections:
  - block: markdown
    id: knitpurl
    content:
      title: '뜨개질'
      subtitle: ''
      text: |-
        대바늘은 중급, 코바늘은 초급!
    design:
      css_class: cloud
      columns: '1'
  - block: markdown
    id: travel
    content:
      title: '여행'
      subtitle: ''
      text: |-
        공강이 있는 학기엔 여행을. 지난 학기 순천, 광양을 다녀왔습니다. 나서서 가는 것뿐만 아니라 여행을 보내주는 활동도 적극 참여합니다.
    design:
      css_class: cloud
      columns: '1'
  - block: contact
    id: contact
    content:
      title: 다녀온 곳
      subtitle: ''
      text: ''
      # Coordinates to display a map - set your map provider in `params.yaml`
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  - block: markdown
    id: reading
    content:
      title: '독서'
      subtitle: ''
      text: |-
        ...마지막 완독이 언젠지 모르겠네요. 이제 취미라고는 할 수 없고 소망...?
    design:
      css_class: cloud
      columns: '1'
---