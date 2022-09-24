# Kickstarting with Excel

## Overview of Project

### Purpose
Our client's one of the plays are coming closer to reaching its fundraising goal in the near future. This project helps them to figure out patterns between successful campaigns, plays(specifically) and their connection to the launch time and the goal or target amount.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date-Part 1
The analysis was performed by creating pivot chart and changing the pivot fields according to criteria.The pivot table field criteria have been portrayed below.


### Analysis of Outcomes Based on Goals-Part 2
For the analysis of outcomes of the plays based on goals, 3 criteria were selected to populate the number of successful, failed and canceled plays.
- **Plays** from subcategory column in the kickstarter sheet.
- **Successful** from the Outcomes column of the kickstarter sheet.
- **Goals** from Goals column of the kickstarter sheet.

### Challenges and Difficulties Encountered
In the analysis of Part-1, the only challenge was to extract the month from given specific date, which was little tricky and exhausting for starters like me. Other difficulties might be in deciding which criteria to put in appropriate pivot fields, but can be resolved by trail and error. Other challenges could have been faced while applying the filters in the pivot chart.

The analysis of part-2 was quite a challenge for me. At first, I got error while getting correct numbers of successful plays for selected goal amount. The error was simply because I did not specify the "plays" in criteria section of the countifs formula. Other than this, once we fill out the Column B **Number Successful** with the formula, column C & D only required to replace **successful** to **failed** and **canceled**. No other challenges were faced. 

## Results

- ### What are two conclusions you can draw about the Outcomes based on Launch Date?
  Based on the analysis, following can be concluded:
  - The least favourable month to launch a theatre performace would be December. The predominant factor for the low success rate in December could be due to the holidays season.
  - The most favourable months to launch a theatre performance would be May, Jun and July. Amongst all three months, the month of May would be better to succeed the most.


- ### What can you conclude about the Outcomes based on Goals?
 The main conclusions one can draw from the analysis of goals based on the outcome is, higher the goal of the play, the lesser its chances to get succeed. Of course, there are some cases where plays succeeded despite of higher financial goals. But if we look on larger scale we can agree that, lower the financial goal of charity, more will be chance to get succeed.  

- ### What are some limitations of this dataset?
  - The datset could be more detailed to specify states or regions. For instance, if the states were provided then, it would be more helpful to find variation between the states.
  - The data should also consists the audience background like their age or gender, so that it would be helpful to target particular audience who are willing or likely to donate to meet the goal of play.   

- ### What are some other possible tables and/or graphs that we could create?
