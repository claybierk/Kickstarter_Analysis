# An Analysis of Theatrical Kickstarter Projects

## OVERVIEW
A client has an idea for a play and is launching a Kickstarter campaign to fund it. They request insights on how to maximize their efforts. The purpose of this project is to analyze theatrical campaigns on Kickstarter and derive guidelines that ensure the client will have the best chance to fund their project fully

### LEARNED
1. VLOOKUP
2. COUNTIF
3. Pivot tables

## ANALYSIS
*Used pivot tables to create charts that displayed data-over-time:

Example:

<img width="323" alt="PivotTable" src="https://user-images.githubusercontent.com/100488626/171947507-2ccb1072-e034-428b-a1cb-c7693efa6292.png">

*Used COUNTIFS functions to calculate all campaigns with funding goals from $30,000 to $34,999 that failed to get funded:

Example:
```
=COUNTIFS(Kickstarter!D:D,">=30000",Kickstarter!D:D,"<=34999",  Kickstarter!F:F, "=Failed",Kickstarter!R:R,"=Plays")
```
## CHARTS

![LaunchOutcomes](https://user-images.githubusercontent.com/100488626/171944434-a5f2c330-db51-41bd-9a3d-8cc729a4c12d.png)
![GoalOutcomes](https://user-images.githubusercontent.com/100488626/171944130-fc476381-7c59-4cb5-a3c9-2f91c979755f.png)

## CONCLUSIONS

### - Launch between April & August 

## ADDITIONAL DATA NEEDED

### - The design of the individual campaign landing pages and media attachments
### - Play genre and marketing efforts run by each campaign
### - The dollar amount by which each failed campaign missed its funding target
