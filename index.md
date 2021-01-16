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

## Articles

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

## Selected videos

### Mom Test Q&A
<iframe width="560" height="224" src="https://www.youtube.com/embed/videoseries?list=PLvHabB7atz2tOjQs1OMzjaDPziat0aVry" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="224" src="https://www.youtube.com/embed/FrQRH2gxgWo?start=8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Chit-chat

<iframe width="560" height="224" src="https://www.youtube.com/embed/gbneoAPOVvg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="224" src="https://www.youtube.com/embed/_CmDj-Ry_-I" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Talks

<iframe width="560" height="224" src="https://www.youtube.com/embed/O_xjb7LB7VY?start=8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="224" src="https://www.youtube.com/embed/FG1Fa-t4AEQ?start=24" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

With plenty more on [my YouTube channel](https://www.youtube.com/c/robfitzpatrick). Also happy to do the occasional [interview or talk](/about/#teaching).