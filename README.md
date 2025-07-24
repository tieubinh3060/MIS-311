# MIS-311
Introduction to Business Analytics
# Project 1: Student Performance Analysis

## Overview
This project focuses on analyzing student academic performance across three core subjects: **Math, Reading, and Writing**. The goal is to understand how demographic and socioeconomic factors may influence academic outcomes and identify potential areas for educational improvement.

## Dataset Description
The dataset includes records of student performance, along with demographic information. It provides a foundation for exploring patterns and disparities in academic achievement.

### Key Variables
- `gender`: Binary-coded (0 or 1), likely representing male and female.
- `race_ethnicity`: Categorical variable (e.g., Group A, B, C...).
- `parental_level_of_education`: Educational attainment level of the student's parents.
- `math_score`: Student's score in math.
- `reading_score`: Student's score in reading.
- `writing_score`: Student's score in writing.
- `total_score`: Combined total of the three subject scores.
- `average_score`: Average of the three subject scores.

## Key Insights
- **Math Score**:
  - Median and mode are both 65, indicating symmetry in the central tendency.
  - The distribution is negatively skewed (-0.397), with a standard deviation of 15.98—higher than that of reading and writing.
  - Boxplot analysis reveals a greater spread toward lower values and the presence of outliers.
  - These findings suggest that although average math performance is moderate, a larger number of students are underperforming in this subject compared to reading and writing.

- **Total and Average Scores**:
  - The range for `total_score` is 272, and for `average_score` is 90.67, reflecting high variability.
  - Average scores range from as low as 9 to nearly 100, indicating significant disparities in academic outcomes.
  - This may be attributed to differences in background, academic support, or engagement levels among students.

## Conclusion
The analysis highlights **notable disparities in student performance**, particularly in math. The wide range in total and average scores points to substantial variation in academic achievement. These findings underscore the importance of:
- Providing targeted support for lower-performing students.
- Reviewing and improving instructional methods in math to better support learners.
  
Efforts to address these gaps can lead to more equitable and effective educational outcomes.
