# Bikesharing

## Project Overview
The purpose of this project was to investigate bikesharing data from New York City to find trends that might reveal information about business potential of expanding to Des Moines, IA. While most columns in the downloaded CSV file were immediately ready for usage in Tableau, a dataframe manipulation was utilized to change Trip Duration to a usable Datetime format, then exported back to CSV. For all bike analysis images, please visit my [Tableau Page](https://public.tableau.com/app/profile/bowman.o.brannon.iii#!/?newProfile=&activeTab=0).

## Results
* The first visual from our Tableau story provides an overview of some general data trends and insights. Males account for a strong majority of riders, particularly when "Unknown" is not included. Trip duration tended to slowly increase as birth year increased, with a sharp increase for riders born after 1995. Certain bikes had more concentrated starting locations, and consequently more rides. The map shows that these higher concentrations occurred in tourist hotspots.
* ![NYC Story Front Page](https://github.com/manBow1119/bikesharing/blob/main/NYC_story.png)

* This is confirmed when we examine the map closer. The number of rides is much more concentrated in areas that also have highly concentrated starting locations. 
* ![Ride concentration map](https://github.com/manBow1119/bikesharing/blob/main/Starting_locations.png)

* Peak hour ride data shows that most rides occurred during expected work commute times, while fewest rides occurred between 3-4 in the morning.
* ![August Peak Hours](https://github.com/manBow1119/bikesharing/blob/main/Peak_usage_hours.png)
 
* Average bike checkout time (trip duration) for all riders shows most riders rode for less than a half hour, and very few more than one hour.
* ![Trip duration](https://github.com/manBow1119/bikesharing/blob/main/User_trip_duration.png)
  
* When split by gender, we see that both males and females follow this trend, as do riders who did not specify a gender.
![Trip duration by gender](https://github.com/manBow1119/bikesharing/blob/main/Trip_duration_by_gender.png)

* A look at number of trips per hour by weekday offers a closer look at how weekdays vary from weekends. On weekdays, a high concentration of rides occur during typical work commute hours. Meanwhile, weekends showed more rides between these hours.
* ![Number of trips per hour by weekday](https://github.com/manBow1119/bikesharing/blob/main/Trips_by_hour.png)

* Split by gender, trends for male and female seem to reflect similar concentrations. It is worth nothing that riders not specifying gender tendended not to ride during the week (perhaps casual riders, not subscribers)
* ![Number of trips per hour by weekday by gender](https://github.com/manBow1119/bikesharing/blob/main/Trips_by_hour_gender.png)

* Looking at type of user split by weekday and gender, we see most suscribers declare their gender while most non-subscribing customers do not. IT should be noted that most non-subscribers ride on weekends, while subscribers ride mostly during the week.
* ![Number of trips per hour by weekday by gender](https://github.com/manBow1119/bikesharing/blob/main/Trips_by_user_gender.png)

* One final visual looks at the number of rides and trip duration relative to rider's birth year and split by gender. For the most part younger riders tended to ride more often and longer with an abrupt drop in number of riders born between 1998 and 2003. There is one considerable spike in the graph worth noting for both number of rides and trip duration for riders born in 1969. Looking closer at the number of riders, most of those with birth year of 1969 did not declare their gender. It is possible that 1969 is the default birth year setting, as is unknown for gender. Other entries dating back to 1885 may need to be considered entry error by the user. 
![Number of trips and ride duration by birth year and gender](https://github.com/manBow1119/bikesharing/blob/main/Birthyear_outlier.png)

## Summary
The visualizations provide some strong evidence that can help guide business operations and target marketing strategies. Immediately it is obvious most riders are male, and subscribers. What marketing approach could result in attracting more subscribed female riders? There is a fairly large spread of users by age, with a large portion coming from the 1970-2000 birth year range. Most of the visuals reveal the data provide some expected results for a large metropolitan area: that most rides occurred during typical commute times for weekday jobs, between 7-9 am and 4-7 pm. Further, the least rides occur between 3-4 am, which might provide a good time for bicycle maintenance on the bike IDs with highest usage numbers. Some visuals revealed data that could be eliminated based on potential user input error, or default settings, such as "Unknown" gender and the potential outlier with birth year. Future analyses could benefit from cleaning for more precision in projections. While much of this data seems to generalize pretty easily to other urban areas, I caution against overgeneralizing data from one of the most densely populated and culturally diverse cities to one such as Des Moines. These data can also provide baselines to compare UI adjustments that accept user input.
