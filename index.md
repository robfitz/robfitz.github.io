---

layout: home
permalink: /
redirect_from:
  - /articles
  - /articles/

---

# Toward entrepre&shy;neurial thinking and living
by <a href="/about/">Rob Fitzpatrick</a>

{% if site.categories['learn'] %}
## Knowledge

{% for post in site.categories['learn'] limit:10 %}

  <p class="col{{ colvar | modulo: 5 }}">
  <a href='{{ post.url }}' class='article'>{{ post.title }}</a>
  </p>
  {% capture _ %}{% increment colvar %}{% endcapture %}
{% endfor %}
{% endif %}

## Perspective

{% for post in site.categories['articles'] limit:10 %}

  <p class="col{{ colvar | modulo: 5 }}">
  <a href='{{ post.url }}' class='article'>{{ post.title }}</a>
  </p>

  {% capture _ %}{% increment colvar %}{% endcapture %}

{% endfor %}

## My books

<p class="col{{ colvar | modulo: 5 }}">
<a href="http://geni.us/momtest" class="book"><strong>The Mom Test</strong>: How to talk to customers and figure out if your business is a good idea when everyone is lying to you</a></p>

{% capture _ %}{% increment colvar %}{% endcapture %}

<p class="col{{ colvar | modulo: 5 }}">  
<a href="https://geni.us/workshopsurvival" class="book"><strong>The Workshop Survival Guide</strong>: How to design and run educational workshops that work every time</a>
</p>

{% capture _ %}{% increment colvar %}{% endcapture %}

<p class="col{{ colvar | modulo: 5 }}">  
<a href="https://writeusefulbooks.com" class="book"><strong>Write Useful Books</strong>: A modern approach to designing and refining recommendable nonfiction (Early Access)</a>
</p>

{% capture _ %}{% increment colvar %}{% endcapture %}
