---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/Peer Reviewed Pub Banner.jpg)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
