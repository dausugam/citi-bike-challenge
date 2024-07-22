# Module 18: New York Citi Bike (Tableau Visualizations)

## 01. Data

For this module assignment, the Citi Bike Trip History for June 2024 have been used. The information is publicly available on this [link](https://s3.amazonaws.com/tripdata/index.html). A total of 4,768,748 trips were analyzed.

## 02. Data Preprocessing

To combine and clean the information provided by the New York Citi Bike project, the Pandas library in Python was used. Additionally, the calculation for the total bike trip length (in minutes) was included. See the Jupyter Notebook `file data_preprocessing.ipynb`

## 03. Tableau Visualization

Various visualizations and dashboards were constructed using "Tableau Public 2024". See the Tableau file `tableau_file.twb`

## 04. Analysis of Results

The analysis of the New York Citi Bike project for June 2024 focused on two main aspects:
- Identifying the most popular stations used by users and determining the most common trips.
- Analyzing the average trip duration and examining differences between members and casual riders.

### Number of Rides

From the data collected for June 2024, it is evident that the majority of trips are concentrated in Lower Manhattan. The top three stations for trip departures were "West St & Chambers St," "University Pl & E 14 St," and "W 21 St & 6 Ave," with 18,141, 17,954, and 16,194 trips, respectively. These stations were also the top destinations, with 18,275, 18,200, and 16,248 trips, respectively.

Moreover, the most common trips for the month were:
- Starting and ending at "Central Park S & 6 Ave" with 2,124 trips.
- Starting and ending at "7 Ave & Central Park South" with 1,588 trips.

This suggests that these trips are popular among users for leisurely rides through Central Park, returning the bike to the same station.

The "Trips by Day and Rider Type" bar chart shows that casual riders predominantly use the service on weekends, indicating its use for leisure. In contrast, members displayed consistent usage throughout the week, suggesting a mix of leisure and commuting purposes.

### Ride Lenght

There is a significant difference in the average trip length between user types. Casual riders had an average trip duration of over 20 minutes, while members had average trip lengths of 11.69 minutes for classic bikes and 12.50 minutes for electric bikes. These results support the hypothesis that casual riders primarily use the service for leisure activities such as sightseeing and exercise, rather than for commuting.