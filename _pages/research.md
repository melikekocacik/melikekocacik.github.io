---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Publications

{% for post in site.publications reversed %}
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
### [Quantitative Analysis of Statements of the United States’ Presidents on Internal Armed Conflicts](/research/tubitak-3501/)
TÜBİTAK 3501 Career Development Program, 2026–2027. An original dataset of US presidents' public statements on civil conflicts since 1945, built with machine learning and large language models. [Read more about the project →](/research/tubitak-3501/)

---

