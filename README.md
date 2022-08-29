# School District Analysis

## Overview
The school board has notified Maria and her supervisor that their is evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth  She has asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once I replaced the math and reading scores, Maria would requested me to repeat the school district analysis that I did in this module and write up a report to describe how these changes affected the overall analysis.

## Purpose
The purpose of this analysis was to highlight the differences that will occur in the student data and school data after math and reading scores of the ninth grade students in Thomas High School are removed. To help Maria present the information to the school board, I will show her the major differences between the district summary, school summary, Thomas High School's performance relative to the other schools, math and reading scores bby grade, scores by school spending, scores by school size, and scores by school type.

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
  - The first four columns of the school summary will be the same due to the number of students in the data staying the same. The following 5 columns are affected, but with little significance. After the upperclassmen % Passing Math, % Passing Reading, and % Overall Passing are calculated and entered into the school summary DataFrame, each respected category is only slightly changed.  
  
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

-Scores by school spending
  -

-Scores by school size
  -

-Scores by school type
  -
