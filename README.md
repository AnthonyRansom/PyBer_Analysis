# PyBer_Analysis

## Overview of Project

### Purpose

The analysis of the Pyber Ride data will provide insight on the weekly fare income for the various types of cities Pyber operates.
The results of the analysis will look into how the weekly fares differ between Urban, Suburban and Rural cities and compare the results to the number
of Drivers and Number of Rides for each city type.

Through the insights gained from this analysis multiple business cases will be presented in order to advise on how Pyber can improve
business in the relevant city sectors.

## Analysis and Challenges

### Results

#### Review of Fare Summary

![Summary Table]("analysis\PyBer_summary.PNG")

From the summary data table certain patterns have be noted:
 - The average fare per driver and average fare per ride increases in less populated areas such as Rural areas compared to more densely populated areas such as Urban areas
 - More densely populated areas indicate an increase in rides but also shows higher competition in the number of drivers operating in the Urban city areas.

With further review of the summary, the provided dataset shows the number of rides and the total fares in each city type increases as there are more drivers present
but the data does indicate that Urban areas have more drivers than the number of rides for the period analyised which may indicate too many drivers have been 
allocated to Urban city areas which is reducing the average fare per driver.


#### Review of Weekly Fare by City Type Graph

![Total Fare by City Type Graph]("analysis\PyBer_fare_summary.png")

Looking at the provided graph shows the weekely fare by city type matches the summary table above with the Total fares for Urban areas showing the highest Fares followed by Suburban and then Rural.
 - The Urban graph indicates there is a slow increase in the fares starting from January and peaking at around the end of February with weekly fluctuations throughout the month of March.
 The graph shows a steady decline in Fares starting the middle of April but there is not enough data to determine if the decline continues or is temporary
 
 - The Suburban graph shows a steady weekly fare throught the Months January to April but there is large increase in fares in the last weeks of March
	which aligns with the same weeks of the Rural and Urban graphs.
	
 - The Rural graph shows some steep fluctations for the fares for each week but the weekly fares are maintained within the 0$ to $500 bracket through the Months of January to April.
	The same increase in Fares in the week at the end of March is also seen on the Rural graph align with the Urban and Suburban graphs.
	
 - The graphs for the the three city types indicates a consistant income from Fares within a $1,000 range for each city type

## Summary

The analysis from the graph indicates the City Types maintain a fairly consistent Fare income but there are some disparities between the various city types shown on the summary table.
The below business cases will propose some solutions in order to resolve these disparities across the city types:

#### Business Case 1
business 1 - The data shows there are less people taking rides in Rural areas but the average fare per ride is hgiher whcih could indicate the rides are longer compared to the other city types,
It may be beneficial to decrease the fare price in Rural areas which will encrourage more people to make use of the service with the aim to increase demand which which will increase the number of drivers
aligning the Total fare income and number of rides and drivers with the Suburban and Urban city areas

#### Business Case 2
business 2 - THe data show a high number of drivers compared to the number of rides in Urabn areas causing the average fare per driver to decrease. Pyber could look at reducing the number of drivers in Urban cities
in order to resolve the dipsarti between the number of rides vs the number of drivers in Urban cities compared to Suburban and Rural areas.

#### Business Case 3
business 3 - The data shows Rural areas have the least amount of rides but the highest fare per ride which may indicate the rides in Rural areas take longer than other city types
It would be beneficail to increase the number of drivers in Rural areas as the current quantity of drivers may not be able to accomodate the demand for rides in Rural areas.