---
---
Hi, I'm Jelle. I work as a data engineer. This is where I write things down.

## Posts

<ul class="posts">
{% for post in site.posts %}
  <li><time>{{ post.date | date: "%Y-%m-%d" }}</time><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
