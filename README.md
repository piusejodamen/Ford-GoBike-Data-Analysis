# Ford GoBike System Data Analysis
## by Pius Uagbae Ejodamen


## Dataset

> The Ford GoBike System data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset used for this study (named '201902-fordgobike-tripdata') may be made available on request; its about 37MB.

> There 183412 records and 16 features in the dataset. Participants in the ride sharing were either Subscribers or customers and were aged from 18 and above. No underage rode the bikes! The bikes were available for riding at various times - from morning to night!

> Some of the data had either quality issues or tidyness issues. The include: 
> - start_time and end_time should be converted to datetime datatype
> - convert start_station_id, end_station_id, bike_id datatype to string
> - There are empty (NaN) entries in some attributes. This should be looked into.
> - Create new columns - hour, day - extracted from the 'start_time' date column
> - Birth year alone donot state the age. Create another column to contain the ages of each rider.

> It was important to clean the data so as to be able analyse them correctly.

## Summary of Findings

> The charts show that riders in the 'Customer' category, had more ride duration than those in 'Subscriber' category. This could be interpreted that, while there are more subscribers embarking on rides, they spend less time riding. On the other hand, the customers who gain access to the bike, tend to ride much longer that their subscriber counterparts.

> Comparatively, there are lesser riders on Saturdays and Sundays. Probably, this may be due to lesser people riding to work and weekends are used for fun rides.

> Bikes will be more available for others, if those who collect bikes return them. Among the known age groups, riders in the Elder age group spend lesser time riding and hence return them so others can collect.  Also, they take a little more time during riding to arrive at their destination. Whereas, the Youth were fastest covering their route!

> Data indicates that an Adult will likely prefer Thursday to ride.

> There is a group of individuals that did not specify their dates of birth. This category, if considered, spends far more time riding than others.

> We see from charts that male customers spend more time riding than male subscribers. 
> Subscribers have a very stable riding pattern, whereas customers have very irregular ride pattern. 

> The Youth, Adult, and Elder follow similar pattern in the time they start their ride and the duration per day. The youth class spend lesser duration riding than the adults and elders. However, on Thursday the three main classes tend to ride at same pace.

> Saturdays and Sundays witnessed more ride time, despite the significantly lesser riders on Saturdays and Sundays. Probably there are lesser demands for bikes, resulting in more time available for those that come for it.

> The male gender rode fastest! The female gender was significantly slower than their male counterparts, but faster than the unclassified gender and those indicated as "other".

> The male and female genders have very similar riding duration pattern, except on Sundays where there is a drop on the riding time by males.


## Key Insights 

> We see from charts that male customers spend more time riding than male subscribers. 
> Saturdays and Sundays witnessed more ride duration, despite the significantly lesser number of riders on Saturdays and Sundays. Probably there are lesser demands for bikes, resulting in more time available for those needing bikes to come take them.
> From the pattern in data, we can perceive that subscribers are workers who ride to work on weekdays since there is a regular ride time during this period. They spend more time at weekends, probably for fun rides.
> Among the known age groups, riders in the Elder age group spend lesser time riding.  Also, they take a little more time during riding to arrive at their destination. Whereas, the Youth were fastest covering their route!
