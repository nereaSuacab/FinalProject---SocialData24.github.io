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
Today the San Francisco airport comprises four terminals: Terminal 1, Terminal 2, Terminal 3, and the International Terminal, in addition to seven concourses identified as Boarding Areas A through G. Within this expansive infrastructure, a total of 115 gates are arranged in a counterclockwise configuration.
Terminal 1 (Boarding Area B), Terminal 2 (Boarding Areas C and D), and Terminal 3 (Boarding Areas E and F) handle domestic and precleared flights. The International Terminal (Boarding Areas A and G) handles international flights and some domestic flights.  
Given the seasonal fluctuations inherent in airport data, it becomes imperative to conduct year-on-year comparisons. Therefore, our analysis zooms in on the evolution of boarding areas utilization at San Francisco Airport across different years. By examining these trends, we aim to uncover any significant shifts or patterns in passenger traffic volumes over time.


<iframe src="images/terminal_heatmap.html" width="1000px" height="1000px"></iframe>

<p style="text-align:center; font-size:small;"><strong>Figure 1:</strong> <em>Boarding area density of passengers evolution from 2000 to 2023</em></p>

Overall there is an upward trend in passenger traffic at San Francisco Airport, notwithstanding occasional setbacks triggered by significant events such as the COVID-19 pandemic and the aftermath of September 11th.

It can be seen that there was a reorganization of passenger traffic across different boarding areas. In year 2000, the starting year of our study, Boarding Area F was congested compared to its counterparts. However, as the years progressed, even thought the flight activity growed there started to be a more balanced distribution of passengers across other areas.
By 2023, Boarding Area F was still the most used but overall the distribution of passengers wwere more balanceed. 
The high density of activity of boarding area F can be attributed to its association with United Airlines, the airport's predominant carrier. United Airlines, known for its extensive domestic flight operations, records the highest average passenger count annually.

During the 23-year examination period, certain boarding areas appeared inactive for varying durations. For instance, boarding area E exhibited minimal activity in 2012, followed by no activity in 2013, before reopening on January 28th, 2014 after remodelated works. Likewise, boarding area D remained inactive for nine consecutive years, from 2001 to 2009. The cause of this prolonged inactivity remains unclear, though it is conceivable that it may have been attributed to construction and maintenance work.

To sum up the San Francisco airport growed over the years,  Boarding Area F emerges as the focal point of activity, with a high density of gates and a consistent association with United Airlines, the airport's primary carrier renowned for extensive domestic flight operations. Our analysis unveils a reorganization of passenger traffic across different boarding areas over time

<!-- Back button -->
<button onclick="goBack()">Back</button>
<script>
function goBack() {
  window.history.back();
}
</script>


