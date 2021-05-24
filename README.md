# School_District_Analysis
In Module 4, you will begin working with some powerful tools as you assist the Chief Data Scientist for the PyCity School District. You’ll use an open-source distribution software called Anaconda and the Jupyter Notebook to analyze data. You’ll be helping the school board and superintendent make strategic decisions regarding future school budgets and priorities based on the standardized test scores and current school funding.


## Overview of the School District Analysis: 
### Background
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. 

### Purpose 
The purpose of this analysis was to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact and repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

Recreate the following metrics:
1. The district summary
2. The school summary
3. The top 5 and bottom 5 performing schools, based on the overall passing rate
4. The average math score for each grade level from each school
5. The average reading score for each grade level from each school
6. The scores by school spending per student, by school size, and by school type



## Results: 

![District Summary 2](https://github.com/yessiez/School_District_Analysis/blob/master/Resources/district_summary2.png?raw=true)

### PyCity School District Summary


  - Average math scores decreased by 0.12%.
  - Average reading scores stayed the same.
  - Percent passing math scores decreased by 0.25%.
  - Percent passing reading scores decreased by 0.35%.
  - The overall passing percentage for the entire district fell to 64.9%



### PyCity School Summary 


![School Summary2](https://github.com/yessiez/School_District_Analysis/blob/master/Resources/school_summary2.png?raw=true)



![School Summary](https://github.com/yessiez/School_District_Analysis/blob/master/Resources/Untitled.png?raw=true)





#### Students Passing Analysis:
  - Average math scores at Thomas High School decreased by 0.08%
  - Average reading scores at Thomas High School increased by 0.06%.
  - Percent passing math scores at Thomas High School decreased by 0.09%.
  - Percent passing reading scores at Thomas High School decreased by 0.30%
  - Overall passing scores at Thomas High School decreased by 0.35%.


#### Top Five Performing Schools

![Top Schools](https://github.com/yessiez/School_District_Analysis/blob/master/Resources/top_schools2.png?raw=true)


#### Bottom Five Performing Schools

![Bottom Schools](https://github.com/yessiez/School_District_Analysis/blob/master/Resources/bottom_schools2.png?raw=true)


- Replacing the ninth graders’ math and reading scores at Thomas High School with NaN resulted in the following:
  - The overall passing percentage for Thomas High School fell to 65%.
  - Thomas High School remained on the list of top five schools.

#### Math scores by grade

![Math Scores2](https://github.com/yessiez/School_District_Analysis/blob/master/Resources/math_scores2.png?raw=true)

#### Reading scores by grade

![Reading Scores](https://github.com/yessiez/School_District_Analysis/blob/master/Resources/reading_scores_by_grade2.png?raw=true)

- Affect of replacing the ninth-grade scores:
  - Replacing the ninth-grade scores affect the following did not change the math and reading scores by grade.


![Spending Summary](https://github.com/yessiez/School_District_Analysis/blob/master/Resources/spending_summary2.png?raw=true)
- Scores by school spending was basically unchanged
  - $630-644 spending range
    - Average Math Score changed from 78.518855 to 78.502002.
    - Average Reading Score	changed from 81.624473 to 81.636261.
    - % Passing Math changed from 73.484209 to 73.462589.
    - % Passing Reading	changed from 84.391793 to 84.319261
    - % Overall Passing changed from 62.857656 to 62.778233
				
#### Scores by school size

![School size](https://github.com/yessiez/School_District_Analysis/blob/master/Resources/size_summary2.png?raw=true)

#### Scores by school type

![School Type](https://github.com/yessiez/School_District_Analysis/blob/master/Resources/type_summary2.png?raw=true)

# Summary
After the ninth grade reading and math scores at Thomas High School have been replaced with NaNs:
  1. Average math scores at Thomas High School decreased by 0.08%
  2. Average reading scores at Thomas High School increased by 0.06%.
  3. Percent passing math scores at Thomas High School decreased by 28.26%.
  4. Percent passing reading scores at Thomas High School decreased by 28.41%
  5. Overall passing scores at Thomas High School decreased by 28.45%.
