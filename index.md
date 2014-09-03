---
layout: page
title: Home
tagline: A programmer's thought
---
{% include JB/setup %}

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Links

* [Semver](http://semver.org/)
* [JekyllBootstrap](http://jekyllbootstrap.com/)
