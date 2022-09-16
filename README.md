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
The following line graph shows 

![Theater_Outcomes_vs_Launch.png](https://github.com/Li11iana/kickstarter_analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The following line graph shows 
![Outcomes_vs_Goals.png](https://github.com/Li11iana/kickstarter_analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
In order to analyze the Kickstarter data it was necessary to transform timestamp dates into a working Excel date for both campaign start and end dates. For that the following converter was used to check the Unix Timestamps:
https://www.epochconverter.com/
Converted dates through excel Formula were added to the data sheet.

To have an initial sense of the data a series of pivot tables and graphs were obtained. 
* To do so it was important to review the data type for the cells, since the initial file had various formats and when using Excel formulas the final value might not be in the appropriate cell type.
* Another important aspect was to separate the data into secondary sheets in order to further analyze data subgroups, for example, successful vs failed campaigns and therefore, determine its key differentiators.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?


