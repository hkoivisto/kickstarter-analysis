# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to provide recommendations to the client on the most important factors of their kickstarter campaign to create the best chance of reaching the fundraising goal. Data from completed theater kickstarter campaigns is anlayzed to determine any trends in launch date and goal amount that could predict success or failure to raise funds.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I reviewed 1369 kickstarter campaigns within the Theater category. Of these, 37 were canceled, 493 failed, and 839 succesfully raised their goal amount. [(see here)](https://github.com/hkoivisto/kickstarter-analysis/blob/master/data-1-1-3-StarterBook.xlsx) Plotting these results  based on the campaign launch date, we can see that campaigns launched in May and June have the highest rate of success. Campaigns launched from October through Decemeber have the highest rate of failure. 

![Theater Outcomes Based on Launch Date](https://github.com/hkoivisto/kickstarter-analysis/blob/master/resources/Theater_Outcomes_vs_Launch.png)

It is recommened that future kickstarter campaigns be launched between May and June to provide the best chance of reaching the fundraising goal.

### Analysis of Outcomes Based on Goals
I reviewed 1047 kickstarter campaingns under the subcategory 'plays.' Of these, 694 were successful, and 353 campaigns failed. [(see here)](https://github.com/hkoivisto/kickstarter-analysis/blob/master/data-1-1-3-StarterBook.xlsx) I grouped these campaigns by their fundraising goal amount to look for trends in success or failure. While smaller goals tend to be more succesful than larger goals, this trend is only valid for goals up to around $15,000. Failure or success of campaigns targeting larger fundraising amounts cannot be considered to be dependent on goal amount.

![Outcomes Based on Goal](https://github.com/hkoivisto/kickstarter-analysis/blob/master/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
Though the analysis from Outcomes Based on Launch Date shows a clear trend of successful campaigns being launched in May and June, it does not take into account the number of total campaigns lauched for each month. If it was noted that number of campaigns launched varied siginificantly from month to month, further analysis could look at the percentage of successful campaigns by month. This anlaysis also does not account for the duration of the campaign. This presents a challenge in determining if failed campaigns could have been successful if allowed to fundraise for an extended period of time.

The analyis of Outcome vs. Goal Amount also encounters a challenge when trying to predict fundraising success for high dollar goals due to the limited number of campaigns attempted in these ranges. 92% of play campaigns had a goal amount less than $15,000.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  -Theater campaigns launched in May and June have the highest rate of success.
  -There are siginificanlty more theater campaigns launched in May and June as compared to other months.

- What can you conclude about the Outcomes based on Goals?
  -For the majority of campaigns, lower goal amounts have a higher chance of success. 

- What are some limitations of this dataset?
  -This data set does not provide information on how advertisement or promotion of these campaigns may have influenced outcome.
  -This dataset also does not provide a quantitative way to compare the quality of a proposed play vs. its outcome. The blurb provides some amount of description to subjectively analyze why some campaigns may have succeeded over others.
  
- What are some other possible tables and/or graphs that we could create?
   -It would be helpful to create a table and graph to plot percentage of successful and failed campaigns by launch date.
