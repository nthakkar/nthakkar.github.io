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

<!-- Epi section -->
<h2 id="epi header" class="archive__subtitle">Epidemiology</h2>
<h2 class="archive__item-title" itemprop="headline">
	<a href="https://www.pnas.org/content/116/22/11069">Decreasing measles burden by optimizing campaign timing</a>
</h2>
This paper describes a predictive measles time series model and shows how it can be used to forecast policy outcomes to optimize our measles vaccination strategy in Pakistan. This collaboration with the World Health Organization, the Gates Foundation, and researchers in Pakistan helped motivate a large-scale vaccination campaign that happened in October 2018. 

<h2 class="archive__item-title" itemprop="headline">
	<a href="https://nthakkar.github.io/assets/docs/comment_immuneshadow.pdf">Are there issues with the ecological evidence for measles-induced, long-term immune suppression? [preprint]</a>
</h2>
I was asked by colleagues at [IDM](http://idmod.org) and the Gates Foundation to take a close look at [this paper](http://science.sciencemag.org/content/348/6235/694) which argues that measles infection causes immune system suppression lasting 2 to 3 years, much longer than previously thought. I found some mathematical issues, summarized in this comment ([now published](https://science.sciencemag.org/content/365/6449/eaax5552.abstract)).


<!-- Stats and bball section -->
<h2 id="basketball header" class="archive__subtitle">Basketball</h2>
<h2 class="archive__item-title" itemprop="headline">
	<a href="https://nthakkar.github.io/state_space/" rel="permalink">Predicting scores with state space models</a>
</h2>
This post is still under construction.

<h2 class="archive__item-title" itemprop="headline">
	<a href="https://nthakkar.github.io/bballref/" rel="permalink">Scraping data off of basketball reference</a>
</h2>
I've been (sorta) joking a lot about how [IDM](http://idmod.org) should use its new hardware for sports gambling. That (sorta) joke got taken a little further recently: I used [PyQuery](https://pythonhosted.org/pyquery/) to write a web scraper for [basketball-reference.com](https://www.basketball-reference.com/). My fantasy team still sucks this year (seriously, really bad), but this turned into a learning experience that's given me some interesting data so I thought I'd share.

