---
layout: page
cover: Learn.jpg
---

CVMake is a [Makerspace](/faq) in the Conejo Valley.  Our mission is to ..??

# Who

A Makerspace is a place where [Makers](/faq) can get together and help each other create interesting projects.

# What



# Where


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
