---
layout: archive
title: "Projects"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px;">

{% for post in site.portfolio %}
  <div class="grid-card" style="border: 1px solid #e5e5e5; border-radius: 10px; padding: 15px;">

    <img src="{{ post.image }}" style="width: 100%; height: 200px; object-fit: cover; border-radius: 8px;">

    <h2 style="margin-top: 15px;">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </h2>

    <p>{{ post.excerpt }}</p>

  </div>
{% endfor %}

</div>
