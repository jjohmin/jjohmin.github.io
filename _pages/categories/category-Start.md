---
title : "기초"
layout : archive
permalink : categories/Start
author_profile : true
sidebar_main : true
---

{% assign posts = site.categories.Start %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}