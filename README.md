# pandas-challenge
Module 4 Pandas Challenge
1. Xpert Learning Assistant helped with formatting a % ".map(lambda x: f"{x:.2f}%")"
2. Xpert Learning Assistant helped with function to determine the total number of students who passed both 

More detailed explanation of findings

### Findings

**Scores by Grade Level**  
When examining outcomes by grade level, there is no observable trend between grade levels and scores. Within each school, the average scores vary by one point or less between grade levels, and no discernible pattern emerges in this minor variation across schools.

**Scores by School Spending per Student**  
The highest average scores, along with the highest percentage of students passing math, percentage of students passing reading, and percentage of students passing overall, were found in the spending range of <$585 per student. This was followed by the $585–630 per student range. Student performance decreased significantly in the $630–645 and $645–680 spending ranges. Based on this data, it appears that lower spending per student is associated with better student performance.

**Scores by School Size**  
School sizes were categorized into three ranges: large (2000–5000 students), medium (1000–2000 students), and small (<1000 students). Large schools had the lowest percentage of students passing math, percentage of students passing reading, and percentage of students passing overall, with the lowest overall passing percentage by far. One notable exception is Wilson High School, which had among the highest passing percentages despite being in the large school category. Medium and small schools showed little to no difference in student performance between them, but all had higher passing percentages than large schools. From this data, we observe that schools with more than 2000 students tend to have lower performance, while schools with fewer than 2000 students generally perform better. Overall, it appears that school size influences student performance, with schools having fewer than 2000 students performing better, except in the case of Wilson High School.

**Scores by School Type**  
Charter schools outperform district schools in every category. While district schools’ average reading scores are relatively close to those of charter schools, charter schools far surpass district schools in the percentage of students passing math, percentage of students passing reading, and percentage of students passing overall. This suggests that school type is a contributing factor to student performance, with charter schools performing better overall.

Analysis included in PyCitySchools_Code.ipynb

# PyCity Schools Analysis

### Project Summary

This project involved aggregating data to create a district summary that highlights key performance metrics. These metrics include:
- Total number of schools
- Total number of students
- Total budget
- Average math and reading scores
- Percentage of students passing math
- Percentage of students passing reading
- Overall passing percentage

Additionally, the analysis extended to the district’s 15 individual high schools where data was aggregated to examine a number of metrics potentially influencing the percentages of students passing math, percentage of students passing reading, and percentage of students passing overall. These metrics include:
- Grade (9th, 10th, 11th, and 12th)
- School spending per student
- School size
- School type (district or charter)

The purpose was to understand how different metrics at the school level might contribute to these outcomes.

---

### Summary Analysis

**Lower Performing Schools**  
- All are district schools.  
- All fall into the "Large" category for number of students.  
- All are in the $630–680 spending per student range, except for Bailey High School, which, despite being in the $585–630 range, exhibits the same low student performance as the other district schools.  

**Higher Performing Schools**  
- All are charter schools.  
- Most fall into the "Small" or "Medium" categories for number of students, except for Wilson High School, which is in the "Large" category but still maintains high student performance.  
- All are in the <$585–630 spending per student range, except for Thomas High School, which, despite being outside this range, still exhibits the same high student performance as the other charter schools.

Grade level has no correlation with student performance.

---

### Overall Findings

- **District Schools** tend to have larger student populations and higher spending per student, which correlates with lower student performance across the board. The exception to this trend is Bailey High School, which, despite being in the lower $585–630 spending per student range, exhibits the same low student performance as the other district schools.  
- **Charter Schools**, on the other hand, tend to have smaller student populations and lower spending per student, which is associated with higher student performance. The exceptions to this trend are Wilson High School, which is in the "Large" size category, and Thomas High School, which is in a higher spending per student range, however, both still exhibit the same high student performance as the other charter schools.  
- Charter schools outperform district schools across all analyzed metrics. Lower spending per student and smaller school size appear to be contributing factors to better student performance.

Since all charter schools outperform district schools despite some outliers in the spending per student and school size categories, a possible next step would to be to further analyze charter schools to see what other factors could be contributing to such high student performance. Potential metrics could be student:teacher ratio and parental involvement measured in number of volunteer hours.  
