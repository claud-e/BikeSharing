# BikeSharing

## Overview
The purpose of this analysis is to explore the behavoir of CitiBike users in NYC during August 2019, with the objective of finding trends and useful information that coul be extrapolated to a similar business in a different city.


## Results

Seven visualizations were constructed to help explain the data.

The first one is the time users utilize the bikes. It is immediatly obvious that most rides are about 5 minutes long, and very rarely does anyone use the bikes for over 50 minutes at a time.
![hour distribution](/Checkout_time.png)

The next one is the same information as before but broken down by the gender of the user, this shows that the majority of our users are in fact male.
![hour distribution by gender](/time_by_gender.png)

Next we can see a distribution of the time of day vs the weekday when the bikes are used. It is evident that most uses of the service are from monday to friday at around 8 AM and 6 PM, probably due to the service being used by people who commute to work.
![hour vs weekday heatmap](/trips_by_weekday.png)

Here we see the same information as before but broken down by gender. We can see the same pattern for both genders but a different density of use, explained by the difference in users.
![hour vs weekday by gender heatmap](/trips_by_gender.png)

This heatmap shows that subscribers use the bikes more than customers, and the pattern of use remains that of mostly males prioritizing workdays.
![usertype and weekday vs gender](/user_gender_weekday.png)

This map shows the locations of all stations, and marks in a darker color those that are more popular, i.e. used the most.
![startstation map](/starts.png)

Finally, this graph shows the most active hours for bikes, which indicates the best time for maintenance to be performed.
![use times](/rides.png)

## Summary

Overall, this analysis shows that male subscribers are the majority of users, and that they use the bikes at times consistent with a normal work schedule. This analysis can be used to either accomodate specific needs for the users, or attract users of a different market segment.

Further visualizations to perform could be:
- a split of users by age to try and find who they are and what makes them chose us.
- a map that compares top start and stop stations, to find which routes are used the most and prioritize the number of bikes there.

To explore the Story itself follow this link:
[link to Story](https://public.tableau.com/app/profile/claudio.rocha3144/viz/CitiBikeNYC_16401960751490/CitiBikeStory?publish=yes)
