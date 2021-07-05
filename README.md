# kickstarter-analysis

## Overview of Project

The purpose of this analysis is to help Louise to determine how different campaigns fared in relation to their lauch dates and their fundding goals.

## Analysis and Challenges

The analysis is performed based on the Kickstarter dataset. The raw dataset consists various of elements for campaign history. The most crucial data I used in this analysis are, launch date, outcome, country, category, goal and pledged. In order to answer Louise’s Question, outcomes were analysis against launch date and goal amount. Respective charts are included in the file Kickstarter_Challenge. The data was reorganized. Unix timestamp was converted to easier-to-read format. 
Two graphs were made, Outcomes VS Goals and Theater Outcomes VS Launch date. The challenge when performing the analysis was that there are situations that spelling error of the heading or in the function could lead to wrong auto fill if not examined carefully. In this analysis, errors were discovered from the check answer in the assignment material, thus corrected in time. I will pay more attention to detail in future analysis to avoid spelling error.

##Results

###From Theater Outcomes by Launch Date

![Alt text](resources/Theater_Outcomes_vs_Launch.png?raw=true )
According to the historical data regarding campaign outcome and launch date. The conclusion is that theater category campaign launched in May, June and July have significant more success comparing to other month of a year. Meanwhile, theater category campaign has less success toward end of a year, November and December. 

###From Outcomes Based on Goals

![Alt text](resources/Outcomes_vs_Goals.png?raw=true )
According to the data, in the subcategory of Plays, most project sets funding goal below $10000. And successful campaigns account for more percentage among campaigns under $15000. Campaigns that have goal in range of 15000 and above are more likely to fail.

###Recommendation

The recommendation from this analysis is that for theater category campaigns. The best launch date is from May to July. It is not recommended to launch toward the end of the year. In subcategory plays it is recommended to keep campaign goal lower than $15000. 

###Limitation

There are outliers in the dataset. Specifically, there are campaigns that set goal as $1, and there are campaigns setting goals at extremely high goals such as 30 million dollars. The outliers might affect the result of the analysis. Because the goal may not reflect the real expectation of the fundraiser.
