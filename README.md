# bikesharing

## Overview
The purpose of this analysis was to use existing Citi Bike data from New York City in August to inform a possible bike-sharing business in Des Moines.  Using Tableau, we created a number of visualizations to help show user patterns and bike information that can help better visualize data.  This, in turn, can assist with decision making for this new business. 

The Tableau visualizations were put into a Tableau Story and the below analysis references this story. The link to the Story is below.

[Link to Story](https://public.tableau.com/app/profile/collin.lavallee/viz/CitibikeChallenge_16399487400070/NYCCitiBikeStory_1#1)

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
Using the heatmap below, we see that during the week the most popular Citi Bike times were morning and evening, while on the weekends, the most popular times were during the day.  This might imply that Users are commuting to and from work with Citi Bikes, which would contradict the idea that tourists are the main Users.  Futher analysis should be done on this trend.

![Weekday](https://github.com/cflavallee/bikesharing/blob/main/DayofWeek.PNG)

#### Trips by Time and Day by Gender
When we take the above visualization a step further, by comparing Male and Female users, we see that the same pattern is seen as above, the main difference being the higher number of users who identify as Male.

![MaleFemale](https://github.com/cflavallee/bikesharing/blob/main/MaleFemale.PNG)

#### Trips by Day of Week - Gender and User Type
When the number of trips are broken down by User Type and Gender, we can see a slight preference for Customers to use Citi Bikes on the weekends, while Subscribers use them throughout the week.  Here again, we can see how significant Subscribers are for the business. 

![GenderUser](https://github.com/cflavallee/bikesharing/blob/main/WeekdayGenderUser.PNG)


## Summary
Overall, there are some important takeaways we get from analyzing and visualizing the NYC Citi Bike data. 

- Most Users are Subscribers.  Building a Subscriber base is crucial to a sustained bike-sharing business.
- Most trips are short in duration and take place within the busiest and most populated area.  Focusing on downtown   Des Moines and other heavy traffic areas is key to the bike-sharing business.
- Most Citi Bike users are Male, but all riders follow similar patterns for trip duration and day/time of the week for usage. Finding ways to expand Female clientelle could really help the Des Moines business.

### Further Research and Visualizations
Below are a few suggestions for further research, analysis, and visualization.

- Analyzing data for other months will be important, but also monitoring high traffic areas and community events would be helpful to prepare to have sufficient bikes ready at certain times.  A visualization with layers would be helpful to easily see key differences.

- Cost per bike analysis could be helpful to determine inventory levels as well as the type of bikes to purchase.  This should include repair costs and human hours needed to maintain the inventory. A visualization of Citi Bike bike IDs showing when they were in service, for how long, and type of use could be helpful.

### Note:  Due to the security issue with Tableau Public Desktop, I did all of the work in the web version.  There were some features, such as editing headers to show 12-hour time that I could not do on the web version.

