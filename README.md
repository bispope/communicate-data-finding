# communicate-data-finding
# (Ford GoBike Data System)
## by (Gozie Achebe)


## Dataset
> **Download the remaining files here -** https://drive.google.com/drive/folders/1L4dmqQEBikBzEHFtdKIrGDGwqOK2Smce?usp=sharing and https://drive.google.com/file/d/1obR0-MnO_N_Q5f1xbFlnjhGauoOSlg0O/view?usp=sharing
> Ford GoBike Data is a dataset with 16 columns and 183412 rows. The dataset contains information about the Bike Sharing System in San Francisco Area. The data pulled covered entries in February 2019. There bike station names, latitude and longitude of the stations, duration of the bike taken from the station, biker year of birth etc..


## Summary of Findings

> UNIVARIATE EXPLORATION: In this section, I took univariate exploration in the format “Question-Visualization-Observations” repeatedly

>Question 1: Which gender in the distribution of Ford GoBike data patronises the share bicycle system the most?
>Observation: The males are more in number. Up to 74.6% percent of the whole members are male. There are few that did not specify gender, 2.1% percent of them. The male patronises the bicycle share system
>Question 2 - What are the types of users or members and what is their distribution
>Observation: They are only two types of users: Subscriber and Customer. Subscribers are 90.5% of the total users
>Question 3 - What is the most common distance between start stations and end stations
>Observation: This is right skewed. Distances between start and end destinations are relatively small
>Question4: What is the age of the majority of the riders?
>Observation: Majority of the riders are in their 30's
>Question 5 - What are the major stations
>Observation: Most of the popular stations in the start_stations are also popular in the end_station. They are really popular stations. San Francisco Caltrain Station 2(Townsen St at 4t St) and Market St at 10th St are the most popular stations
>Question 6 - On which day of the month the riders had the highest number trips
>Obersation: Day 28 is the most occured day in the monyh of February 2019 when the riders had the highest activities
>Question 7 - At what points in the day do riders picked bicycle most?
>Observation: The hours are 7-9 am and 4-6pm having 8am and 5pm as the peak hour
>Question 8 - What is the common duration a user will be in possession of the bicycle
>Observation: The common duration of the bikers is around 300 seconds
>Question 9 - What is the percentage of those that share bike
>Observation:  Just 9.9% shared bike.

### BIVARIATE EXPLORATION
>In this section, I did bivariate analysis of the variables I have already done before
> Question 10: Do older persons share bike?
> From the violinplot, the age that share bike more is the young riders
> Question 11: Do we have more proportion of your male in males than female in females?
> The percentage of youger female in feamles is moe than that of male in males. Females have more yonger ones than the males in their ratio
>Question 12 - Do male riders use the bike longer than the females?
> There is evidence that males keep bikes a bit longer that the females
> Question 13: Is peak time for males different from the females?
> The peak time for males is almost the same for females. There is no significant difference observed in the peak hour for taking bikes
> Question 14: Is the peak days for males different from females for taking bikes?
> I could not find significant difference in peak days. Following the shape of the plot,  they have similar peak days for picking bikes


### MULTIVARIATE EXPLORATION

> Created plots of three or more variables to investigate your data even
further.
> Question 15: What is the relation between age and gender grouped by user type?
> The duration of the subscribers is less than that of customers for both male and female
> Question 16: What is the relation between start_hour and start_day grouped by Gender?
> No relationship is found here



## Key Insights for Presentation

> I investigated on this Ford GoBike Dataset. I did some wrangling that helped me to change types of some varables and also create more columns I would need. I went on to take 15 questions on which I used the plots to find the answers.
>My findings from this dataset are: The males are more in number. Up to 74.6% percent of the whole members are male. There are few that did not specify gender, 2.1% percent of them. The male patronises the bicycle share system. Majority of the riders are in their 30's. There is evidence that males keep bikes a bit longer that the females. The peak time for males is almost the same for females. There is no significant difference observed in the peak hour for taking bikes. I could not find significant difference in peak days. They have similar peak days for picking bikes
