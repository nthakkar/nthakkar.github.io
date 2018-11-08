---
layout: single
permalink: /actual_ignorance/
---

<!-- Banner heading -->
<figure>
<center> <img src="../assets/images/ai_banner.png" width="800px" /> </center>
<figcaption> Very public learning about statistics, machine learning, and artificial intelligence.  </figcaption>
</figure>

<!-- Posts -->
{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
{% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
{% if year != written_year %}
<h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
{% capture written_year %}{{ year }}{% endcapture %}
{% endif %}
{% include archive-single.html %}
{% endfor %}