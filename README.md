# School_District_Analysis
## Overview of the school district analysis
### Introduction
#### Maria is a chief data scientist in a city school system and she is tasked with preparing all the standardized test data for analysis. This will help to inform decisions about a number of issues. Maria asks for your help in this analysis to look at things such as funding and standardized test scores. This will help the school board understand how a number of factors affect the test scores and preformances of the kids in that school.
### Purpose
#### In the challenge it was discovered that the 9th graders from Thomas High School may have had some corruption with their data. After you and Maria have run the analysis on the school data you are requested to go back through and run the analysis without that data to  make sure that the analysis is cleaned from discrepiences.
## Results
#### How is the district summary affected?
* After taking out the 9th graders that go to Thomas High School (THS) the count of total students went from 39170 to 38709, making a total of the students removed 461. This group makes up about 1.17 % of all the students in the summary but the removal had a large affect on the data. Before the removale of the data the passing math percentage was 78.9% and the passing reading percentage was 81.8%. After the removal of the corrupt data the pasisn math percentage went down to 74.7% and the passing reading went up to 85.6%. The overall passing math and reading combined went from 65.1% to 65.9% so it did not have as much affect on that number
#### How is the school summary affected?
* For THS, the % Passing Math and % Passing reading scored for THS went from 93.27% to 66.9% and 93.31% to 69.66%, though the % Overall Passing went from 90.94% to 90.63%.
  * Before
  ![school before](https://github.com/allisonorourke-ufGfGy/School_District_Analysis/blob/main/Images/THS%20summary%20before.png)
  * After:
  ![school after](https://github.com/allisonorourke-ufGfGy/School_District_Analysis/blob/main/Images/THS%20summary%20after.png)
#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
* Before and after the removal of the 9th grade score, THS stayed in the second place position among all of the schools. It did not seem to have much affect on the standing of the school.
  * Before:
  ![standing before](https://github.com/allisonorourke-ufGfGy/School_District_Analysis/blob/main/Images/School%20standing%20after.png)
  * After:
  ![standing after](https://github.com/allisonorourke-ufGfGy/School_District_Analysis/blob/main/Images/School%20standing%20after.png)
  
#### How does replacing the ninth-grade scores affect the following:
* Math and reading scores by grade : Only the 9th grade score was affected. All of the other grades (10th, 11th, and 12th) had no impact. Previously the math and reading scores for the 9th graders at THS was 85.6% but then this went down to null after the removal. The overall passing scores for 9th graders among the district consequently also went down.
* Scores by school spending : THS is in the range of $631 - $645 spent per student. Before the removal the overall percent passing for this spending range was 62.85%. After the removal, the score for that category went up to 66.0%.
  * Before:
  ![spending before](https://github.com/allisonorourke-ufGfGy/School_District_Analysis/blob/main/Images/spending%20before.png)
  * After:
  ![Spending after](https://github.com/allisonorourke-ufGfGy/School_District_Analysis/blob/main/Images/spending%20after.png)
* Scores by school size : THS is a medium sized school (1000-1999 student). Before the removal the overall passing score was 90.62%. After the removal of the data, the score went down to 90.55%.
  * Before :
  ![Size Before](https://github.com/allisonorourke-ufGfGy/School_District_Analysis/blob/main/Images/size%20before.png)
  * After:
  * ![Size After](https://github.com/allisonorourke-ufGfGy/School_District_Analysis/blob/main/Images/size%20after.png)
* Scores by school type : Before the removal of the corrupt data, Charter schools had an overall passing rate of 90.43%. After the removal this went down to 90.39 % for charter schools. 
  * Before:
  ![type before](https://github.com/allisonorourke-ufGfGy/School_District_Analysis/blob/main/Images/type%20before.png)
  * After:
  ![type after](https://github.com/allisonorourke-ufGfGy/School_District_Analysis/blob/main/Images/type%20after.png)
## Summary

