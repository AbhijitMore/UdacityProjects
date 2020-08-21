# FordGoBike Insights and Visualization

## Dataset

The data consists of trip records of approximately 519700 bike trips. The dataset can be found at
[here](https://s3.amazonaws.com/baywheels-data/2017-fordgobike-tripdata.csv.zip),
with feature documentation available [here](https://www.lyft.com/bikes/bay-wheels/system-data).


## Summary of Findings

In the exploration, I found that there was a strong relationship between the
Trip duration, user type , weekday and month. I found a
somewhat surprising result that though subsribers are 4 times more than customers, customers tend to ride for longer duration.
On weekends i.e. saturday and sunday both subscriber and customer tend to ride for more duration than working days.


## Key Insights for Presentation

For the presentation, I focus on just the influence of the weekday and user type.
first I plotted distribution for each feature.
Afterwards, I introduce each of the categorical variables one by one. To start,
I use the violin plots of user type vs trip duration. Then I plotted weekday vs trip duration and month vs trip duration.
Lastly I looked at weekday vs trip duration for both subscriber and customer user type.
