# Recettes

{% for post in site.posts | sort: "title" %}
* [{{ post.title }}]({{site.baseurl}}{{ post.url }})
{% endfor %}
