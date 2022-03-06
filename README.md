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

The analysis was then performed to give the average math and reading scores per school.

![Average Math Score](https://user-images.githubusercontent.com/94252681/156942414-725257b7-0316-4454-879f-1d418cf488c1.png)
![Average Reading Score](https://user-images.githubusercontent.com/94252681/156942423-da4dd3b0-1eb7-4af6-94e2-2d7823940565.png)


