# CitiBike Bike Sharing Analysis

## Overview

### Purpose of Analysis

The purpose of this analysis is to develop a deeper understanding of the business model, user statistics, and general business trends for CitiBike NYC in August 2018. We hope to use this valuable information as part of our business proposal to launch a CitiBike location in Des Moines, Iowa. We used Tableau Public to create many eye-catching visualizations describing key trends in NYC's bike-sharing program to convince our stakeholders that a bike-sharing program in Des Moines is a solid business proposal once we consider these trends when planning our own program. 

## Results of NYC Analysis

### Visualizations and their descriptions

![top_starting_locs](/images/top_starting_locs.png)

- Symbol map displaying the most popular bike rental starting points using the longitude/latitude values of all Starting Stations
- Size of symbol represents the popularity of each rental station (the larger the symbol, the greater the number of rides starting from that location)
- Colour provides a clear indication of relative popularity
  - Red = least popular rental starting point
  - Green = most popular rental starting point
- Locations of the largest and darkest green symbols show that major tourist spots/high-traffic areas should be prioritized when planning where to install bike rental starting locations for Des Moines 

![top_ending_locs](/images/top_ending_locs.png)

- Symbol map displaying the most popular bike rental ending points using the longitude/latitude values of all Starting Stations
- Symbol and colour representation is as stated above for Top Starting Locations
- Locations of the largest and darkest green symbols show that major tourist spots/high-traffic areas should be prioritized when planning where to install bike rental ending locations for Des Moines 
- The largest and darkest green symbols in the Top Ending Locations almost overlap with the Top Starting Locations, which means that both should be installed in the same areas (maybe side by side)

![checkout_user](/images/checkout_user.png)

- Line graph displaying the length of time that bikes are checked out for all riders, filtered by the 24 hours of the day
- Highest peak within the rider's first hour
  - Almost 150,000 bikes checked out within 15 minutes
- This graph indicates that bike rental stations in Des Moines should be prepared for a quick turnaround as most bikes are checked out for 15 minutes

![checkout_gender](/images/checkout_gender.png)

- Line graph displaying length of time bikes are checked out for all riders, filtered by hours of the day and with colours representing gender
- All genders reach their peak number of bikes checked out within the first 15 minutes of the hour 
- Most of the riders have self-identified as male (~110,000 out of the 150,000 total bikes were checked out by males as indicated by orange line)
- This graph further supports the last graph's conclusion; this graph also shows that majority of customers in NYC were male

![trips_weekday_hour](/images/trips_weekday_hour.png)

- Heatmap displaying the number of bike trips by weekday for each hour of the day
- Graph shows that peak hours with the greatest number of rides (indicated by darker orange/red colour) are 5pm-6pm on Mon, Tues, and Thurs
- General trend shows that morning rush hours during the weekdays (8am-9am) and evening rush hours during the weekdays (5pm-6pm) have large number of trips
- Des Moines locations should plan for these rush hours by ensuring we have enough bikes during these hours 

![trips_gender_weekday](/images/trips_gender_weekday.png)

- Heatmap displaying the number of bike trips by weekday and by gender for each hour of the day
- The above trend for morning and evening rush hours during the weekdays is seen in this heatmap for all genders
- Darker areas are more present in the Male heatmap, but that may be due to much of the data consisting of male riders

![usertrips_gender_weekday](/images/usertrips_gender_weekday.png)
- Heatmap displaying the number of bike trips by weekday, gender and user type
- Overall, male and female subscribers are going on more bike trips during the entire week in comparison to male and female customers 
- Overall, unknown customers are going on more bike trips during the entire week in comparison to unknown subscribers

## Summary

### Higher level summary

Analysis of NYC CitiBike August 2018 data supports the success of a future Des Moines bike-sharing program pending it prioritizes the construction of rental locations in tourist sites/high-traffic areas and supports the workforce by ensuring enough bikes are available during the morning/evening rush. Des Moines should prioritize diversifying their customer/user pool and incentivizing customers to become subscribers. 

Two additional visualizations that could be created for further analysis are:

1. Repair Facility Locations - Symbol Map 
    - Comparing the distance between repair facilities and top starting/ending locations 
    - This visualization could help with improving efficiency in repairing bikes and transporting them to the rental locations

2. Checkout Times by User Type - Line graph
    - Similar to Checkout Times by Gender
    - this visualization will help us understand the needs required by each user type (subscriber vs customer) and whether we can target deals/incentives to convert  customers to subscribers 

## Tableau Public Link
[link to dashboard](https://public.tableau.com/views/NYCCitiBikeWorkbookModule14/NYCStory?:language=en-US&:display_count=n&:origin=viz_share_link)
