# Ford GoBike System Data Investigation
## by Meutem Gervis Dylan


## Dataset

### Structure of dataset

The dataset consist of 174955 entries, entries are made when a user uses Ford GoBike. Each entry records the user's information and the user's activity. Each entry has 13 features. The features are as below:
- duration_sec
- start time
- end time
- start_station_id         
- start_station_name    
- end_station_id       
- end_station_name    
- user_type         
- member_gender    
- bike_share_for_all_trip  
- member_age               
- weekday                  
- time      



In this dataset we have excluded missing information and inconsistent information. 

The variables in the dataset have been assigned to the correct datatype. The time variable has been assigned labels to aid visualisation.

### Main feature(s) of interest in dataset

Our interest here is to understand how customers and subscribers make use of the service in terms of duration, age,gender and frequency of use and mosrt importantly the user's behavior.


## Summary of Findings

We categorise our findings in terms of GoBike user behavior and GoBike user demographics.

In terms of user demographcis, we found that:
- majority of the GoBike users are males. 
- majority of the user base is between the age of 25-35.

In terms of user behaviour, we found that:
- GoBike users use GoBike for an average duration of 10 mins (600 sec)
- GoBike users are less likely to use GoBike above 30 minutes (1,800 sec)
- GoBike users tend to use GoBike more on weekdays
- GoBike users tend to use GoBike during peak hours: between 8-9am and 5-6pm


Looking at both user demographics and user behaviour, we found that:
- GoBike user age has no obvious relationship with the user behaviour (usage duration)
- GoBike user gender has no obvious relationship with the user behaviour (usage duration)
- GoBike user type has a large impact on the user behaviour
    - GoBike subscribers, in general uses GoBike for shorter duration
    - GoBike subscribers, in general uses GoBike for longer duration 
- Time has an impact on user behaviour
    - GoBike users tend to use GoBike less during weekends
    - GoBike users tend to use GoBike for longer periods of time during weekend
- Time has an impact on the user type
    - Subscribers tend use less GoBike on weekends, as compared to weekdays
    - Pool of customers that uses GoBike is fairly constant with time


## Key Insights for Presentation

The focus of the presentation is to bring the audience to understand Ford GoBike's users. We start with the trends in user demographic followed by trends in user behaviour and time. After that, we explored the effect of user demographics on the user behaviour.

The presentation starts off with understanding GoBike user demographics in terms of user type and gender. 

By looking into the age variable, we factor in the user type into the picture. We show the audience that we have 2 very different user base, namely: subscriber and customer.

With the introduction of user demographics, we introduce the factor of time into the picture. We look at the impact of time on the user behaviour. We left out some intermediate plots, and showed that time has an impact on the user behaviour. But not all users are equally affected.

We then looked into the impact of age on the behaviour, while still showing the two different group of user type. Age has no impact on the behaviour. On the other hand, by showing the different group of users, we let the audience know that the two groups of users behave very differently.

In the presentation, we left out the member gender, as it has no direct effect on the user behaviour. We also left out some exploratory plots that leads us to the findings. We know that age has no direct impact on the user behaviour. But it can serve as a good variable to showcase the difference in user behaviour between different user type.
As for color, we stick to 'Blues' for different user types, for a consistent perception on the color and the variables it represents. 

