# School District Analysis

## Overview
The school board has notified Maria and her supervisor that their is evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth  She has asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once I replaced the math and reading scores, Maria would requested me to repeat the school district analysis that I did in this module and write up a report to describe how these changes affected the overall analysis.

## Purpose
The purpose of this analysis was to highlight the differences that will occur in the student data and school data after math and reading scores of the ninth grade students in Thomas High School are removed. To help Maria present the information to the school board, I will show her the major differences between the district summary, school summary, Thomas High School's performance relative to the other schools, math and reading scores by grade, scores by school spending, scores by school size, and scores by school type.

### Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Anaconda Prompt (Python Data), Jupyter Notebooks

## Results
- How is the district summary affected?
  - Due to there only being 461 ninth grade students in Thomas High School, out of the 39,170 (~1%), the removal of the reading and math scores did not have a large impact on any components of the district summary.

**District Summary, with Thomas High School ninth graders**
![District_Summary_Full](https://user-images.githubusercontent.com/109091887/186651315-0be756a1-f52c-4d3c-b0a2-a7874e97d56b.PNG)

**District Summary, without Thomas High School ninth graders**
![District_Summary_New](https://user-images.githubusercontent.com/109091887/186651363-7cdfbd6e-3552-446e-89a0-2983568277c5.PNG)


- How is the school summary affected?
  - The first four columns of the school summary will be the same due to the number of students in the data staying the same. The following 5 columns are affected, but with little significance. After the upperclassmen's % Passing Math, % Passing Reading, and % Overall Passing are calculated and entered into the school summary DataFrame, each respected category is only slightly changed.  
  
**School Summary, with Thomas High School ninth graders**
![School_Summary_Full](https://user-images.githubusercontent.com/109091887/186653601-055e5d29-a0a3-4cd4-92c6-aeb1a526a064.PNG)
 
**School Summary, without Thomas High School ninth graders**
![School_Summary_New](https://user-images.githubusercontent.com/109091887/186670984-4856130d-83f7-452a-9b67-6fb312d6d82e.PNG)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - With the ninth graders' math and reading scores included in the overall school data, Thomas High School ranks 2nd among all schools, using % Overall Passing. When the ninth graders' scores are replaced, Thomas High school remains at 2nd, of the 15 schools in the district.

How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
  - By replacing the ninth-grade math and reading scores, instead of the ninth-grade having math and reading scores or 83.6 and 83.7, respectively, the scores will be shown as 'NaN.' The scores for upperclassmen will remain the same. Images of the math scores are shown below.

**Math Scores by Grade, with Thomas High School ninth graders**

![Math_Scores_by_Grade_Full](https://user-images.githubusercontent.com/109091887/187212196-462629a7-fecd-4ca1-92c0-b08d5f47b18d.PNG)

**Math Scores by Grade, without Thomas High School ninth graders**

![Math_Scores_by_Grade_New](https://user-images.githubusercontent.com/109091887/187212246-e129173a-a5d6-4599-b5e4-0894d2675e71.PNG)

- Scores by school spending
  - Thomas High Schools falls in the $631-645 spending range. When looking at the values for Average Math Score,	Average Reading Score,	% Passing Math,	% Passing Reading, and	% Overall Passing, they are only slightly affected when the ninth grade students are removed. Once the value are rounded, there is no difference between in the values of the two charts.

**Scores by School Spending, with Thomas High School ninth graders**
![Scores_by_Spending_Full](https://user-images.githubusercontent.com/109091887/187212929-7e2396a1-d97d-48b1-b884-c74eb80bac05.PNG)

**Scores by School Spending, without Thomas High School ninth graders**
![Scores_by_Spending_New](https://user-images.githubusercontent.com/109091887/187212949-436fc33a-56b9-4aa3-8590-ddd201907e90.PNG)

- Scores by school size
  - Thomas High Schools falls in the Medium (1000-1999) school size range. Similarly to the Scores by School Spending, you can only see the change by comparing the tables before rounding the values. Therefore, the removal of the ninth-grade students had little to no effect on the scores by school size.

**Scores by School Size, with Thomas High School ninth graders**
![Scores_by_SchoolSize_Full](https://user-images.githubusercontent.com/109091887/187214514-0f493f9c-bd62-4694-9587-c32c017e1f25.PNG)

**Scores by School Size, without Thomas High School ninth graders**
![Scores_by_SchoolSize_New](https://user-images.githubusercontent.com/109091887/187214529-e1632be3-a087-4378-a77e-c57720a6a80c.PNG)

- Scores by school type
  - Thomas High School is a Charter School. As one may predict by the end of this analysis, the removal of the ninth grade students had minimal effect on each of the categories.

**Scores by School Type, with Thomas ninth graders**
![Scores_by_SchoolType_Full](https://user-images.githubusercontent.com/109091887/187215743-819fee60-ca79-4608-a0a0-58dfeb8f8e50.PNG)

**Scores by School Type, without Thomas ninth graders**
![Scores_by_SchoolType_New](https://user-images.githubusercontent.com/109091887/187215768-713739ff-eda2-4fdd-a592-5c690e64197e.PNG)

## Summary
After the ninth grade students from Thomas High School are removed, it is unclear if there was plagiarism occuring. I would recommend looking further into the details of the ninth graders opposed to comparing the overall metrics with and without them. Due to the large about of students in the district, when looking at the values that include all of these students, we are not able to see changes. This includes the district summary, scores by school spending, scores by school size, and scores by school type. When looking specifically at Thomas High School in the per school summary, we are able to see five minor changes occur in Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, and % Overall Passing. These minor changes vary in whether the score or percent increases or decreases, so we are not able to make a claim that the removal of the ninth grade scores affected the overal scores of Thomas High Schools students one way or another. 
