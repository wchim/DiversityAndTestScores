# Diversity and Test Scores
This is an extension of my first analytics project. 
The original project focused on looking into demographic and examination scoring data during the 2011-12 school year. 
The intention is to prove/disprove my hypothesis on whether diversity in student population correlates with better academic performance.

The extension will focus on demographic and examination scoring data during the 2017-2018 school year and explore new data visualization techniques that I learned since.

This will primarily focus on exploratory data analysis (EDA).

## Content
This repository will include both the original project code for when I was a student in Baruch College's CIS 3120 course, which is instructed by professor Kannan Mohan. (Group members include: Haoxiang C., Amanda C., Ka Ren L.)

And of course, the extension project code.

## Constraints
The original project focused on the 2011-12 school year because of a lack in data availability for state ELA examination scores for any school year beyond. 

Recency is critical in assessing a school's current performance. While student demographic data is kept up to date, state math examination score data only goes to the 2017-18 school year.

Until I can find examination scores for other subjects, the extension will only use state math examination scores.

## Pre-Processing

The first step was to isolate records from the 2017-18 school year and also scores that encompasses the school to make it easier to analyze. Then the irrelevant columns were dropped that were given such as 'Year'. A couple of columns had to be renamed to shorter length to make it more convenient to use in code. The heatmaps make for quick visualizations on the completeness of the datasets, but it is a little redundant in our case since the datasets were complete to begin with. Finally the dataframes were merged and exported to a new .csv file and that will be used for the EDA.

### Student Demographic Snapshot Dataset
https://data.cityofnewyork.us/Education/2018-2019-School-Demographic-Snapshot/45j8-f6um/data
### State Math Exam Score Dataset
https://data.cityofnewyork.us/Education/2013-2018-School-Math-Results/m27t-ht3h
