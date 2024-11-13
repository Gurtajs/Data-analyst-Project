# Data-analyst-Project
This project analyzes a movie dataset to explore the relationship between different variables, including budget, company, and gross revenue. The analysis involves several steps, such as data cleaning, correlation testing, hypothesis testing, and data visualization.

# Project Overview
In this project, we examine a dataset containing various details about movies, including their budget, gross revenue, company, and other attributes. The objective is to determine if there are any significant relationships between budget and gross revenue, and whether the company producing the movie has an impact on the gross revenue.

# Data Cleaning
The dataset is first cleaned to ensure the data is ready for analysis. The following steps are performed:
* Any rows with missing data in important columns (e.g., budget, gross, company) are removed to ensure a complete dataset for analysis.
* Fix values with ".0": Some numerical values have a .0 at the end (indicating they were originally float types but have whole numbers). These are converted to integer values for consistency.
* Remove duplicates: Duplicate rows are removed to avoid skewing the analysis.

# Correlation Analysis
After cleaning the data, I perform a correlation analysis to examine the relationships between various variables in the dataset. Specifically, the focus is on:
* Budget and Gross Revenue: Analyzing if there is a correlation between the budget allocated to a movie and the gross revenue it generates.
* Company and Gross Revenue: Testing whether the company responsible for the movie has any significant effect on its gross revenue.

# Hypothesis Testing
To test whether budget and company are correlated with gross revenue, I conduct the following analyses:
* Scatter Plot: A scatter plot is created to visualize the relationship between budget and gross revenue. This helps in understanding if there is a visible trend or correlation between these variables.
* ANOVA Test: I perform an ANOVA test to analyze whether the company has a statistically significant effect on gross revenue. This test checks if there are differences in gross revenue based on the company producing the movie.

# Findings
Afer doing the analysis we find that:
* Correlation between Budget and Gross Revenue: A strong positive correlation was found between the budget of a movie and its gross revenue. This suggests that higher budget movies tend to generate higher revenues.
* ANOVA Test for Company and Gross Revenue: The ANOVA test revealed a statistically significant difference in gross revenue between different companies. This indicates that the company producing the movie does have a measurable impact on its gross revenue.

