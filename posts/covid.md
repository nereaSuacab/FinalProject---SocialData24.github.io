---
title: "COVID-19"
date: 2024-05-01
author: Your Name
tags: [tag1, tag2, tag3]
---

<!-- Back button -->
<button onclick="goBack()">Back</button>
<script>
function goBack() {
  window.history.back();
}
</script>

# COVID-19

In late 2019, a new coronavirus, COVID-19, surfaced in Wuhan, China, rapidly evolving into a global pandemic. The rapid spread of the virus triggered unprecedented global reactions, leading to implementation of lockdowns, travel bans, and social distancing mandates. As a consequence, the aviation industry faced challenges since travel restrictions and plummeting demand led to a sharp decline in flights. Therefore, SFO felt the impact as passenger volumes dwindled, airlines canceled routes and stringtent health protocols were implemented. In this section, these consequences are studied through different visualizations.

## Temporal analysis

As it could have been seen in the [Trends Over Time](/temporalEvolution.md), the number of passengers in SFO had a sharp decreased in 2020 due to COVID. This fact affected the three different types of passengers. To better understand this fact, a stacked bar plots of all the month in the Covid-19 year and the previous and following year were generated to compare these values.

<iframe src="images/2019-2021_passengers_type_monthly.html" width="100%" height="630px"></iframe>
<p style="text-align:center; font-size:small;"><strong>Figure 1:</strong> <em>Monthly evolution of the passenger counts between the years 2019 and 2021</em></p>

The distribution of the passengers in 2019 is the typical one that follows the seasonal patterns. This means that in the summer months, the amount of travelers increases because of the holiday and the good weather. As it was explained at the beginning, Covid-19 appeared at the end of 2019, however, until March of 2020 it din't become real. At that moment, there is a noticeable fall in the number of people traveling but it is not until April when the lowest peak appeared. This fact could have been caused because in March, some people were still traveling to go back to their homes because of the different added restrictions. For this reason, in April everyone was already locked and almost anyone traveled around the world, including to or from San Francisco.

From April 2020 on, it can be seen a slow rise of the number of passengers that stepped SFO. However, it is not until one year after this event that the amount of travelers is above 1.0e6. Even though it was increasing while the Covid situation was being managed and solved, comparing the graphs from 2019 and 2021, there is still a clear difference with the number of passengers. So, the same bar plot was generated from the year 2022 to analyze if the passenger count continue to increase.

<div style="display: flex; justify-content: center;">
    <iframe src="images/2022_passengers_type_monthly.html" width="75%" height="620px"></iframe>
</div>

<p style="text-align:center; font-size:small;"><strong>Figure 2:</strong> <em>Monthly evolution of the passenger counts in 2022</em></p>

We can observe that even though the amount of passengers achieved before the arrival of Covid-19 is not reached, it increased noticeable during the year 2022. So, observing the line graphs from the [Trends Over Time](/temporalEvolution.md), we can conclude that, even though the amount of travelers increased a lot after 2020, we are still recovering from the consequences that Covid-19 gave and some years are still missing to achieve the peak reached in 2018. 

# Geographical Analysis
As it has been explained in [Geographical Distribution of Passenger Traffic](passengerStudy.md), COVID-19 is one of the historical facts we can see by taking a quick look at the visualizations.

Figure 3 provides an overview of the effects of the pandemic, particularly in terms of the implementation of travel restrictions in the different regions. In particular, Europe experienced a sharp decline in flight volumes, reflecting the severity of the impact of the virus on the continent.

Regions such as Asia, Europe and Canada maintained lower flight volumes even as restrictions were eased, reflecting continued caution and compliance with security protocols. This caution was likely due to concerns about the possible resurgence of the virus and the emergence of new variants.

In contrast, regions such as the US, Mexico and the Middle East experienced a gradual upturn in aviation activity from 2021 onwards. This resurgence can be attributed to several factors, including the success of vaccination campaigns, the gradual relaxation of travel restrictions and the pent-up demand for travel after long periods of blockades and restrictions.

<iframe src="images/area_covid.html" width="100%" height="640px"></iframe>
<p style="text-align:center; font-size:small;"><strong>Figure 3:</strong> <em>Yearly evolition of Regions form 2019 until 2023</em></p>

<!-- Back button -->
<button onclick="goBack()">Back</button>
<script>
function goBack() {
  window.history.back();
}
</script>