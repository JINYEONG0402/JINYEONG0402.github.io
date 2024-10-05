---
# Leave the homepage title empty to use the site title
title: JINYEONG
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
        - title: 어서오세요 반갑습니다
          content: "IT지능정보공학과 고진영입니다."
          align: center
          background:
            image:
              filename: code.jpg
              filters:
                brightness: 0.7
            position: right
            color: "#666"
        - title: Portfolio
          content: "#코딩 #IT"
          align: center
          background:
            image:
              filename: C.jpg
              filters:
                brightness: 0.7
            position: center
            color: "#555"
        - title:
          content: "더 자세한 사항은... "
          align: center
          background:
            image:
              filename: phone.jpg
              filters:
                brightness: 0.5
            position: center
            color: "#333"
          link:
            icon: graduation-cap
            icon_pack: fas
            text: 클릭
            url: ../people/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ""
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

  - block: collection
    content:
      title: it, 테크닉 뉴스
      subtitle:
      text:
      count: 5
      filters:
        author: ""
        category: ""
        exclude_featured: false
        publication_type: ""
        tag: ""
      offset: 0
      order: desc
      page_type: itnews
    design:
      view: card
      columns: "1"

  - block: markdown
    content:
      title:
      subtitle: ""
      text:
    design:
      columns: "1"
      background:
        image:
          filename: people.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ["20px", "0", "20px", "0"]
      css_class: fullscreen
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text=" send email →" %}}
    design:
      columns: "1"
---
