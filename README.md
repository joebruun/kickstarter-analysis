# An Analysis of Kickstarter Campaigns

## Overview of the Project

The purpose of this analysis was to uncover and understand any hidden trends regarding the funding, outcomes, and launches of Kickstarter campaigns so Louise can decide the goal, launch date, and duration of her campaign for her play Fever. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Using pivot tables and filters, I extracted the necessary information to show Louise which month is the most successful month to launch her campaign for Fever, and which months have the most failed campaigns. From the graph below, we can see how many different campaigns for the category ‘Theater’ failed, succeeded, or got canceled in different launch months.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/76556050/138974151-30c2c6c6-0e70-4caa-8d4f-c8ce4ce0f561.png)

### Analysis of Outcomes Based on Goals

For this analysis, I used the COUNTIFS() function to populate cells with specific data and the SUM() function to find the totals of successful, failed, or canceled projects in different goal ranges. From the graph below, we can see the percentage of successful, failed, and canceled plays regarding their various funding goals. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/76556050/138974234-1f79df15-43cb-4e07-b049-f026dea00dc8.png)

### Challenges and Difficulties Encountered

While I didn’t encounter many challenges or difficulties, one difficulty I faced was using the COUNTIFS() function to populate a table. I remembered how to use the COUNTIFS() function to accept only one criterion, but couldn’t recall how to accept several criteria at once. Fortunately, I worked through some of the older lessons, implementing what I had learned into my worksheet. I learned that you can accept multiple criteria at once with the COUNTIFS() function simply by using a comma and stating a criteria range which is extremely useful if you only want to populate a cell or table with very specific information.

## Results

### What are two conclusions you can draw about the Outcomes Based on Launch Date?

From the (Theater) Outcomes Based on Launch Date graph, there are some conclusions we can make. Firstly, we can conclude that the best months to launch a campaign are May, June, and July as those months have the highest number of successful campaigns, while also having relatively low failed campaigns. Another conclusion we can make is that Louise should stay away from launching her campaign in October, November, or December as the difference between successful and failed campaigns decreases significantly, showing that these months are not ideal for launching a campaign.

### What can you conclude about the Outcomes Based on Goals?

From the Outcomes Based on Goals graph, we can conclude that Louise should set a goal for her campaign that is under $5000. We can make this conclusion as the graph illustrates how successful campaigns with goals between $1000 and $4999 account for 72.66% of the total projects for that funding range and successful campaigns with a goal less than $1000 accounts for 75.81% of the total projects for that funding range, meaning that having a goal under $5000 is ideal for a successful campaign. 

### What are some limitations of this dataset?

One limitation of this dataset is the sample size. While there are 4113 different campaigns, having more data from more campaigns can only help to improve our analysis so Louise can make a more informed and educated decision for her campaign. Another limitation is the outliers. The outliers skew our data and prevent us from making visually appealing worksheets, thus weakening the analyses and presentation we have made. 

### What are some other possible tables and/or graphs that we could create?

I believe we could have used pie charts to help illustrate the percentage successful, percentage failed, and percentage canceled for the outcomes based on goals. We would simply create enough pie charts with the funding ranges as their titles and percentages as their values. From here, we would easily be able to see at a glance which goal ranges had the most success and which goal ranges failed the most. This would also help to conclude which goal ranges are the best for Louise to set for her play. 
