# Bikesharing

[Tableau Public Link - Citibike Analysis Dashboard](https://public.tableau.com/views/Module_14Challenge_16623219874910/CitibikeAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

## Purpose

The purpose of this analysis was to paint a picture of the Citibike trip data that enhances our business proposal geared towards an audience of key stakeholders, 
more specifically:
- the length of time that bikes are checked out for all riders and genders
- the number of bike trips for all riders and genders for each hour of each day of the week
- the number of bike trips for each type of user and gender for each day of the week.

## Results

Below are 7 key visualizations generated using our Citibike trip data. These visuals are aimed at addressing the relationships mentioned above:
1. August Peak Hours
2. Trips by Weekday
3. Checkout Times by Gender
4. User Trips by Gender by Weekday
5. Starting Locations by Customer Type
6. Checkout Times
7. Customer Types

**In general, we can hypothesize that ride data will show a relationship between the popular commute times ("rush hour"), and the amount of rides across all users.

1. August Peak Hours

![August Peak Hours](https://github.com/jmalauss/bikesharing/blob/main/August%20Peak%20Hours.png)

We are able to see that the peak hours for rides during the month of August are around 8AM, 5PM and 6PM. The bar chart suggests many users may be using the citibike to commute to and from work.

2. Trips by Weekday

![Trips by Weekday](https://github.com/jmalauss/bikesharing/blob/main/Trips%20By%20Weekday.png)

This heat map shows the same increase of rides around the times of 8AM, 5PM and 6PM but gives the audience the granularity of weekday, showing more rides during rush hour on the weekdays, and less rides during rush hour on the weekends.

3. Checkout Times by Gender

![Checkout Times by Gender](https://github.com/jmalauss/bikesharing/blob/main/Gender%20Breakdown.png)

The image shows a dashboard with a breakdown of the relationships found where Gender is a factor. In other words, this dashboard suggests differences in usage based on Gender. For example, the Checkout Times by Gender visualization suggests that Males may take longer rides than females and those who did not disclose their Gender.

4. User Trips by Gender by Weekday

![Trips by Gender by Weekday](https://github.com/jmalauss/bikesharing/blob/main/Gender%20Breakdown.png)

User Trips by Gender by Weekday shows the audience which users (customer or subscriber) ride the most on which weekday. This heatmap also adds Gender as an additional factor to add more detail. We can tell from this visualization that Subscribers, across all Genders, ride more than Customers. Additionally, we can see that Thursday is a popular day for riding for Subscribers across both Genders, although Males have more rides on Thursdays than Females. 

5. Starting Locations by Customer Type

![Starting Locations](https://github.com/jmalauss/bikesharing/blob/main/Starting%20Locations.png)

On the map above we can see where users start their journey. There is not much of a difference between Customers and Subscribers when it comes to their starting location, but the map allows us to understand where all users are starting their journey, and may help us understand areas in which we can advertise to gain new Customers, and turn Customers into Subscribers.

6. Checkout Times

![Checkout Times](https://github.com/jmalauss/bikesharing/blob/main/Checkout%20Times.png)

From this line chart, we can tell that most rides last about 5 minutes. This indicates that Citibike users may prefer Citibike for shorter distances, and would prefer not to be on the bike for that long.

7. Customer Types

![Customer Types](https://github.com/jmalauss/bikesharing/blob/main/Customer%20Types.png)

This last pie chart is a simple demonstration of the amount of Customers and Subscribers to Total Users. We can use this information to understand where to best implement user-facing promotional events, and how much each user type is responsible for our total revenue.

## Summary

The results indicate a few different relationships within our Citibike utilization. For starters, we can understand that there is an apparent relationship between rush hour and Citibike usage. Given the tendency for users to take shorter rides, and the proportion of Subscribers to Customers, we can assume that most of our customers are using the bike for a commute during the week. 

Some additional analyses we can perform to better understand our data would be to create a map that shows where our most frequent users start and finish their journey. Additionally, we can add a layer to that map showing local businesses and places of work to see if there are any businesses where bike users start or finish their trip often. Partnerships with these businesses could benefit Citibike when it comes to advertising, discounts/specials and visibility. 
