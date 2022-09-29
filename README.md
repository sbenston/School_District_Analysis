# School_District_Analysis

## General Overview

Takes data of a school district from a CSV file and uses Pandas to analyze the contents as a dataframe within Jupyter Notebook. The data includes:
* student_id: student's identification number
* student_name: student's name
* grade: student's academic year - (9th, 10th, 11th, 12th)
* school_name: school the student attends
* reading_score: tested reading score of student
* math_score: tested math score of student
* school_type: either Public or Charter for school student attends
* school_budget: the school's budget

## Summary
(Also found as last cell in Student_Data_Challenge.ipynb)

### Summary of all data

The dataset of all students within the district appears to have a fairly normal distribution of both reading scores and math scores. The average reading score for all students was 72.4 with the median being 73, with most of the data points being clustered within the 25% to 75% percentiles judging from the the standard deviation. For math scores, 64.7 was the average and 65.3 was the median, with the data being in a similar range as the reading scores.

### Lowest Math Score

Dixon High School displayed the lowest math score, though more analysis would need to be done to better determine if this is a problem with a particular student or a more widespread issue of all students at that school. Dixon High School is the 3rd largest within the district, the potential relationship of large class size could contribute to a lowering of students' scores, though without data on the teacher count a link cannot be established.

### Comparison of Charter and Public Schools

For the district, despite Charter Schools receiving on average less funding they display higher math scores on average for most grades other than the 12th graders. It would be useful to examine this further, getting other measures of central tendency as well as the student count between these school types to better analyze what other factors might be influencing this discrepancy, and whether or not it is worth examining what these schools might be providing that could improve scores for the entire district.
