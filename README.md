# PBI-YYC-Crime-Stats

**Dashboard**

![alt text](https://github.com/aaronmkwong/PBI-YYC-Crime-Stats/blob/main/Images/PBY_YYC_Crime_Stats.JPG)

**Purpose**

The purpose of the dashboard is to identify the categories of crime and disorder that are increasing or decreasing for the past 8 years in Calgary in terms of a count of incidents and a percentage of population. Communities will be assessed in terms of overall threat to person or property. Significant shifts in the types of crime or disorder in the communities will be highlighted. The dashboard is intended to be exploratory in nature.

**Types & Locations of Charts**

There are 3 sections of the dashboard. The first section summarizes, geographically orients, enables investigation and drives interactivity whereas the second and third sections reinforce the trend and contributors of change through time, respectively. The first provides a point in time view consisting of a bar chart summarizing incidents per capita by sector and broken down by physical and property categories, a table detailing incidents, residents, incidents per capita and the percentage change since 2012 for each community and incident description, as well as a plot map of the centre points of each community orienting the user to the locations of the sectors and communities. The second section is a time series view using a dual axis line chart depicting incidents per capita and residents for each year from 2012 to 2019. The third section is a change contribution view with a waterfall chart that depicts how much each incident description contributes to the overal change in incidents per capita from 2012 to 2019.

**Chart Measures**

![alt text](https://github.com/aaronmkwong/PBI-YYC-Crime-Stats/blob/main/Images/PBY_YYC_Crime_Stats_1.JPG)

**Chart Dimensions**

![alt text](https://github.com/aaronmkwong/PBI-YYC-Crime-Stats/blob/main/Images/PBY_YYC_Crime_Stats_2.JPG)

**Interactivity**

There are 5 interactive elements in the dashboard. The first section contains 4 interactive elements: a year filter that interacts with the bar chart and table within the first section; the bar chart filters the table and map within the first section as well as the line and waterfall charts in the second and third sections; the table filters the bar chart and map within the first section as well as the line and waterfall charts in the second and third sections; there is also a reset button that clears the year filter and any contexts established through the interactions. The fifth interactive element is located at the top right and is available for the user to understand in brief how to navigate the dashboard. 

![alt text](https://github.com/aaronmkwong/PBI-YYC-Crime-Stats/blob/main/Images/PBY_YYC_Crime_Stats_3.JPG)

**Data Sources**

The data source is Calgary Community Crime and Disorder statistics. https://data.calgary.ca/Health-and-Safety/Community-Crime-and-Disorder-Map-to-be-archived-/hhjd-wzc2. Incidents of crime are reported by sector (e.g. north east), community (e.g. whitehorn),  group (e.g. crime, disorder) and category (e.g. vehicle theft, commercial break and enter) from 2012 to 2019 with community centre latitude and longitude coordinates, which will allow for categorical, time series and mapping visual analytics.


