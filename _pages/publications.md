---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Rychert C.A., Tharimena S., Harmon N., <b>Wang, S.</b>, Kendall J.M., Constable S., Bogiatzis P., SchlaphorstD., Agius M., Hicks S., 2019. <br> <b>[A dynamic lithosphere-asthenosphere boundary dictated by variations in melt generation and migration.]</b> <br> <i>Under review</i> 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
