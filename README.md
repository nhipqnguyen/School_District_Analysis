# School District Analysis
# Project Overview
The Chief Data Scientist for the PyCity School District has given us the tasks to help make strategic decisions regarding future school budgets and priorities based on the standardized test scores and current school funding.

1. Generate the school district summary.
2. Generate the school summary.
3. Determine top 5 and bottom 5 performing schools based on the pverall passing rate .
4. Calculate average Math and Reading Scores by grade.
5. Group scores by school spending per Student.
6. Group scores by school size.
7. Group scores by school type.

## Challenge Overview
After we generate the needed information, the school board has notified us that the provided students' scores data file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders. Therefore, we have been asked to replace the math and reading scores for Thomas High School ninth graders with NaNs while keeping the rest of the data intact, then repeat the school district analysis with the updated dataset. 

## Resources
- Data Source: schools_complete.csv and students_complete.csv
- Software: Anaconda 4.10.1, Jupyter Notebook.

## School District Analysis Results
- Below are the screeenshots of the original and updated district summaries:

  ![Original District Summary](https://github.com/nhipqnguyen/School_District_Analysis/blob/main/Analysis/original_district_summary.png)

  ![Updated District Summary](https://github.com/nhipqnguyen/School_District_Analysis/blob/main/Analysis/updated_district_summary.png)

  - We can see that while the average reading scores remain unchanged, the average math score goes down by 0.1, the passing math percentage goes down by 0.2, the passing reading perentage goes down by 0.3, and the overall passing percentage goes down by 0.1.

- Below are the screeenshots of the original and updated school summaries:

  ![Original School Summary](https://github.com/nhipqnguyen/School_District_Analysis/blob/main/Analysis/original_school_summary.png)

  ![Updated School Summary](https://github.com/nhipqnguyen/School_District_Analysis/blob/main/Analysis/updated_school_summary.png)
  
  - While the figures for other schools remain unchanged, Thomas High School's figures have some changes. After the change we made to the dataset, its average math score and passing math percentage go down by approximately 0.07 and 0.09. While its average reading score go up by approximately 0.05, its passing reading percentage goes down by approximately 0.3. Its overall passing percentage goes down by approximately 0.3.

- Below are the screeenshots of the original and updated math scores by grade:

  ![Original Math Scores by Grade](https://github.com/nhipqnguyen/School_District_Analysis/blob/main/Analysis/original_math_scores_by_grade.png)

  ![Updated Math Scores by Grade](https://github.com/nhipqnguyen/School_District_Analysis/blob/main/Analysis/updated_math_scores_by_grade.png)

  - Except for Thomas High School nith graders average math score, which became NaN,  math scores for other schools remain unchanged.

- Below are the screeenshots of the original and updated reading scores by grade:

  ![Original Reading Scores by Grade](https://github.com/nhipqnguyen/School_District_Analysis/blob/main/Analysis/original_reading_scores_by_grade.png)

  ![Updated Reading Scores by Grade](https://github.com/nhipqnguyen/School_District_Analysis/blob/main/Analysis/updated_reading_scores_by_grade.png)

  - Simialr to math scores by grade, except for Thomas High School nith graders average reading score, which became NaN, reading scores for other schools remain unchanged.


- Below are the screeenshots of the original and updated scores by school spending (per student):

  ![Original Scores by School Spending](https://github.com/nhipqnguyen/School_District_Analysis/blob/main/Analysis/original_scores_by_school_spending.png)

  ![Updated Scores by School Spending](https://github.com/nhipqnguyen/School_District_Analysis/blob/main/Analysis/updated_scores_by_school_spending.png)

  - While the average math and reading scores for all spending groups remain unchanged, the passing math percentages for all groups go slightly up. The passing reading percentages of spending groups "<$548" and "$585-$629" go slightly down while those of the other 2 spending groups go slightly up. In contrast, the overall passing percentages of spending groups "<$548" and "$585-$629" both go up by 0.4 while those of the other 2 spending groups go down by 0.2 and 0.5.

- Below are the screeenshots of the original and updated scores by school size:

  ![Original Scores by School Size](https://github.com/nhipqnguyen/School_District_Analysis/blob/main/Analysis/original_scores_by_school_size.png)

  ![Updated Scores by School Size](https://github.com/nhipqnguyen/School_District_Analysis/blob/main/Analysis/updated_scores_by_school_size.png)

  - The average math and reading scores for all size groups remain unchanged.

- Below are the screeenshots of the original and updated scores by school type:

  ![Original Scores by School Type](https://github.com/nhipqnguyen/School_District_Analysis/blob/main/Analysis/original_scores_by_school_type.png)

  ![Updated Scores by School Type](https://github.com/nhipqnguyen/School_District_Analysis/blob/main/Analysis/updated_scores_by_school_type.png)

  - The average math and reading scores for both groups remain unchanged.
 

## School District Analysis Summary
After reading and math scores for the ninth graders at Thomas High School have been replaced with NaNs, we notice the following main changes:
- Thomas High School's average math scores, math passing percentage, reading passing percentage, and overall passing percentage all go down. However, its average reading score goes up.
- The change in Thomas High School math and reading scores lead to the decrease of all related numbers in the district summary.
- There is no patterns in the changes of the passing rates of different spending groups. Some of the numbers go up and some go down.
- There is no changes to the data of different school size groups and school type groups.
