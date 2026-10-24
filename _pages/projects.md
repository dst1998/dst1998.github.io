---
layout: page
title: Projects
permalink: /projects/
description: Selected research and design projects in AI hardware and computer architecture.
nav: false
nav_order: 3
display_categories: [research, design]
---

{% if site.enable_project_categories and page.display_categories %}
{% for category in page.display_categories %}

<h2>{{ category | capitalize }}</h2>
{% assign categorized_projects = site.projects | where: 'category', category %}
{% assign sorted_projects = categorized_projects | sort: 'importance' %}
{% for item in sorted_projects %}
{% include work.liquid item=item %}
{% endfor %}
{% endfor %}
{% else %}
{% assign sorted_projects = site.projects | sort: 'importance' %}
{% for item in sorted_projects %}
{% include work.liquid item=item %}
{% endfor %}
{% endif %}
