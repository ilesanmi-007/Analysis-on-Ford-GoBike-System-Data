# Analysis-on-Ford-GoBike-System-Data

# **Ford GoBike System Data**

## Dataset
The dataset, 201902-fordgobike-tripdata, is downloaded from Ford GoBike and licensed by Ford GoBike. 
This dataset includes 183412 trips with 16 features such as locations, time, and user attributes. There are start and end stations.
The dataset only has records for the second month -- February. I noticed that most trips happen on the same stations, 
so I subset the dataset by choosing top 10 trips start stations with the most trips. 


Thus, the following analysis is performed by this subsetted dataset.


# *Summary of Findings*

### Univariate exploration:
 
During the day, there are more trips in the morning and evening than there are at afternoon and night. 
The busiest hours are 8am and 5pm. 
This happen to be transition hours of workers hence the possible cause.
 
There are more male who use this services than women. Though their average age is close.
For the gender groups, the number of trips in male riders is 3 times more than the number of trips in females.
Judging by distance traveled by gender, though there are more men but also there are women with high duration rides

There are more subscribers than customers possibly due to the pricing.



### Bivariate exploration: 
There is a slightly negative correlation between age and duration of trips. 
And for the gender groups with most duration_sec, no gender explicitly won.
Average age by gender type is similar even with obvious variation are the subscribes

Top 10 station and the most usertype. Having more subscribers generally made it imbalance. But based on the data it is the subscribers 
that makes use of their services mostly

### Multivariate exploration: 
Used Facetgrid to look into the number of rides per the top10 trips start station for each day time. And the visuals still agrees with
former visuals that the morning have more rides. Followed by the evenig and then afternoon and night


## **Key Insights for Presentation**

We have more male users than females and the other genders
Most time of the rides are morning > Evening > Afternoon > night. And the most active hours are 8am and 5pm
We have more of Subscribers than customers and it seems the cusomers use the bikes in the afternoon well cause there's no drop
Theres a slight negative correlation between Duration_sec and member_age
The average age of users are close



Helpful reviews: 
https://review.udacity.com/#!/reviews/3614365
https://review.udacity.com/#!/reviews/3616766
