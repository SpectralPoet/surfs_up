
# Surf's Up!

### Overview of the analysis: 

Weather analysis for a prospective surf shop in Oahu, Hawaii (mock)


### Results: 

<img width="173" alt="December Summary data" src="https://user-images.githubusercontent.com/21095468/128192496-2b2a451a-273c-4c14-8987-690240a74d47.png"> <img width="150" alt="June summary data" src="https://user-images.githubusercontent.com/21095468/128192510-3e49f08b-8eda-4f27-9df4-ca039ff6dc5f.png">

- On average, the results of the analysis are remarkably similar- within 4F
- The one thing that jumps out is a significaantly lower minimum in December, despite similar quartiles
- It's also perhaps worth noting that Demeber has about 10% fewer samples overall

### Summary:

![IceCreamSales](https://user-images.githubusercontent.com/21095468/128192122-e34a32df-6e42-4b67-8ff6-a802817fe80a.png)
Since the mean temperature of the two months are fairly similar I will conflate them usinga measurement of 73F, which is roughly 23C. (Also, imprtantly, while the min is very much lower than the mean, the 25% is not very different.) According to the analysis of Week 5, Day 1, Activity 8, a mean temperature of 23C should result in good sales.

Since weather can vary by local geography, I would do a query specific to the weather station closest to wherever we plan to open the shop. While it's likely there would be significantly less data due to the number of stations being queried in the original analysis, perhaps too few data points to draw valid inferences, it would be interesting at least to see if they deviate significantly from the population data.

I'd also like to get data on how ice cream sales vary by humidity, cloud cover, and rain, and so on- as I imagine some of those variables would have significant correlations- and plot those along with temperature on a line graph (or perhaps have several separate graphs to improve readability.)
