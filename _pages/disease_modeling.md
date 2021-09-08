---
layout: single
site.title: #My research
permalink: /disease_modeling/
---
<!-- Alternative to the header image above --> 
<figure>
<center> <img src="../assets/images/measles_time_to_rash.png" width="1200px" /> </center>
<figcaption>Combining epidemiological and statistical principles, in this case to estimate that it takes about 15 days for a rash to show up after you're exposed to measles.</figcaption>
</figure>

My work at [IDM](http://idmod.org) focuses on combining ideas from probability theory and statistics with classical epidemiology to better understand disease transmission, generally in the measles and COVID contexts. Being at the [Gates Foundation](https://www.gatesfoundation.org/), I’ve placed particular emphasis on scientific communication and advocacy for informed decision-making, and I try hard to align the mathematical side of my research program with open questions in vaccine delivery and public health policy.

On this page I try to give a general overview of my work at [IDM](http://idmod.org) and where I think it's headed. If you're looking for some specific disease modeling projects, check out the epidemiology sections of [actual ignorance](https://nthakkar.github.io/actual_ignorance/). For a more comprehensive look at my work, see my [Google Scholar profile](https://scholar.google.com/citations?user=4XfFTrEAAAAJ&hl=en&oi=ao) or my [CV](../assets/docs/CV.pdf). 

The math and methods perspective
--------------------------------------------
<center> <img src="../assets/images/cartoon_tree.png" width="600px" /> </center>

Speaking as a mathematician, I work on inference and uncertainty quantification in the context of imperfectly observed stochastic processes like disease transmission. Over the last few year, I’ve been developing inference algorithms leveraging classical, nonlinear epidemiological models to estimate disease prevalence, population immunity, transmission rates, and predictive risk with high spatial, temporal, and demographic resolution. 
<ul>
  <li>One thing I enjoy about these problems is that they involve working with a large variety of data types, including time series, satellite imagery, demographic and serological survey, randomized-control-trial data, and geographic-information-systems data.</li>
  <li>I've found that algorithm speed is critical to supporting global health since high-performance computing resources aren't available in most places. Towards that goal, I focus on deterministic and approximate approaches, and most models I've developed can go from raw data to estimates in seconds on a laptop.</li>
  <li>A key feature of transmission systems is their inherent volatility, and accurately quantifying uncertainty is a (mostly fun) mathematical challenge. Lately, I've been interested in better understanding what the level of uncertainty can teach us about the transmission process, leveraging ideas from statistical physics.</li>
</ul>

The policy and advocacy perspective
--------------------------------------------
<center> <img src="../assets/images/prediction_test.png" width="800px" /> </center>

While I think about the math most days, my broader goal is to create tools that help health-care workers deliver vaccines and other treatments. 
<ul>
  <li>In some cases, like in measles vaccine delivery, this is a predictive modeling problem since we want to vaccinate in advance of outbreaks. As a result, my measles work has largely focused on forecasting.</li>
  <li>In other contexts, like COVID, mitigation policy needs to be informed by good situational awareness. In this case, my work has focused mainly on descriptive modeling and inference, creating high-resolution estimates of transmission rates and prevalence to give balanced perspective on multiple data sources.</li>
  <li>In general, decision-making and health-care delivery require a massive collaboration. I create estimates and forecasts to help inform broader conversations that include equally important cultural, historical, and economic considerations.</li>
</ul>
