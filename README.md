# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this analysis is to illustrate how different campaigns fared in relation too their launch dates and their funding goals. This will allow the client to make informed decisions about when to create a Kickstarter campaign and the amount to set as the goal.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

For the analysis based on launch date, we created a pivot table and graph based on the launch date versus the number of cammpaigns with each outcome. This was grouped by month.
Optionally we could group by year to see overall trends. Below is the data for the theater category. It is also possible to filter by year. 

(rescources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

For the analysis based on goals, we created a pivot table and graph based on the goal amount versus the percentage of cammpaigns with each outcome. This was accoumplished by using the conditional function `COUNTIFS()` to sort based on goal amount and outcome.

(resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

Our data for the buckets that we sorted the goals into was inconsistent in size, so the Outcomes Based on Goals data may be skewed when viewing the chart for the sections with high goals. In the future, I would structure the buckets such that the size of data used is consistent between buckets. Alternatively, we could expand our data sets to view all theater projects rather than looking at plays alone.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The most favorable time of year to launch a campaign is in May or June, with the least favorable time being December.

- What can you conclude about the Outcomes based on Goals?

The crux at which it becomes more likely for a goal to fail than succeed is around $20000.

- What are some limitations of this dataset?

The plays subcategory had no canceled campaigns so that category is not represented in our analysis. All of this data is from a single source. I would be interested to compare with other crowdfunding platforms such as goFundMe.

- What are some other possible tables and/or graphs that we could create?

We could create a graph that compares theater trends over years rather than over months to see if it is becoming more or less popular to crowdfund for plays on Kickstarter. If we had more data, we could compare other modes of crowdfunding.
