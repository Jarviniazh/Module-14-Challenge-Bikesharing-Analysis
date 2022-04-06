# NYC Citi Bikesharing Analysis

## Overview

### Purpose
A friend Kate and I would like to start a bike share business for Des Moines Iowa after a trip in New York City. We were impressed by the NYC Citi Bike that we had biked everywhere, which allowed us to really get to know the city and interact with the people who live there and who are using bikes for their commutes. To present our business proposal to a potential angel investor, I decide to figure out how the bike-share business works in New York City using NYC Citi Bike data that has been released to the public. Since August can be a good month to visit New York City, I retrieve the data of August 2019 to analyze and visualize them for better understanding. 

## Resources
- Data Source: 
[Citi Bike program in New York City](https://ride.citibikenyc.com/system-data)
- Software: Python 3.10.1, Jupyter Notebook, Tableau Public


## Results
Staring with a general user information of NYC Citi Bike sharing service in August 2019, include the total service minutes, usertype and gender distribution, and sharing location map.

Then focus on the following aspect which could help us plan the business in Des Moines:
1. What Are Peak Riding Hours in the Month of August: The number of the bike trips for all genders of each hour are present with horizontal bar chart.
2. How long do users bike for: Total user checkout times are shown in line chart, which is then followed by the same graph filtered by gender. 
3. Who is using the bikes: Heatmaps indicate the number of bike trips for all riders and genders of each day of the week.
4. When are users using the bikes: Heatmaps indicate the number of the bike trip for each type of user and gender for each day of the week.

Use Tableau to visualize our analysis, please view the detailed figures:

[NYC Citi Bikes Analysis](https://public.tableau.com/app/profile/jiawen.zhao/viz/Module14ChallengeBikesharingAnalysis/Story1)


## Summary

#### Conclusion
The bike sharing business is popular in NYC with monthly total 2,344,244 minutes trip (daily average: 75,620 min).  The long-term and short-term customers have a different usage preference. The subscribers choose to take bikes during peak hours in weekdays, while the short-term customers bike short trip in weekends between 11am-5pm.

The majority of Citi bike users in New York City identify as Male. Additionally, these rides typically are annual subscribers for their commutes. Since the terrible traffic in NYC, bike may be an attractive transportation alternative.


#### Recommendation
Other than the current visualizations there should be more analysis to convince our investor.

- Visualization 1: Since the majority users are long-term subscribers that should be New York City residents. Understanding the relationship between sharing location and local population is a great way to predict our spots choice in Des Moines. Add the census data to map layer such as white collar occupation and population by census tract.

- Visualization 2: Bike utilization is a great way to estimate bike maintenance expense. Determine which bikes have the highest utilization, and map the check-in and checkout locations for the highest utilized bike.  
