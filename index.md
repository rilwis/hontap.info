---
layout: home
---

<ul class="posts">
	{% for post in site.posts %}
		<li>
			<a href="{{ post.url }}">{{ post.title }}</a>
			<time>{{ page.date | date: "%d/%m/%y" }}</time>
		</li>
	{% endfor %}
</ul>
