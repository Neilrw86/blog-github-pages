{% assign sorted_posts = site.posts | sort: 'date' | reverse %}
{% for post in sorted_posts limit:1 %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}