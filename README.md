# Cyclistic_analysis.github.io
OBJECTIVE

A marketing team believes the company’s future success depends on maximizing the number of annual memberships. Therefore,your team wants to understand how casual riders and annual members use Cyclistic bikes differently.

I have have divided my ananlysis in 6 steps.

1.ASK

This phase denotes to asking specific questions about business task in this case- Specific objective is already mentioned at top ,So focused more converting casual riders to annual members for speedy success of company.

2.PREPARE

In this step I imported data of last 12 months From companies data server through this link-https://divvy-tripdata.s3.amazonaws.com/index.html
after that i loaded necessary packages and libraries .
I imported this files in directory of R studio , after that i have used commands to import this data 
since, the data is divided in 4 quaters ,I have to combine them in further steps to get a complete data of past 12 months.

3.Process

since the columns in all 4 data is not same ,so i renamed the columns in 3 quaters of 2019 same as qauter data of 2020 for further process, after that i changed the data types of 
some particular columns for binding purpose.
after that i used commands to combine all 4 data set in a whole.
I found out some uncertanities in column member_casual there should be only 2 charaters in this column i.e either a rider is casual rider or member rider.
But the columns had 4 charaters - subsciber , casual , member , customer.
Therefore I used some codes and changed it to 2 charaters 

4.Analyze

created new columns for months,weekdays and year for analysis and changed ride length to numeric,after that created new table and used code(summary) to get the statistics of data.
created one more table to get the most and least used station for later marketing campaign.

5.Share and analyze

In this step I created visuals of data to get the exact story that the data tells and analyze it to draw usefull conclusions for speedy success.
I used ggplot library in R for creating usefull visuals of data.
I found out that casual riders rides mostly on weekend with greater length and the company have its peak on july and august.

6.ACT and Conclusions

new offer should be introduced for membership which will include lower ride charges for members in weekends.
reduced charges should be given for members after a particular ride length in weekends.
Marketing campaign should used in places with less use of rides ,starting station like LBS - BBB La Magie,south chicago ,Michigan Ave & 71st St etc.

wohoo,Finally I completed my project .
In this project I endorsed and learnt alot of coding and analyical skills.
