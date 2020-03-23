---
title: "COVID-19 Data Exploration"
date: 2020-03-22
tags: ["r", "tidyverse", "covid-19", "coronavirus", "ggplot"]
draft: false
---

## Help prevent the spread of COVID-19

The COVID-19 (2019 coronavirus disease) pandemic caused by the SARS-CoV-2 (severe acute respiratory syndrome coronavirus 2) is a global health and humanitarian challenge.

* Please help flatten the curve by [doing the five](https://www.google.com/search?q=coronavirus+tips&fbx=dothefive).
* Follow public health guidelines at the [CDC](https://www.cdc.gov/coronavirus/2019-ncov/index.html) and your local public health authorities.
* Stay informed on the disease's progression at [Google's](http://google.com/covid19) COVID-19 information hub.

## Situation in the US

In trying to understand the basic trends of the virus in the US, I have aggregated some publicly available data and visualized their  trends.

A few days before February 26, the day when the CDC confirmed the first possible case of [community spread](https://www.cdc.gov/media/releases/2020/s0226-Covid-19-spread.html), the number of confirmed cases spiked and started an exponential increase.

When viewing the cumulative number of cases on a log scale, you can easily see the spike and change in progression around February 23-24. On the normal scale, it is hidden by more recent exponential increases.

Fortunately, the level of testing has began to catch up to the exponential growth in cases (as seen in the purple lines below). Roughly 14% of tested individuals have had a positive result.

In California, only 12,840 tests results have returned from the labs, with thousands more tests pending. At a population of roughly 39.5 million people, for every million residents, only 325 individuals have been tested.

*([Github](https://github.com/leecjohnny/covid-19) source code. All statistics as of March 22, 2020. Sources: JHU, COVID Tracking Project*)


### To be continued ...


---

## Plots

#### Total US Cases (log scale)
![Log scale of total US cases](/images/total_us_cases_log_scale_2020-03-22.png)

#### Total US Cases (normal scale)
![Normal scale of total US cases](/images/total_us_cases_2020-03-22.png)

#### Total California Cases
![Normal scale of total CA cases](/images/total_california_cases_2020-03-22.png)

