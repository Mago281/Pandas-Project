Pandas Project:  PyCitySchools
----------------------

## Introduction

***Applying Python Pandas for Data Analysis in Jupyter Notebook.***

This project leverages Python Pandas within a Jupyter Notebook environment to perform comprehensive data analysis.  The focus is on creating and manipulating Pandas DataFrames to analyze school-related data and standardized test scores.

The PyCitySchools Jupyter Notebook and accompanying Excel files form the foundation of this analysis:

   <img src="https://github.com/Mago281/pandas-challenge/assets/131424690/f77ded6d-6ba1-4b43-b84b-b7df026e0d71" width="160" height="75">


Using Pandas and Jupyter Notebook, this analysis culminates in a detailed report featuring relevant datasets and a narrative highlighting two key trends observed from the data.

---


**Background - Objective & Overview**
----------------------

As the newly appointed Chief Data Scientist for our local government, my primary responsibility is to support the school board and mayor in making data-driven decisions about future school budgets and priorities.

My initial task involves an in-depth analysis of standardized test results across the area.  With access to comprehensive data, including math and reading scores for each student, along with various school-related information; my objective is to identify significant trends in school performance.

The resulting report includes the following components:
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

This analysis is critical for informed decision-making and strategic planning within our educational framework.
________________________________________

## Analysis Report
________________________________________


### Local Government Area Summary

A comprehensive analysis provided a succinct overview of key metrics within the local government area, including math and reading scores, with an emphasis on a passing grade threshold of 50 or higher.


![image](https://github.com/Mago281/pandas-challenge/assets/131424690/13bf2d4e-35a2-4693-9f38-a671dd283a6b)

________________________________________
 
### School Summary

The performance metrics of each school were analyzed in detail, highlighting critical aspects such as passing grades and overall performance:
<br>

$${\color{black}**Note:** \space \color{black}A  \space \color{blue}passing \space \color{blue}grade \space \color{black}is \space \color{blue}50 \space \color{black}or \space \color{blue}higher}$$ 
<p align="left">
</p>  

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/b946ab5b-939b-4683-a811-db31e8747a4b)

________________________________________

### Top 5 Performing Schools by Percentage of Overall Passing

The top 5 performing schools were identified based on the percentage of overall passing rates, providing insights into exemplary educational institutions:

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/45653e1c-7282-49d8-9415-2e6cc4ec7c2d)

________________________________________

### Bottom 5 Performing Schools by Percentage of Overall Passing

Conversely, the bottom 5 performing schools were highlighted, emphasizing areas needing improvement:

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/a3aaebf7-421c-4445-84cf-b26ab215cbcf)

________________________________________

### Scores by Grade (Grades 9 to 12)
________________________________________

### Math scores by Grade

An insightful breakdown of `average maths scores` across various grade levels `(year levels 9 to 12)` provided valuable insights into academic performance trends:

   <img src="https://github.com/Mago281/pandas-challenge/assets/131424690/973cb0f5-a537-4032-bda8-4b62caedb9bd" width="400" height="375">

________________________________________ 

### Reading scores by Grade

Similarly, the analysis extended to `average reading scores` across various grade levels `(year levels 9 to 12)`, contributing to a comprehensive understanding of educational dynamics.


   <img src="https://github.com/Mago281/pandas-challenge/assets/131424690/868e97d3-a39c-4376-8588-27de7648bf5e" width="400" height="375">

________________________________________

### Scores by School Spending

A detailed examination of school performance vis-a-vis average spending ranges per student revealed significant insights into the correlation between financial allocation and academic outcomes.

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/ff203710-c690-4377-9af5-42647fded64c)
 
Four bins with appropriate cutoff values were implemented to categorize school spending, thereby enhancing the organization of expenditure data:

Utilized the aforementioned scoring metrics, a meticulously structured DataFrame termed _`spending_summary`_ was constructed.

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/7e213fd4-f47c-4a72-92ed-b2bf8b5b32fa)

________________________________________

### Scores by School Size

Stratifying school performance based on size categories facilitated a nuanced understanding of the impact of school size on academic achievements:

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/4013aec4-4f87-4005-8723-36f7e819e62c)

A DataFrame was provided that broke down `school performance based on school size`:

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/23d70d85-eddc-4b40-ad15-3a8a1618554a)

________________________________________

### Scores by School Type

The analysis also examined school performance concerning different types, providing insights into variations based on institutional characteristics:

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/e632d31b-7c31-4864-b80e-d0ff89fc639e)

________________________________________
## Summary of Analysis
________________________________________

### Budget Allocation Impact:
The analysis revealed that funding levels did not consistently correlate with academic performance.  Lower per-student spending was associated with lower average scores and passing rates.

### School Size Matters:
Smaller schools tended to outperform larger ones, suggesting that smaller class sizes contributed to higher academic success.     

### School Type:
Independent schools, despite lower per-student budgets, exhibited higher overall performance compared to government schools, indicating potential efficiency differences between the two systems.  Specifically, independent schools performed 4.74% better in Math and 2.66% better in Reading. 

---

In conclusion, a targeted approach to budget allocation and class size management could enhance academic outcomes within the local government area.  These findings underscore the importance of data-driven decision-making in shaping future educational initiatives.












