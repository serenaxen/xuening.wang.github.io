---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
This should be my publication list please wait for another five years to see a satisfactory one good luck.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
