---
layout: page
permalink: /dd_fireside
title: Drug Discovery Fireside Chats
nav: true
nav_order: 2
---

How are new therapeutics developed? What are the bottlenecks at the various stages in the process? And what is the role that machine learning can play in addressing these challenges? Given the recent interest in applying AI to drug discovery, it is critical for ML researchers to answer these questions. This webinar series aims to connect ML researchers with people with first-hand experience developing new drugs.

Each event is a casual discussion with different veterans of the drug discovery process. They are scheduled on an ad-hoc basis; I aim to schedule one every couple of months. To receive updates, please join the <a href="https://mailchi.mp/d71d31b07ac8/drug-discovery-fireside-chats">mailing list</a>. Details about future chats can be found below and on the <a href="https://calendar.google.com/calendar/embed?src=2c5a3a0d21e84619a66c9df4fc1b7cba62b5d1acc13db8b175611dcbd953ea15%40group.calendar.google.com&ctz=America%2FNew_York">Google calendar</a>.


<div class="post">

  <h2 class="chat-overtitle" style="margin-bottom: -0.5em;">Past events</h2>

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
