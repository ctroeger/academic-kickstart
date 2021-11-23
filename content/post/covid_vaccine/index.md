---
title: Estimating COVID-19 Vaccine Delivery
subtitle: A component of the IHME COVID-19 Projections

# Summary for listings and search engines
summary: COVID-19 vaccine delivery

# Link this post with a project
projects: []

# Date published
date: "2021-11-22T00:00:00Z"

# Date updated
lastmod: "2021-11-23T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: ''
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin

tags:
- COVID-19 Projections

categories:
- 
---

## [IHME COVID-19 Projections](https://covid19.healthdata.org/united-states-of-america?view=cumulative-deaths&tab=trend)

As part of the Institute for Health Metrics and Evaluation (IHME) COVID-19 Projections, I helped to develop a model for estimating
the scale-up of vaccine delivery. The model is a mixed-effects spline regression representing the time from the first COVID-19
vaccine doses delivered in a given country or state (United States) until all people who are willing to be vaccinated in that
location are vaccinated. The number of people who have received any vaccination are from [Our World in Data](https://ourworldindata.org/covid-vaccinations) and the number of people
who are willing to be vaccinated are from the [Facebook COVID-19 Trends and Impacts Survey](https://dataforgood.facebook.com/dfg/tools/covid-19-trends-and-impact-survey).
The results of this model are used in projecting the infections, hospitalizations, and deaths for the [IHME COVID-19 Projections SEIR model](http://www.healthdata.org/covid/faqs).

The figure above shows the number of days since the first COVID-19 vaccine doses were delivered until all people who
self-report willingness to be vaccinated have been vaccinated by location. High-income locations were included
as the model is intended to represent the scale-up without major supply constraints (the "expected" scale-up).
There is a clear sigmoid pattern where vaccinations are slow to scale up, rapidly reach many individuals at their peak rate, then slow down
as the vaccination campaigns make effort to reach all willing people who may not live in cities or have less
access or enthusiasm for vaccination. Rates are generally faster in the United States (many locations above the 
purple line) and a bit slower to start in Europe (many locations below the purple line). 

