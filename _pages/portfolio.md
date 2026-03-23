---
layout: archive
title: "Projects"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

<div class="grid__wrapper">
{% for post in site.portfolio %}
  <div class="grid__item">
    <article class="archive__item">
      
      <div class="archive__item-teaser">
        <img src="{{ post.image }}" alt="">
      </div>

      <h2 class="archive__item-title">
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </h2>

      <p>{{ post.excerpt }}</p>

    </article>
  </div>
{% endfor %}
</div>
