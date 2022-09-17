# Kickstarting with Excel

## Overview of Project
This project reviews the historical data of how different Kickstarter campaigns have behaved. The objective of this revision is to establish the  best way forward for a play crowdfunding project in the US according to the retrospective data insights. 

### Purpose
The client Louise wants to start a crowdfunding campaign to fund her play *Fever*, therefore, the results and conclusions obtained from this assessment aim to set up her campaign for success.

## Analysis and Challenges
To determine the best strategy for Louise's crowfunding campaign the following factor were evaluated:
- Launch date: To determine if the start date of the campaing had a significant effect on its outcome. A Pivot table was created to summarize and better review the data.
- Goals: The specific amount that is set to be collected could have an impact in the success rate of the campaign, to evaluated this case a complementary table was created classifying the campaings by the monetary goal they were set to accomplish. 
- For both cases  only closed campaigns were evaluated, campaigns in the "Live" status were not included.

### Analysis of Outcomes Based on Launch Date
The data from 1369 *Theatre* category campaigns was used for this chart. The following line graph shows the number of theater campaigns that have succeded (green line), failed (orange line) or being cancelled (purple line) according to the month whent they were launched.

![Theater_Outcomes_vs_Launch.png](https://github.com/Li11iana/kickstarter_analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

As can be observed there were more successfull than failed campaings throughts the year, as well the number of canceled campaigns remains almost constant through the months.
The month of May has the highest count of crowfunding campaings with a total of 166, this month is also were most successful campaings were created with 111 campaings.
December contrasts with the least amount of campaings created. This month also has the almost equal amount of successful and failed campaings with 37 successful campaings and 35 failed ones.

### Analysis of Outcomes Based on Goals

The following line graph shows a line chart of all projects within the *Theater* Category specific for the *Plays* subcategory. The X axis shows the monetary goal range and the Y axis contains the porcentage of campaings that were sucessful, failed or were canceled for each monetary goal range. The successful campaings are denoted in green, blue for  failed campaings and purple for those that were canceled.

![Outcomes_vs_Goals.png](https://github.com/Li11iana/kickstarter_analysis/blob/main/Resources/Outcomes_vs_Goals.png)

The line graph shows that the success/fail ratio changes greatly depending on the monetary goal evaluated. The percentage of canceled campaigns remains constant throughout the different ranges.
The highest percentage of successful campaigns is found in "Less than 1000" with a 76%, followed closely with 73% of successfull campaings for those with a goal between "1000 to 4999".This second range also contains the highest amount of campaigns with a total of 534 projects.
The success rate for campaings in the "35000 to 39999" and "40000 to 44999" also shows favorable results with 67% of successful campaings for both ranges. Howeverk, only 9 projects had these monetary objective (6 projects in the "35000 to 39999" range and 3 projects in the "40000 to 44999" range).

The desired goal for Louise's play of $10000 falls into the range of "10000 to 14999" were 54% of the projects have had a successful outcome. Very similarly the range "5000 to 9999" has 55% of successful campaigns. It would appear that a 1% difference is not that important but there were more than twice as many projects in this range. Out of 72 projects in "10000 to 14999" 39 were successful and 33 failed, however there were 169 projects in the "5000 to 9999" range, 93 projects were sucessful and 76 failed.

### Challenges and Difficulties Encountered
In order to analyze the Kickstarter data it was necessary to transform timestamp dates into a working Excel date for both campaign start and end dates. For that the following converter was used to check the Unix Timestamps:
https://www.epochconverter.com/
Converted dates through excel Formula were added to the data sheet.

To have an initial sense of the data a series of pivot tables and graphs were obtained. 
* To do so it was important to review the data type for the cells, since the initial file had various formats and when using Excel formulas the final value might not be in the appropriate cell type.
* Another important aspect was to separate the data into secondary sheets in order to further analyze data subgroups, for example, successful vs failed campaigns and therefore, determine its key differentiators.

## Results

### Based on the Analysis of Outcomes Based on Launch Date

* May is the best month to launch the Kickstarter campaing.
* Decenber is the least favorable month to launch the Kickstarter campaing.

### Based on the Analysis of Outcomes Based on Goals

* Louise's play *Fever* goal of funding $10 000 appears to have a positive success change.
* Data shows that projects with smaller goals are more common and a have greater chance of success, if reductions on the budget are possible reducing the crowdfunding goal would be favorable to its success.

### What are some limitations of this dataset?

This data set provides a worldly view of crowdfunding campaigns, differenciating the campaigns only by country. For the current objective a more specific information about the campaigns in the US could provide more accurate trends, perhaps cultural hubs and more populated areas would behave differently than their conterparts.


### What are some other possible tables and/or graphs that we could create?

* Having notived the tendencies of success by launch date and goal further evaluation improve the recomendations. For example evaluating smaller goal ranges around $10 000 since its Lousie target amount.

* An additional table evaluating the time it took for each to achieve the goal could also be usefull to set an real expectation of how long it could take to obtain the requiered funds.




