---
title: "Geographical Distribution of Passenger Traffic"
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

# General Analysis

The San Francisco International Airport (SFO) is one of the busiest and most iconinc airports in the United States.

In understanding the evolution of SFO, one cannot overlook the pivotal role of geographical factors. The airport's strategic location on the western coast of the United States places it at the nexus of domestic and international air travel routes as we can see in Figure 1.

![Alt text](images/type_flight.png)
<p style="text-align:center; font-size:small;"><strong>Figure 1:</strong> <em>Percentage of International and National flights in SFO</em></p>

Through the Geo Region of the flights we can understand the airport's changing significance in global air transportation networks.

The GEO Region Provides a more detailed breakdown of the GEO Summary field to designate the region in the world where activity in relation to SFO arrived from or departed to without stops

## Mapping Flight Destinations

In the Figure 2 bar plot, we observe the distribution of flights across various regions analyzed. Notably, the United States emerges as the region with the highest volume of flights, exceeding 12,000 over the past 25 years. Following closely is Asia, with Europe ranking third.

Despite geographical proximity potentially suggesting South America to have a higher volume of flights compared to Europe, intricate international relationships between countries reveal the opposite trend.

<iframe src="images/air_traffic_by_continent.html" width="100%" height="500px"></iframe>
<p style="text-align:center; font-size:small;"><strong>Figure 2:</strong> <em>Passenger count by Regions</em></p>

The visualization shown in Figure 3 breaks down flights by continent, providing insights into the global relationships established with San Francisco. It highlights the significance of each region in shaping SFO's role in the global air transportation network.

<iframe src="images/map_heatmap.html" width="100%" height="500px"></iframe>
<p style="text-align:center; font-size:small;"><strong>Figure 3:</strong> <em>Passenger count by continent</em></p>

## Tracking Changes in Flight Patterns

Analyzing data from 2000 to 2023 allows us to trace the impact of significant historical events on different regions across the globe. By observing fluctuations in flight patterns during this period, we gain insights into how geopolitical, economic, and social developments have influenced air travel dynamics worldwide.

<iframe src="images/line_regions.html" width="100%" height="500px"></iframe>
<p style="text-align:center; font-size:small;"><strong>Figure 4:</strong> <em>Yearly flight count filtering by Region</em></p>

Upon a quick examination of the visualization in Figure 4, we can identify three significant historical events.

The first is the aftermath of the September 11 attacks (11S). The US was notably affected, leading to worldwide changes in airport security protocols, resulting in a decrease in flights per year across all regions.

The second event is the Great Recession, triggering a severe global economic downturn, particularly affecting the US and Europe. Meanwhile, regions like Asia and Central America maintained relatively stable flight volumes.

Finally, the impact of COVID-19 on different regions and the subsequent travel restrictions can be observed. Further details are available in (COVID-19).

Furthermore, it's noteworthy to observe that the Middle East connection began in 2008 and continues to date. In contrast, the South America connection commenced in 2010 when San Francisco International Airport (SFO) emerged as a new gateway for travel between the United States and South America, specifically to Peru. This development likely coincided with LAN Airlines, now part of LATAM Airlines Group, introducing new non-stop flight service between SFO and Peru, offering convenient travel options for passengers between the two regions.

<!-- Back button -->
<button onclick="goBack()">Back</button>
<script>
function goBack() {
  window.history.back();
}
</script>