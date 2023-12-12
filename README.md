# pandas-challenge

# PyCitySchools
----------------------

## Introduction

***Applying Python Pandas into analysis via Jupyter Notebook.***

In this challenge, I will be creating and manipulating Pandas DataFrames to analyse school and standardised test data.

The `PyCitySchools` Jupyter Notebook and following excel files were provided for this challenge:

   <img src="https://github.com/Mago281/pandas-challenge/assets/131424690/f77ded6d-6ba1-4b43-b84b-b7df026e0d71" width="160" height="75">

I used the sample solution called `PyCitySchools_starter.ipynb`  to review the desired format for this assignment.

Using Pandas and Jupyter Notebook, I created a report that included the following data and included a written description of two observable trends based on the data.

---


**Background - Objective & Overview**
----------------------

In my capacity as the new Chief Data Scientist for my local government area, I will be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, I have been asked to analyse the area-wide standardised test results.  I have been given access to every student's maths and reading scores, as well as various information on the schools they attend.  My task is to aggregate the data to showcase obvious trends in school performance.

The final report includes each of the following:
   - District Summary
   - School Summary
   - Top 5 Performing Schools (By % Overall Passing)
   - Bottom 5 Performing Schools (By % Overall Passing)
   - Scores by Grade (9th to 12th)
   - Math scores
   - Reading scores
   - Scores by different categories
   - School Spending
   - School Size
   - School Type
   - Analysis

________________________________________

## Analysis with Report
________________________________________


### Local Government Area Summary

Performed calculations and then created a high-level snapshot of the `local government area's key metrics` in a DataFrame:

**Note: _A passing grade is 50 or higher._**

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/13bf2d4e-35a2-4693-9f38-a671dd283a6b)

________________________________________
 
### School Summary

Performed the necessary calculations and then created a DataFrame that `summarised key metrics about each school`:
<br>


$${\color{black}**Note:** \space \color{black}A  \space \color{blue}passing \space \color{blue}grade \space \color{black}is \space \color{blue}50 \space \color{black}or \space \color{blue}higher}$$ 
<p align="left">
</p>  

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/b946ab5b-939b-4683-a811-db31e8747a4b)

________________________________________

### Highest 5 Performing Schools by Percentage of Overall Passing

Sorted the schools by `% Overall Passing` in descending order and displayed the top 5 rows:

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/45653e1c-7282-49d8-9415-2e6cc4ec7c2d)

________________________________________

### Lowest 5 Performing Schools by Percentage of Overall Passing

Sorted the schools by `% Overall Passing` in ascending order and displayed the top 5 rows:

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/a3aaebf7-421c-4445-84cf-b26ab215cbcf)

________________________________________

### Scores by Grade (Grades 9 to 12)
________________________________________

### Math scores by Grade

Performed the necessary calculations to create a DataFrame that listed the `average maths score` for students of each `year level (9, 10, 11, 12)` at each school:

   <img src="https://github.com/Mago281/pandas-challenge/assets/131424690/973cb0f5-a537-4032-bda8-4b62caedb9bd" width="400" height="375">

________________________________________ 

### Reading scores by Grade

Performed the necessary calculations to create a DataFrame that listed the `average reading score` for students of each `year level (9, 10, 11, 12)` at each
school:

   <img src="https://github.com/Mago281/pandas-challenge/assets/131424690/868e97d3-a39c-4376-8588-27de7648bf5e" width="400" height="375">

________________________________________

### Scores by School Spending

Created a table that broke down `school performance based on average spending ranges` (per student).

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/ff203710-c690-4377-9af5-42647fded64c)
 
Created four bins with reasonable cutoff values to group school spending and categorised spending based on these bins:

<img src="https://github.com/Mago281/pandas-challenge/assets/131424690/2079f0f9-b0d2-445d-b5a5-d556a9efa331" width="430" height="45">

Used the scores above to create a DataFrame called _`spending_summary`_.

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/7e213fd4-f47c-4a72-92ed-b2bf8b5b32fa)

________________________________________

### Scores by School Size

Binned the _`per_school_summary`_:

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/4013aec4-4f87-4005-8723-36f7e819e62c)

Created a DataFrame called _`size_summary`_ that broke down `school performance based on school size` (small,
medium, or large).

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/23d70d85-eddc-4b40-ad15-3a8a1618554a)

________________________________________

### Scores by School Type

Used the _`per_school_summary`_ DataFrame from the previous step to create a new DataFrame called _`type_summary`_.

This new DataFrame `shows school performance` based on the `"School Type"`.

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/e632d31b-7c31-4864-b80e-d0ff89fc639e)

________________________________________
## Summary of Analysis
________________________________________

### Budget Allocation Impact:
From the 5 Highest-Performing and 5 Lowest-Performing Schools, the analysis showed that funding did not make a significant impact to the results obtained.  Schools with higher budgets do not necessarily guarantee higher academic performance.  The analysis of spending ranges indicated that lower per student spending was associated with lower average scores and passing rates.    

### School Size Matters:
Smaller schools tended to outperform larger ones.  The data suggests that smaller class sizes contribute to higher academic success i.e. there was an inverse correlation between the size of a school and the results achieved:  larger student numbers showed lower scores.     

### School Type:
Independent schools had smaller student numbers and less budget allocated per student.  They performed 6.27% higher overall than Government schools; this is a significant difference.  In particular, Independent schools performed 4.74% better in Maths and 2.66% better Reading. 

---

In conclusion, a targeted approach to budget allocation and class size reduction could potentially improve academic outcomes in the local government area.  It is essential to consider these insights when planning future educational initiatives.












