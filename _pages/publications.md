---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<b><a href="https://www.w3schools.com/">Visit W3Schools.com!</a></b>

<span style="color:blue">some *blue* text</span>.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
