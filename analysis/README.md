# Ford GoBike System Exploration
## by Ebele-Muolokwu Nonso


## Dataset

> The data consists of information regarding 183,000 rides made in a bike-sharing system covering the greater San Francisco Bay area. The data features include duration (secs) and others such as DateTime, customer type, gender, as well as some additional variables. The dataset can be downloaded from !['https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv'](here)


## Summary of Findings

In my research, I discovered that trips typically last 500 seconds on average and that Tuesdays and Thursdays are the busiest days. The fewest trips have occurred on weekends, while having higher durations than other weekdays. The higher trip records for the eighth and ninth hours of the morning and the seventeenth and eighteenth hours of the evening are something else I discovered to be fascinating. The bustle at the two times of the day may be responsible for this. Over 90% of the rides were taken by subscribers, while more than 70% of all rides were taken by men.

I discovered that non-subscribers spend far longer on their excursions than regular customers do, and women typically ride for longer than men do. Bicycles can only be shared on excursions by subscribers, and these journeys make up roughly 10% of all rides.

The number of rides on any given day does not appear to be impacted by user type. Additionally, compared to subscribers, customer user type tends to spend more time traveling on any given day.
## Key Insights for Presentation

I exclude other variables and concentrate on the frequencies of rides per hour, day, and user type for the presentation. I begin by utilizing the seaborn countplot to examine trip frequencies by the user type, hours, and days of the week.

Then I go over each of the categorical variables individually. I begin by using the length over days and user type boxplot graphs. The following section uses point plots to discuss the other two categorical variables, days and user type. To ensure that it is obvious that each quality variable differs between plots, I have taken care to utilize distinct color palettes for each of them.