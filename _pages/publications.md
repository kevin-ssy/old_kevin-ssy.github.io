---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Still too weak to publish a paper. Just wanna sleep at home.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
