# Kickstarting with Excel

## Overview of Project
This project will help Louise with insights of her different campaings trough:
Definition number of canceled, successful and failed theater plays  based on lauch dates and, 
Calculation the percentage of canceled, successful and failed play during 2010 to 2017  in function of outcome ($)
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
To create a pivot chart it was necessary to get the month in text format. The results were:
839 OF 1369 Theater campaings were successful in the launch date. However 493 (~ 36%) of theater plays failed in the period of launch. The peak of these 2 outcomes are in May. Also, the cancelations represent less 3% of total of theater plays and there was not any during October. 
### Analysis of Outcomes Based on Goals
Table contains countifs in order to get information of several outcomes as a result:
% Of Successful plays were concentrate under $49999, Also the grafic shows the successful plays have a tendency of fall down when the goals are higher of $50000. Otherwise, failed plays stay under 33%    however, there was peak with plays >$50000 that means if play is expensive there may be more probability to fail. Finally, the % of  cancelations was zero.

### Challenges and Difficulties Encountered
 Deadline and launched_at: name of colums and format it does not make sense, I would add comments to let user what is these data
 Different currency. There will be a colum with exchange rate to get the equivalent in USD
 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
 60% of plays are successful during the period of time of analysis.
 Around 3% of plays were cancel.
 There is not a tendency in either of 3 outcomes 
- What can you conclude about the Outcomes based on Goals?
The mayority of successful plays generate outcomes  with less of $50000 and the failed plays > $50000 represent 83% of total of these categories
- What are some limitations of this dataset?
Missing data , live plays were not considerate in the analysis, several countries.
- What are some other possible tables and/or graphs that we could create?
Outcomes vs. country
Outcomes vs pledge 
subcategories vs. outcomes
subcategories vs . goal
years, subcategories, outcomes table
subcategories, goal vs pledge