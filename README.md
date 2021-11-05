# kickstarter-analysis
performing analysis on Kickstarter data to uncover trends
# Kickstarting with Excel

## Overview of Project
In this project we are reviewing how different campaigns fared in realation to their launch dates and their funding goals.
In Kickstarter Dataset we are visualizing Campaign outcomes based on their launch dates and their fundig goals. we're going to have two dataset which one is outcomes based on launch date and the other one is based on goals and by creating pivot tables and pivot tables we're comparing the results and having a better understandig of data.

### Purpose
In Outcomes Based on Launch Date by using Pivot table and Pivot chart we're trying to visualize campaigne outcomes(successful, failed and canceled) based on launch date. and then we're reviewing this chart for specific categry which is Theater and we can easily compare the outcomes on new chart to see the differences.
In Outcomes Based on Goals, we're trying to calculate numbers and percentages of outcomes based on subcategory of plays and funding goals. and then reviewing the chart which is showing us relationsip between goal amount ranges and percentages of outcomes.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
In outcomes based on launch date, we're building a pivot table with outcome values, rows with date conversion, columns with outcomes and filter with Parent category which is Theater and years. and by visualizing the chart we relize that Theater category in failed projects is almost under 10 all year, canceled projects almost stays the same all year with slight difference in different months , but in successful projects by reviewing the chart we can see a huge difference in May and June, we have a good increase in successful projects which shows it's a good time we have the most projects and the most successful ones.

### Analysis of Outcomes Based on Goals
In outcomes based on goal, we're visualizing the percentage of successful, failed, and canceled plays based on the funding goal amount. for this purpose first we're going to count outcomes and goal data which we use coutifs() function to collect the information, based on "plays" in subcategory and with sum() function we collect total which makes it easier to calculate the percentage of outcomes. when we collect all the information we create a pivot chart which has goal amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis. 
By visualizing this chart, we haven't had any canceled project, everything is been successful or failed. we have a very interesting synchrony between successful and failed projects in dollar amount ranges. however in different goal ranges by increasing successful projects, failed ones are decreasing and by increasing failed projects, successful ones are decreasing which are very synchronized.
In the other hand, we can't see the real numbers of projects which for smaller amount ranges we have more projects and by increasing goal dollar amount, the numbers of projects are going down but in the chart we don't really see the difference because chart is based on percentages. 

### Challenges and Difficulties Encountered
in the outcomes based on launch date when I was trying to convert launch date format to date it was giving me a very large number that it's not even like a date, as I was searching for the result I realized that I have to use specific formula to find out the real date.and then I could use date column in my project.
and my next challenge was in outcomes based on goal, using countifs() function to count the numbers with different conditions. there is different solutions but I always want the fastest and easiest way.

## Results
-about the Theater outcomes based on launch date, according to pivot table we can see we have the maximum projects in May, June and July which seems the best time for Theater projects and we have the most successful projects which is great.
-about the Outcomes based on Goals, by reviewing the chart we can see the difference of total projects in different goal amount ranges, as we're increasing dollar amount ranges total projects are going down and we have the most successful projects in the less goal dollar amount, and by increasing goal dollar amount failed projects are going over successful projects.
-in dataset we are so limited bacause of the data size otherwise we could have more tables and charts to compare them and have more accurate results and a better understanding. in second chart outcome based on goals if we could have another chart based on numbers of projects we could have a better vision about the result.
