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