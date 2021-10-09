# School_District_Analysis
Analyzing school district standardized test scores using Anaconda and Jupyter Notebook

## Overview of the school district analysis
There was evidence of a academic dishonesty in the school district.  The analysis looked at the total data with the suspect data removed.  The suspect data (math and reading scores for 9th grader Thomas High School) was replaced with NaN. Once replaced, a new analysis is done for the schools in the district.

## Results
 - District Summary 
 
 The district summary between the original data with the suspect data and the revised data with the suspect data removed shows a slight difference.

Original Data

![District_Analysis_Before](https://user-images.githubusercontent.com/86331812/136638242-75cc69d3-b26e-4aaa-b2c5-718d08514943.png)

Revised Data

![District_Analysis_After](https://user-images.githubusercontent.com/86331812/136638248-110d7fad-1e89-4302-b2fd-b0d1ce8487c2.png)

The data shows a slight difference in the average math score, %Passing Math, %Passing Reading, and %Overall Passing. 


- School Summary

The school summary shows a slight increase in Thomas High School's reading and math scores.  

Original Data

![School_Analysis_Before](https://user-images.githubusercontent.com/86331812/136636107-0e0fa615-4e40-45c6-bf1b-01c30c428979.png)

Revised Data

![School_Analysis_After](https://user-images.githubusercontent.com/86331812/136636116-6c3bb79c-069a-4783-9c25-30fecf529573.png)

All the other schools scores did not change.  

- Affect of taking out the suspect data (Thomas High School ninth graders' math and reading scores) was slight.  There was a decrease in both the reading and math scores for Thomas High School. The overall %passing score goes from 90.95% to 90.63%. 

- Replacing the 9th grade scores affected the other comparisions.

  - Math and reading by grade

Original Data - Math

![MathScores_by_grade_before](https://user-images.githubusercontent.com/86331812/136636999-bc82883e-26cb-4337-82e0-ff405ca9a89f.png)

Orignal Data - Reading

![ReadingScores_by_grade_before](https://user-images.githubusercontent.com/86331812/136637065-225246a4-376c-471b-b771-3549d947afef.png)


Revised Data - Math

![MathScores_by_grade_after](https://user-images.githubusercontent.com/86331812/136636989-5e406093-b8e3-42c4-ae56-5a1424110bcd.png)

Revised Data - Reading

![ReadingScores_by_grade_after](https://user-images.githubusercontent.com/86331812/136637197-0c61bcd5-f9f5-44c5-9e8e-73e92218d742.png)



The only difference shows that the there is NaN for the Thomas High School 9th grader math and reading scores.

  - Scores by school spending

Original Data

![Scores_by_Spending_Before](https://user-images.githubusercontent.com/86331812/136637303-13b0eb22-c1ee-4acf-b0ec-32afc09ce129.png)

Revised Data

![Scores_by_Spending_After](https://user-images.githubusercontent.com/86331812/136637312-f8e38672-623b-4055-9554-a6730ba67186.png)

There is a slight change in math and reading scores due to spending per school.  For the spending range (per student) for the $630 - $644 range, the original data shows 81.62% for the average reading score.  The revised data shows the average reading score of 81.63%.  The original data shows an average math score of 78.50% and the revised data shows 78.51%.  

  - Scores by school size

Original Data

![Scores_by_Size_Before](https://user-images.githubusercontent.com/86331812/136637687-0a312160-5454-4aa7-91df-bc9c3042ce70.png)


Revised Data

![Scores_by_Size_After](https://user-images.githubusercontent.com/86331812/136637694-74f07d40-7530-41a4-b1bf-754d8f262a0d.png)

The original data and the revised data shows there is a difference in the medium school size during the comparision. For example, in the initial data for the average math score for the medium sized schools is  83.38%.  In the revisied data, the average math scoore is 83.36%. For each category in the medium sized school row, there is a difference between the original data and the revised data. 


 - Scores by school type

Original Data

![Scores_by_Type_Before](https://user-images.githubusercontent.com/86331812/136637936-13bd4128-3bf8-47b0-968c-de61655754cf.png)

Revised Data

![Scores_by_Type_After](https://user-images.githubusercontent.com/86331812/136637970-3e18b6c3-761b-4ebd-bc2b-df74e8e7beed.png)

This data shows a slight difference in the charter school data.  Thomas High School is a charter school.  By dropping the suspected dishonest data from Thomas High school, a slight difference is shown in the summary.  In the original data, it was shown that the average math score is 83.465%.  After the data is revised, it is shownd that the average math score is 83.474%.  The average reading score was 83.90% with the original data.  The revised data shows that the average reading score is 83.896%. The difference in the percentages is slight.  The overall percentage of students passing both math and reading goes from 90.39% in the original data and 90.43% in the revised data.  


## Summary
There were for changes in the updated school district analysis.  

  - the scores by type for the charter schools
  - the scores by size for the medium size schools
  - the scores by spending per spending per student range in the $630 - $640 
  - the average in scores for reading and math for Thomas High Schools
