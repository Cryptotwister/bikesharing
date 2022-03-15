# Bikesharing
Citi Bike data analysis For NYC using Tableau.

## Overview
After visiting New York City and using the Citi Bike for visiting most of the landmarks, we are considering staring a similar Bike sharing business in Des Moines, IO.
Analysis of the Citi Bike data with tableau is a great choice as the purpose of this analysis is to find the factors that make the Citi Bike in NYC such an impressive experience, 
finding out the best times, top stations, demography, type of the users etc. to draw a proposal for Bike share in Des Moines for a presentation to an angel investor.

## Results

The visualizations for the NYC bikeshare Analysis can be viewed in tableau public as [Citi Bike Story](https://public.tableau.com/app/profile/sergei7887/viz/CitiBikiChallengeStory/CitiBikeStory?publish=yes).

### Converting the data
To begin with we have converted the data in the "tripduration" column from integer to a datetime datatype to have the correct time format using Python and Pandas.
![Convert 'tripduration' to datetime dt](https://user-images.githubusercontent.com/42978221/158293667-2914d84e-e414-44cb-bfde-874e89a5a2bd.png)
The DataFrame is exported as a new file without the index column. We use tableau to connect this new csv file to make visualizations.


