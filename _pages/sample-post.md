---
title: Sample Post
layout: single
permalink: /sample-post/
author_profile: true
toc: true
toc_sticky: true

sidebar:
    nav: "categories"
---

마크다운 테스트 용 페이지입니다. 

{% assign posts = site.categories.['Sample Post'] %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}