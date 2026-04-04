Assignment 1</br>
Evaluate the usefulness of the calculations performed for ProPublica's analysis of the COMPAS Recidivism Risk Scores

**The purpose of the analysis:**
This project analyzes the COMPAS risk assessment algorithm, especially for biases based on race, age, or gender, and how accurately it predicts an individual’s likelihood of recidivism. We examine how different demographic groups are scored and how those scores relate to actual recidivism outcomes. We also evaluate the algorithm’s predictive accuracy through statistical modeling, survival analysis, and comparisons of false positive and false negative rates.

**The Python libraries used:** 
For data cleaning and manipulation, pandas, numpy, date time, and warnings were used. 
For visualizations, maptlotlib and seaborn were used. 
For statistical modeling, statsmodels was used. 
For survival analysis, lifelines, including CoxPHFitter and KaplanMeierFitter were used.
For numerical operations, math and numpy were used. 

**Instructions for reproducing the results:**
1. Install and import required libraries
2. Load in the COMPAS data
3. Filter the data in accordance with ProPublica standards
4. Create the factor variables and convert numerical and date/time variables
5. Run logistic regression to test for bias
6. Compute likelihood multipliers
7. Plot racial disparities in decile scores
8. Run Cox Proportional Hazards models
9. Plot Kaplan–Meier Survival curves
10. Build confusion matrices (truth tables)

**AI Use Dislosure**
Google Gemini was used in Colab to troubleshoot transforming the code from R to Python as needed. All statistical analysis and explanation was written by me. 
