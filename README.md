# Kickstarting with Excel

## Overview of the Project

This project analyzes key datasets of kickstarter campaigns to assess for trends. Key data points include: goal amount, pledged amount, creation date, termination date, category, subcategory, and outcomes. The data was organized within Excel through the use of functions, data sorting, conditional formatting, and creation of pivot tables and charts. The outcomes were categorized as, "Successful", if the pledged amount was greater than or equal to the goal amount, "Failed", if the pledged amounts was less than the goal amount, or "Canceled", if the campaign was cancled without meeting the desired goal. In this project, the outcomes were assessed against the month of launch within theater campaigns and ranges of goal amounts for all campaign categories. 

### Purpose

The purpose of this project was to analyze data of kickstarter campaigns to assess trends associated with outcomes. 

## Analysis and Challenges

### Analysis Based on Launch Date
Kickstarter data was organized into a pivot table to display the trends between the launch month and outcomes. The data was filtered by theater category and portrayed as a line chart to show the trends of outcomes and monthly launch dates within theater campaigns. Below is the line chart showing outcomes of theater campaigns by month of launch. The line chart portrays a spike for successful outcomes for compaigns launched in the month of May and June. The campaigns with failed outcomes appears to depict a less severe flux throughout the months. The canceled campaigns remain relatively consistent between launch months, as well. 
![Line Chart_Showing_Outcomes_Trend_with_Creation_Date](/Resources/Theater_Outcomes_VS_Launch.png)

### Analysis Based on Goals
The number of successful, failed, and canceled campaigns within play subcategory were categorized according to the campaigns' set goal amounts in twelve ranges. The percentage of successful, failed, and canceled outcomes were analyzed for each goal range and displayed as a line chart, shown below. The ranges showing the highest percentage of successful campaigns were goals set to less than $1,000, $1000 to $4,999, $35,000 to $39,999, and $40,000 to $44,999. The ranges with the highest percentage of failed campaigns were goals set to $25,000 to $29,999, $30,000 to $34,999, $45,000 to $49,999, and $50,000 and more. There is no data for canceled campaigns withing the play subcategory.

![Line_Chart_Showing_Outcomes_Trend_with_Goals](/Resources/Outcomes_Vs_Goals.png)

### Challenges and Difficulties Encountered
Upon initial analysis of outcomes based on goal amount, I did not filter campaigns to only those within the subcategory "play". I had calculated percentages of outcomes for all kickstarter data and created a line chart. When I realized my line chart did not match the expected, I had to re-read the instructions, and recalculated the percentages for those campaigns within the "play" subcategory.

No other issues were personally encountered during the completion of this project. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
- Upon reflection of the data comparing theater campaign outcomes and months of launch date, it can be concluded that theater campaigns launched in the summer months, May-July, have a higher success rate than those launched in other months. It can als be concluded that campaigns launched in December, have the worst outcomes with the same number of successful campaigns and failed campaigns. After reviewing the line graph, the months May - July should be targeted as the launc date while September through March should be avoided.

- What can you conclude about the Outcomes based on Goals?
- Campaigns with goals set of less than $5,000 and between $35,000 and $44,999 showed to have a 60% success rate. While campaigns with goals set between $5,000 and $24,999 had a success rate between 60% and 40% and campaigns set with goals between $25,000 and $34,999 and goals set greater than $45,000 had a succes rate of less than 30%. Using this data, the target of the future campaign goal should be less than $5,000. 

- What are some limitations of this dataset?
- The kickstarter campaign data categories are not specific enough to depict the uses of money and does not explain the goals, backers, or any marketing data. The sources of the pledged amounts are limited to only listin the number of backers, and do not show any trends of bias in the data. The data is unable to answer the question: Are more backers willing to support campaigns for certain causes, or are backers selected due to personal relations with the campaigns? 

- What are some other possible tables and/or graphs that we could create?
- Other correlations I would be interested in, are between the outcome data and length of time that campaign was open. Is there an average length of time that campaigns were extended that ensure success? 
- I would also be interested in looking specifically at campaigns that raised the targeted amount ($12,000) and the goal amount, regardless of outcome. Is there a correlation between raising a specified amount and the set goal amount displayed to the donor?
