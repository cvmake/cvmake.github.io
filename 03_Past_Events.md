---
layout: page
title: Past Events
permalink: /past
cover: DigisparkDark.jpg

---

<div class="posts">
  <ul class="posts-list">
    {% for post in site.posts %}
      <li class="post-link">
        <a class="post-title" href="{{ post.url }}">
          {{ post.title }}
          <span class="post-date">{{ post.date | date_to_string }}</span>
        </a>
      </li>
    {% endfor %}
  </ul>
</div>
