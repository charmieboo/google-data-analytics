# Google Data Analytics Capstone Project
# Bellabeat Fitness Tracker Analysis
<img width="223" alt="bellabeat_logo" src="https://user-images.githubusercontent.com/92185928/170800905-eaa108af-7a5f-45e6-ac5f-f9fc19b29d54.png">

## About
Bellabeat is a fictional manufacturer of health-focused technology products for women. Founded in 2013 and now a successful small company, Bellabeat wants to expand further into the global smart device market. The company currently offers several smart device products including a wellness tracker, a smartwatch, and smart water bottle, and an app to connect to these smart products and manage user data. Bellabeat offers a subscription-based membership for users to access fully personalized guidance on nutrition, activity, sleep, and mindfulness based on their lifestyle and goals.

## Stakeholder Goals
In order to better inform Bellabeat's marketing strategy, the company's cofounder and Chief Creative Officer would like to understand how consumers use smart devices across the market and find out how that may translate to the way Bellabeat consumers use their devices. They want to understand the following:<br><br>
<b>
1. What are some trends in smart device usage?<br>
2. How could these trends apply to Bellabeat customers?<br>
3. How could these trends help influence Bellabeat marketing strategy?</b>


## Dataset
The data source used for the case study is Fitbit Fitness Tracker Data. This dataset is stored in Kaggle and was made available through Möbius. The dataset contains personal fitness tracker from 30 Fitbit users. The dataset includes information about daily activity, steps, and heart rate that can be used to explore users’ habits.
* [FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit)


## Limitations
A limitation of a sampling bias could be presented due to the small size resulting between 8 users (minimum) to 33 users (maximum) and lack of demographic information. The dataset does not reveal whether the sample is representative of the whole population. Another potential issue is the relevancy of the information could be outdated since the scope of the data set reveals information from 2016 within a three-month time frame, March to May. Our case study entails an operational approach tapping into data to extract valuable insights.

## Data Preparation
For the most straightforward analysis, data was arranged according to granularity. Daily data (activity level, daily steps, sleep hours) was compiled together and hourly data was analyzed separately to assess trends across users throughout the day. This analysis will focus on overall user habits over days and hours.

Data was inspected, organized, and cleaned in Microsoft Excel before being loaded into Tableau for visualization. 


### This dataset has been visualized as an interactive dashboard in Tableau which can be accessed [here](https://public.tableau.com/views/BellabeatTrackerAnalysis/BellabeatTrackerAnalysis?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link).<br><br>
(![Bellabeat Tracker Analysis](https://user-images.githubusercontent.com/117857989/222955447-10938d21-b897-4bd8-b5f8-c5fa887b28aa.png)

## Analysis
For the purposes of this analysis, the question of searching for trends across the user base is extremely broad: this warrants more discussion of the stakeholder's goals and interests. However, for now, there are a number of interesting data points here. For example, in the daily data we can look at the date, total steps, total distance, distance over activity type, minutes of activity type, calories burned, minutes asleep, and minutes in bed. Some further questions I'll try to answer in regards to everyday use of the fitness tracker are: <br> <br>
<b>Q: How much time do users spend doing activities throughout the day?</b> <br>
A: Users spend 81% of the day sedentary, 16% of the day lightly active, 1% of the day fairly active and 2% of the day very active.<br><br>
<b>Q: Do users prefer rigorous workouts or more lowkey forms of exercise like walking? </b><br>
A: Based on the distribution of activity preferences, we can conclude that most workout-type activity undertaken by users is in the lightly active category (walking, pilates, yoga).<br><br>
<b>Q: Are users more active in the morning, afternoon, or evening?</b><br>
A: Users are more active in the afternoon and early evening, with the two peak activity times being 12pm-2pm and 5pm to 7pm.<br><br>
<b>Q: What range of activity level was observed among participants?</b><br>
A: Users ranged from an average of 916 daily steps to 16,040 daily steps. <br><br>
<b>Q: Does the user pool contain more sedentary, lightly active, fairly active, or very active users?</b><br>
A: Based on step count data, the user pool largely favors lower activity levels, with 24% considered sedentary, 27% lightly active, 27% somewhat active, 15% active, and 6% very active.<br>

## My recommendations to the stakeholders
* To help motivate users, the Bellabeat app could send daily, weekly, monthly recaps regarding the total number of steps, burned calories, and total time spent on the different activity levels. The app could send motivation to users who are not meeting their goals and send applause to those who meet their goals.

* The users have an average of 7,638 steps which is below the CDC recommended 10,000 daily steps. Additionally, the analysis revealed that the average user spent 81.3% of their day being sedentary. Bellabeat could send notifications on its app to encourage users to stay active throughout the day. The notification could include how many steps the user has taken so far and give examples on activites they could do to be more active.
