---
title: "Assembly"
layout: archive
permalink: categories/assembly
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.assembly %}
{% for post in posts %} {% include archive-single-custom.html type=page.entries_layout %} {% endfor %}
