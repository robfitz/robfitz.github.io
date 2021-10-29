---

layout: home
permalink: /
redirect_from:
  - /articles
  - /articles/

---

<h1>Understand your customers.<br/>Build desirable products.<br/>Write useful books.</h1>
by <a href="/about/">Rob Fitzpatrick</a>

<p>&nbsp;</p>

<img class='banner-img' src='img\rob-fitzpatrick-write-useful-books.jpg' />

Heya. I've been running little businesses for the past fourteen years and have written three books about what I've learned.

If you'd like to stay in the loop about my projects and thinking, the best place is [my youtube channel](https://www.youtube.com/c/robfitzpatrick). Alternatively, you can also [receive an occasional email](/subscribe) when I've got something worth sharing.

My next decade is devoted to serving indie nonfiction authors via a [handbook](https://geni.us/useful), better [tools for beta reading](https://helpthisbook.com), a [nonfiction authors' community](https://writeusefulbooks.com/community/), and more. If you've ever wanted to write nonfiction that works for your readers and succeeds for you, then [join us](https://writeusefulbooks.com/community/).

I live in a teensy tiny mountain village in upper Catalonia [📷](https://www.instagram.com/robfitzpatrick/)

## My books

{% capture _ %}{% increment colvar %}{% endcapture %}

<div class='row covers3d'>
  {% capture _ %}{% increment colvar %}{% endcapture %}
  <a class='cover3d col{{ colvar | modulo: 5 }}' href='http://geni.us/useful' style="background-image:url('/img/write-useful-books-cover.png')">
  </a>
  {% capture _ %}{% increment colvar %}{% endcapture %}
  <a class='cover3d col{{ colvar | modulo: 5 }}' href='http://geni.us/momtest' style="background-image:url('/img/the-mom-test-cover.png')">
  </a>
  {% capture _ %}{% increment colvar %}{% endcapture %}
  <a class='cover3d col{{ colvar | modulo: 5 }}' href='http://geni.us/workshopsurvival' style="background-image:url('/img/workshop-survival-guide-cover.png')">
  </a>
</div>

{% capture _ %}{% increment colvar %}{% increment colvar %}{% increment colvar %}{% endcapture %}

<p class="col{{ colvar | modulo: 5 }}">  
<a href="https://writeusefulbooks.com" class="book"><strong>Write Useful Books</strong>: A modern approach to designing & refining recommendable nonfiction</a>
</p>

{% capture _ %}{% increment colvar %}{% endcapture %}
<p class="col{{ colvar | modulo: 5 }}">
<a href="http://geni.us/momtest" class="book"><strong>The Mom Test</strong>: How to talk to customers and figure out if your business is a good idea when everyone is lying to you</a></p>

{% capture _ %}{% increment colvar %}{% endcapture %}

<p class="col{{ colvar | modulo: 5 }}">  
<a href="https://geni.us/workshopsurvival" class="book"><strong>The Workshop Survival Guide</strong>: How to design & run educational workshops that work every time</a>
</p>

{% capture _ %}{% increment colvar %}{% endcapture %}


{% if site.categories['learn'] %}

## Knowledge

{% for post in site.categories['learn'] limit:10 %}

  <p class="col{{ colvar | modulo: 5 }}">
  <a href='{{ post.url }}' class='article'>{{ post.title }}</a>
  </p>
  {% capture _ %}{% increment colvar %}{% endcapture %}
{% endfor %}
{% endif %}

## Essays

{% for post in site.categories['articles'] limit:10 %}

  <p class="col{{ colvar | modulo: 5 }}">
  <a href='{{ post.url }}' class='article'>{{ post.title }}</a>
  </p>

  {% capture _ %}{% increment colvar %}{% endcapture %}

{% endfor %}

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