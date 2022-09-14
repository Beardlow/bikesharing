# Bikesharing in NYC Module 14 Tableau

## Purpose
The purrpose of this analysis was to get a better understanding of the CitiBike rental bike company so that the idea can be replicated in Des Moines, IA. This analysis uses Python Pandas to munge/transform the data into a usable format. It also uses Tableau in order to provide visualization of the NYC use case. All data visualizations were created using data from August 2019.

### Understanding the Customers
Any business, in order to be successful, must understand their customer base. Below are some visualizations that give some insight into the customer base for CitBike in NYC.

#### Gender Split

This pie chart shows the ratio of each gender that has used CitiBike during August 2019. Orange is male. Blue is female. Red is unknown.
![Gender Pie](https://github.com/Beardlow/bikesharing/blob/main/Usertypes_by_G.png)

#### How Old are CitiBike's Users?

This bubble chart uses all of the data to come up with the bubbles for each birth year; however, this look is flawed. See image below.
![Incorrect Age Bubble](https://github.com/Beardlow/bikesharing/blob/main/Incorrect_Age_Bubble.png)

When removing those users of an unknown gender, we get the following, more correct, age distribution bubble chart.
![Adjusted Age Bubble](https://github.com/Beardlow/bikesharing/blob/main/Usertype_by_Age.png)

#### When do Users Rent Bikes?
The following heatmap show that there are heavy use periods at 7 to 8 in the morning and again from 5 to 7 pm.
![Use Times Holistic](https://github.com/Beardlow/bikesharing/blob/main/Trips_per_Weekday_per_Hour.png)

#### When do Users Rent Bikes by Gender?
![Use Times by Gender](https://github.com/Beardlow/bikesharing/blob/main/Trip_per_Weekday_per_day_per_Hour_by_G.png)

#### How Long do Users Rent Bikes For?
The vast majority of the rentals lasted from 0 to 45 minutes long as seen below.
![Length of Rentals](https://github.com/Beardlow/bikesharing/blob/main/Trip_Duration.png)

#### Where do Users Start and End Their Bike Trips?
The first image below is a heatmap of where users start their bike trips. The second image is where users end their bike trips. As you can see, starts and stops are heavily concentrated in a few areas.
![Trip Starts](https://github.com/Beardlow/bikesharing/blob/main/Rides_by_Starting_Location.png)

![Trip Ends](https://github.com/Beardlow/bikesharing/blob/main/Rides_by_Ending_Location.png)

### Tableau Story
[link to dashboard](https://public.tableau.com/app/profile/eric.bartlow/viz/NYC_Citi_Bike_Challenge_16630124140270/NYCStory)

## Summary
In summary, we can see that NYC CitiBike has heavy usage. Their customers are majority male and in their upper twenties to mid thirties. The trips are relatively short with the vast majority being under 45 minutes long. Most rentals occur during daylight hours and open up a chance for bike maintenance from the hours of 12am to 4 am. Also, since the majority of the bikes are rented from and returned to a few locations, centering the maintenance hub in the midst of these location would help reduce maintenance transport time and cost.  Some further information could really bolster the conclusions that can been drawn from this data. For instance, if the weather conditions for each of the shown days was known, an understanding of the reduction in use due to bad weather could be understood. This could also be tied into the weather conditions of Des Moines, IA so that use could be better understood as well.  Another piece of useful information would be the pay structure so that an understanding of the benefits of offering a subscription service vs only a pay per use cycle could be.





