---
layout: default
title: "Home"
---

I am a mathematician at heart,  specializing in Data Science, Machine Learning, Business Intelligence, & AI/ML, and a passion for teaching mathematics. 

Behind the data is a story, and I want to tell that story.


{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="" %}
{% endif %}
