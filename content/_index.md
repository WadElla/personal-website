---
title: ''
summary: ''
date: '2022-10-24'
type: landing
sections:
- block: resume-biography-3
  content:
    username: me
    text: ''
    button:
      text: Download CV
      url: uploads/resume.pdf
    headings:
      about: ''
      education: ''
      interests: ''
  design:
    background:
      gradient_mesh:
        enable: true
    name:
      size: md
    avatar:
      size: medium
      shape: circle
- block: markdown
  content:
    title: Research
    subtitle: ''
    text: 'My research develops systems that help administrators understand, secure,
      and preserve privacy in Internet of Things environments. I work at the intersection
      of network systems, security, machine learning, and large language model agents,
      with emphasis on transforming IoT traffic, packet captures, logs, and operational
      evidence into trustworthy security intelligence.


      Current themes include interpretable IoT traffic analysis, transformer-based
      anomaly detection, retrieval-augmented security reasoning, and privacy-preserving
      communication for connected devices.'
  design:
    columns: '1'
- block: collection
  id: papers
  content:
    title: Selected Publications
    text: ''
    filters:
      folders:
      - publications
      featured_only: true
  design:
    view: article-grid
    columns: 2
- block: collection
  id: news
  content:
    title: Recent News
    subtitle: ''
    text: ''
    page_type: blog
    count: 10
    filters:
      author: ''
      category: ''
      tag: ''
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      publication_type: ''
    offset: 0
    order: desc
  design:
    view: card
    spacing:
      padding:
      - 0
      - 0
      - 0
      - 0
---
