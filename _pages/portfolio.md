---
layout: archive
title: "Projects"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

{% for post in site.portfolio %}
  <div style="margin-bottom: 40px;">

    <img src="{{ post.image }}" style="width: 100%; max-width: 500px; border-radius: 8px;">

    <h2>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </h2>

    <p>{{ post.excerpt }}</p>

  </div>
{% endfor %}
