# bikesharing
Using '201908-citibike-tripdata.csv', the data was preprocessed before being imported to Tableau where visualizations were created to formulate a story about the data.
## Overview of Analysis
For this project, the tripduration column was modified from an integer to a datetime datatype before beginning the visualization process in Tableau. Once completed, updated data was placed into Tableau to create the new visualizations listed here:
- How long bikes are checked out for all riders and genders.
- How many trips are taken by the hour for each day of the week, for all riders and genders.
- A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.
## Results
1. This is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour.
![Checkout Times for Users](https://user-images.githubusercontent.com/110861876/202020113-2ca3fa0d-8f42-4537-a068-188035dd7562.png)
2. This is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour. The graph can be filtered by the hour and gender.
![Checkout Times by Gender](https://user-images.githubusercontent.com/110861876/202020793-5f06c7ef-f20f-4143-b177-cce48456f8b7.png)
3. This is a heatmap showing the number of bike trips for each hour of each day of the week.
![Trips by Weekday by Hour](https://user-images.githubusercontent.com/110861876/202021030-6a6def01-c195-4ea0-9f04-873c6aed0f0d.png)
4. This is a heatmap showing the number of bike trips by gender for each hour of each day of the week. The heatmap can be filtered by gender.
![Trips by Gender](https://user-images.githubusercontent.com/110861876/202021148-97f80fca-c566-4033-9c32-75541af836d3.png)
5. This is a heatmap showing the number of bike trips for each type of user and gender for each day of the week. It can be filtered by user and gender.
![User Trips by Gender](https://user-images.githubusercontent.com/110861876/202021273-cb39d18f-f014-4f57-970f-e61f12385480.png)
6. This is a area graph showing the average trip duration by birth year.
![Avg trip duration](https://user-images.githubusercontent.com/110861876/202021437-14aff0be-a3d7-4392-8391-ec5e053c995b.png)
7. This is a horizantal bar chart showing the peak hours of number of rides in August.
![August Peak Hours](https://user-images.githubusercontent.com/110861876/202021614-1afe85e7-c78b-4690-a5a8-5de60d183225.png)
## Summary
This is the link to my story:
[[link to dashboard]((https://public.tableau.com/app/profile/holden.b.lauer/viz/CitiBikeChallenge_16685424053890/CitiBikeStory?publish=yes))](https://public.tableau.com/app/profile/holden.b.lauer/viz/CitiBikeChallenge_16685424053890/CitiBikeStory?publish=yes)

From the results, it is evident that the majority of our customers are male. Also, about 80% of customers are subscribed. The most frequent riding times are in the morning and afternoon (approximately 6AM to 9AM and 4PM to 7PM). Additionally, our heatmap displays the weekend being much busier than the weekdays.
Two additional visualizations for further analysis:
1. Get the gender count for subscribed to non-subscribed users to determine which gender tends to subscribe more.
2. Create a map that shows the top stations with the income overlay to determine if income has an effect on the amount of riders.
