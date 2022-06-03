# An Analysis of Kickstarter Projects & Campaigns

## Overview of Project
A client has requested information and insights into understanding and implementing successful Kickstarter campigns. The purpose of this project was to analyze theater campaigns on Kickstater to find associations, corelations, and causations within the dataset to derive a set of guidelines for future project launches to ensure the highest success rate in reaching 100% or more of the fundraising goal.

## Skills Used:
- VLOOKUP
- COUNTIF
- Pivot tables 
- Creating charts

## Analysis and Challenges
The analysis was done by using Pivot tables to create charts that displayed data-over-time in an easily digestible format
Example:
<img width="323" alt="PivotTable" src="https://user-images.githubusercontent.com/100488626/171947507-2ccb1072-e034-428b-a1cb-c7693efa6292.png">
It was necessary to use COUNTIFS functions to calculate the goal based outcomes, and this enabled me to get numeric counts from the original dataset that matched my specified criteria
Example:
=COUNTIFS(Kickstarter!D:D,">=30000",Kickstarter!D:D,"<=34999",  Kickstarter!F:F, "=Failed",Kickstarter!R:R,"=Plays")
*This function counts all plays with funding goals from $30,000 to $34,999 that failed to raise this amount
### Challenges


## Results
![LaunchOutcomes](https://user-images.githubusercontent.com/100488626/171944434-a5f2c330-db51-41bd-9a3d-8cc729a4c12d.png)
### What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Campaigns launched between April & July are the most successful with a 63%+ success rate, but these campaigns also face the most competiton
2. While it is reccomended to adhere to the conclusion above and launch April-July, February and November have particulary good success rates considering their smaller sample size and nonideal launch dates.

![GoalOutcomes](https://user-images.githubusercontent.com/100488626/171944130-fc476381-7c59-4cb5-a3c9-2f91c979755f.png)
### What can you conclude about the Outcomes based on Goals?
1. It is easier to successfully fund small campaigns, and once the goal is over $20,000, it becomes less likely to meet its goal.

### What are some limitations of this dataset?
To better help the client more information would be needed, such as:
1. The methods/mediums used to promote each campaign 
2. How much each campign met or missed its goal by
3. Data on the listing/landing page including photos, video clips, copywrite, and other design aspects critical to appeal

### What are some other possible tables and/or graphs that we could create?
1. Comparisons between country
2. Comparisons between different cateogries (theater, technology, food, games, etc.)
