---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<b><a style="font-size:100px;" href="https://pubs.acs.org/doi/10.1021/acs.energyfuels.9b02113">Phase Behavior of Mixtures of Bitumen and n-Butane</a></b> <br>
<b>Yulman Perez</b>, Florian Schoeggl, Shawn Taylor, and Harvey Yarranton <br>
Energy & Fuels, 2019 <br>



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
