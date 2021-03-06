# An Analysis of School District Data using Python, Pandas, Anaconda and Jupyter Notebook

## Overview
School district data on standardized reading and math test scores as well as on current school funding was analyzed. The main purpose of this analysis was to help the school administration make strategic decisions with respect to the school district priorities and future school budgets.

## Results
The analysis were first conducted with the whole sample, which consisted of 15 schools and 39,170 students. As there was evidence of misconduct, analysis were rerun excluding the reading and math scores for Thomas High School 9th grade students (n = 461). The results will center on reporting the results for the second analysis. Differences between results from the two analysis will be noted.

### District Summary
Table 1 shows a summary of the district overall outcome measures. As seen in Table 1, the majority of students in the school district scored higher than the passing grade (set as 70) for math (74.8% of students passed) and reading (85.7% of students passed). This summary was only slightly affected by the exclusion of the Thomas High School 9th grade scores. All averages and percentages decreased slightly with the greater drop happening in the Overall Passing percentage from 65.2% to 64.9%. 

Table 1. District Summary
![Table_1](https://user-images.githubusercontent.com/89421440/141709118-a9831008-3dcf-4028-81aa-edacde135e44.png)

### School Summary 
Table 2 details the district summary by school. As seen in Table 2, schools vary by the total number of students and total budget they receive, but the rate of school budget per student remains in a range from $500 to $700. With respect to average scores and percentages of passing grades, it is possible to observe that the performances of schools vary more for math compared to reading.

Table 2. School Summary
![Table_2](https://user-images.githubusercontent.com/89421440/141731757-202ebc02-28b8-4d8c-b436-eb4f0151b740.png)

Again, the exclusion of the Thomas High School 9th grade scores had only a minimal effect on this school???s summary outcomes. All averages and percentages decreased a maximum of 3 decimal points, which would not be considered a statistically significant difference.

### Top Performing Schools 
As shown in Table 3, the school with best overall passing percentages was Cabrera High School with over 91% of students achieving math and reading passing grades.

Table 3. Top Schools
![Table_3](https://user-images.githubusercontent.com/89421440/141731794-98db407f-41a7-460d-a6e4-ebaaf6b24a0d.png)

The exclusion of the scores from 9th grade students didn???t affect Thomas High School position rank. Thomas High School was still the second best performing schools with over 90% of students achieving math and reading passing grades.

### Further Score Analysis
The following analysis weren???t affect by the exclusion of the scores from Thomas High School 9th grade students:
	
#### Math and reading scores by grade
As seen in Table 4, reading scores were relative constant among schools and grades, ranging 80 to 90.

Table 4. Reading Scores

![Table_4](https://user-images.githubusercontent.com/89421440/141731912-8637b3eb-c909-47c4-b5a2-cbe7463aff6b.png)

As seen in Table 5, math scores varied more compared to reading scores. The variation in scores seems to point to differences between schools rather than differences between grade levels. That is, math scores across grades in one school varied less than math scores across schools in the same grade.

Table 5. Math Scores

![Table_5](https://user-images.githubusercontent.com/89421440/141731971-c63cf074-1a08-4b9e-ab12-2caeabb0dab8.png)

#### Scores by school spending
Table 6 displays students??? scores by the range amount each school spends per student. It seems that schools that spend less with each students perform better than schools that spend more. This result is counterintuitive and may require further investigation to inform school decisions

Table 6. Scores by School Spending

![Table_6](https://user-images.githubusercontent.com/89421440/141731999-f6e8b219-8ac8-4e92-a335-222abe6eb756.png)

#### Scores by school size
Table 7 shows how scores varied by the size of schools. It appears that larger schools tend to perform more poorly, specially in math, compared to smaller schools.

Table 7. Scores by School Size

![Table_7](https://user-images.githubusercontent.com/89421440/141732027-79e3f12f-226b-41bc-9a93-583c23d31274.png)

#### Scores by school type
As seen in Table 8, students in charter schools seems to perform  better, especially in math, compared to students in district schools.

Table 8. Scores by School Type

![Table_8](https://user-images.githubusercontent.com/89421440/141732061-ae4741b9-5a61-4561-96cc-82297e695289.png)

## Summary
In sum, excluding the reading and math scores for Thomas High School 9th grade students did not lead to striking differences in the school district analysis. The main differences concerned the adjustment of averages and percentages values for the district and the school summaries.
