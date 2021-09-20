# Kickstarter-Project

## Overview of Project
The playwright, Louise wants to kickstart her theater production using crowdfunding campaign. This analysis gains insights from existing Kickstarter dataset to determine factors that were critical in making a campaign successful.  The existing dataset is organized, analyzed, and visualized in microsoft excel to communicate relevant findings to Louise.

### Purpose
The purpose of this project is to determine if Louise's fundraising campaign will succeed, fail, or get canceled based on the time of the year when the campaign is launched.  Furthermore, through analysis of fundraising goals of existing plays, this project conveys successful goal targets for this campaign.

## Analysis and Challenges 

### Analysis of Outcomes Based on Launch Date
First, a pivot table is created from the Kickstarter sheet to determine the time of the year that is most suitable for starting a campaign. This pivot table is filtered to show data for parent category “theater”. The total number of successful, failed, and canceled campaign outcomes are added for all the years since the campaigns started and further categorized by months of the year in rows. A line graph is created from this table to show the general trend for successful, failed, and canceled campaigns.


![Theater Outcome Pivot Table](https://github.com/vedikanigam/Kickstarter-Project/blob/main/Resources/Theater_Outcome_vs_Pivot_Table.png)


### Analysis of Outcomes Based on Goals
The analysis of outcomes based on goals is performed by first categorizing projects based on their goal amount. These categories define different dollar amount ranges sorted in ascending order. The total number of successful, failed, and canceled projects are shown in these categories as numbers as well as percentages. The percentages are further plotted in a line graph to show a general trend. 


![Theater Outcome Based on Goals Graph](https://github.com/vedikanigam/Kickstarter-Project/blob/main/Resources/Outcomes_Based_On_Goals_Table.png)


### Challenges and Difficulties Encountered

## Results

### Conclusions about the Outcomes Based on Launch Date

- **Finding 1** - 
	From the chart below it can be concluded that most successful theater campaigns occurred in May. However, during May failed theater campaigns were also the highest. 
- **Finding 2** - 
	There is a steep downward trend in successful plays from May to September and from October to December. 
- **Finding 3** - 
	May, June, July, and August had nearly the same number of failed campaigns launched. 
- **Finding 4** - 
	At the end of the year in December the number of successful theater campaigns is almost equal to failed theater campaigns. 


![Theater Outcome based on Launch Date](https://github.com/vedikanigam/Kickstarter-Project/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Conclusions about the Outcomes Based on Goals

- **Finding 1** - 
	The theater campaigns for plays were most successful when the goal was either in the two categories - below $1000 or when it was between S1000 and $4999. 
- **Finding 2** - 
	Two other goal categories in which the projects were successful was between $35000 and $39999 and between $40000 and $44999. However, this finding was based on a very small sample size and therefore may not be reliable.
- **Finding 3** - 
	No projects got canceled for theater campaigns for plays.
- **Finding 4** - 
	Most failed campaigns happened when the goal was set between $25000 and $29999 or when the goal was greater than $45000.


![Theater Outcome based on Goals](https://github.com/vedikanigam/Kickstarter-Project/blob/main/Resources/Outcomes_vs_goals.png)

### Limitations of this Dataset
One of the limitations of this dataset is that there is no information about the quality of the projects and what were some other factors that influenced pledged versus goal targets.

### Possible tables and/or graphs that can help with analysis
For, campaign outcomes based on launch date chart, it may be useful to see the percentages of successful, failed, and canceled projects in a chart. 


