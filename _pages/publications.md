---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

:pushpin:[Integrating Uncertainty Awareness into Conformalized Quantile Regression](https://arxiv.org/abs/2306.08693)
**Raphael Rossellini**, Rina Foygel Barber, Rebecca Willett

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
