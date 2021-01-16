# project-one
### Documentation https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if
### Crash Data -  Chicago
##### Timeframe: 2015-2021

##### Sample Questions/Types of Graphs
* What impacts crash type the most?
	* Crash type vs lighting
	* Bar graph for first crash type
	* Frequency of crashes at specific time of day

* What type of injuries are caused by what types of crashes?
	* Cost of damage and type of injury
	* Speed vs fatality count
	* Direction (NSEW) facing wrecks, more common than others

* What types of wrecks occur based off location?
	* Road condition vs type of road vs weather
	* Hit and run vs location (lat nad lng), over time
	* Time between when crash occurred and when police showed up. (compared to police stations near by)

* Scatterplot outliers for lane count


#### Injuries Section - Jon

###### Do car crashes tend to yield more serious injuries as the cost of damage increases?

1st Plot: Cost of Damage group vs. Injuries Total (pie chart)

-- The cost of damage shows that the large majority of injuries fall within the damage group of over $1500, at 74.1%, and the $500-1500 group taking up 12.5% of injuries. With that being said, only 13.4% of total injuries due to car wrecks ended up having a damage cost of less than $500. More injuries result from car crashes that have higher costs of damage.

2nd Plot: Cost of Damage vs. # of Fatal Injuries

-- Based on the graph, there is a clear positive correlation between cost of damage and fatal injury count. As the as cost of damage increased, the # of fatal injuries increased as well.

3rd Plot: Speed Limit vs. # of Fatal Injuries

-- A huge number of fatal injuries proved to be in areas where the posted speed limit was 30mph. This could largely be due to the fact that people speed in residential areas which are prone to having more parked cars, dips, lights, stop signs, etc. as opposed to areas with faster speed limits like freeways where people are likely to be paying more attention as they are surrounded by others who are driving faster. As shown in the trafficway and injuries bar chart, the trafficway types which have the largest number of fatal injuries are on roads with undivided or unraised barriers and at intersections, which are typically the trafficway types you will find in areas that have lower posted speed limits.

#### New Driver/High School Impact?
###### Do more accidents occur close to local high schools?
-- Many people begin to learn to drive in high school. We sought to examine a potential correlation between location of high schools and crash counts in Chicage. A heatmap of crash counts by location paired with the location of local high schools shows that although plenty of crashes occur near high schools, there are plenty of locations that experience a high frequency of accidents without a local high school nearby.

#### Street Direction
###### Does the direction of the street and time of day impact the number of crashes?
-- Looking at Total Crashes per Street Direction (2015-2021), there is an alarmingly high disparity between the total number of accidents on Eastbound vs. Westbound roads. Over 4x more accidents happen on Westbound roads than Eastbound. We sought to examine the relationship between time of day and street direction to see if Eastbound roads would show a slight spike in crash count earlier in the day possibly due to the rising sun. As well by the same logic, the crash count for Westbound roads would be higher in the evening due to the setting sun. The results show Westbound roads outweigh Eastbound roads regardless of the time of day.

----

