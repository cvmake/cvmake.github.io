---
layout: page
cover: default.jpg
---

CVMake is a [Makerspace](/faq) in the Conejo Valley.  Our mission is to ..??

We serve the US-101 Tech Corridor, in easy reach for Calabasas, Simi Valley, Camirillo, etc.

The Conejo Vally includes Thousand Oaks, Newbury Park, Westlake Village, Oak Park and Agoura Hills.

# What is our mission?
ss
# What areas do we serve?
what cities inside conejo valley 101 tech corridor, calabass

# What is the meeting agenda?
agenda

<div class="home">
  <h1 class="page-heading">Recent Events</h1>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
      <h2>
          <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>
  <div class="colophon">
    <p>
      <p >subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>
    </p>
  </div>
</div>
