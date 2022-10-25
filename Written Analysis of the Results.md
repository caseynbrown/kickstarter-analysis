# Kickstarting with Excel

## Overview of Project
Louise is an up-and-coming playwright who wants to start a crowdfunding campaign to help fund her play. This project is intended to help Louise analyze the data of thousands of crowdfunding projects to discover any trends or relevant information to help her. 
### Purpose
Louise's play "Fever" fell close to its fundraising goal. Showing Louise visual demonstrations of the data in the forms of graphs and charts will assist her in understanding campaigns from start to finish. 
## Analysis and Challenges
To better demonstrate to Louise the outcomes of the campaigns based on their goals, I used the existing Kickstarter data set and extracted the percentage successful, percentage failed, and percentage canceled based on the fundraising goal. 
I then analyzed the outcomes of a specific subcategory based on launch date. This provides Louise with a detailed picture of successful, failed and canceled outcomes by month. 
### Analysis of Outcomes Based on Launch Date
![Theater Outcomes Based on Launch Date](../../../Theater_Outcomes_vs_Launch.png)
I used the Kickstarter data set to create a visualization of the outcomes based on launch date for the subcategory Theater. I created a pivot table and added filters of parent category and years. Then added outcomes as a column, date created conversion as a row, and count of outcomes as values within the pivot table fields to display the correct data I was looking for. I filtered by theater, which provided the requested results. The final step was taking the filtered results from the pivot table and creating a line chart that was easily understandable and readable. 
### Analysis of Outcomes Based on Goals
![Outcomes Based on Goal](../../../Outcomes_vs_Goals.png)
I used the Kickstarter data set to create a visualization of the outcomes based on fundraising goals. I created a new sheet within the Kickstarter workbook to house the following data points: number successful, number failed, number canceled, total projects, percentage successful, percentage failed and percentage canceled, along with a reference point of different goal ranges. I took the data and created a line chart that showed the percentage successful, failed and canceled based on the goal ranges within the data.
### Challenges and Difficulties Encountered
One of the challenges within the dataset was the Deadline and Launched At columns had the dates in Unix timestamps format, which is not easily understandable or readable. To overcome this, I completed a conversion in order to make the dates understandable for analysis. 
## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
May, June and July were the most successful months for campaigns
Theater was the most successful category of campaigns 
- What can you conclude about the Outcomes based on Goals?
The most successful goals were between 1000-4999, and the most failed foals were between 45000-49999
- What are some limitations of this dataset?
There were no expenses or other potential financial factors within the dataset for review which could have a significant impact on campaign success
- What are some other possible tables and/or graphs that we could create?
We could create a pivot chart to display all categories and subcategories based on country individually or a box and whisker plot to demonstrate the mean, median and quartile ranges. 
