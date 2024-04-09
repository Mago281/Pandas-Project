Pandas Project:  PyCitySchools
----------------------

## Introduction

***Applying Python Pandas into analysis via Jupyter Notebook.***

This project delves into the utilization of Python Pandas for data analysis within a Jupyter Notebook environment.

The focus lies on creating and manipulating Pandas DataFrames to dissect school-related data alongside standardized test scores.

The PyCitySchools Jupyter Notebook and accompanying Excel files serve as the foundation for this endeavor:

   <img src="https://github.com/Mago281/pandas-challenge/assets/131424690/f77ded6d-6ba1-4b43-b84b-b7df026e0d71" width="160" height="75">


To ensure alignment with the project requirements, I referenced the provided sample solution named PyCitySchools_starter.ipynb.

Utilizing Pandas and Jupyter Notebook, the analysis encompasses a comprehensive report featuring relevant datasets. Additionally, the report offers insights through a written narrative, elucidating two discernible trends extracted from the data.
Using Pandas and Jupyter Notebook, I created a report that included the following data and included a written description of two observable trends based on the data.

---


**Background - Objective & Overview**
----------------------

In my role as the newly appointed Chief Data Scientist for our local government, I am tasked with aiding the school board and mayor in making informed decisions regarding future school budgets and priorities.

My initial assignment involves conducting an in-depth analysis of area-wide standardized test results. With access to comprehensive data including math and reading scores of every student, as well as various school-related information, my objective is to synthesize this data to identify prominent trends in school performance.

The resultant report encompasses the following components:
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

This analysis serves as a crucial foundation for informed decision-making and strategic planning within our educational framework.
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












