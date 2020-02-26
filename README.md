# Kickstarter Data Analysis Using Excel from Microsoft Office 365
<br>
<br>

## Background Information

Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.
<br>
<br>

## Project Goal:
Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. My goal is to organize and analyze a database of 4,000 past projects in order to uncover any hidden trends that will help will successfully executing a Kickstarter campaign.
<br>
<br>

## Analyses Performed:
- Identified which campaigns were: successful, failed, canceled, or currently live
- Calculated the `Percent Funded`  to discover how many campaigns reached its initial funding goals
- Use conditional formatting to fill each cell in the `Percent Funded` column using a three-color scale. The scale starts at 0 and is a dark shade of red, transitioning to green at 100, and blue at 200.
- Calculated the `Average Donation` to view how much each backer for the project paid on average
- Created two new columns, one called `Category` at Q and another called `Sub-Category` at R, which use formulas to split the `Category and Sub-Category` column into two parts.
- Created a new sheet with a pivot table that analyzes the initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per **category** and **sub-category**.
- Created a stacked column pivot chart enabling a filtered view by country and parent-category
- Converted the time and date to Unix timestamps for convertability and compadability
- 