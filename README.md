# Kickstarting with Excel  
An Analysis of Kickstarter Campaigns.  
Performing analysis on Kickstarter data to uncover trends Vanderbilt University Data Analytics and Visualization Bootcamp, jun 2021  
## Overview of Project  
The playwriter Louise need assistance to create a crowdfounding campain for her play "Fever", she also wants to know how different campaigns fared in relation to their launch dates and their funding goals.  
### Purpose  
The purpose of this task is to organize, analyze, and visualize crowdfunding data obtained in the course of 8 years from 2009 to 2017 in order to gain insights into what makes a crowdfunding campaign successful. With these inisights Louise can make decisions that give her a better chance of succeeding.  
## Analysis and Challenges  
With the use of Excel I was able to organized the raw data in order to make the analysis more efficient, the category and subcategory data were parsed into two new columns: a parent category and subcategory, an average donation column was created and calculated by dividing the pledged data by the number of people that donated to the campaign, the deadline and launched at data was displayed in Unix timestamps and were converted to Date data in two columns: Date Created Conversion and Date Ended Conversion, a new column for the year was created too using the new Date created conversion column.  
I was able to find that failed campaigns have much higher fundraising goals than successful campaigns and Louise is asking for more than twice the average successful goal, this is not good for her campaign, the mean campaign goal is around £4,000 and half of the campaign goals are less than £2,000, which is just over the 3rd quartile for amounts pledged.  

-The following graphic chart shows a representation of Goals and Pledges that sustain the conclusion we arrived to:  
![box and whisker Analysis plot](https://user-images.githubusercontent.com/16723095/120903358-5ea8e900-c60b-11eb-8c82-5223c0c25ce0.png)

### Analysis of Outcomes Based on Launch Date  
There are a total of 1,369 campaign records in our Excel spreedsheet and 839 compaigns were successful, 493 failed and 37 were canceled. I created a pivot table chart to be able to arrive to the conclusion that most successful campaigns are held in May, Jun and Jul being May the top of them.  
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/16723095/120903373-71232280-c60b-11eb-9233-eac0403c6b7f.png)

### Analysis of Outcomes Based on Goals  
The analysis of Outcomes Based on Goals was conducted based on the dollar amount criteria, the number of different outcomes and the percentages based on the outcomes, campaigns with goals up to $5,000 have about a 75% of being successful, campaigns between $5,000 to $25,000 have roughly a 50% chance of being successful, projects with small budgets have more possibilities to reach their goals.  
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/16723095/120903384-797b5d80-c60b-11eb-8894-5ef175ef7047.png)

### Challenges and Difficulties Encountered  
The instructions were very clear and straight forward, I was able to make use of what I learned.  
## Results  
- What are two conclusions you can draw about the Outcomes based on Launch Date?  
	1-The more successful campaigns for theatre occur during May, June, and July, the campains created on May have a better opportunity of success.  
	2-December is not a good month to start a crowdfounding  
- What can you conclude about the Outcomes based on Goals?  
	Projects with a lower budget have more possibilities to get fulfilled  
- What are some limitations of this dataset?  
	The dataset only contain data from 2009 to 2017 which is out of date, the results we got from this dataset might not be accurate today     
- What are some other possible tables and/or graphs that we could create?  
	A graph comparing plays-specific data in different countries to determine whether the country of origin can determine success rate.   