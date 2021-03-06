# School District Analysis

## Overview

Maria, the chief data scientist for a city school district is responsible for analysing information and preparing all standardised test data for analysis, reporting, and presentation. She has requested assistance in completing the analysis of the school district. The analysis will assist the school board and superintendent in making decisions regarding the school budgets and priorities.

After the initial analysis, there was evidence showing academic dishonesty; specifically, math and reading scores for Thomas High School ninth graders. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. 

In this analysis, the math and reading scores for Thomas High School ninth graders were replaced with NaNs while keeping the rest of the data intact. The school district analysis was then repeated to show how these changes affected the overall analysis. Below is the list of the deliverables for the analysis of the school district:
-	A high-level snapshot of the district's key metrics, presented in a table format
-	An overview of the key metrics for each school, presented in a table format
-	Tables presenting each of the following metrics:
    -	Top 5 and bottom 5 performing schools, based on the overall passing rate
    -	The average math score received by students in each grade level at each school
    -   The average reading score received by students in each grade level at each school
    -	School performance based on the budget per student
    -	School performance based on the school size 
    -	School performance based on the type of school


## Results

### 1. District Summary

**District Summary Before NaNs**
![District Summary before NaNs](resources/DistrictSummary_beforeNaNs.PNG)

**District Summary After NaNs**
![District Summary after NaNs](resources/DistrictSummary_afterNaNs.PNG)

The district summary was not significantly affected after the grades were replaced with NaNs. The “Average Math Score” went down by 0.1 points, the “Average Reading Score” had no changes, and the “% Passing Math”, “% Passing Reading”, and “% Overall Passing” all went down by 1%.
<br>
<br>
### 2. School Summary

**School Summary Before NaNs**
![School Summary before NaNs](resources/SchoolSummary_beforeNaNs.PNG)

**School Summary After NaNs**
![School Summary after NaNs](resources/SchoolSummary_afterNaNs.PNG)

The only school affected after the scores were replaced in the school summary was Thomas High School. There were barely any changes to the average scores; the “Average Math Score” remained the same and the “Average Reading Score” increased by 0.1 points. However, the passing percentages decreased significantly; the “% Passing Math” decreased by 26% from 93% to 67%, the “% Passing Reading” decreased by 27% from 97% to 70%, and the “% Overall Passing” decreased by 26% from 91% to 65%.
<br>
<br>
### 3. Top 5 Performing Schools & Bottom 5 Performing Schools, based on overall passing rate

**Top 5 Performing Schools Before NaNs**
![Top 5 before NaNs](resources/Top5Schools_beforeNaNs.PNG)

**Top 5 Performing Schools After NaNs**
![Top 5 after NaNs](resources/Top5Schools_afterNaNs.PNG)

**Bottom 5 Performing Schools Before NaNs**
![Bottom 5 before NaNs](resources/Bottom5Schools_beforeNaNs.PNG)

**Bottom 5 Performing Schools After NaNs**
![Bottom 5 after NaNs](resources/Bottom5Schools_afterNaNs.PNG)

Thomas High School was ranked 2nd in the top 5 performing schools in the district before the ninth graders’ math and reading scores were replaced with NaNs. Thomas High School has since dropped to 8th place and no longer in the top 5 performing schools. The bottom 5 performing schools did not change.
<br>
<br>
### 4. Average Math & Reading Scores by Grade

**Average Math Scores Before NaNs**                              **Average Math Scores After NaNs** <br>
![Avg Math Scores before NaNs](resources/AvgMathScoresByGrade_beforeNaNs.PNG)
![Avg Math Scores after NaNs](resources/AvgMathScoresByGrade_afterNaNs.PNG)
<br>
<br>

**Average Reading Scores Before NaNs**                           **Average Reading Scores After NaNs**
![Avg Reading Scores before NaNs](resources/AvgReadingScoresByGrade_beforeNaNs.PNG)
![Avg Reading Scores after NaNs](resources/AvgReadingScoresByGrade_afterNaNs.PNG)
<br>

The only grades affected were math and reading scores from 9th graders in Thomas High School. Their grades were replaced with NaNs. All other grades from all other schools were not affected.
<br>
<br>
### 5. School performance based on the budget per student

**Scores by School Spending Before NaNs**
![Scores by School Spending before NaNs](resources/ScoresBySchoolSpending_beforeNaNs.PNG)

**Scores by School Spending After NaNs**
![Scores by School Spending after NaNs](resources/ScoresBySchoolSpending_afterNaNs.PNG)

Since Thomas High School is in the $630-$644 bin, the “% Passing Math”, the “% Passing Reading”, and the “% Overall Passing” were affected in the $630-$644 Spending Ranges (Per Student) category. The “% Passing Math”, the “% Passing Reading”, and the “% Overall Passing” decreased by 6%, 7%, and 7%, respectively.
<br>
<br>
### 6. School performance based on the school size
**Scores by School Size Before NaNs**
![Scores by School Size before NaNs](resources/ScoresBySchoolSize_beforeNaNs.PNG)

**Scores by School Size After NaNs**
![Scores by School Size after NaNs](resources/ScoresBySchoolSize_afterNaNs.PNG)

Since Thomas High School is a medium sized school, only the “% Passing Math”, the “% Passing Reading”, and the “% Overall Passing” were affected in the medium (1000-2000) school size category. The “% Passing Math”, the “% Passing Reading”, and the “% Overall Passing” all decreased by 6%.
<br>
<br>
### 7. School performance based on the type of school
**Scores by School Type Before NaNs**
![Scores by School Type before NaNs](resources/ScoresBySchoolType_beforeNaNs.PNG)

**Scores by School Type After NaNs**
![Scores by School Type after NaNs](resources/ScoresBySchoolType_afterNaNs.PNG)

Since Thomas High School is in the charter type category, only the “% Passing Math”, the “% Passing Reading”, and the “% Overall Passing” were affected in the charter school type category. The “% Passing Math”, the “% Passing Reading”, and the “% Overall Passing” decreased by 4%, 4%, and 3%, respectively.
<br>
<br>
## Summary
Some of the major changes in the updated school district analysis after math and reading scores for the ninth grade at Thomas High School have been replaced with NaNs include:
1. Thomas High School is no longer in the top 5 performing schools.
2. In the school summary, the “% Passing Math”, the “% Passing Reading”, and the “% Overall Passing” for Thomas High School drastically went down by 26%, 27%, and 26%, respectively.
3. In the school performance based on the budget per student summary, the “% Passing Math”, the “% Passing Reading”, and the “% Overall Passing” decreased by 6%, 7%, and 7%, respectively.
4. In the school performance based on the school size summary, the “% Passing Math”, the “% Passing Reading”, and the “% Overall Passing” all decreased by 6%.
