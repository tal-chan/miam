# Recettes


{% for post in site.posts %}
* [{{ post.title }}]({{site.baseurl}}{{ post.url }})
{% endfor %}

{% for tag in site.tags %}
## {{ tag[0] }}
{% for post in tag[1] %}
* [{{ post.title }}]({{site.baseurl}}{{ post.url }})
{% endfor %}

{% endfor %}
