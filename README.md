# School_District_Analysis
Module 4 School District Analysis

## Overview of the School District Analysis Project
The School District Analysis project was designed to help Maria, a data scientist for a school district, to assess performance trends and patterns at the school and school district level in an effort to inform school district strategic planning. Specifically, this analysis looked at performance summary information by school and at the district level. The analysis also considered factors such as school spending, school size, and school type (charter or district) in relation to students' performance in math and reading. Additionally, given concerns for academic dishonesty, math and reading scores for Thomas High School 9th graders were removed in a follow-up analysis and those students were excluded from the overall student count.


## Results
### Removal of Thomas High School 9th Graders
Prior to removing Thomas High School 9th grade students, the overall passing percentage at Thomas high school was 90.9%. Upon removing these students, the score decreased significantly until we updated the analysis to exclude those students from the overall student count. Excluding those students from the overall student count brought the overall passing percentage for Thomas High School back to 90.6%. 

### How is the district summary affected?

Interestingly, removing the Thomas High School 9th grade students from the overall analysis had a minimal impact on the overall school distruct summary analysis. The tables below show the top 5 performing schools pre and post removal of the Thomas High School 9th grade students. In both cases, Thomas High School ranks #2 in top performing schools based on the overall passing percentage. 

#### Prior to removing Thomas High School 9th Grade Students
![](/Resources/high_low_v1.png).

#### After removing Thomas High School 9th Grade Students
![](/Resources/High_Low_Schools_2.png).

### How is the school summary affected?

#### Prior to removing the 9th graders, Thomas High School performed as follows: 
![](/Resources/school_summary_v1.png)

#### After remove the 9th graders, Thomas High School performed as follows: 
![](/Resources/school_summary_2.png)

### Affect to the Analysis by School Spending, School Size and School Type

#### Prior to removing the Thomas High School 9th grade students, the school spending summary was as follows: 
![](/Resources/spendingranges1.png)

#### After removing the Thomas High School 9th grade students, the school spending summary is as follows: 
![](/Resources/spendingranges2.png)

#### Prior to removing the Thomas High School 9th grade students, the school size summary was as follows: 
![](/Resources/schoolsize1.png)

#### After removing the Thomas High School 9th grade students, the school size summary is as follows: 
![](/Resources/schoolsize2.png)

#### Prior to removing the Thomas High School 9th grade students, the school type summary was as follows: 
![](/Resources/schooltype1.png)

#### After removing the Thomas High School 9th grade students, the school type summary is as follows: 
![](/Resources/schooltype2.png)


## Summary 
Summarize four changes in the updated school distric analysis after reading and math scores for ninth grade at Thomas High School have been replaced with NaNs
Removing grades for Thomas High School 9th grade students could have had a very significant impact on the analysis had we not also excluding those students in the overall student count within our analysis. However, because we excluded those students with NaNs in our overall analysis, the impact was minimal and the Thomas High Scool average scores were largely unchanged. 

- Removal of Thomas High School 9th grade students did not impact Thomas High School's ranking as #2 in the Top Schools analysis for this district.
- Removal of Thomas High School 9th grade students did result in a slight decrease to Thomas High Schools' overall passing percentage (90.9% decreased to 90.6%). 
- Removal of Thomas High School 9th grade students led to slight decreases in Thomas High Schools' average reading and math scores and passing percentages. 
- Removal of Thomas High School 9th graders did not impact the overall analysis by school spending, school size, or school type.


