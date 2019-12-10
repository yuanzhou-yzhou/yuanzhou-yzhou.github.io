---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can find my articles on my <u><a href="{{author.googlescholar}}">Google Scholar</a></u> or <u><a href="{{author.dblp}}">DBLP</a>.</u>

1. <span style="color:blue">Yuan Zhou</span>, Hesuan Hu, Yang Liu, Shang-Wei Lin, and Zuohua Ding, "**[A distributed method to avoid higher-order deadlocks in multi-robot systems](https://www.sciencedirect.com/science/article/pii/S0005109819305692)**." In *Automatica*, vol. 112, 2020. 


{% if author.googlescholar %}
  You can find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
{% if author.dblp %}
  You can also find my articles on <u><a href="{{author.dblp}}">my DBLP profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
