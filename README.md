# Unit 4 Challenge – School District Analysis
## Overview of the school district analysis
### Purpose of this analysis
This project centered on standardized testing data from the high schools in a simulated school district. From CSV files containing student data, including students’ raw scores on standardized math and reading tests, along with data regarding the size, budgets, and educational models of the schools themselves, several data frames were constructed that summarized student performance on standardized tests. The metrics used to measure student performance were the average scores on the math and reading tests, the percentage of the student body that passed each test, and the percentage of the student body that passed in both math and reading. 
Subsequently, the challenge assignment started from the supposition that there had been an academic integrity violation among the ninth graders at one of the schools in the dataset, Thomas High School. The same data summaries were assembled again, this time excluding the group that was said to have been affected. Our objective is to note any changes to the data summaries when removing the suspect scores, and to observe trends in how the various traits of the schools relate to student performance.
## Results
### Effects of removing the THS ninth-grade scores
- The removal of the scores did not have a substantial impact on the performance of the district as a whole. The passing percentages (reading, math, and overall) remained the same when rounding to the nearest whole percentage point. The district’s average score in reading remained an 89.1, while the average math score dropped by only one tenth of a point, from 79 to 78.9. For reference, this is the summary including the students in question ![District summary with all students](Resources/Original_district_summary.png). For comparison, this version excludes the disputed scores from the averages: ![District summary excluding THS 9th graders](Resources/New_district_summary.png).
- Effects on the school summary
- Effects on Thomas High School relative to other high schools
- Effects on analysis of subgroups of schools
-By grade:
-By spending:
-By size:
-By school type: 

## Summary
Changes to the updated analysis after replacing the Thomas High School ninth-grade scores with NaNs include the following:
-
-
-
-
