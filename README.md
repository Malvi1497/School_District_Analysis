# School_District_Analysis
An analysis of district school trends using PANDAS in Jupyter Notebook.

## Overview
The analysis was performed for the school district on their budget and priorites for a list of 15 schools. The analysis included a comparison of the data provided by the schools to compare various metrics.

## Purpose
The purpose of this project is to compare the various data between schools based on their student size, school type (District vs Charter) and grades. However, thw school district discovered a miscalculation for the ninth grade students at Thomas High School while keeping the other data intact.

## Data
The data was provided by the school and was compiled into two files with the following data:
### School Data
* School ID
* School_name
* Type
* Size
* Budget
### Student Data
* Student ID	
* Student_name	
* Gender	
* Grade	
* School_name	
* Reading_score	
* Math_score

## Analysis
The intial analysis to create a ditrict summary after merging the two data sets into one dataset to calculate the total number of schools and students, the total budge, the average scores for math and reading, passing percentage for both math and reading scores and the overall passing percentage between schools.

![District summary](https://user-images.githubusercontent.com/94252681/156941076-5b316619-6c47-4513-97a9-5301bfcdede0.png)

The same analysis was then performed per school and it was seen that the changes to dataset in Thomas High School did not affect the school district summary by more than .1%.

![School Summary](https://user-images.githubusercontent.com/94252681/156942042-a9cfdbd4-b75b-4c99-b61d-cff80751cfa5.png)

The analysis was sorted to get the five top and bottom performing schools based on their overall passing percentage from the per school summary. The change in Thomas High School affected the top five schools dropping it from the top five list to 8th in the list.

![Top and bottom performing schools](https://user-images.githubusercontent.com/94252681/156942198-500fc1f4-06ac-432b-bfcd-47eaf6bc4745.png)

The analysis was then performed to give the average math and reading scores per school and the scores for Thomas High School was replaced with NaN while keeping the data for the other grades intact.

Average math scores per school

![Average Math Score](https://user-images.githubusercontent.com/94252681/156942414-725257b7-0316-4454-879f-1d418cf488c1.png) 

Average reading scores per school

![Average Reading Score](https://user-images.githubusercontent.com/94252681/156942423-da4dd3b0-1eb7-4af6-94e2-2d7823940565.png)

The analysis was performed to show the overall performance of schools based on their spending summary.

![Spending Summary](https://user-images.githubusercontent.com/94252681/156942717-19213e56-8805-457f-bceb-921f2bdd14e9.png)


The analysis was perforemd to show the overall performance for schools based on their size or number of students.

![School Size Summary](https://user-images.githubusercontent.com/94252681/156942777-4ee460c2-25ef-46c4-9b2d-84298bc996bf.png)

The analysis was perforemd to show the overall performance for schools based on their school type (District vs Charter).

![School Type Summary](https://user-images.githubusercontent.com/94252681/156942850-faf94777-c784-4839-b7e3-f080389ed379.png)

## Observations
The five significant changes in the analysis that occurred due to the reomval of data from Thomas High School dataset is in the following, 
* Number of total students, 
* Number of students counted at Thomas High School, 
* Average math and reading scores,
* Overall percentages for math and reading at Thomas High School and 
* Top performing schools

## Results
The removal of data implies a decrease in the count of total students overall, and total students at Thomas High School, specifically for this analysis. And since the population amount was decreased, this leads to a change in average scores and score percentages. The most significant change was the removal of Thomas High Schhol which was initally ranked second performong school with the Overall Passing percentage being 91% to the eight ranking school with the overall passing percentage being 65%.However, these score and percentage changes were minimal hence we can assume that the removal of math and reading scores of 9th graders at Thomas High School not as significant as we would imagine it to be.
