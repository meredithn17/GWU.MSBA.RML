Assignment 2</br>
Evaluate the COMPAS Replacement Model for transparency and explainability

**The purpose of the analysis:**
This project examines how the COMPAS Replacement Model makes risk score predictions, and whether those predictions behave consistently and fairly across individuals and demographic groups. The analysis identified which factors most strongly influence the model’s risk predictions to compare global patterns with SHAP and individual‑level explanations with LIME. The analysis also generated counterfactuals with DiCE to understand what minimal changes would alter a prediction. I evaluated whether the model behaves differently across racial groups to assess whether the model is stable, interpretable, and aligned with responsible governance expectations. These steps helped identify the strengths and limitations of the model, and highlight areas where additional monitoring or safeguards may be needed.

*8The Python libraries used:**
For data cleaning and manipulation, pandas and numpy were used.
For modeling and machine learning, scikit‑learn was used.
For explainability, shap, lime, and dice-ml were used.
For visualizations, matplotlib and seaborn were used.

**Instructions for reproducing the results:**
1. Install and import required libraries
2. Load and preprocess the COMPAS dataset
3. Train the COMPAS Replacement Model on the processed data
4. SHAP: beeswarm and waterfall plots
5. LIME using same individuals
6. DICE to generate counterfactuals

**AI Use Disclosure**
Google Gemini was used in Colab to troubleshoot code. Microsoft Colab was used for some initial memo ideas, but only in bullet-point form, and updated this ReadMe from the first assignment.
