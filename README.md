# A PyBer Analysis: Discrepancies in Rideshare Fares By City Type
## Purpose

The purpose of this project was to help the fictional rideshare service "PyBer" understand prices, sales and capacity in different types of communities, using Python summary
statistics and visualization tools. The analysis included reading data from .csv files into dataframes, and grouping them by specific attributes -- most notably, by category of community: rural, urban and suburban. 

## Overview

Unsurprisingly, urban communities had the largest capacity in multiple categories, including total rides (1,625), total drivers (2,405), and total in fares ($39,854.38). Perhaps because of that level of bandwidth, the average prices were also the lowest ($24.53 average per ride and $16.57 average fare per driver). The suburban market had the second-highest capacity of rides, drivers and total fares, and the second-highest averages, while rural markets had the reverse -- the lowest number of drivers, rides and fares but the highest average prices.

### Summary of Data

![image](https://user-images.githubusercontent.com/1015285/120113807-d37aaf80-c141-11eb-8320-59be159385be.png)

The graph of total fares by city type illustrates the different levels of capacity on a week-by-week basis. At no point do the lines intersect -- urban fares are always higher than suburban; suburban always higher than rural. Although we can expect rideshare service use to be approximately correlated by date, rather than simply type of community, the lines aren't always totally in synch. For instance, the total fares began to increase at the start of February in urban communities, while decreasing in the other two types of city. The peaks and valleys throughout March were also more dramatic in cities than the suburbs or rural communities.

### Total Fares by City Type

![image](https://user-images.githubusercontent.com/1015285/120114797-6f0e1f00-c146-11eb-944d-bef81a1abd97.png)

## Conclusions

Although more data would be ideal, there are at least a few conclusions PyBer could draw from this summary. First, the company may want to consider a better equilibrium between prices and capacity in rural communities. Obviously the cost of rides ($34.62 on average per ride; $55.49 per driver) is going to be higher because there are compratively few of them; demand is less, and it's possible that those rides are longer than in other communities (and perhaps some of that is driven by long-distance commuters). But because of those numbers, the company may want to try a campaign to entice more rural passengers, or else move some of its capacity to suburban communties, where the prices are only slightly lower and demand is bound to be higher.

Second, although it could just be noise, each community saw a noticeable dip in fares at the end of Februrary. The company should at least investigate whether there is a systematic change in demand at that particular time of year, and if so, look for ways to offset those expected losses next time. 

Finally, the month of March in urban communities is worth further study. The month brings total fares to a roughly four-month high, around $2,500, as well as below $2,000, which looks more like sales in the dead of winter in January than the start of spring. Although we don't have temperature data, or additional information on climate in the cities being analyzed, such a varied performance is worth a closer look.
