# Bikesharing Project

## Overview of the Analysis
This project uses Tableau to perform an analysis on public Citi bike data in NYC to help determine how to expand Citi bike in another location. We analyze the ride data and create visualizations to show the length of time that bikes are checked out by the riders, the number of bike trips by hour for each day of the week, and the number of bike trips for each type of user and gender for each day of the week. To create these visuals we needed to adjust the trip duration from an integer to a date time in pandas and then export the new data to a CSV to upload in Tableau.

## Results
- The images below are screenshots of the visualizations created in Tableau with the data that was updated using pandas

![Checkout Times](https://github.com/kmaluccio/bikesharing/blob/main/CheckoutTimes.png)

The above shows how long bikes are checked out for all riders. We can see that most riders are riding the bikes for 5-15 minutes and after 30-40 minutes there are much less riders still on trips. One purpose of Citi bike is to give people a simple way to travel around the city without dealing with traffic or with parking and so trip durations are rather short.


![Checkout Times by Gender](https://github.com/kmaluccio/bikesharing/blob/main/CheckoutTimesbyGender.png)

The above shows how long bikes are checked out for all genders. Here we can see that there are many more male riders compared to female riders with a small amount of unknown rider gender data. This could mean we want to advertise to more female riders to increase females using the bikes or there just happen to be more males using the bikes.


![Trips by Weekday](https://github.com/kmaluccio/bikesharing/blob/main/TripsbyWeekday.png)

The above map shows the number of bike trips by time of day and day of the week. We can see that on weekends (Saturday and Sunday), there are larger number of users throughout the day from 11am to 7pm. We compare this to the week days when the busiest times are 7am to 9am and again from 5pm to 7pm. There are still many riders during the day through the week, but it is clear that the busiest times are before and after work hours, so there must be many people using the bikes to travel to and from work.


![Trips by Gender](https://github.com/kmaluccio/bikesharing/blob/main/TripsbyGender.png)

The above map shows the number of bike trips by gender each day of the week. We can see males use the bikes the most compared to females, specifically on week day mornings and evenings (again, the hours before and after working hours). 


![User trips by weekday and gender](https://github.com/kmaluccio/bikesharing/blob/main/UserTripsbyGenderbyWeekday.png)

The above shows the user trips by gender and day of the week. We can see that there are many more subscribers compared to short term riders and the most users during the week are the male subscribers.


![Top Starting Locations](https://github.com/kmaluccio/bikesharing/blob/main/TopStartingLocations.png)

The above map shows the starting locations and we have filtered by size and color. So, the larger circles represent more bikes in that starting location and you can see which colors represent more or less bike count as well. You may notice the larger circles and darker red colors represent areas that might have larger tourist numbers and/or larger groups of people biking to work in the city.


![August Peak Hours](https://github.com/kmaluccio/bikesharing/blob/main/AugustPeakHours.png)

The above displays the time of day in August when bikers begin their trips. We can see that early morning, 2am - 5am, would be a good time to perform maintenance on the bikes. Additionally, the peak hours for starting a trip are 5pm - 7pm.

## Summary
The results have shown how Citi bike has performed in New York City and proves this would be a good business for another city such as Des Moines. The focus areas should be tourist areas and business districts so that tourists can use the bikes as well as people who wish to bike to and from work. It is important to note the times when most bikes are in use as well as times when less bikes are in use. With this information, bikes can undergo maintenance during the times when there is little to no use and then be ready for the users during busy times. Citi bike is not only good for the environment, but also fun for tourists to explore the city using this refreshing and healthy mode of transportation.
- Link to my Tableau Public Story: [link to dashboard] (https://public.tableau.com/app/profile/kelly.maluccio/viz/CitiBikeChallenge_16480025538630/NYCCitiBikeStory)
- Some suggestions for future analysis:
	- it would be useful to look at data for other months with warm weather such as June, July, or September and then create the same visualizations
	- compare the trip duration with short term users and subscribers to see the types of trips for each user
	- compare the start and end stations to focus on where bikes need to be and if/when they need to be moved from specific end stations to have supply at the start stations
