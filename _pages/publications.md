---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

These are some key publications in different areas. For a full list, please see my profile on <a href="{{author.googlescholar}}">Google Scholar</a>.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
