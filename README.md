# School District Analysis

## Overview of the school district analysis
The school district would like me to summarize math and reading scores by different categories and breakdowns which include the district overview, school summary, scores by grade, scores by spending, scores by size, and scores by type. 

The school board has notified that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders. I have been asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. I am to use this new data to report how these changes affected the overall analysis.

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.7.7 with Anaconda running Jupyter Notebook

## Results
- How is the district summary affected? The school district summary changed very slightly with the average and the percent passing slightly decreasing for both math and reading.

![](/Resources/District_Summary.png)

- How is the school summary affected? The school summary was affected because Thomas High School also went slightly down in average math score, percentage passing math, percent passing reading, and percent of overall passing with a slight increase of the average reading score.

![](/Resources/School_Summary.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? Thomas High School after readjusting for 9th graders being excluded ended in second highest once again albeit with a slightly lower score in math scores, percent passing math and reading, and percent overall passing. 

![](/Resources/Comparison_Summary.png)

- How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade: The math and reading scores were affected for Thomas High School 9th graders as these were made to be NaN until the investigation is complete.

For math:

![](/Resources/Math_Grade_Summary.png)

For reading:

![](/Resources/Reading_Grade_Summary.png)

- Scores by school spending: The bin of $630-$644 was affected by Thomas High School slightly with the average math score going down, the average reading score going up, and the percent passing math, reading, and overall going down.

![](/Resources/School_Spending_Summary.png)

- Scores by school size: The bin of "Medium (1000-2000)" students was affected by Thomas High School slightly with the average math score going down, the average reading score going up, and the percent passing math, reading, and overall going down.

![](/Resources/School_Size_Summary.png)

- Scores by school type: The bin of "Charter" schools was affected by Thomas High School slightly with the average math score going down, the average reading score going up, and the percent passing math, reading, and overall going down.

![](/Resources/School_Type_Summary.png)

## Summary
Four major changes in the updated school district analysis occured after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. 

- The analysis for math grades was affected by the NaNs of Thomas High School so it was not easy to compare schools for that specific year. 
- The analysis for reading grades was affected by the NaNs of Thomas High School so it was not easy to compare schools for that specific year. 
- The overall rank of Thomas High School was not affected by the removal of the 9th grade grades indicating that Thomas High School is an overall good school to be able to remain in second place even after potential academic dishonesty occuring. 
- The averages were barely affected by the removal of the ninth grade grades of Thomas High School indicating that the true scores for this grade should be similar to what was submitted or it would be different from the school's overall performance.
