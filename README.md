# Project 1: SAT & ACT Analysis

## Problem Statement
How can we increase SAT participation rates in states with high score like North Dakota?  Should the tests be mandatory if 100% partipation states have lower averages?  If yes, should they be nationally standardized?  Are they even helpful anymore since many colleges are dropping their requirement? 

## Executive Summary

The 2017 and 2018 data shows a correlation between high particpation rates and lower scores as well as low participation rates and higher scores for both the SAT and ACT tests. The tests themselves are standardized, however, who has to take them is not. There are many outside factors that affect the average scores as well as the popularity of each test per state. 


### Contents:
- [2017 Data Import & Cleaning](#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|SAT|This is the state where students took the SATs.| 
|sat_participation_2017|float|SAT|The percent of students that took the test in their state.| 
|sat_rw_2017|int|SAT|The average score for the Evidence-Based Reading and Writing portion of the test for each state.|
|sat_math_2017|int|SAT|The average score for the Math portion of the test for each state.|
|sat_total_2017|int|SAT|The average of the Reading & Writing and Math scores added together for each state.|
|state|object|ACT|This is the state where students took the ACTs.|
|act_participation_2017|float|ACT|The percent of students that took the test in their state.|
|act_english_2017|float|ACT|The average score for the English portion of the test in each state.|
|act_math_2017|float|ACT|The average score for the Math portion of the test in each state.|
|act_reading_2017|float|ACT|The average score for the Reading portion of the test in each state.|
|act_science_2017|float|ACT|The average score for the Science portion of the test in each state.
|act_composite_2017|float|ACT|The average score for the total of all 4 portions of the test in each state.|
|sat_participation_2018|float|SAT|The percent of students that took the test in their state in 2018.| 
|sat_rw_2018|int|SAT|The average score for the Evidence-Based Reading and Writing portion of the test for each state in 2018.|
|sat_math_2018|int|SAT|The average score for the Math portion of the test for each state in 2018.|
|sat_total_2018|int|SAT|The average of the Reading & Writing and Math scores added together for each state in 2018.|
|act_participation_2018|float|ACT|The percent of students that took the test in their state in 2018.|
|act_composite_2018|float|ACT|The average score for the total of all 4 portions of the test in each state in 2018.|

### Key takeaway: 
I think it is important to note correlation between states having a high participation for one test being very low for the other.  It seems we can deduce that few students want to take both tests so in states where one is mandatory, the other is very low. 

North Dakota SAT participation is very low. If we made that test free, but not manadatory, I think the number of students taking it would definitely increase.

I would have liked to dive deeper into the necessity of the tests.  They seem like an ancient and inaccurate tool.  Especially with the recent college admissions scandals in the news, I think it would be important to figure out the percent of fraudulent high scoring tests last year and focus on fixing that problem first.


### Sources 
https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/
https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows
https://blog.prepscholar.com/which-states-require-the-act-full-list-and-advice
https://study.com/academy/lesson/descriptive-and-inferential-statistics.html
https://www.washingtonpost.com/education/2019/03/19/is-it-finally-time-get-rid-sat-act-college-admissions-tests/?noredirect=on&utm_term=.67e2f1579130
