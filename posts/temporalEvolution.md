---
title: "Trends Over Time"
date: 2024-05-01
author: Paula Gambús i Moreno
tags: [tag1, tag2, tag3]
---

# Temporal patterns

In this section there is our exploration into San Francisco Airport's (SFO) data landscape. As one of the busiest airports in the world, SFO serves as a bustling hub connecting millions of travelers to destinations worldwide. Within this dynamic environment, understanding the temporal patterns and trends of the airport's operations gives a lot of valuable insights. Therefore, we embark on a journey through time, delving into monthly and yearly rythms. 

Our dataset holds a monthly breakdown of passenger counts from 2000 to 2023, offering a detailed look at SFO's activity over the years with three types of passengers: enplaned, deplaned, and in transit. This lets us see how passenger numbers fluctuate month by month, giving us insights into seasonal trends and travel patterns. Additionally, we've studied the evolution of these trends across the years, providing a comprehensive understanding of how passenger dynamics have evolved over the two-decade period.  Let's dive into the data and uncover the stories it tells!

## Yearly analysis
Let's first take a look upon the overarching trends in passenger activity spanning these two decades. This graph offers a panoramic view of the total passenger volume, encompassing enplaned, deplaned and in-transet people. 

![Alt text](images/total_passenger_count.png)
<p style="text-align:center; font-size:small;"><strong>Figure 1:</strong> <em>Yearly trend of the total passengers count without taking into account the type</em></p>

The flunctuations of the amount of passengers during the years are noticeable and they happened due to different events that occured during these years. The first descense of the passenger count appears between the years 2000 and 2003, afterwards, the amount of travelers started increasing again. However, the most drastic declined happens in 2020. After researching about historical facts, different conclusions were achieved. Nevertheless, before confirm them, another yearly analysis was performed to compare the amount of the three different types of passengers stepping at SFO. 

<iframe src="images/passengers_type_yearly.html" width="100%" height="530px"></iframe>
<p style="text-align:center; font-size:small;"><strong>Figure 2:</strong> <em>Yearly trend of the passengers count according to the type</em></p>

EXPLANATION ABOUT:
- similarities between enplaned and deplaned passenger count
- 11S and Iraq war in 2003
- Covid

## Monthly analysis
It is time to turn the attention to the monthly analysis, where we delve deeper into the data to uncover seasonal patterns and other valuable insights. Therefore, different fluctuations in passenger counts on a month-to-month basis are detected. Again, firstly, the total amount of passengers per month without taking into account the type was evaluated calculating the mean between all the years from our dataset.

<iframe src="images/total_passengers_monthly.html" width="100%" height="530px"></iframe>
<p style="text-align:center; font-size:small;"><strong>Figure 3:</strong> <em>Monthly trend of the mean passengers count between the years without taking into account the type</em></p>

Different conclusions could be made after analyzing this plot but firstly, we wanted to observe too the evolution of the number of passengers according to their type.

<div style="display: flex; justify-content: center;">
    <iframe src="images/passengers_type_monthly.html" width="90%" height="560px"></iframe>
</div>
<p style="text-align:center; font-size:small;"><strong>Figure 4:</strong> <em>Monthly trend of the mean passengers count between the years according to the type</em></p>

EXPLANATION ABOUT:
- again similarities between enplaned and deplaned passenger count
- february as the lowest month
- high peaks in summer months
