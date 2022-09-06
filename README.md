# School District Analysis on High School Math and Reading Scores

## Project Overview
###  The school board has to set the budget for the upcoming school year. After reviewing Math and Reading Test Scores for the high schools in the district, there is evidence of academic dishonestly; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. We want to uphold state-testing standards. We will replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact to retrieve a school district analysis for testing to be presented to the school board.

### In this project, we will replace the math and reading scores for nineth graders at Thomas High School with NaNs and create a better analysis for the school board of the Math and Reading Test Scores. We will also determine how the changes to the data altered the overall analysis. We will show data filtered the scores by size of school, spending per student, and type of school. This data will help the district determine how much money should be allocated to and spent on each school. 

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Jupyter Notebook

## Results

### District Summary
<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/district_summary_THS_adjusted.png" width="800">
The above table is the District Summary after the alterations to the math and reading scores have been taken. The below table is the district summary prior to the alterations in the data. We can note the following changes:

- The total number of students have changed from 39,170 to 38,709.
- The % Passing Math has changed from 75.0 to 74.8. There is a 0.02 difference in percentage.
- The % Passing Reading has changed from 85.8 to 85.7. There is a 0.01 difference in percentage.
- The % Overall Passing has changed from 65.2 to 64.9. There is a 0.03 difference in percentage.

<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/district_summary_original_data.png" width="800">

### School Summary
<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/school_summary_THS_adjusted.png" width="800">
The above table is the School Summary after the 9th Graders from Thomas High School has been removed. The below table is the district summary prior to the removal of the "NaN" score of 9th Graders from Thomas High School. We can note the following changes:

- The total number of students have changed from 39,170 to 38,709.
- The % Passing Math has changed from 66.9 to 93.2. There is a 0.02 difference in percentage.
- The % Passing Reading has changed from 69.7 to 93.2. There is a 0.01 difference in percentage.
- The % Overall Passing has changed from 65.1 to 90.6. There is a 0.03 difference in percentage.
<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/school_summary_nan.png" width="800">

<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/school_summary_original_data.png" width="800">

- How is the school summary affected?
  - 
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?


### How removing the currupted data affected the analysis
- How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade

<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/grade_math_scores.png" width="250">
The above is the math scores by grade and high school.
<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/grade_reading_scores.png" width="250">
The above is the reading scores by grade and high school.
  
#### Scores by school spending
<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/scores_by_spending.png" width="700">
  - Scores by school spending
  
#### Scores by school size
<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/scores_by_size.png" width="700">
  - Scores by school size

#### Scores by school type
<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/scores_by_type.png" width="700">
  - Scores by school type

### After running the python code, the following results were displayed in a text file for easy viewing:

## Summary
Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced.
