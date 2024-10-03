---
# Leave the homepage title empty to use the site title
title: JINYEONG
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        안녕하세요
      text: |
        <br>

        저의 블로그에 오신 걸 환영합니다! 
        주로 제가 진행한 프로젝트를 업로드할 예정입니다.

  - block: slider
    content:
      slides:
        - title: 👋 어서오세요 반갑습니다
          content: "jinyeong portplio"
          align: center
          background:
            image:
              filename: AI.jpg
              filters:
                brightness: 0.7
            position: right
            color: "#666"
        - title: show
          content: "팀 과제, 공부, 관심있는 것"
          align: left
          background:
            image:
              filename: C.jpg
              filters:
                brightness: 0.7
            position: center
            color: "#555"
        - title: JBNU
          content: "컴퓨터인공지능학부(CSAI)"
          align: right
          background:
            image:
              filename: csai.jpg
              filters:
                brightness: 0.5
            position: center
            color: "#333"
          link:
            icon: graduation-cap
            icon_pack: fas
            text: 클릭
            url: ../contact/
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
      title: Latest News
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
      page_type: post
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
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ["20px", "0", "20px", "0"]
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: "article"
    design:
      view: citation
      columns: "1"
---
