# case-study-google-data-analytics
## Cyclistic Case Study: Converting casual riders into annual members

<img width="111" alt="logo" src="https://user-images.githubusercontent.com/117749618/228404994-939fb3e8-11e7-4bca-bcb8-34ee6ce29e69.PNG">

### Introduction
In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime like rent and use. For now, customers who purchase single ride or full day passes are known as casual riders meanwhile customers who purchase annual memberships are Cyclistic members. 

Moreno has aimed at converting casual riders into annual members. In order to do so, the marketing analytic team plays a crucial part to understand how to differentiate both riders in Cyclistic. 
### Ask
They have identified the first step in data analysis which is to ask. The following questions will guide to the marketing program: 
 
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?

### Prepare
The data was retrieved from Index of bucket "divvy-tripdata". The data is organized from 2014 until 2022 in csv. format. We have downloaded the data of 2022 from January to December and stored it in a file on a desktop named trip 2022. The data was collected by the Cyclistic team for the team to help guidance in Cyclistic marketing strategy. In each file, there is information such as ride id, rideable type, time started, time ended, start station name, start station id, end station name, end station id, latitude, longitude and type of member. 
### Process 
After we were done with the preparation, we decided to choose Excel because it empowers you to understand your data through natural language queries that allow you to ask questions about your data without having to write complicated formulas. We have checked for data errors such as duplicates data, missing value or null. There are no duplicates in the data. We added new columns named “ride_length” and “day_of_week” to analyze my data. My team also checks the ride_length column that has a negative value. If so, then remove the row because time should not consist of negative values and always positive. 
### Analyze 
Now that our data is stored appropriately and ready for the analysis. We start by conducting descriptive analysis such as mean, min, max, mode, sum and count on the column “ride_length”. After that, I created a pivot table such as average ride length among riders, average ride length among riders by day, total riders by weekday, preference of bikes and total rides by day and rides. These steps perform repeatedly until the dec workbook. When finished, we merge them into a full year view. 
### Share 
Now, we have performed the analysis and proceeded to create visualization based on our findings. We decided to share the findings using a dashboard so that the stakeholder can see the clear meaning.

![Screenshot (456)](https://user-images.githubusercontent.com/117749618/228405067-7d008072-b189-44ed-9146-f350ca39c3f1.png)

According to data collected in 2022, It shows that Cyclistic members have about 3,345,685 rides while casual members only have 2,322,032 rides. Nevertheless, the casual rider has the longest trip taken compared to the members. 

Based on the chart average daily rides length, the casual rider shows the highest average ride length over the week while the members have almost uniformly ride length by week. A casual rider rode a bicycle most on Sunday with the average trip taking about 32 minutes and the least at 23 minutes on Tuesday. whereas the Cyclistic member's average trip took about 13 minutes 30 seconds on Saturday. 

The above chart of the type of bike used among riders reflects that riders tend to use electric bikes rather than classic bikes and docked bikes. It shows that the highest used bikes among the rest are from classic bikes and Cyclistic members with an amount 1,709,755. While, the highest electric bike user is also from members with 1,635,930 used and the least used bike is docked bike with 177,474 from casual riders. 

Analysis of daily ridership reveals inconsistent over the week. It shows most of the rides are conquered by cyclistics members rather than casual. The most peak rides for members occuring in Thursday followed by Wednesday and the least rides happen on Sunday. For the casual rider, their peak rides occur on Saturday followed by Sunday and friday. 

The chart above shows the monthly total of rider over the year 2022. The chart rises from January to July then plunges until december. Members of Cyclistic rides uprising in August at 427,008 rides from only 85,250 on january. 
### Discussion
Now that we have produced the dashboard, should we answer the question to help the marketing team. The insight from the question “How do annual members and casual riders use Cyclistic bikes differently?”: 
- Casual riders liked riding bicycles during the weekend while members preferred rides on weekdays
- Most of the casual riders rode the longest rides length compared to Cyclistic members.
- Members preferred using classic bikes while casual likes to ride using electric bikes. 
- Casual and member rides have the same pattern on their monthly ride which increases from jan to july then decreases until dec.
- Both riders like to ride on jun, july and august and not preferred ride on jan and december. 

Since the Cyclistic does not include the price of being a member, there is some insight from the question “Why would casual riders buy Cyclistic annual memberships?”: 
- Members can use most of the bikes without worrying about the price because they have premium access.
- They can ride as many as they want during the weekdays, not only on the weekend. 
- Since the casual rider enjoys rides, they can join a marathon at the end of the year with the rest of the annual memberships.

Last but not least, for the question “How can Cyclists use digital media to influence casual riders to become members?” we get several answers such as:
- It can be that the riders are from a young age, so Cyclistic can use the social media platforms that are famous among them such as Instagram, TikTok and Facebook. 
- Hiring an influencer to promote the benefit of becoming Cyclistic also plays a crucial part since about 92% of marketers believe it is effective marketing. 
- Cyclistic can develop their brand so that the casual rider has confidence to purchase the annual membership.
### Recommendation
Based on the analysis, the three top recommendation we found on the findings is:
1. Offer casual riders the best price when purchasing the annual membership so they can ride bikes during weekdays or use bikes as transportation to commute from one place to another.
2. Cyclistic can do campaigns to develop brand name by doing some fun activities such as free rides, fun rides, and marathons to attract casual members.
3. Since our country has inconsistent climate change, Cyclistic can offer a discount rate during January and December so that the annual membership does not feel like a waste of money.
