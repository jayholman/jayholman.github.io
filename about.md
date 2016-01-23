---
layout: page
title: About
permalink: /about/
---
So you'd like to learn more about jayholman.xyz. Well, this is probably the worst
page for that! You should go to the other sections to see what it's all about. But,
if you insist, this is my website that I'm mostly using to learn on. I'll practice
constructing it in different ways and trying unique things. There will probably
be lots of weird video embeds and tests, but it's also all about adventure.
I'll add sections and create more posts about things I like doing. I've even put
useful categories up top that will split the posts up, but, conveniently, you can
also access all the posts on this page!

<div class="home">

  <h1 class="page-heading">The Most Recent Posts</h1>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>

        <a class="post-meta" href="{{ post.url | prepend: site.baseurl }}">{{post.thumbnail}}</a>
      </li>
    {% endfor %}
  </ul>

</div>
