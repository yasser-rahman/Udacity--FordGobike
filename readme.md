# Ford Gobike Data Exploration
## by Yasser A.Rahman


## Dataset
 
> Bike Sharing is one of the innovative solutions in very congested cities. This dataset concerns San Fransisco city in 2019.
The dataset contains the trip data of the ford gobike approximately 183,412 with 16 features (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip). 
I have decided to take trip duration as a target variable for this project and then study the variability with other features in the dataset.
I have chosen 3 other features to use in my analysis; namely; age of rider, gender of rider and user type.
Due to large amount of outliers in trip duration, I have decided to cut out duration greater than 60,000 seconds (100 minutes) as I assumed that 100 minutes are quite long duration for bike riding inside San Farnsisco city. and due to the fact that having this limit will not hamper the integrity of our analysis as more than 90% of trips were less than 19 minutes as will be shown in the analysis.



## Summary of Findings

> * 90% of rides are with duration less than 1158 seconds (19 minutes).
> * The most frequent rides in San Fransisco Bike Share is with duration of 10 minutes
> * The Age distribution is a unimodal one with its mode around 30 years old. The majority of the riders are between 20 and 40 years.
> * The ratio of male to female users is 3:1.
> * Subscribers have completed more than eight times the number of rides compared to customers who hold single-use or day-ride passes.
> * It's quite clear that there is an inversely proportional relationship between age and trip duration as it can be observed from the declining distribution of trip duration over age in years.
it's also very obviuos that the main age interval of riders arwe between 20 and 40 years. the peak of that age interval exists on 25-30 years old.
> * This is an intersting insight form this dataset. Female and other have a higher median of trip duration than Male.
> * This is also an intersting insight form this dataset. Casual customers have a higher median of trip duration (1.5x times) than regular subscribers.
> * There is no signifcant difference between male and female regarding the age effect on the rate of rides (same age group of both male and female are showing identical behaviuor).
> *The user type does not have any significant effect on the age profile of riders (same age group in both custmer and subscriber shows similar dependency with duratio trip). But, on the other hand, Customer type has a gap in the age group from 70-80 years old compared to Subscriber type.


## Key Insights for Presentation

> The Analysis has shown the folowing takeaways:

> * The most frrequent usage of bike sharing is around 10 minutes. So, looks it's inteded for short trip as a repalacement for regular trasnportation like bus or cab. This fact has been emphasized by a fact that more than 90% of rides are with duration less than 20 minutes.

> * The age profile for the majority of users are in range of 20-40 years old. with median value around 30 years old.
> * The ratio of male to female is 3:1. while women - in average - have alonger rides (with median value around 500 second).
> *Subscribers have completed more than eight times the number of rides compared to customers who hold single-use or day-ride passes.