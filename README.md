# bikesharing

# Overview
The purpose is to analyze bike trip data of the bike-sharing program launched in NYC.  
1. Customer breakdown based on gender and usertype.
2. Trip duration with starting, and ending locations.
3. Trip peak hours by weekday, and dayhour.
4. Trip peak hours by weekday, dayhour, and gender.

## Resources
- Data Source: NYC Citibike Data
- Software: Tableau 2021.3.3, Jupyter Notebook 4, Python 3.7.13, Visual Studio Code 1.68.1

## Results

### NYC Bike Trip Story

The link to the NYC bike trip story created by using Tableau.<br>
[NYC Bike Trip Story]("https://public.tableau.com/views/nyc_citibike_challenge_16625773674590/NYCCitibikeStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link")<br>

### Customer and location breakdown

1. Number of rides for month of August in 2019 are 2,344,224.
2. 65% customers are male, 25% are female, and 10% are unknown.
3. 81% customers are annual subscribers, and 9% are short term customers.
4. Most bikes are used close to business locations. 

<figure>
    <figcaption>Customer breakdown</figcaption>
    <img src="/customer_breakdown.png" width=901 height=auto
         alt="Customer breakdown">
</figure> <br>


### Trip duration

1. Most trips are less than 20 minutes.
2. It is likely that bikes are used by workers employed at establishments concentrated in business locations.
3. Most likely to travel from public transit to work location.
4. It explains 81% customers are annual subcribers while 9% are short term customers most likely tourist.
5. Majority of customers are male.

<figure>
    <figcaption>Peak duration</figcaption>
    <img src="/peak_duration.png" width=999 height=auto
         alt="Peak duration">
</figure> <br>


### Peak hours

1. Peak hours are 7-9AM and 5-7PM on weekdays.
2. It coincides with office hours.
3. Most used hours are 5-6PM on Monday, Tuesday, and Thursday.
4. Majority users are male.

<figure>
    <figcaption>Peak hours</figcaption>
    <img src="/peak_hour_day.png" width=1000 height=auto
         alt="Peak hours">
</figure> <br>

<figure>
    <figcaption>trips by gender</figcaption>
    <img src="/trips_by_gender.png" width=995 height=auto
         alt="Trips by gender">
</figure> <br>


## Summary

1. 65% customers are male, 25% are female, and 10% are unknown.
2. 81% customers are annual subscribers, and 9% are short term customers.
3. Most trips are less than 20 minutes.
4. Peak hours are 7-9AM and 5-7PM on weekdays.
5. Two additional visualizations to get more insights are locations vs bikeid and gender vs bikeid. It will help to design repair schedule.  