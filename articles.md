---

layout: home
---

# Tools for entrepreneurial thinking and living



## Articles

{% for post in site.posts limit:10 %}
  <a href='{{ post.url }}' class='article'>{{ post.title }}</a>
{% endfor %}