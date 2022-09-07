# Bikesharing
![logo](https://user-images.githubusercontent.com/68654746/188967168-5236c4ed-1ad4-4adb-aee4-f065d086a5f0.jpg)

Checkout my Tableau viz [here](https://public.tableau.com/app/profile/elise1409 "here")
## Overview

There is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

## Purpose
- Import data into Tableau
- Create and style worksheets, dashboards, and stories in Tableau
- Use Tableau worksheets to display data in a professional way
- Portray data accurately using Tableau dashboards

![TotalRidesUserGender](https://user-images.githubusercontent.com/68654746/188963166-365ff274-a52c-4a2f-84ec-cc65570d0fff.png)

*Findings*
- In NYC, there were over 2.3M trips taken in the month of August. 
- Approximately 81% of the riders in the "subscriber" category and male riders were the primary user of this program (65%).

### Deliverable 1: Change Trip Duration to a Datetime Format
Using Python and Pandas functions, you’ll convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After you convert the "tripduration" column to a datetime dataytpe, you’ll export the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.
![pandas1](https://user-images.githubusercontent.com/68654746/188958492-7ca4cfd2-a991-445c-9f55-d23ab8f96c60.jpg)
![pandas2](https://user-images.githubusercontent.com/68654746/188958502-fdc57a4c-370b-4cb9-8338-590e222f4db4.jpg)
![pandas3](https://user-images.githubusercontent.com/68654746/188958524-e7725a08-8387-473a-b290-fb6e3bda82f6.jpg)
![pandas4](https://user-images.githubusercontent.com/68654746/188958544-df851833-da47-4130-b617-a2824ce1a7ce.jpg)

### Deliverable 2: Create Visualizations for the Trip Analysis
Using Tableau, create visualizations that show:
- How long bikes are checked out for all riders and genders.
- How many trips are taken by the hour for each day of the week, for all riders and genders.
- A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

**Checkout Times for Users** 
![checkout_for_Users_Viz](https://user-images.githubusercontent.com/68654746/188957839-882816cb-0532-447e-985a-6b7572ed5cde.jpg)

**Checkout Times for Users by Gender**
![checkout_for_Gender](https://user-images.githubusercontent.com/68654746/188957843-b5785d30-25f9-4439-96b4-7e3eceb9fc75.jpg)

*Findings*
- Nearly all of the bike trips taken in NYC were under 60 minutes.
- More than 50% trips were under 10 minutes, for females and males and unknown genders.
- Male riders are primarily using nyc's bike sharing program making up about 65% of the program population, with the remaining being 25% female and 10% unknown.

**Trips by Weekday for Each Hour** 
![trips_by_Weekday](https://user-images.githubusercontent.com/68654746/188957819-5f55b827-05c9-4105-bd80-c9777e61ef1f.jpg)

**Trips by Gender (Weekday per Hour)**
![trips_by_Weekday_Gender](https://user-images.githubusercontent.com/68654746/188957808-8fea6b49-4653-4535-91e0-b9f5fed69fbf.jpg)

*Findings*
- Most rides were taken during the weekdays (Mon-Fri) and concentrate during normal commuting/work hours of 7am-9am and 5pm-7pm. For these reasons, it can be assumed that the nyc bike sharing program is one of the preferred methods for commuting to and from work.
- In comparison to females and unknown gender riders, male riders are more inclined to use the bike sharing program to commute to and from work, as well as midday on the weekends.

**User Trips by Gender by Weekday**
![user_trips_by_Weekday_Gender](https://user-images.githubusercontent.com/68654746/188957720-1b9b571d-f0a5-46b3-8eba-a7a15001af67.jpg)

*Findings*
- Among the subscribers, Thursday had the highest bike usage day for male, female and unknown gender riders, with Friday following closely second. 
- The day with the most usage for non-subscribers was on Saturday, closely followed by Sunday.

### Deliverable 3: Create a Story and Report for the Final Presentation
Create a story in Tableau and write a report that describes the key outcomes of the NYC Citibike analysis you did in the module and the challenge.

Checkout my viz [here](https://public.tableau.com/app/profile/elise1409 "here")
