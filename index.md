---

layout: home
redirect_from:
  - /articles
  - /articles/
  
---

# Tools for entrepreneurial thinking and living

## Articles

{% for post in site.posts limit:10 %}
  <a href='{{ post.url }}' class='article'>{{ post.title }}</a>
{% endfor %}

<hr/>

## My books

<a href="http://geni.us/momtest" target="_blank" class="book"><u>The Mom Test</u>: how to talk to customers and figure out if your business is a good idea when everyone is lying to you</a>

<a href="http://workshopsurvival.com" target="_blank" class="book"><u>The Workshop Survival Guide</u>: how to design and run educational workshops that work every time</a>