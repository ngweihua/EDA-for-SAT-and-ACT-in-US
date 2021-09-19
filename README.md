# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis

### Background 

For the first project, we're going to take a look at aggregate SAT and ACT scores and participation rates in the United States. We'll seek to identify trends in the data and combine our data analysis with outside research to address the problem statement.
The SAT and ACT are standardized tests that many colleges and universities in the United States require for their admissions process. This score is used along with other materials such as grade point average (GPA) and essay responses to determine whether or not a potential student will be accepted to the university.
The SAT has two sections of the test: Evidence-Based Reading and Writing and Math. The ACT has 4 sections: English, Mathematics, Reading, and Science, with an additional optional writing section and they have different score ranges.
Standardized tests have long been a controversial topic for students, administrators, and legislators. Since the 1940's, an increasing number of colleges have been using scores from sudents' performances on tests like the SAT and the ACT as a measure for college readiness and aptitude. Supporters of these tests argue that these scores can be used as an objective measure to determine college admittance. Opponents of these tests claim that these tests are not accurate measures of students potential or ability and serve as an inequitable barrier to entry.

### Problem Statement

As a data analyst to identify and report the potential states to the business team to increase participation rate in order to make more profits for SAT.

---

### Datasets


|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|sat|A region in US; total of 51 states| 
|participation|float|sat|percentage of students taking the exam| 
|ebrw|int|sat|SAT Evidence-based Reading and Writing Score| 
|math|int|sat|SAT Math Score| 
|total|int|sat|Sum of SAT ebrw and SAT math score | 
|year|int|sat|The year for the data | 
|exam|object|sat|The type of exam : SAT or ACT | 
|---|---|---|---|
|state|object|df|A region in US; total of 51 states| 
|participation|float|df|percentage of students taking the exam| 
|total|object|df|The score for the choice of exam| 
|year|int|df|The year for the data | 
|exam|object|df|The type of exam : SAT or ACT | 
|---|---|---|---|
|state|object|target|A region in US; total of 30 states| 
|participation|float|target|percentage of students taking the exam| 
|total|object|target|The score for the choice of exam| 
|year|int|target|The year for the data | 
|exam|object|target|The type of exam : SAT or ACT | 

---

### Conclusion

Students in the US are taking either SAT or ACT as their college admission exam. Based on the exploration of the data, out of the 51 states, it was observed that there were more students taking ACT than SAT. Despite that, the  SAT participation rate have been increasing since 2017 which indicates a potential for growth. This could be due to the SAT reform in 2016. The objective of this study is to recommend the potential state(s) to SAT management to increase participation rate.

With a deeper study into SAT results, it is interesting to see that the participation rate is inversely proportional to the total score and evidence-based reading and writing score directly impact the total score to a large extent. However, with the increase of SAT participants, it will be a better indicator to understand the performance of the students across US.

The potential states will have to meet the following criterias:
1. States that did not choose their preferred admission exam
2. State participation rate in 2019 falls between the 50th and 75th percentile
3. Increasing state participation rate on a yearly basis from 2017 to 2019
4. States that score better than the average 

With that, the recommended states will be 
1. Massachusetts
2. Vermont
3. Washington

---

### Recommendations
Based on the outside research, the following are the recommendations to improve the participation rates :
1. SAT pre-examination materials to better prepare the students for the exams. 
2. Provide SAT day for the students to have the exams in school.


---
### Appendix
ACT compulsory state :
 https://blog.prepscholar.com/which-states-require-the-act-full-list-and-advice
SAT compulsory state: 
https://blog.prepscholar.com/which-states-require-the-sat
SAT day : 
https://collegereadiness.collegeboard.org/sat/k12-educators/sat-school-day
SAT pre-examination materials
https://collegereadiness.collegeboard.org/sat/k12-educators/advising-instruction/outreach-materials

---





