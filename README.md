# fordgobike_exploration
Exploring fordgobike Dataset
# Ford GoBike System
## by Osama Salem


## Dataset

> There are 183412 rows (fordgobike trips), 4646 bikes. The trips in the dataset have 16 variables (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip) two of them are datetime, four are object type and 1 is bolean type and the rest are numerical.

> There wasn't much wrangling to be done except:

          > Changing start_time and end_time to datetime to be able to extract days and months if needed.
          
          > Change bike_share_for_all_trip to boolean.
          
          > Creating a column for age to see the impact of age on trip duration.


## Summary of Findings

> After The Univeriate Exploration:

    > The majority lasting below the 10 minutes mark and the average trip lasts between 1 and around 100 minutes.
    
    > Some station are frequent as start station and end station.
    
    > The majority of the users are between the age of 20 to 40 years old.
    
    > The majority of trips are led by Subscribers rather than Customers.
    
    > The male users are dominating the trips with more than 12000 users while the females are around or slightly more 4000 users.

> After The Bivariate Exploration:

    > The majority of users are between 15 to 45 years old with concentrated high duartion of trips around the age of 30 years old.
    
    > We can see that the duration for some stations as a start station for some are higher and for others as end stations are higher.
    Also we can detect a pattern of stations which might result in longer trip duration.
    
    > The amount of male riders are obviously higher than the others but the longer trips came from other and females more than males.
    
    > The longer trips were preformed more by Customers more than Subscribers.

> Multivariate Exploration:
    
    > More frequent longer duration for Other between the age of 50 to 60 years old.
    
    > We can see that both Customer and Subscriber are the same regarding the trends for age and trip duration.
    It's noticeable that there is a slightly higher age for subscribers having higher duration trips than customers.
    

#### Investigating the impact of age, the idea came from a user on kaggle and I used the idea by creating a user_age column to figure out the impact of age on trip duration. https://www.kaggle.com/skostis/data-analysis-fordbike-with-ride-duration-predict

