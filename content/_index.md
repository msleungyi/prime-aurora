---
title: ""
summary: ""
date: "2022-10-24"
type: "landing"
design:
  spacing: "6rem"
sections:
  - block: "resume-biography-3"
    content:
      username: "me"
      text: ""
      button:
        text: "Download CV"
        url: "uploads/resume.pdf"
      headings:
        about: ""
        education: ""
        interests: ""
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: "md"
      avatar:
        size: "medium"
        shape: "circle"
    ue: "section-35c5fc4d"
    Bi: "section-76dcdc52"
  - block: "resume-experience"
    content:
      username: "me"
    ue: "section-4-resume-experience"
    Bi: "section-f567f706"
  - block: "tech-stack"
    ue: "section-5-tech-stack"
    Bi: "section-d9ba3249"
  - block: "resume-languages"
    content:
      username: "me"
    ue: "section-6-resume-languages"
    Bi: "section-ff9b2885"
  - block: "markdown"
    content:
      title: "📚 My Research"
      subtitle: ""
      text: |-
        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.

        Please reach out to collaborate 😃
    design:
      columns: "1"
    ue: "section-1e35c729"
    Bi: "section-0953b90e"
  - block: "collection"
    content:
      title: "Featured Publications"
      filters:
        folders:
          - "publications"
        featured_only: true
    design:
      view: "article-grid"
      columns: 2
    ue: "section-papers"
    id: "papers"
    Bi: "section-b5810282"
  - block: "collection"
    content:
      title: "Recent Publications"
      text: ""
      filters:
        folders:
          - "publications"
        exclude_featured: false
    design:
      view: "citation"
    ue: "section-26d9236d"
    Bi: "section-3ff359fa"
---
