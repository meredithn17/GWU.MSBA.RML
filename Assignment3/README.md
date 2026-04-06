Responsible Machine Learning</br>
Assignment 3

**The purpose of the analysis:**</br>
This project evaluates whether the COMPAS risk‑assessment algorithm produces racially or gender‑based disparities in how defendants are labeled “high risk,” and whether those disparities persist across multiple fairness metrics. </br>
- AIR and ME were used to analyze disparities in selection rates.</br>
- FPR, FNR, and accuracy rates were used to analyze disparities in error rates.</br>
- SMD was used to analyze differences in how subgroups were scored.</br>
- Subgroups combining race with gender (sex) were used to analyze disparities among intersectional subgroups.</br>

**The Python libraries used:**</br>
For data loading, cleaning, and manipulation, pandas and numpy were used. </br> 
For AID and SMD fairness metrics, solas_ai and IPython.display were used. </br>
For the bar chart visualization, maptlotlib was used. </br> 
For statistical modeling, statsmodels snd scipy were used. 

**Instructions for reproducing the results:**</br>
Install and import required libraries
Load in the COMPAS data
Filter the data in accordance with ProPublica standards
Create the binary high‑risk variable
Compute adverse impact ratio (AIR), marginal effects (ME), and standardized mean difference (SMD) by race
Compute adverse impact ratio (AIR), marginal effects (ME), and standardized mean difference (SMD) by gender
Run the two‑proportion z‑test
Compute error‑rate disparities
Generate the grouped bar chart
Compute standardized mean differences (SMD)
Conduct the intersectional subgroup analysis

**AI Use Dislosure:**</br>
Google Gemini was used in Colab to troubleshoot code as needed. All statistical analysis and explanation was written by me. Copilot was used after drafting to double-check my analysis.
