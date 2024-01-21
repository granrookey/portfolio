---
title: "Hello, World"
layout: splash
# <!-- permalink: /splash-page/ -->
date: 2024-01-21T23:12:00-09:00
header:
  overlay_color: "#000"
  overlay_filter: "0.4"
  overlay_image: /assets/images/mainBanner.png
  # actions:
  #   - label: "Download"
  #     url: "https://github.com/mmistakes/minimal-mistakes/"
  # caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "프로젝트에 필요한 궁금증은 여기에서!"
intro:
  - excerpt: '*다양한 프로젝트 경험* : Bixby, Samsung Internet, Samsung Galaxy Store, Embedded, LG VS본부<br>
*다양한 역할 수행* : Application, Backend, Data Engineering / Analytics, Infra(DevOps), QA 등<br>
*신규 프로젝트 다수 참여* : Bixby, Search Platform,Internet 신기능, QT, KTD 멘토링 등<br>
*다양한 개발 환경 경험* : Linux / Windows, Cloud(AWS), Git, Gerrit, SVN, AOS, Jira, Confluence, Slack 등<br>
**Usage Skill**<br>
Language : Python, Java, C, C++, Javascript, HTML, CSS, R, SQL<br>
Data : Pandas, Tensorflow, Tableau,  DataDog, Sumo Logic<br>
Database : PostgreSQL, MongoDB, ElasticSearch, MySQL, SQLite, InfluxDB, Redshift<br>
Application : Android, QT, Flutter<br>
Backend : Django, Spring, Node.js<br>
DevOps : Docker, CircleCI, Jenkins, Ansible, JMeter, Grafana'
feature_row:
  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}

