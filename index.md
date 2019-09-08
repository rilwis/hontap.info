---
layout: home
---

<ul class="posts">
	{% for post in site.posts %}
		<li>
			<a href="{{ post.url | relative_url }}">{{ post.title }}</a>
			<time>{{ post.date | date: "%d/%m/%y" }}</time>
		</li>
	{% endfor %}
</ul>
