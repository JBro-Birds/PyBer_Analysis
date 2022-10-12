# PyBer Analysis

## Overview of Project
PyBer is a ride-sharing app company valued at $2.3 billion.  The CEO has assigned this project to analyze all the rideshare data from January to early May of 2019 and create a compelling visualization.  In order to produce a summary, perform analysis and make recommendations python and Pandas will be used to create a summary DataFrame of the ride-sharing data by city type and Pandas and Matplotlib will be used to create a multi-line graph that shows the total weekly fares for each city type.  Rider and city type data .csv files have been provided as the data source.  The final deliverable is a written report that summarizes how the data differs by city type and how these differences can be used by decision-makers at PyBer.

### Purpose
The purpose of this project is to use images from the summary DataFrame and multi-line chart and describe the differences in ride-sharing data among the different city types.  Based on the results business recommendations need to be made to the CEO for addressing any disparities among the city types.

## Results

### Data Analysis Results
The student and school type data analysis shows comparisons of reading and math scores, school budgets and school student counts. A finding that stood out is the average math score for charter schools decreased from 9th grade to 12th grade by ~10% while public school average math scores remained consistent grade-over-grade. Performing additional analysis on the average reading score by school type and grade shows the charter school average decreased by ~10% from 11th grade to 12th grade while the public school average remained mostly consistent grade-over-grade.  There could be many drivers that impact math and reading scores between school types and grades, and from the dataset provided further reasoning could be determined by analysing the impact of school size (student count) and school budget values.  Running a groupby on school_name and then aggregating on mean math_score, mean_reading score, school_budget and student_count provides a useful summary to perform a deeper analysis to determine if there are correlations impacting scores.  In addition, the dataset provided could be more powerful by including demographics or other external factors for specific school regions in order to better analyze and determine drivers and reasons for fluctuations grade-over-grade within schools as well as comparing charter schools to public schools. 

Total Fare by City Type Line Chart:

![Total_Fare_By_City_Type_Line_Chart](https://raw.githubusercontent.com/JBro-Birds/PyBer_Analysis/master/analysis/Total_Fare_By_City_Type_Line_Chart.png)
