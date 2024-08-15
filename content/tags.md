---
layout: page
permalink: /s/tags/
title: Tags
---

<div id="archives">
  {% for tag in site.tags %}
    <div class="archive-group">
      {% capture tag_name %}{{ tag | first }}{% endcapture %}
      <div id="#{{ tag_name | slugize }}"></div>
      <a name="{{ tag_name | slugize }}"></a>
      <h3 class="tag-head">{{ tag_name }}</h3>
      {% for post in site.tags[tag_name] %}
      <article class="archive-item">
        <p>
            <a href="{{ post.url }}">{{post.title}}</a>
        </p>
      </article>
      {% endfor %}
    </div>
  {% endfor %}
</div>