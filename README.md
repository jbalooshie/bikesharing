# Bikeshare Analysis
This repository was created as part of a 6 month Data Analystics Bootcamp administed by George Washington University. This is the repository for the Module 12 Challenge. This challenge served as an introduction to Tableau. Topics covered included creating charts, graphs, heatmaps, views, stories, and importing data.

You can view the final dashboard here:
[Dashboard Link](https://public.tableau.com/shared/WZ4QPFMWY?:display_count=n&:origin=viz_share_link)

## Overview of the Analysis
### Purpose
The purpose of this project is to create a business case for starting a bikesharing business in Des Moines, Iowa. Using publicly available data from Citi Bike, we created seven visualizations that will help address questions potential investors might pose. These visualizations also help highlight areas of the business that might operate differently outside of New York City. 

### Methodology
The primary platform used in this project is Tableau. Tableau is a data visualization software that is easy to use but also can create robust representations. We will use existing data that is made freely available by Citi Bike. Although this data is specific to New York City, it can help us create a picture of how their customers utilize the service. This data is imported into Tableau, and then our visualizations are created in the software, and can be uploaded to their platform to be made available to interested parties. 

## Results
Below are seven visualizations that were created to explore the feasibility of starting a bike sharing company in Des Moines, Iowa. 

![Checkout Times](/images/checkout_times.PNG)
* This image shows the duration of rentals, by number of bikes rented. It can be filtered based on time of day. Right now, it shows that from 12am-1am, most trips are under 30 minutes, with the most only lasting 5 minutes. 

![Checkout Times by Gender](/images/checkout_gender.PNG)
* This image is like the previous but includes three separate lines showing the trends by gender. It can also be filtered by time of day. From 12am-1am, most riders are still only taking very short trips, but the gender of these riders is heavily skewed towards males. 

![Trips by Weekday](/images/trips_weekday.PNG)
* This image is a heatmap of the most popular startimes during the week. The most popular times of day are during rush hour in the morning and afternoon. 5pm - 7pm is the most consistently busy time of day. 

![Trips by Weekday by Gender](/images/trips_weekday_gender.PNG)
* Like the previous images, this one is a heatmap of the most popular startimes during the week, broken down by gender. Both male and female riders tend to follow the same patterns, but there is a much higher proportion of male riders throughout all times of day. 

![User Trips by Gender](/images/user_trips.PNG)
* This image is a heatmap of the number of trips by user type, separated by gender. The gender gap seen in other categories is also present here. It is interesting to note that subscribers make up a much higher number of riders for both males and females.

![Top Starting Location](/images/start_locations.PNG)
* This image shows the most popular starting locations for riders. In New York, this is around Midtown and Lower Manhattan. This tells us that the most popular locations have a high amount of tourist and commuter traffic. The more residential areas in Queens have less data points, indicating that bike share might not be a popular way for just getting around the neighborhood. 

![August Peak Hours](/images/august_peak.PNG)
* This is a bar graph showing the most popular start times. This reinforces that rush hour times are the busiest for the business. It also makes it clearer that the least busy times are 3-5am. 

## Summary
Based on our results, we believe that a bike sharing business is feasible in any urban environment. In New York, Citi Bike was most heavily utilized by male riders, Monday through Friday, during "rush hour" times. On weekends, utilization shifted to daytime hours. Many trips do not last longer than 10 minutes. Finally, the service is more heavily utilized by "subscribers" rather than one-time customers who pay for individual rides. Based on this, the target group for our services are regular commuters in urban areas who need to travel short distances quickly. 
 
### Additional Visualizations
Here are two suggestions for additional visualizations that might help us better understand our potential customer base. 
1. A visualization showing the start station latitude and Usertype categories to determine the most popular locations for subscribers and customers to start their rides. This can help us determine if certain locations need to be consistently filled with bikes. I.E., a station next to a subway stop might be very popular during the week with commuters with subscriptions but might become less trafficked on weekends with the commuters gone. 

2. A visualization that shows the number of rides on holidays. Certain holidays might be a good opportunity for maintenance if there is a large drop off in riders. Others might see a spike in riders. For example, the time around or on Christmas might see a decrease in riders. On the other hand, Memorial Day might see an increase as more tourists ride while taking advantage of the long weekend.
