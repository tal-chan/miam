# Index

{% assign posts = site.posts | sort: "title" %}
{% for post in posts %}
* [{{ post.title }}]({{site.baseurl}}{{ post.url }})
{% endfor %}
