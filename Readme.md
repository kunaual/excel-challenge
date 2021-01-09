﻿
Data (1st sheet)--
Given kickstarter data in columns A-N:
* Utilized conditional formatting columns F & O
* Created columns O through T to use various excel functions:
		* Basic Math (Percent Funded - Column O)
		* IF (Average Donation - Column P)
		* text REPLACE/SEARCH (Category - Column Q & Sub-Category - Column R)
		* date conversions (Date Created Conversion - Column S & Date Ended Conversion - Column T)

Created 3 sheets to utlize pivot tables and charts (2nd-4th sheets):
1. Category Pivot sheet contains a stacked pivot chart comparing project status (successful, failed, canceled, live) per category.  The data is filterable by country.

2. Sub-Category Pivot sheet contains a stacked pivot chart comparing project status per sub-category.  The data is filterable by country and parent category.

3. Dates Pivot sheet contains pivot table and associated line pivot chart showing project state per month created.   Data can be filtered by parent category and year.


Created Percent Successful by Goal (5th) sheet utilizing COUNTIF function to show number of successful, failed, canceled projects for each goal level. Line chart displays the % of each state by goal level.

Created Backer Stats (6th) sheet to list the count of backers for each successful and failed project.  Used excel stats functions to display the mean (AVG), median, minimum, maximum, variance (VAR), standard deviation (STD) for failed and successful backer counts.

