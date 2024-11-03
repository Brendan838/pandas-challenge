# PyCitySchools Analysis

## Overview

This project, **PyCitySchools**, is an assignment for the U of MN data science bootcamp that involved completing data tasks within a Jupyter Notebook. Using Python and the Pandas library, I performed data analysis on school and standardized test data to identify trends in school performance across a city’s school district. 

## Project Structure

- **Notebook**: The Jupyter Notebook in `PyCitySchools` is the primary script used for analysis, featuring data manipulation and table views to gain insights. This file was provided to me via the bootcamp and contained starter code. 
- **Data Files**: Relevant data files were provided (created using Mockaroo), enabling the analysis and generation of trend observations. Find these in the `Resources` folder. 


## Written Analysis:


# Summary:

This analysis involved two merged data sets. The first was a spreadsheet of students and some basic information (name, gender, grade, school name, and their test scores. The district data was a small spreadsheet table that showed each of the schools, and their total students counts and budget. 

In this analysis we added calculated columns to show passing rates of reading and math scores, and looked at overall passing rates by school. We then grouped this data by school to see overall reading and math passing rates, rank the schools by overall passing rates

From there, we recreated the data into several different views that looked at the relationship of spend per student, average scores by grade for each school, and average test scores and pass rate by whether the school was small, medium, or large in volume of students. 

# Conclusions:

Charter schools have close to a 90% overall pass rate compared to district schools at 53%, and this is despite variances in both the number of total students at the schools, as well as a relatively consistent spend per student across all of the schools (ranges between roughly $575 to $650 per student).

Looking closer at the passing rate, all district schools in the district show roughly 80-83% of their students passing reading, but there is a large gap between charter and district schools in passing math (93% for charter versus 66% for district schools). Again, these differences don’t seem to fluctuate based on the spend per student, and the math scores are consistent across grade levels at each school, not usually fluctuating above or below 1 pt in scoring. 

From this data, the main takeaway to improve test scores is that the district schools need to focus on emulating the charter schools in how they approach math teaching techniques and curriculum. If the difference can’t be clearly seen in the cost per student (which indicates there isn’t necessarily smaller class sizes in these charter schools), there must be specific standards or processes being implemented in the charter schools that the district schools can emulate to improve overall passing rate. 




