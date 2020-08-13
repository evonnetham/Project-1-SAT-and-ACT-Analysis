# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: SAT & ACT Analysis

_Author: Evonne Tham_

## Problem Statement

![image.png](https://www.ajtutoring.com/wp-content/uploads/2016/09/banner-subpage-SAT-vs-ACT.jpg)

There has been several changes made since the new format for the SAT was released in March 2016, which reshaped SAT and ACT participation rates within the U.S, categorized by states.

In 2018 alone, over 2 million students took the SAT, an increase of 25% over the class of 2017, making it the most widely used college admission test. Furthermore, college, universities or other higher education admission decisions were made largely on SAT scores.

As part of a team that tracks statewide participation, this project seeks to understand the factors that influence the changes in SAT and ACT participation rates. The goal of this study is to find out how can we maximize the positive effect of the investment to bring up the participation rate in a chosen state.

Citation:

https://magoosh.com/hs/sat/2016/new-sat-vs-old-sat-format/
https://www.edweek.org/ew/articles/2018/10/31/sat-scores-rise-as-number-of-test-takers.html
https://research.collegeboard.org/programs/sat/data
https://www.collegeboard.org/releases/2018/more-than-2-million-students-in-class-of-2018-took-sat-highest-ever

## Executive Summary

The SAT is a standardized test in the US and is made up of Evidence-Based Reading and Writing and Math components, each with a maximum score of 800, which is added up to give a total score with a maximum of 1600. On the other hand the ACT is a standardized test in the US and is made up of English, Math, Reading and Science components, scored from 1 to 36. A composite score is taken from the average score of all four components.

By finding out how can we maximize the positive effect of the investment to bring up the participation rate, we will be looking at the aggregate SAT and ACT scores and participation rates from each state in the United States through data cleaning, visualisation and examining. 

## Content

- [1. Data Cleaning](./codes/01_Data_Cleaning.ipynb)
- [2. Full Exploratory Data Analysis](./codes/02_EDA.ipynb)
- [3. Data Visualisation and Inference](./codes/03_Data_Visualisation.ipynb)

## Data Dictionary

------

|Feature|Type|Dataset|Description|
|---|---|---|---|
|State|*object*|final|Names of all US states and the District of Columbia| 
|sat_part_17 |*float*|final|Percentage of students participated in the SAT test in 2017|
|sat_erw_17|*int*|SAT|final|Evidence-Based Reading and Writing score in 2017 |
|sat_math_17|*int*|final|SAT Math Score in 2017|
|sat_total_17|*int*|final|Sum of ERW and Math scores in 2017|
|act_participation_17|*float*|final|The percentage of students participated in the ACT test|
|act_eng_17|*float*|final|ACT English Score in 2017|
|act_math_17|*float*|final|ACT Math Score in 2017|
|act_read_17|*float*|final|ACT Reading Score in 2017|
|act_sci_17|*float*|final|ACT Science Score in 2017|
|act_composite_17|*float*|final|The mean score across all components of the ACT in 2017|
|sat_part_18|*float*|final|Percentage of students participated in the SAT test in 2018|
|sat_erw_18|*int*|final|Evidence-Based Reading and Writing score in 2018|
|sat_math_18|*int*|final|SAT Math Score in 2018|
|sat_total_18|*int*|final|Sum of ERW and Math scores in 2018|
|act_participation_18|*float*|final|Percentage of students participated in the ACT test in 2018|
|act_eng_18|*float*|final|ACT English Score in 2018|
|act_math_18|*float*|final|ACT Math Score in 2018|
|act_read_18|*float*|final|ACT Reading Score in 2018|
|act_sci_18|*float*|final|ACT Science Score in 2018|
|act_composite_18|*float*|final|The mean score across all components of the ACT in 2018|

## Conclusion and Recommendation 

Based on the data, participation rates are largely influenced by the policies that were made in place within a State. Participation rate is tied strongly to mandantory requirements. Furthermore, with the help of School Day Program, student were given more time to prepare for the test. Cost subsidy also contributed to the increase rates of participation in SAT.

In order to further improve the participation rate across states, collaboration with the states' department of education would help enable access. However, high participation rate does not equate to good performance in test. Hence it is recommended to invest on creating better test prep material for states with highest participation rates.

On top of that, as we are a mission driven NOT-FOR-profit organization that connects students to college success. It is recommended to invest in Arkansas. Not only does Arkansas has a lower participation rate of 3% in 2017 and %5 in 2017 it is one of the highest poverty rate. With free online tutoring and materials, and funding scholarship for those who needs who help exponentially.

Citation:
- https://www.edweek.org/ew/articles/2018/10/31/sat-scores-rise-as-number-of-test-takers.html
- https://www.usatoday.com/story/money/economy/2018/10/08/wealth-america-household-income-richest-poorest-states/38051359/
- https://www.washingtonpost.com/education/2019/10/18/record-number-colleges-drop-satact-admissions-requirement-amid-growing-disenchantment-with-standardized-tests/