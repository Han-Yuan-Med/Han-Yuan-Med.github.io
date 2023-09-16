---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---
FedScore: A Privacy-Preserving Framework for Federated Scoring System Development.Journal of Biomedical Informatics. ([Paper](http://han-yuan-med.github.io/files/FedScore A Privacy-Preserving Framework for Federated Scoring System Development.pdf))
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
