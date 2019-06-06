---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

For a full publication list, see [this link](http://inspirehep.net/search?ln=en&p=find+a+J.+D.+Osborn&of=hb&action_search=Search&sf=earliestdate&so=d)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
