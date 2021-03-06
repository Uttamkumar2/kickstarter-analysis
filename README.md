# Kickstarting with Excel

Given Excel contains several thousand crowdfunding data related to fundraising campaign in various category and subcategories like Films & videos, games, food, music etc. along with other details like goal which tell us that how much money each campaign will need to success,  and Pledge actually tells how much actually made, outcome tells whether it was success,  failed or cancel or still live, it also contains how may ppl participated in fundraising activity in a given country, All this data will help to visualize data trend and help in decision making process of helping Louise. 
## Overview of Project
Louise wants to start her fund-raising campaign for Play “Fever”, She wants to know how other campaign showed off in terms of date and time of launch and goal.
### Purpose
Analyze crowdfunding data by organize, sort, filter abstract data to help Louise with specific factors to make project campaign successful. 
## Analysis and Challenges
Louise is looking for other campaign fared in relation to their launch dates and their funding goals, it is required to analyze outcome based on launch date and goal, now challenge here is given excel has huge 4115 record, it required to improve its visual representation by doing sorting and filtring data, launch/Deadline dates are in UNIX timestamp format, which is difficult to read, that need to transform to date format using advance transformation formula. As its huge data it required to summarize with the help of PIVOT and graphs.
### Analysis of Outcomes Based on Launch Date
If you see in given line graph based on Parent category “Theater” on the “Theater Outcome Based on Launch Date” Chart, the month that launched the most successful Kickstarter campaigns was May & June. However failed campaigns were quite significant through the year starting from January to December. This can be determined by examining the points along the trend lines of the chart. As you hover over each point with your mouse pointer, a tooltip appears with the corresponding information.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/91766890/137613488-f2d6a465-3141-4d65-ad12-24a3eb6cfded.png)

### Analysis of Outcomes Based on Goals
As Louise want to do fundraising campaign, for her play “Fever”, it is required to analyze data to visualize different range of goal and are their success/failed/cancellation ratio for a given subcategory “Plays” and look at the percentage of success success/failed/cancellation rates with total projects in every goal range of $ 5000. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/91766890/137613494-2e03a392-5ed8-47c7-b0ae-e438616e733c.png)

### Challenges and Difficulties Encountered
To identify counts on status of outcomes, have to define range of goal of $ 5000 each, for optimum result.  to get counts of each outcome based on Goal range, has to use built-in function COUNTIFS () to scan “Kickstarter” sheet “Goal” column for reach range for a given outcome. Had little difficulties to display 0% to 120% in “Y” axis to match line graph as given in challenge. Once we removed counts on total project count it took max range of percentage. 

## Results
After visualizing outcomes from Launch data for given play “theater” and Outcome based on Goal Chart, its looks like best time for Louise to start her campaign for play “Fever” is between the month of may & June as the success is very high and found raising Goal should be close $ 5000 as success rate below 5000 is 76% and 73%.
