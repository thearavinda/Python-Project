# Employee Data Analysis 

 ## Project Overview
This project focuses on analyzing employee data to uncover trends, patterns, and correlations within the organization. The analysis involves data preprocessing, statistical insights, and visual representations to derive meaningful conclusions about salary distribution, age influence on salaries, and team-based expenditures.

### Data Preprocessing

Before analysis, the dataset was cleaned and prepared as follows:

Handling Missing Values:
The College column was filled with the most frequent college name. 

The Salary column was filled with the median salary value.

Correcting Data:

The Height column values were replaced with random values between 150-180 cm to ensure consistency.

Data Integrity Checks:

Verified missing values, checked data types, and ensured uniform formatting.

 ### Analysis Performed

1. Team & Position-Based Salary Expenditure:

Identified teams and positions with the highest salary costs.
Used bar charts and histograms for visualization.

2. Employee Segmentation by Position & Team:

Determined the distribution of employees across different teams and positions.
Used pie charts and grouped bar plots for representation.

3. Age Group Analysis:

Categorized employees into age groups using pd.cut().

Identified the most common age group and visualized it with a histogram and box plot.
4. Correlation Between Age & Salary:

Found a weak correlation (0.20), meaning age has a minimal impact on salary.

Visualized using a scatter plot and a correlation heatmap.

### Graphical Representations

Bar Charts → Employee Distribution across distribution across  positions and Age Distribution across Age Group, Total Salary Expenditure by Team

Pie Chart → Percentate Split of Employees Across Teams and Salary Expenditure Distribution by Position

Scatter Plot → Relationship between Age & Salary.



 ### Key Insights & Findings

 Salary Disparities: Some teams contribute more to salary expenditure than others, indicating pay gaps across departments.

Weak Age-Salary Correlation: Older employees tend to earn more, but age is not a significant salary determinant.

 Team & Position Trends: Some positions dominate salary expenditure, emphasizing higher pay in senior roles.

 Employee Segmentation: Certain age groups dominate specific roles, reflecting a structured career progression pattern.
