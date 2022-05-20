# School District Analysis
## Overview
##### Assisting the school board with analyzing the standardized testing results of 15 high schools within the same school district to provide insight into performance trends and patterns. As we were reaching the end of our analysis, we were notified by the school board that there was evidence of academic dishonesty among Thomas High School ninth graders'. To make our analysis as accurate as possible, we modified our Python code to edit the dataset to replace null values for all Thomas High School ninth graders' math and reading scores.
## Results
##### Upon editing our dataset, we were able to identify several differences in the results with all students vs. without Thomas High School ninth graders. The differences and their impacts are shown and discussed below. 

### How is the district summary affected?
![District Summary_ver1.PNG](https://github.com/carinaediaz/school_district_analysis/blob/main/Analysis/District%20Summary_ver1.PNG)
##### Running our analysis for all of the students within the district, we found that 75% of students passed math, 86% passed reading, and 65% of students passed both reading and math tests. 
![District Summary_ver2.PNG](https://github.com/carinaediaz/school_district_analysis/blob/main/Analysis/District%20Summary_ver2.PNG)
##### When we updated the data to remove Thomas High School 9th graders' grades, the passing percentages dropped slightly, 74.8% of students passed math, 85.7% passed reading, and 64.9% of students passed both reading and math. The differences are nominal, but still notable on the district level. Total schools, total students, and total budget all remain the same, as we are not removing the Thomas High School 9th graders' data completely, but just changing their grades to null so they are not accounted for in testing analysis. 

### How is the school summary affected?
![School Summary_ver1.PNG](https://github.com/carinaediaz/school_district_analysis/blob/main/Analysis/School%20Summary_ver1.PNG)
##### Running our analysis for all of the students within the district, when grouped by the high school they attend, Thomas High School had nearly 91% of students who passed both math and reading exams. 
![School Summary_ver2.PNG](https://github.com/carinaediaz/school_district_analysis/blob/main/Analysis/School%20Summary_ver2.PNG)
##### Upon removing the 9th graders' test results, the passing percentages changed drastically. Students who passed the math exam dropped from 93.3% to 66.9%. Students who passed the reading exam dropped from 97.3% to 69.7%. Students who passed both exams dropped from 90.9% to 65.7%. These dramatic changes show how much the ___ ninth graders' test results were skewing the passing percentages. 

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Thomas High School went from being the second top performing high school in the district to 8th. 

### How does replacing the ninth-grade scores affect the math and reading scores by grade?
![Math by Grade_ver1.PNG](https://github.com/carinaediaz/school_district_analysis/blob/main/Analysis/Math%20by%20Grade_ver1.PNG)
![Math by Grade_ver2.PNG](https://github.com/carinaediaz/school_district_analysis/blob/main/Analysis/Math%20by%20Grade_ver2.PNG)
##### Changes were only made to the Thomas High School ninth graders' math test results. "nan" now shows where the ninth graders' passing percentage once was. No other school or grade's data was affected.
![Reading by Grade_ver1.PNG](https://github.com/carinaediaz/school_district_analysis/blob/main/Analysis/Reading%20by%20Grade_ver1.PNG)
![Reading by Grade_ver2.PNG](https://github.com/carinaediaz/school_district_analysis/blob/main/Analysis/Reading%20by%20Grade_ver2.PNG)
##### Changes were only made to the Thomas High School ninth graders' reading test results. "nan" now shows where the ninth graders' passing percentage once was. No other school or grade's data was affected.

### How does replacing the ninth-grade scores affect the scores by school spending?
![Scores by Spending_ver1.PNG](https://github.com/carinaediaz/school_district_analysis/blob/main/Analysis/Scores%20by%20Spending_ver1.PNG)
![Scores by Spending_ver2.PNG](https://github.com/carinaediaz/school_district_analysis/blob/main/Analysis/Scores%20by%20Spending_ver2.PNG)
##### Thomas High School falls into the $631-645 spending budget range. Because changes were only made to Thomas High School's test results, the other spending categories will not see any changes to their results.

### How does replacing the ninth-grade scores affectthe scores by school size?
![Scores by Size_ver1.PNG](https://github.com/carinaediaz/school_district_analysis/blob/main/Analysis/Scores%20by%20Size_ver1.PNG)
![Scores by Size_ver2.PNG](https://github.com/carinaediaz/school_district_analysis/blob/main/Analysis/Scores%20by%20Size_ver2.PNG)
##### Thomas High School has 1,635 students, falling into the medium school size cateogry, therefore we will only see changes in the passing percentages for the medium high school category. 

### How does replacing the ninth-grade scores affect the scores by school type?
![Scores by Type_ver1.PNG](https://github.com/carinaediaz/school_district_analysis/blob/main/Analysis/Scores%20by%20Type_ver1.PNG)
![Scores by Type_ver2.PNG](https://github.com/carinaediaz/school_district_analysis/blob/main/Analysis/Scores%20by%20Type_ver2.PNG)
##### Thomas High School is a charter school, therefore the district schools' passing percentages remain unchanged. 

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
