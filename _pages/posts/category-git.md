---
layout: archive
permalink: /posts/git
title: "Git 카테고리의 포스트"
author_profile: true
sidebar_main: true
search: false
---

{% assign posts = site.categories.Git | sort:"date" | reverse %}

{% for post in posts %}
{% include archive-single.html type=page.entries_layout %}
{% endfor %}
