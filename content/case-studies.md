---
layout: page
permalink: /s/case-studies/
title: Case Studies
tag_name: "Case study"
---

<div id="archives">
    <div class="archive-group">
      {% for post in site.tags[page.tag_name] %}
      <article class="archive-item">
        <p>
            <a href="{{ post.url }}">{{post.title}}</a>
        </p>
      </article>
      {% endfor %}
    </div>
</div>