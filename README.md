# (Ford GoBike EDA)
## by (Ahmed Muhumed)


## Dataset

> Ford, in collaboration with Motivate has launched Ford GoBike – a regional bike-share network designed to enhance sustainable transportation in the San Francisco Bay Area. Designed for the hilly urban environment of San Francisco, Ford GoBikes are built to be comfortable and easy to ride. Ford GoBike is the Bay Area's bike share connecting you to work, friends and your favorite restaurant. Thousands of bikes to pick up and drop off anywhere. No schedule. No rails. Ride your way. Available in San Francisco, San Jose, and the East Bay 24/7. here is the source of the data [here](https://s3.amazonaws.com/fordgobike-data/index.html)

>This dataset contains 174952 entries and a total of 16 columns. In other words, we have 16 features in this dataset:
         
         1. duration of the trip in seconds
         2. start time and end time
         3. id, name and the coordinates of the start station
         5. id, name and the coordinates of the end station
         6. bike id
         7. user type (Customer or Subscriber)
         8. birth year of the member
         9. member gender (Female, Male or Other) 
         10. bike_share_for_all_trip - if it is round trip or not    
         
> Most of the variables are numeric (int and float), and there are object variables.

> For the data wrangling steps, I have visually and programmatically assessed the entire dataset. There have been some quality issues in the dataset, so, I have cleaned them, I have dropped all the null values for the sake of convenience analysis. Moreover, I have changed the data types of some columns.


## Summary of Findings

>In the dataset, we have higher of males compared to females and other genders. Also, we have higher number of subscribers compared the number of customers that have been used the bikes. The age of the bikers is highly distributed around 25 up to 45. Moreover, the most of the trips were one-way trips. In single variable exploration of data, I have compared the variables of interest. I have compared the age of the bikers and the frequency of the user types, and I have explored that in terms of frequency, subscribers are always higher in number than the customers. But the relation that exists is that the higher frequency of user types coincides when the age is between 25 up to 43. I have also explored the relationship between the gender types and the frequency of user types, and I have noticed that the males have the highest subscribers and customers, where the females are next the males and the other genders have the smallest number of subscriber/customer user types. The relationship between the age of the bikers and the duration of the trips is also plotted. In multivariate exploration of data, I have compared the three variables of gender, age and the user types. So, I have observed the median, first and third inter quartiles in order to get the relationships between these variables. I have noticed that when we have subscribers – largest number of the users, the median coincides the ages between 36 to 40 approximately in all gender types. The median of user types in all different genders does not vary.


## Key Insights for Presentation

> In the key insights of presentation, I am going to present the descriptive statistics of the duration of the trips, the gender composition of the bikers, start stations that are mostly used by the bikers, the age distribution of the users, the bikes that are mostly used, the relationship between the age of the bikers and the duration of the trips, user types according to round trips, are the customers usually take a round trips or subscriber take a round trips and the relationship between the age of the bikers, gender of the bikers and their user type.