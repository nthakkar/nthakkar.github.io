---
layout: single
permalink: /actual_ignorance/
---

<!-- Banner heading -->
<figure>
<center> <img src="../assets/images/ai_banner.png" width="800px" /> </center>
<figcaption> Very public learning about statistics, machine learning, and artificial intelligence.  </figcaption>
</figure>

<!-- Posts 
{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
{% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
{% if year != written_year %}
<h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
{% capture written_year %}{{ year }}{% endcapture %}
{% endif %}
{% include archive-single.html %}
{% endfor %} -->

<!-- Posts v2 (Manual for more control?) -->

<!-- Stats and bball section -->
<h2 id="basketball header" class="archive__subtitle">Basketball</h2>
<h2 class="archive__item-title" itemprop="headline">
	<a href="https://nthakkar.github.io/state_space/" rel="permalink">Predicting scores with state space models</a>
</h2>
This post is still under construction.

<h2 class="archive__item-title" itemprop="headline">
	<a href="https://nthakkar.github.io/bballref/" rel="permalink">Scraping data off of basketball reference</a>
</h2>
I've been (half-)joking a lot about how [IDM](http://idmod.org) should use its new hardware for sports gambling. That (half-)joke got taken a little further recently: I used [PyQuery](https://pythonhosted.org/pyquery/) to write a web scraper for [basketball-reference.com](https://www.basketball-reference.com/). My fantasy team still sucks this year (seriously, really bad), but this turned into a cool learning experience that's given me some interesting data.

