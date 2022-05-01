# PyBer_Analysis

## Purpose 
The purpose of this project was to create a visualization of the total weekly fares based on city type for PyBer Ridesharing. This data will then be used to make decisions about allocating drivers and other resources to specific areas if needed.

## Results
A perfunctory look at the graph of total weekly fares based on city type shows a clear lucrative hierarchy. Urban cities generate the most total weekly fares, followed by suburban cities, and finally rural cities. However, there is more to this story. A look at the data of total drivers shows that there is an abundance of drivers in urban cities, with nearly 1.5 drivers available per ride. While this is good given that urban areas have higher population density, and therefore a possible need for more drivers, the number of drivers available far out paces the number of total rides that were given. Many of these drivers may be redundant to have in the urban city. Further, a look at the same data for suburban cities. shows the exact opposite: less drivers available than there were rides given. This perhaps points to a need for more drivers available in suburban cities (see image below for details).

!["Data by City Type"](https://github.com/conorwhanson/PyBer_Analysis/blob/main/resources/city_type_data.png)

A look a the total weekly fares graph also shows that fares for urban and suburban cities begin to rise after January 1st, with urban fares continuing to increase into February while suburban fares dip beginning in the end of January. Rural fares stay consistently under $500/week. All 3 city types see a jump in fares the third week of February, with suburban and rural cities seeing the largest percent increase (35% and 337% respectively). See graph below.

!["Total Fares by city Type"](https://github.com/conorwhanson/PyBer_Analysis/blob/main/analysis/PyberPlot1.png)

## Summary and Recommendations

Based on the available data here I would suggest 3 actions to take:
1. Take approximately 200 drivers from urban cities and allocate them to suburban and rural cities to meet the total ride needs.
2. Gather more data on each city type to discover the cause(s) of peaks and valleys in fares, particularly the spike in all 3 city types during the third week of February.
3. Based on recommendation 2 above, have drivers ready to be moved to a particular city type based on the expectation of total ride needs. The timing and kind of spike to expect (sporting events, college events, larger groups, families, college students, etc) will give a clearer picture of the causes of spikes and how to better prepare for them.