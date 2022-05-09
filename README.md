# Kickstarting with Excel

## Overview of Project

The Excel File containing data on KickStarter projects in KickstarterAnalysis.xlsx contains name, 
funding, goals, categories, location, and temporal information. The data will be analyzed.

### Purpose
	
The Purpose of the Analysis is to obtain information and trends based on the data in 
KickstarterAnalysis.xlsx. By honing in our analysis on a few sub-characteristics, a view of specific trends 
appeared. The relationship between the success of a kickstarter and the date and funding were established. 


## Analysis and Challenges
	
### Analysis of Outcomes Based on Launch Date

To analysize the rate of success, failure, and cancellation with respect to date a pivot table was
created in a new sheet. It contains Year and Parent Category in the filters, Outcomes in the legend, Date 
Created in the categories, and outcomes in the values. A simple line graph was created to visual the specific
relationship between the month of creation of the theater kickstarters and the amount of successful, failed, and 
cancelled outcomes. This graph can be viewed in Theater_Outcomes_vs_Launch.png. The data seems to infer that
theater kickstarters beginning in summer months have a much higher chance of occuring.

### Analysis of Outcomes Based on Goals
	
A fresh table was created in a new sheet with ranges of funding goals for the rows and the amount of 
successful, failed, and cancelled projects for the columns. Percentages of success, failure, and cancellation
were calculated for each row. A line graph was created with the ranges of funding on the x-axis, and the outcomes
on the y-axis. This can be viewed in Outcomes_vs_Goals.png. The rate of cancellation and rate of failure have 
direct correlations with the funding goal. The percentage successful has an indirect correlation with the goal.

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	
The data we filtered for primarily concerns the outcome based on month. It shows that the theater 
kickstarters beginning in the warmer summer months are more successful with success peaking in May and June. 
It also showed that more theater kickstarters are created in the summer months than in the winter months.

- What can you conclude about the Outcomes based on Goals?
	
Our visualization of the data shows that the higher the funding goal a kickstarter has, the greater the 
chance of a negative outcome is. Kickstarters with a goal of >50000 had a 16% success rate compared to a 71%
success rate for those with a goal of <1000. The higher percentage of cancellations among kickstarters with high
goals indicates that many ambitious kickstarters are unable to meet expectations.

- What are some limitations of this dataset?

The Outcomes based on Goals data ignore kickstarters from the primary data sheet that are in between there launch
and deadline.Future analysis based on the location of the kickstarters used in the Launch Date analysis is 
needed so that other conclusions can be made.
	

- What are some other possible tables and/or graphs that we could create?

We could create tables relating broader timescales like year with the outcomes of the kickstarters.
Filtering existing tables by location could shed insight on why we are seeing the patterns in the month data.
