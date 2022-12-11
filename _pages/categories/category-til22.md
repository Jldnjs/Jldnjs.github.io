---
title: "Today I Learnd - 2022"
layout: archive
permalink: categories/til22
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.til22 %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %}{% endfor %}