# Module 4 Assignment - School District Analysis

## Background
After a meeting with the school board, Maria and her supervisors were asked to use the data that they currently have and look into the possibility of academic dihonesty. In particular, the school board believes that reading and math grades may have been altered for ninth grade students at Thomas High School. Maria has asked us to review the data with and without the potentially altered data to see if there is merit to the school boards claims. In our reporting below, we will look to answer the following questions:

- How is the district summary affected?
- How is the school summary affected?
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- How does replacing the ninth-grade scores affect the following:
	- Math and reading scores by grade
	- Scores by school spending
	- Scores by school size
	- Scores by school type

Differences between the data point for the scenarios with and without the Thomas High School nineth grade data will give us talking points to use when discusssing the possibility of academic dishonesty.

## Academic Analysis Results
After performing the analysis of the student and school data initially provided by the school board, we are now able to review the impact that the Thomas High School nineth grade students have on different success metrics from the district level to the school and grade level. Due to how extensive our review is and the number of exhibits that are needed to fully flush out the impact of a specific population, exhibits for the analyses below can be found in the appendix. The analyses will note where the exhibits can be found.

### The district summary
When reviewing the data from the district level, removing the ninth grade students from Thomas High School does not materially impact the overall percentages for students in the district passing math or reading. Under both scenarios, the percentage of students passing reading was 81.9%. For the percentage of students passing math, the average decreased slightly from 79.0% to 78.9%. This is an extreemly small amount and not one that would point to academic dishonesty. This is also a result that one would expect when looking how well Thomas High School students do in comparison to the overall district. As the second rated school (see below), removing grades from thier students will cause the district averages to decrease.

### The school summary
When reviewing school specific data for Thomas High School, removing the ninth grade students does impact the results in a manner that could be consistant with academic dishonesty (see Appendix A for ehibits). Before reviewing the numbers we need to add context to the situation. If academic dishonesty occured, the result would likely be that more students received passing grades in reading or math. In addition, we would expect the variance in scores to be lower, likely causing the average to decrease. Reviewing the exhibits in Appendix A, the removal of the students reveals the results discussed above. The removal of the students causes the average reading score to increase (i.e. the average reading score for the students removed was lower than the school average) and the percetn passing math, reading, and subsequently overall passing, to decrease (i.e. the percent of students removed who passed math and reading was higher than the school average). 

While the movement in the scores and passing rates when the ninth grade students were removed were consistant with what we would expected if academic dishonesty occured, the movements are not large enough to prove it. The average math score didn't change, and the average reading score increased by a tenth of a percent. For passing rates, the decreases for math, reading, and overall were only one, three, and three tenths of percent, respectively. These are not significant by any means.

### The top 5 and bottom 5 performing schools, based on the overall passing rate
When removing the ninth grade students from Thomas High School the impact of the removal does not cause the school to change in the overall rankings of schools by overall passing rate (see Appendix B for ehibits). As you may notice from the exhibits in the Appendix, Thomas High School ranks second regardless of if you include their nineth grade class.

### The average math and reading scores for each grade level from each school
Please see Appendix C for the exhibit which outlines the average math and reading scores for each grade level from each school. The exhibits show the scores when the ninth grade class for Thomas High School is included. The only difference between the exhibits when they are or are not included is the one cell showing Thomas High School's ninth grade scores. The rest is unchanged. While the Thomas High School scores for ninth graders is better than their peers from other schools this is not inconsisant with what we see from the other grades at Thomas High School.

### The scores by school spending per student, by school size, and by school type
When reviewing the data based on school spending per student (see Appendix D), by school size (see Appendix E), and by school type (see Appendix F) there is not enough evidence to suggest academic dishonesty occured. Similar to the district level review, the changes are miniscule and are consistant with what we would expect when removing students from the second ranked school in the district.

## Conclusion
After reviewing the analysis with and without the Thomas High School nineth grade student's math and reading grades, there is not conculsive evidence leading us to believe that academic dishonesty occurred. In particular, the district summary statistics were barely affected by the removal of the students, and the impact is consistant with what we would expect when removing students from the second ranked school (regardless of if the ninth grade students are included). When reviewing the district data based on filters like spending per student, school size and school type, the results are the same. On a school level, while the changes in the scores when removing the students is consistant with what we woudl expect if cheating occured, the changes are not large enough to prove that anything occured. In addition, removing the ninth grade students did not affect Thomas high Schools ranking as the second school in the district in terms of overall passing rate. This would suggest that the ninth grade scores were consistant enough with the rest of the school.  

If the school board is convinced that academic dishonesty has occured, they may need to investiagte this from another angle.

## Appendix
**Appendix A**

Thomas High School Data
![pre_ths_summary](https://github.com/kjminges/School_District_Analysis/blob/main/Resources/pre_ths_summary.png)
Thomas High School Data **_Excluding_** Ninth Grade Students
![post_ths_summary](https://github.com/kjminges/School_District_Analysis/blob/main/Resources/post_ths_summary.png)

**Appendix B**

Top Schools By Overall Passing Rate
![pre_top_schools](https://github.com/kjminges/School_District_Analysis/blob/main/Resources/pre_top_schools.png)
Bottom Schools By Overall Passing Rate
![pre_bottom_schools](https://github.com/kjminges/School_District_Analysis/blob/main/Resources/pre_bottom_schools.png)

**Appendix C**

Average Reading Scores by Grade Level and School

![pre_reading_grade](https://github.com/kjminges/School_District_Analysis/blob/main/Resources/pre_reading_grade.png)

Average Math Scores by Grade Level and School

![pre_math_grade](https://github.com/kjminges/School_District_Analysis/blob/main/Resources/pre_math_grade.png)

**Appendix D**

Scores by School Spending per Student

![pre_spending_summary](https://github.com/kjminges/School_District_Analysis/blob/main/Resources/pre_spending_summary.png)

Scores by School Spending per Student **_Excluding_** Ninth Grade Students from Thomas High School

![post_spending_summary](https://github.com/kjminges/School_District_Analysis/blob/main/Resources/post_spending_summary.png)

**Appendix E**

Scores by School Size

![pre_size_summary](https://github.com/kjminges/School_District_Analysis/blob/main/Resources/pre_size_summary.png)

Scores by School Size **_Excluding_** Ninth Grade Students from Thomas High School

![post_size_summary](https://github.com/kjminges/School_District_Analysis/blob/main/Resources/post_size_summary.png)

**Appendix F**

Scores by School Type

![pre_type_summary](https://github.com/kjminges/School_District_Analysis/blob/main/Resources/pre_type_summary.png)

Scores by School Type **_Excluding_** Ninth Grade Students from Thomas High School

![post_type_summary](https://github.com/kjminges/School_District_Analysis/blob/main/Resources/post_type_summary.png)
