---
layout: blog
title: Home
section: Home
---

Thoughts on Open Data Science
==========================================

This is my personal blog on data science and open knowledge. You can find more information about me [here](../info).

Topics of the blog include data science, open data, R, machine learning, statistics, information visualization, my data and open science. 

<!--
More [information](info.html) about this blog and a complete archive of [past](past.html) posts, are available via links at the top of the page.
-->
<a href="/blog/atom.xml"><img src="/images/rss.png" alt="Atom Feed" style="height: 2em; margin-right:2.5em;" class="right"/></a>

Recent Posts
------------

{% for post in site.categories.blog limit:5 %}
<div class="section list">
  <h1>{{ post.date | date_to_string }}</h1>
  <p class="line">
  <a class="title" href="{{ post.url }}">{{ post.title }}</a>
  <a class="comments" href="{{ post.url }}#disqus_thread">View Comments</a>
  </p>
  <p class="excerpt">{{ post.excerpt }}</p>

</div>
{% endfor %}

<p>
<a href="past.html">Older Posts &rarr;</a>
</p>


You can also subscribe to an [RSS feed][] of the most recent posts.

Check out [R-bloggers] for interesting blogs related to the R language. I will add a list of other interesting blogs later.

[RSS feed]: /blog/atom.xml
[R-bloggers]: http://www.r-bloggers.com/


<!-- Add DISQUS stuff from mark/iem/index.markdown -->
