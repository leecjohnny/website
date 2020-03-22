---
title: "COVID-19 Data Exploration"
date: 2020-03-22
tags: ["r", "tidyverse", "covid-19", "coronavirus", "ggplot"]
draft: false
---

## Help prevent the spread of COVID-19

The COVID-19 disease caused by the SARS-CoV-2 virus is a global humanitarian challenge.

* Please help flatten the curve by [doing the five](https://www.google.com/search?q=coronavirus+tips&fbx=dothefive).
* Follow your local public health guidelines at the [CDC](https://www.cdc.gov/coronavirus/2019-ncov/index.html).
* Stay informed at [Google's](http://google.com/covid19) information hub.

## Situation in the United States

As an attempt to understand the trends of the virus so far, I have aggregated some public available data and visualized their general trends.

A few days before February 26, when the CDC confirmed the first [possible case of community spread](https://www.cdc.gov/media/releases/2020/s0226-Covid-19-spread.html), the number of confirmed cases spiked and started an exponential increase.

This is very clear when viewing the cumulative number of cases on a log scale (see plots below). On the normal scale, it is hidden by the recent exponential increases.

Fortunately, the level of testing has also started to catch up to the exponential growth in cases (as seen in the purple lines below). Roughly 14% of tested individuals have had a positive result so far.

In California, only 12,528 tests have been administered. At a population of roughly 39.5 million people, for every million residents, only 317 individuals have been tested.

*([Github](https://github.com/leecjohnny/covid-19) source code. All statistics as of March 21, 2020.*)


### To be continued ...


---

## Plots

#### Total US Cases (log scale)
![Log scale of total US cases](/images/total_us_cases_log_scale_2020-03-21.png)

#### Total US Cases (normal scale)
![Normal scale of total US cases](/images/total_us_cases_2020-03-21.png)

#### Total California Cases
![Normal scale of total CA cases](/images/total_california_cases_2020-03-21.png)

