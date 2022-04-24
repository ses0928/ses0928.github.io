---
title: "Weekly Posts"
layout: archive
permalink: categories/weekly_post
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.weekly_post %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}