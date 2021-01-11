# Random-Forest-Pricing-analysis
Is the subscribe fee too hight? too low? This analysis focus on if the increase of a product sale price is reasonable. A company ran a test that 66% of the users have seen the old price($39), while a random sampe of 33% users a highter price ($59). What is the performce of the test? Should they increase the price to gain more money? What drives the conversion rate?

# Data Explore
* The test ran betweeen May to March 2015
* There was no conversion rate of test data coming from Linex operative system --> something with the UI?
* Lots of user coming from New York. Overall data feature may adopt the primary segment data feature.

# A/B Test 
* Metrics: Conversion rate
the conversion rate of users with higher price is smaller than the cheaper price group
* Metrics: Avg Revenue
Avg revenue of users with higher price is bigger than users with lower price

**Generally speaking, although raising the price will hurt the conversion rate, but the general revenue level will increase. So we should sell the software for $59 to gain more revenueIf the goal of the test is too see if higher price brings larger revenue overall, the experiment is successful

# ML-- Random Forst: What drives the conversion rate
City, Source, and Hour are top three variables have impact on conversion rate
City seems to have the most impact on the oveal conversion rate.

## Closer look on New York
Hypothesis Test from New York shows the conversion rate of users with higher price is smaller than the cheaper price group. However, if we run hypothesis test on each city, cities are Chicago and Hilston are not very price sensitive. Their p-values are not significant.


