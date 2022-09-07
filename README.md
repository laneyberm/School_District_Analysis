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
<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/school_summary_THS_adjusted.png" width="700">
The above table is the School Summary after the 9th Graders from Thomas High School has been removed. The below table is the district summary prior to the removal of the "NaN" score of 9th Graders from Thomas High School. We can note the following changes:

- The % Passing Math has changed from 66.9 to 93.2. There is a 26.3 difference in percentage.
- The % Passing Reading has changed from 69.7 to 97.3. There is a 27.6 difference in percentage.
- The % Overall Passing has changed from 65.1 to 90.6. There is a 25.5 difference in percentage.

By replacing the ninth graders’ math and reading scores, Thomas High School’s performance relative to the other schools puts the school more in line with the overall trend for the district. If we didn't replace them, Thomas High School would look like they were failing in both categories. 

<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/school_summary_nan.png" width="700">

### Top 5 performing schools, based on the overall passing rate
<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/top_five.png" width="700">

### Bottom 5 performing schools, based on the overall passing rate
<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/bottom_five.png" width="700">

### Math and Reading Test Scores Filtered Down
After replacing the ninth graders’ math and reading scores for Thomas High School, the following tables are produced:

#### Math and reading scores by grade

<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/grade_math_scores.png" width="250">
The above is the average math score for each grade level from each school. We can note that we replaced Thomas High School 9th Grade with NaN.

<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/grade_reading_scores.png" width="250">
The above is the average reading score for each grade level from each school. We can note that we replaced Thomas High School 9th Grade with NaN.
  
#### Scores by school spending
<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/scores_by_spending.png" width="700">
  
#### Scores by school size
<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/scores_by_size.png" width="700">

#### Scores by school type
<img src="https://github.com/laneyberm/School_District_Analysis/blob/main/Resources/scores_by_type.png" width="700">

## Summary
By replacing the math and reading scores for nineth graders at Thomas High School with NaNs, we created a better analysis for the school board of the Math and Reading Test Scores. For the district, the % Passing Math, % Passing Reading and % Overall Passing was reduced. The % Overall passing for Thomas High School changed from 65% to 90%, which is more in line with the district. Additionally, Thomas High School moved to the Top Performing School List when the nineth graders were replaced. 
