---
title: "Data Visualization"
excerpt: "Analysis on datasets selected from https://data.gov.in/ using different visualization tools <br/><img src='/images/data_vis.png'>"
collection: projects
---

The dataset used for the bar plot, line plot, and scatter plot is **['State/UT-wise Accidents Classified According to Type of Traffic Violations during 2018'](https://data.gov.in/resource/stateut-wise-accidents-classified-according-type-traffic-violations-during-2018)**, and for the box plot is **['Sub Divisional Monthly Rainfall from 1901 to 2017'](https://data.gov.in/resource/sub-divisional-monthly-rainfall-1901-2017)**

## Bar plot and line plot 
<br/><img src='/images/data_vis/bar_line_plot.png'>
By analyzing the data, the numbers for the cases due to overspeeding are very high compared to others. So it is good to plot the same separately. From the above plot, it can be inferred that the number of accidents due to overspeeding is high in 6 states, crossing 20,000 cases. The number of injuries due to overspeeding is more than the number of cases in some states which shows that more than a single person was injured in some accidents, it can be co-passengers or third parties. In some states such as Bihar, and Punjab, the number of deaths to the total cases ratio is higher. The same is evident from the plot as the number of death pointers lies in the upper part of the bar representing a number of cases.  

## Line plot 
<br/><img src='/images/data_vis/line_plot.png'>

In this plot, the number of deaths by accidents due to causes other than overspeeding is analyzed. The accidents caused by 'Jumping red light' have less death toll compared to others. The statistics of UP are alarming as the deaths due to three violations, 'drunken driving/consumption of alcohol & drug', 'driving on wrong side' and 'use of mobile phone' is very high even though overspeeding cases were less as seen previously. 'Driving on the wrong side' is a major cause of death in many states. This must be due to head-on collision due to traffic coming from the opposite direction which can be fatal.

## Scatter Plot
<br/><img src='/images/data_vis/scatter_plot.png'>

The above scatter plot shows that certain states or UTs are ranked high in all cases and some others ranked low in all cases. This can be a reflection of the stringent and lenient following of traffic rules in those states. Ranking of overspeeding and driving on the wrong side goes in a similar trend in most cases.

## Box Plot

<br/><img src='/images/data_vis/box_plot.png'>

The boxplot shows the rainfall for the period from June to September for South-Indian subdivisions. Coastal Karnataka receives the highest during the period followed by Kerala. The horizontal line represents the median and the green triangle represents the mean in the figure. Tamil Nadu receives the lowest rainfall among the subdivisions for the period.

The codes are available [here](https://github.com/azharctp/data-science-project/tree/main/Data_visualization)
