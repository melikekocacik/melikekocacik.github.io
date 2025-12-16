---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Publications

{% for post in site.publication reversed %}
  <h3>{{ post.title }}</h3>
  <p><strong>{{ post.authors }}</strong><br>
  <em>{{ post.venue }}</em>, {{ post.date | date: "%Y" }}</p>
  
  <details>
    <summary><strong>Abstract</strong> (click to expand)</summary>
    <p>{{ post.excerpt }}</p>
  </details>
  
  {% if post.paperurl %}
    <p><a href="{{ post.paperurl }}">Download paper</a></p>
  {% endif %}
  <hr>
{% endfor %}

## Current Projects
Quantitative Analysis of Statements of the United States’ Presidents on Internal Armed Conflicts
TUBITAK 3501

---

