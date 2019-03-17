---

layout: home
permalink: /
redirect_from:
  - /articles
  - /articles/

---

# For entrepreneurial thinking and living

{% if site.categories['learn'] %}
## Deep knowledge

{% for post in site.categories['learn'] limit:10 %}

  <p class="col{{ colvar | modulo: 5 }}">
  <a href='{{ post.url }}' class='article'>{{ post.title }}</a>
  </p>
  {% capture _ %}{% increment colvar %}{% endcapture %}
{% endfor %}
{% endif %}

## Articles

{% for post in site.categories['articles'] limit:10 %}

  <p class="col{{ colvar | modulo: 5 }}">
  <a href='{{ post.url }}' class='article'>{{ post.title }}</a>
  </p>

  {% capture _ %}{% increment colvar %}{% endcapture %}

{% endfor %}

## My books

<p class="col{{ colvar | modulo: 5 }}">
<a href="http://geni.us/momtest" target="_blank" class="book"><strong>The Mom Test</strong>: how to talk to customers and figure out if your business is a good idea when everyone is lying to you</a></p>

{% capture _ %}{% increment colvar %}{% endcapture %}

<p class="col{{ colvar | modulo: 5 }}">  
<a href="http://workshopsurvival.com" target="_blank" class="book"><strong>The Workshop Survival Guide</strong>: how to design and run educational workshops that work every time</a>
</p>

{% capture _ %}{% increment colvar %}{% endcapture %}
