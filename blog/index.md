---
layout: page
title: Upcoming Events
excerpt: "List of events."
image:
  feature: banner3.png
  credit: WeGraphics
search_omit: true
---

Check here regularly for up-to-date information about talks, programs, and workshops. Do not forget to check out the calendar below. <i class="fa fa-hand-o-down fa-lg"></i>

<br/>

<ul class="post-list">
{% for post in site.categories.blog %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>

<br/>

<iframe src="https://www.google.com/calendar/embed?height=600&amp;wkst=1&amp;bgcolor=%23FFFFFF&amp;src=siam.iisc%40gmail.com&amp;color=%232952A3&amp;ctz=Asia%2FCalcutta" style=" border-width:0 " width="800" height="600" frameborder="0" scrolling="no"></iframe>