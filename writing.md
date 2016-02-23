---
layout: page
title: Writing
permalink: /writing/
---

<h1 class="page-heading">Posts</h1>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
	<h4>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h4>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>        
      </li>
    {% endfor %}
  </ul>
