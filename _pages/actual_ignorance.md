---
layout: single
permalink: /actual_ignorance/
---

<!-- Banner heading -->
<figure>
<center> <img src="../assets/images/ai_banner.png" width="800px" /> </center>
<figcaption> Very public learning about statistics, machine learning, epidemiology, and science in general.  </figcaption>
</figure>

<!-- Posts v2 (Manual for more control?) -->
<h2 id="covid header" class="archive__subtitle">COVID epidemiology</h2>
<h2 class="archive__item-title" itemprop="headline">
	<a href="https://arxiv.org/abs/2205.02150">Situational awareness as epidemiology's statistical mechanics</a>
</h2>
This preprint approaches COVID data from Washington with the goal of developing multi-scale connections similar to the connections between classical mechanics and thermodynamics. What that goal leads us to is both a COVID specific signal processing approach for building a transmission model and an equivalent branching process formulation of that same model. Check out this [twitter thread](https://twitter.com/famulare_mike/status/1523590361972584448?s=20&t=y2Iqd0wYqzx9V-Guu1-Dgg) from my coauthor, describing the work from a more epidemiological perspective. And if you want to see some code, here's the associated [github repo](https://github.com/NThakkar-IDM/covid_and_stat_mech). 

<h2 class="archive__item-title" itemprop="headline">
	<a href="https://iazpvnewgrp01.blob.core.windows.net/source/2021-02/reports/pdf/Towards_robust_real_time_high_resolution_COVID_19_prevalence_and_incidence_estimation.pdf">Working towards high resolution prevalence estimation</a>
</h2>
As we support Washington's pandemic response, I've been trying to add more detail to our prevalence and incidence estimates. In this report, we describe an approach that works in concert with our transmission model to estimate prevalence in sub-populations (like geographic regions or age groups). This method helps us better understand Washington's current COVID-19 situation while also helping us learn retrospectively about COVID-19 transmission across space and age.

<h2 class="archive__item-title" itemprop="headline">
	<a href="https://twitter.com/famulare_mike/status/1328858771733454850?s=20">Estimating gathering risk on Thanksgiving 2020</a>
</h2>
Our COVID transmission model can help us assess the risk of having a COVID positive individual in a random group, and it can help us project COVID burden under different transmission scenarios. I helped create this twitter thread demonstrating both of these use cases in advance of Thanksgiving to help communicate transmission risk.

<h2 class="archive__item-title" itemprop="headline">
	<a href="https://iazpvnewgrp01.blob.core.windows.net/source/2021-02/reports/pdf/One_state_many_outbreaks.pdf">Estimating COVID prevalence with transmission models</a>
</h2>
I helped create a modeling approach (that we call RAINIER, a lengthy backronym that you'll have to email me about) that allows us to quickly fit a compartmental transmission model to COVID-19 time series and age-distribution data. Some of this model's outputs now appear on [Washington's COVID-19 risk assessment dashboard](https://coronavirus.wa.gov/what-you-need-know/covid-19-risk-assessment-dashboard) and in Oregon's modeling reports ([like this one](https://www.oregon.gov/oha/PH/DISEASESCONDITIONS/DISEASESAZ/Emerging%20Respitory%20Infections/Oregon-COVID-19-Projections-2020-12-18.pdf)). 

<h2 class="archive__item-title" itemprop="headline">
	<a href="https://covid.idmod.org/#/SituationReports">Washington's COVID-19 situation reports</a>
</h2>
I've been supporting the Washington Department of Health, in collaboration with researchers from UW, the Hutch, and Microsoft, in their analysis of COVID-19 testing, hospitalization, and mortality data. This work leverages a combination of transmission model-based estimates with more direct data visualization. We reguraly publish our findings in short reports that are used to help inform Washington's pandemic response. 

<!-- measles Epi section -->
<h2 id="measles header" class="archive__subtitle">Measles epidemiology</h2>
<h2 class="archive__item-title" itemprop="headline">
	<a href="https://arxiv.org/abs/2202.11222">Measles case detection as a dynamic process</a>
</h2>
This preprint describes a method for estimating dynamic measles reporting rates using the age distribution of reported measles cases. In the paper, I apply the approach to data from the UK before and after universal healthcare, offering an interesting window into healthcare access changes. For some more perspective on the work, check out this [twitter thread](https://twitter.com/niket_h_thakkar/status/1496916839321915410?s=20&t=lh9qDHOlYc55YfQ2kR9UwA). And if you want to work with the model itself, here's a [github repo](https://github.com/NThakkar-IDM/uk_measles_surveillance). 

<h2 class="archive__item-title" itemprop="headline">
	<a href="https://www.gatesfoundation.org/goalkeepers/report/2020-report/#GlobalPerspective">Measles in the time of COVID-19</a>
</h2>
COVID-19 added complexity to decision-making around Ethiopia's March 2020 measles vaccination campaign. I used an updated version of our [time series model for measles](https://www.pnas.org/content/116/22/11069) to forecast different delayed campaign scenarios, which helped motivate stakeholders to move forward with the vaccination campaign in July despite the added risk of COVID-19 transmission. The overall results of this collaboration with other measles modeling groups are nicely summarized in the first inset of 2020's [Goalkeepers](https://www.gatesfoundation.org/goalkeepers/) report.

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

