# Learner-metrics
Online platform-student performance and engagement analysis
## Project Overview 
This project focuses on analyzing student performance and engagement on an online course platform. By leveraging data cleaning techniques in Microsoft Excel and powerful visualization capabilities in Power BI, it aims to provide actionable insights into student behavior, course completion rates, and learning progress across different course categories.
## Problem Solved 
Online learning platforms often face challenges in understanding why students drop off or complete courses. This project addresses this by:
* Identifying patterns in course completion rates across various course categories.
* Tracking collective student progress to pinpoint areas of success or struggle.
* Providing a clear visual overview of student engagement metrics.
* Thus, helping platform administrators and educators make data-driven decisions to improve course design and student support.
## Features
* Course Completion Analysis: Visualized completion rates broken down by course category.
* Student Progress Tracking: Monitored the progress of students through their enrolled courses, identifying potential bottlenecks. 
* Engagement Metrics: Analysis of time spent on courses based on age.
## Technologies Used
* Microsoft Excel: Utilized for initial data inspection, cleaning, transformation, and preparation of raw student data.
* Microsoft Power BI: Used for creating interactive dashboards, and visualizing key performance and engagement metrics.
## Data Source
The analysis is based on a .csv dataset containing information about students from different countries, their course enrollments,experience, progress, and completion status.
* Key Fields: Student details, country, age, gender, course name, course category, enrollment date, progress percent, time spent, completion, feedback rating and number of sessions attended.
## EXCEL(Clean)
* Raw data was checked for missing values and duplicates.
* Mising values of age substituted with mean(blue) and mail with unknown(red).
* All data standardised and data types corrected.
* Excel functions utilised to create two new columns for 'Experience level' and 'Engagement levels'(blue).
* High performers were identified(green).
## POWER BI(Visualise)
* Dashboard created with following:
* Custom DAX measures
* KPI Cards: Total Students, Avg. Progress, Avg. Rating, Course Completion Rate
* Bar/Column Charts: Students by Course Category, Completion rate by Country, Completion % by Category
* Matrix Table: Course vs. Feedback Rating, Avg. Time Spent per Category
* Line/Area Chart: Enrollment trend by month
* scatter plot: Correlation between Progress and Rating
* Engagement Heatmap
## Key insights
# overview 1 (filtered by course category)
* Features a breakdown of completion rates by the top 5 course categories and countries.
* Feedback rating received per course/category.
#  overview 2 (filtered by year, course, country and experience)
* Enrollment trend analysis for past four years and forecast of next three years.
* Study of corelation between progress and rating
* Display of average time spent by category.
# overview 3 (drill down)
* Engagement heatmap by course, country, gender.
 

