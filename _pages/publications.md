---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  <p>
    TITLE={{ post.title }}<br>
    URL={{ post.permalink }}
  </p>
{% endfor %}
