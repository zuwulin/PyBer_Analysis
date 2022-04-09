# PyBer Ride-Sharing Analysis

## Overview of Analysis
The current project was requested by a PyBer ride-sharing company to evaluate the different trends of ride-sharing phenomenon across three city types (rural, urban, and suburban) and implement changes, according to the data, if needed.

### Purpose
The purpose of the current analysis was, first, to examine the overall trends of ride-sharing across three different types of cities, and investigate whether ride-sharing, as an activity, varies in popularity and demand across the three sectors examined. The second goal was to evaluate any such differences arising from the analysis and to provide the company with recommendations that can increase the ride-sharing demand in the communities identified as less engaged.

## Results
<p align="center">
  <img src="https://user-images.githubusercontent.com/99566803/162546572-6ec65bff-c5e5-4f87-a9e5-2ddd29c61d82.png" />
</p>
Here are some key findings from the data summary overview:

* Urban city type dominates the market in both the total amount of rides (1625) and in the number of drivers (2405). For comparison, total rural driver count (78) represents a mere 3,24% of the total driver count in the urban areas, and the suburban count (490) represents 20% of the urban total count. This discrepancy is partially responsible for the difference in the total revenue provided by the regions, however, might be reversely accounted for by the demand in the region (less demand results in less rides per region, indirectly resulting in a smaller driver count).

* In terms of the revenue, urban regions account for the biggest cut of the revenue ($39,854), with the suburban regions contributing about half of the urban revenue ($19,356), and the rural regions totaling only $4,327 in profits (refer to the "Total Fare by City Type" line chart for a more comprehensible look at the weekly revenue  across three regions).

* Interestingly, however, rural fares showcased the highest averaged price per ride ($34,62), while the most profitable urban region only averaged about $24,53 per ride. This is possibly the result of rural rides comprising of longer commutes, in general, than those performed in the urban region. However, one should not forget the significant different in the amount of total rides per region (125 for rural and 1625 for urban), which would also impact the calculated averaged price.

* Finally, in line with the previous statistic, the average fare cost per driver was highest for the rural regions ($55,49), medium for suburban regions (#39,50), and lowest for the urban regions ($16,57). As with the previous numbers, such huge discrepancy have to do with the amount of drivers allocated to each respective region (78 drivers for rural areas versus 2405 for urban ones).

![PyBer_fare_summary](https://user-images.githubusercontent.com/99566803/162545894-2bcfbd57-c96b-4620-81ee-f21040a8be9a.png)

## Summary
According to the data provided within this analysis, my recommendations to the PyBer ride-sharing company are, as follows:

1. It is highly advisable to reduce the number of drivers in the urban regions, with the potentiality of relocating them to the rural areas. As it stands currently, some 800 drivers in the urban area did not perform a single ride (given that there are 2405 drivers in the area and only 1625 rides have been done in the last year).

2. In order to increase revenue, PyBer might want to examine more closely the peaking weeks on the plot provided within this analysis (e.g., the last week of February), and adjust their prices for the more in-demand times accordingly. Lowering the prices in the "off-season" time can also increase the attractiveness of the service and potentially attract otherwise undecided customers.

3. Finally, an additional analysis of fare cost per minute is recommended in order to compare time cost in the rural versus the urban areas. As of now, rural areas seem to have a rather high "per minute" cost. Unless the consequent analysis reveals that the price is well-balanced in terms of time and distance, it is recommended that PyBer look more closely into increasing their per minute pricing for the urban areas for optimal revenue profit increase.
