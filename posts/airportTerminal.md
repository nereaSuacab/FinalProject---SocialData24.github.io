---
title: "Terminal and Boarding Area Analysis"
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

# Terminal and Boarding Area Analysis

This section focus on studying passenger traffic flow within the boarding areas of San Francisco Airport.

Today the airport comprises four terminals: Terminal 1, Terminal 2, Terminal 3, and the International Terminal. In turn, these include seven concourses identified as Boarding Areas A through G, totaling 115 gates arranged in a counterclockwise configuration.
Terminal 1 (Boarding Area B), Terminal 2 (Boarding Areas C and D), and Terminal 3 (Boarding Areas E and F) handle domestic and precleared flights. The International Terminal (Boarding Areas A and G) handles international flights and some domestic flights.  
Given the seasonal fluctuations inherent in airport data, it becomes imperative to conduct year-on-year comparisons. Therefore, our analysis zooms in on the evolution of boarding areas utilization at San Francisco Airport across different years. By examining these trends, the aim is to uncover any significant shifts or patterns in passenger traffic volumes over time.


<iframe src="images/terminal_heatmap.html" width="1000px" height="1000px"></iframe>

<p style="text-align:center; font-size:small;"><strong>Figure 1:</strong> <em>Boarding area density of passengers evolution from 2000 to 2023</em></p>

Overall there is an upward trend in passenger traffic at the San Francisco Airport, notwithstanding occasional setbacks triggered by significant events such as the [COVID-19 pandemic](/covid.md) and the aftermath of [September 11th](/11S.md) .

It can be seen that there was a reorganization of passenger traffic across different boarding areas. In year 2000, the starting year of our study, Boarding Area F was congested compared to its counterparts. However, as the years progressed, even though the flight activity grew (see [Air traffic evolution over time](/temporalEvolution.md)) there started to be a more even distribution of passengers across other areas.
By 2023, Boarding Area F was still the most used but overall the distribution of passengers was more balanced.  

The high density of activity of boarding area F can be attributed to its association with United Airlines, the airport's predominant carrier. United Airlines is known for its extensive domestic flight operations, recording the highest average passenger count annually.

During the 23-year examination period, certain boarding areas appeared inactive for varying durations. For instance, boarding area E exhibited minimal activity in 2012, followed by no activity in 2013, before reopening on January 28th, 2014 after remodeling works. Likewise, boarding area D remained inactive for nine consecutive years, from 2001 to 2009. The cause of this prolonged inactivity remains unclear, though it is conceivable that it may have been attributed to construction and maintenance work.

In summary, the growth of San Francisco Airport was steady over the years until it was impacted by the [COVID-19 pandemic](/covid.md). With a high density of gates and a consistent association with United Airlines, the airport’s primary air carrier, boarding Area F emerges as the focal point of activity. Over time, the disparity between the heavily utilized boarding area F and other boarding areas began to diminish. This shift can be attributed to airport reorganization and an increase in the number of flights, prompting the airport to utilize all available boarding areas.

<!-- Back button -->
<button onclick="goBack()">Back</button>
<script>
function goBack() {
  window.history.back();
}
</script>


