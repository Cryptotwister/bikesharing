# Bikesharing
Citi Bike data analysis For NYC using Tableau.

## Overview
After visiting New York City and using the Citi Bike for visiting most of the landmarks, we are considering staring a similar Bike sharing business in Des Moines, IO.
Analysis of the Citi Bike data with tableau is a great choice as the purpose of this analysis is to find the factors that make the Citi Bike in NYC such an impressive experience, 
finding out the best times, top stations, demography, type of the users etc. to draw a proposal for Bike share in Des Moines for a presentation to an angel investor.

## Results

The visualizations for the NYC bikeshare Analysis can be viewed in tableau public as [Citi Bike Story](https://public.tableau.com/app/profile/sergei7887/viz/CitiBikiChallengeStory/CitiBikeStory?publish=yes).

### Converting the data
To begin with, we have converted the data in the "tripduration" column from integer to a datetime datatype to have the correct time format using Python and Pandas ([NYC_Citibike_Challenge](https://github.com/Cryptotwister/bikesharing/blob/main/NYC_Citibike_Challenge.ipynb)).
![Convert 'tripduration' to datetime dt](https://user-images.githubusercontent.com/42978221/158293667-2914d84e-e414-44cb-bfde-874e89a5a2bd.png)
The DataFrame is exported as a new file without the index column. We use tableau to connect this new csv file to make visualizations.

### Peak Riding Hours in August
![Peak Riding Hours in August](https://user-images.githubusercontent.com/42978221/158295209-a50483ae-860b-4d49-80b9-8d7c35ef2f79.png)
* Peak hours are 8 to 9AM and 5 to 7PM.

### Checkout Times for Users
![Checkout Times for Users](https://user-images.githubusercontent.com/42978221/158295257-a76549d3-1da8-4d5e-8df8-9bd448abac5f.png)
* Most bikes were checked out for a time duration of 20 mins or less.

### Checkout Times by Gender
![Checkout Times by Gender](https://user-images.githubusercontent.com/42978221/158295275-ee38ded5-eb41-4cf7-851b-18c77eaa4ee0.png)
* Most bikes were checked out mostly by males.

### Trips by Weekday for Each Hour
![Trips by Weekday for Each Hour](https://user-images.githubusercontent.com/42978221/158295304-d5f23a68-081b-46fa-9a12-5a054cd7d100.png)
*  The demand for bikes is the highest on Thursdays, followed by Monday and Tuesday.

### Trips by Gender (Weekday per Hour)
![Trips by Gender (Weekday per Hour)](https://user-images.githubusercontent.com/42978221/158295340-3c875303-13df-4495-9571-fe573db7ecaa.png)
* The highest number of riders are males, on Monday, Tuesday and Thursday the most.

### User Trips by Gender
![User Trips by Gender by Weekday](https://user-images.githubusercontent.com/42978221/158295380-11be0413-70f5-4e99-829a-963ab383947f.png)
* Male subscribers are taking the greatest number of rides.


## Summary
* Busiest hours are 8 to 10 AM and 5 to 8 PM;
* Young people tend to ride for more time;
* Most of the bikes are checked out by males;
* Also, males are the most loyal subscribers and tend to use services more often.


