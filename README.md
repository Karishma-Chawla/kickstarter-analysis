# Kickstarting with Excel
## Overview of Project
### Background 
This project is about analysing the fundraising campaigns to determine various factors like launch date /goal amount to help Louise with her fundraising campaign for a play. Louise has already run the campaign and raised the money close to the goal on a short amount of time. Now she wants to know how different campaigns fared in relation to their launch dates and their funding goals. 
### Purpose
The purpose of the project is to present the analysis of how the various fundraising campaigns for Theatre/ Plays have fared in relation to their launch dates and funding goals. 
## Analysis and Challenges
### Methodology:
The analysis was performed by 
1.	Creating  Pivot tables and Line Chart based on pivot to analyse various outcomes based on launch date for ‘Theatre’.
2.	Building a Table to analyse the outcomes based for bucket of 12 Goals from 0 to 50000+ for the subcategory of plays. Creating a Line Chart with buckets on  x axis and one line for each outcome.
### Analysis of Outcomes Based on Launch Date
![image](https://user-images.githubusercontent.com/98617082/156635620-cabdad30-c704-452b-87f3-4ed38d7eede9.png)

For analysing Outcomes based on launch date, line chart has been used with months on x-axis and number of launches on y-axis to visualize the trend in various outcomes based on date of launch.
It is observed that maximum number of successful fund raising campaigns for Theatre were launched in month of May followed June. Overall, May also saw the maximum number of campaign launches.
Almost half of the campaigns launched in December failed. Also the ratio of failed launches remains high in the months of October, November, January and March.
 
### Analysis of Outcomes Based on Goals
![image](https://user-images.githubusercontent.com/98617082/156635694-c3650fc5-1365-4ece-91f1-efd9c8fd2414.png)

Again, line chart has been used with bins representing various range of goals on x-axis and % of success, failed and cancelled campaigns for Plays. This is help determine what is the range of goals with maximum probability of success.
Campaigns with goal of <5000 have a high chance of success. Majority of the campaigns goals with goal >=45000 fail. 
In the higher end if the spectrum, campaigns with goals between 35,000-45,000 have higher success rates.
 
### Challenges and Difficulties Encountered
Challenges faced in this assignment was Use of function ‘Countifs’. Careful construction of Countis was needed to make sure that the right filtering is done and nothing is missed. Also given the length of the formula, it can be challenging to determine the error. To overcome this difficulty, I looked at the hint to ensure I applying the formula correctly and later checked for some of the results by filtering manually to ensure my formulas were working correctly.
## Results
### Conclusions for analysis on ‘Outcomes based on Launch Date’
1.	Launch of campaign in months of May/ June should have a good chance of success. Maximum number of campaigns are launched in the summer months of May/June and enjoy high success rate. 
2.	October, December and January should be avoided for launch. Almost 50% of campaigns launched in December failed. Overall, October, November December and March have higher proportion of failed campaigns.
### Conclusions for analysis on ‘Outcomes based on Goals’
Campaigns with goal of <5000 have a high chance of success. Majority of the campaigns goals with goal >=45000 fail. 
### Limitations of this dataset
Some of the limitations that I could identify were
1.	Dated information. The data contains dates till 2017 and no recent year information beyond 2017 is available.
2.	Inconsistent currency used. 
3.	Not much qualitative data available to access the reasons for anomalies.
### Additional Charts and graphs that could support the analysisas as below:

1.	Pivot table and Bar Chart on Outcomes based on country for ‘Theatre’ to identify the geography to target fundraising activities. Country on x-axis and Outcome on y axis with outcome as value.
2.	Line chart of year wise funding amount for Theatre to identify the trends in funding of Theatre campaigns. X-Axis will be year and Y-Axis will be total amount pledged for ‘Theatre” in that year.
3.	Box Plot to identify outliers for goal.

