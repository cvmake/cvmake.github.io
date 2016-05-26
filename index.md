---
layout: page
cover: default.jpg
---
# What is a MakerSpace? What is a Maker

Makerspaces (A.K.A hackerspaces, hackspaces, fablabs) encourage people to learn to create via personal and group projects. To complete a project, participants learn new things from many different disciplines: Crafts, Robotics, Soldering, Electronics, Programming. Almost every project will involve all aspects of STEAM (Science, Technology, Engineering, Arts, Math). Learning is informal, demand-driven, person-to-person, where people teach what they know, and learn what they don’t.

Makerspaces are usually open 24x7 so members can work on projects during their spare time. Makerspaces fund rent and equipment via member fees, classes, and donations. This equipment and space attracts members. Makerspaces also have “open house” nights where the community can come to learn and get advice. (This also serves as marketing to find new members.)

Makers are a community of people sharing and learning in the context of building things. When people build things for themselves, plucked out of their imaginations, they are more receptive to learning new skills to accomplish their goals. Most projects have an artistic and creative side, but also technical aspects. Every project involves skills in multiple disciplines (electronics, materials, crafting, robotics, soldering, 3d printing, programming, etc).

Anyone can be a maker: engineers, kids, artists, students, entrepreneurs, housewives, etc.  All it takes is a drive to turn your ideas into real things. When a Maker gets stuck, the Maker community helps out: They an be a source of ideas, creative work-arounds and resources for learning or getting something done. Makers constantly share what they know and encourage learning and teaching in both formal and informal settings.

# What is our mission?
ss
# What areas do we serve?
what cities inside conejo valley 101 tech corridor, calabass

# What is the meeting agenda?
agenda

<div class="home">
  <h1 class="page-heading">Posts</h1>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
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
