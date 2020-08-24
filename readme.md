# Ford GoBike System Data Exploration 
## by Shiying Wang

## Preliminary Wrangling

> This document explores a dataset containing attributes for approximately 520000 trip history in 2017.



## Summary of Findings

> We could see that the customers seem to have higher trip duration than subscribers and median of the trip duration has a tendency of increasing. For customers, the peaks appear between August, September and October. Meanwhile, for subscribers, the peaks appear between October and November. There is no big differences between the 25% and median of the trip duration time. While, in month 10,11 and 12, users are more likely to use bike for a shorter trip which is approximately 400 seconds while in other months, users are relatively likely to use the bikes for 0 and 1000 seconds.

## Key Insights for Presentation

>For the presentation, I focus on just the influence of the trip duration. I start by introducing the distribution of the trip duration then plotting the transformed histogram, followed by the pie chart of user types.

>Afterwards, I introduce the pairwise relationship between categorical and numerical features: the plot matrix of boxplots of trip duration and start month and user types, the countplot of start month and usertypes. I have made another violin plot of trip duration and start month to make it clearer.  Lastly, I plot the multivariate relationship between the trip duration, user types and start month using the barplot.