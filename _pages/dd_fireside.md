---
layout: page
permalink: /dd_fireside
title: Drug Discovery Fireside Chats
nav: true
nav_order: 2
---

<div class="post">

  <ul class="post-list">
    {% for chat in site.chats %}

    <li>
        <h3>
          <a class="post-title" href="{{ chat.url | relative_url }}">{{ chat.title }}</a>
        </h3>
      <!-- <p>{{ chat.description }}</p> -->
      <p class="post-meta">
        {{ chat.zoom_date | date: '%B %-d, %Y' }}
      </p>
    </li>

    {% endfor %}
  </ul>

</div>
