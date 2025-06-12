Boston Housing Data Insights
Project Overview
This project explores the Boston Housing dataset, originally derived from the U.S. Census. As a Data Scientist for a Boston-based housing agency, the goal is to present insights to upper management that support decisions about housing values, environmental quality, and urban planning.

We analyze how different factors like proximity to the Charles River, air pollution, age of housing, and school resources influence home values and living conditions across Boston.

Key Questions We Answer
1. Does living near the Charles River increase home prices?
2. Do older neighborhoods have lower housing prices?
3. Is there a link between air pollution and industrial land use?
4. How does distance from business centers affect housing prices?

Methods Used
I used a combination of:
-Descriptive statistics
-Data visualizations (boxplots, histograms, scatter plots, bar charts)

Statistical tests like:
-T-test (for comparing river-bound vs. non-river homes)
-ANOVA (for comparing home prices across different age categories)
-Pearson Correlation (to check if pollution and industrial land use are related)
-Linear Regression (to predict how distance affects home value)

Dataset Variables
Column	Description
MEDV-	Median value of owner-occupied homes
CHAS-	1 if tract bounds Charles River, 0 otherwise
AGE-	% of owner-occupied units built before 1940
NOX-	Nitric oxide concentration (pollution level)
INDUS-	% of non-retail industrial land per town
DIS-	Weighted distance to employment centers
PTRATIO-	Pupil-teacher ratio by town

Visualizations Included
1. Bar Chart of homes near the Charles River (Bound vs Not Bound)
2. Boxplot of home prices across all of Boston
3. Boxplot comparing prices by home age (New, Mid, Old)
4. Scatter Plot for pollution vs. industrial land use
5. Histogram of pupil-teacher ratios across towns


How to Run
1. Clone the repository
2. Open the notebook or script
3. Run the cells to view graphs and results.
