---
layout: page
<<<<<<< HEAD
title: Upcoming Events
excerpt: "List of events."
image:
  feature: banner3.png
  credit: WeGraphics
=======
title: Blog
excerpt: "An archive of blog posts sorted by date."
>>>>>>> FETCH_HEAD
search_omit: true
---

Check here regularly for up-to-date information about talks, programs, and workshops.

<ul class="post-list">
{% for post in site.categories.blog %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
