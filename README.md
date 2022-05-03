# School_District_Analysis

## Overview of Project
- I have been requested by Maria to create a data analysis for the school board. In this specific analysis we will need to drop the Thomas High School's 9th graders grades because of some academic dishonesty evidence they have and see how it affects the analysis compared to the one we did prior. We will be using python's pandas and numpy libraries for our analysis, pandas will help us for most of our analysis by creating different DataFrames for us to look and compare how schools fare depending on different groups. Numpy library will help us replace the 9th graders grade with a null value.

## How is the district summary affected?
![district_summary](/resources/district_summary_comparison.png)
 - We can see four changes after replacing the 9th graders from Thomas High School to NaNs:
 1. The average math score dropped 0.1
 2. The percentage passing math dropped 0.2%
 3. The percentage passing reading dropped 0.3%
 4. The overall passing percentage dropped 0.1%    
## How is the school summary affected?
![school_summary](/resources/school_summary_comparison.png)
- The school summary was only affected specifically on Thomas High School averages and passing percentages.
## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- After replacing the 9th graders grades to NaN we see a big drop on the average scores as well as percentage on passing the subjects & overall passing percentage. This happened because we are calculating the averages at first including the 9th graders with no scores.
## How does replacing the ninth-grade scores affect the following:
### Math scores by grade
![math](/resources/math_scores_grade.png)
- Replacing the 9th grade scores to NaN only affects Thomas High School specifically returning a NaN on the score.
### Reading scores by grade
![reading](/resources/reading_scores_grade.png)
- Same as above.
### Scores by school spending
![spending_summary](/resources/spending_summary_comparison.png)
- Between $631-$645/per students the average math score was brought down about 0.017 points, the average reading was brought up 0.012 points, passing math percentage dropped 0.022%, passing reading percentage dropped 0.072% and the overall passing percentage dropped 0.08%. Since we are only counting the averages from 10th-12th graders on Thomas High School the changes are minimal for a good analysis.
### Scores by school size
![size_summary](/resources/size_summary_comparison.png)
- Only medium sized schools averages changed, the average math score was brought down about 0.01 points, the average reading was brought up 0.1 points, passing math percentage dropped 0.017%, passing reading percentage dropped 0.06% and the overall passing percentage dropped 0.07%. Since we are only counting the averages from 10th-12th graders on Thomas High School the changes are minimal for a good analysis.
### Scores by school type
![type_summary](/resources/type_summary_comparison.png)
- On charter schools the average math score was brought down about 0.01 points, the average reading was brought up 0.01 points, passing math percentage dropped 0.01%, passing reading percentage dropped 0.03% and the overall passing percentage dropped 0.04%. Since we are only counting the averages from 10th-12th graders on Thomas High School the changes are minimal for a good analysis.
