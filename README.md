# bikesharing

## Overview
The purpose of this analysis was to use existing Citi Bike data from New York City in August to inform a possible bike-sharing business in Des Moines.  Using Tableau, we created a number of visualizations to help show user patterns and bike information that can help better visualize data.  This, in turn, can assist with decision making for this new business. 

The Tableau visualizations were put into a Tableau Story and the below analysis references this story. 

## Results 

### Subscribers vs. Customers
Using a simple graph to illustrate User type, we see that Citi Bike has 4x as many Users who are Subscribers than simply Customers.  Creating a solid Subscriber base will be important when starting out in Des Moines.

![Users](https://github.com/cflavallee/bikesharing/blob/main/Users.PNG)

### Start vs. End of Trip
By mapping starting and ending Station IDs, we see that most NYC trips start and end within Manhattan.  This could be due to the high number of tourists who use Citi Bike while in NYC.  However, we could also understand how bike-sharing would be an easier 


![Start](https://github.com/cflavallee/bikesharing/blob/main/StartStationID.PNG)
![Stop](https://github.com/cflavallee/bikesharing/blob/main/EndStationID.PNG)

### Trip Duration, Including Accounting for Gender 
The data for Trip Duration shows that most rides are of a very short duration.  This data aligns with the data showing most trips beginning and ending in Manhattan.  Additionally, when the line graph (see below) is broken down by gender we see that the short trip duration holds for both Male and Femail, while the curve for Uknown is flatter.  More investigation would be needed to see why that is, but the data is likely not significant due to the sample size.

![TripDuration](https://github.com/cflavallee/bikesharing/blob/main/TripDuration.PNG)

### Number of Trips - Day of the Week

#### Trips by Time and Day of Week

![GenderUser](https://github.com/cflavallee/bikesharing/blob/main/Weekday.PNG)

#### Trips by Day of Week - Gender and User Type

![GenderUser](https://github.com/cflavallee/bikesharing/blob/main/WeekdayGenderUser.PNG)


## Summary


Data for other months/not peak times
Further subscriber data
Cost per bike

### Note:  Due to the security issue with Tableau Public Desktop, I did all of the work in the web version.  There were some features, such as editing headers to show 12-hour time that I could not do on the web version.

