---
layout: page
permalink: /publications_topic/
title: Publications (by Topic)
topics: [Control Theory and Dynamical Systems, Convex and Nonconvex Optimization, Data-driven Optimization and Control]
nav: false
---

<div class="publications">
{% for t in page.topics %}
  <h1 class="year">{{t}}</h1>
  {% bibliography -f papers -q @*[topic={{t}}]* %}
{% endfor %}
</div>