
# pandas-challenge

### Background

As part of a personal initiative to apply data analysis skills, I worked on a project to analyze standardized test results from a random city's school district. The objective was to uncover insights and trends in school performance to guide future decisions on budgets and educational priorities. This project gave me an opportunity to showcase my proficiency in data manipulation and visualization using Python and the Pandas library.

### Project Setup

I created a dedicated repository named `pandas-challenge` to house this project. Inside the repository, I organized the project structure, including a subfolder named `PyCitySchools`, which contains all the analysis scripts and data files. The entire workflow was managed using Git, with all changes pushed to a remote repository on GitHub.

### Approach

The analysis was performed in Jupyter Notebook and aimed to provide a detailed report of the following:

#### District-Wide Summary

I calculated district-level metrics, including:

* Total number of unique schools
* Total students
* Total budget
* Average math and reading scores
* Percentages of students passing math, reading, and both subjects overall

These insights were compiled into a high-level snapshot using a Pandas DataFrame.

#### School-Level Analysis

I extended the analysis to a school-by-school breakdown, generating key performance metrics:

* School name and type
* Total students
* School budget (total and per student)
* Average scores in math and reading
* Passing rates for math, reading, and overall performance

#### Performance Rankings

To identify performance extremes, I ranked schools by their overall passing percentages:

* Top 5 highest-performing schools
* Bottom 5 lowest-performing schools

#### Subject Scores by Grade

I drilled down into performance by grade level, calculating the average math and reading scores for each grade (9th to 12th) at every school.

#### Performance by Spending

I analyzed the impact of per-student spending on performance using categorized spending ranges. Metrics included:

* Average math and reading scores
* Passing percentages for math, reading, and overall performance

This analysis utilized `pd.cut` to categorize spending into bins and grouped the data to extract averages.

#### Performance by School Size

I explored the relationship between school size and performance by grouping schools into size categories (small, medium, large) and calculating average scores and passing percentages for each category.

#### Performance by School Type

Finally, I summarized performance based on school type (e.g., public vs. charter) to identify trends and variances.

---

### Observations and Insights

1. **Spending Patterns** : Schools with higher per-student spending did not always have better performance, highlighting the need for strategic allocation of resources.
2. **School Type Advantage** : Charter schools generally outperformed public schools in overall passing rates, suggesting potential differences in resource management or teaching methods.
3. **Size Considerations** : Smaller schools tended to have higher average passing rates compared to larger ones, possibly due to more personalized attention.

This project not only enhanced my technical skills in Python and Pandas but also deepened my understanding of how data-driven insights can inform critical decisions in education.
