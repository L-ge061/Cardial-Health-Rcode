# Heart Attack Risk Analysis  

This project explores the factors that contribute to heart attack risk using statistical analysis and predictive modeling in **R**. The analysis applies ANOVA, logistic regression, and ROC curve evaluation to identify key predictors of heart attack risk and assess potential interventions for risk reduction.  

---

## Project Overview  
Heart disease remains one of the leading causes of mortality worldwide. This project uses a dataset (`heart_attack_Fixed.csv`) containing demographic, lifestyle, and health factors to examine their impact on blood pressure and heart attack occurrence.  

The analysis is structured into three main parts:  

1. **Blood Pressure Analysis (ANOVA)**  
   - Investigated the effects of smoking status, alcohol consumption, and physical activity on blood pressure.  
   - Found that each factor independently has a statistically significant impact, but no strong interaction effects.  

2. **Heart Attack Prediction (Logistic Regression)**  
   - Built a logistic regression model with predictors like age, smoking status, alcohol consumption, and physical activity.  
   - Achieved a high performance with **AUC = 0.98**.  
   - Key findings: Smoking, alcohol consumption, and age increase heart attack likelihood, while higher physical activity lowers it.  

3. **Intervention Scenarios**  
   - Simulated lifestyle interventions (e.g., quitting smoking, reducing alcohol, increasing activity).  
   - Found that **quitting alcohol** and **smoking** had the greatest reduction in predicted risk.  

---

## Methods & Tools  
- **Language:** R  
- **Libraries:** `tidyverse`, `broom`, `pROC`, `gridExtra`, `ggplot2`  
- **Techniques Used:**  
  - Data preprocessing & visualization  
  - ANOVA for blood pressure analysis  
  - Logistic regression for risk prediction  
  - ROC curve for model evaluation  
  - Scenario analysis for interventions  

---

## Key Visuals  
- Boxplots: Effects of smoking, alcohol, and physical activity on blood pressure  
- Logistic regression coefficient plots with odds ratios  
- ROC curve with strong model performance (**AUC = 0.98**)  
- Bar chart: Potential risk reduction from different interventions  

---

## Findings & Insights
- Smoking and alcohol are the strongest lifestyle risk factors.
- Age is a consistent demographic risk factor.
- Higher physical activity generally lowers risk.
- Reducing alcohol consumption and quitting smoking provide the largest risk reductions.

---

## Conclusion / Business & Health Insights
- For Public Health: Interventions targeting smoking cessation and alcohol reduction may yield the highest returns in reducing heart attack risk.
- For Healthcare Providers: Predictive models like the one built here can be integrated into screening tools to identify high-risk patients early.
- For Policy Makers / Employers: Workplace wellness programs that promote active lifestyles and discourage harmful habits could significantly reduce long-term healthcare costs.
- For Individuals: Even small lifestyle changes (quitting smoking or drinking less) have measurable impacts on reducing heart attack risk.

---

## What’s Next
If given more time, future exploration could include:
- Additional Statistical Tests: Explore Chi-square tests, survival analysis, or mixed models for richer insights.
- Different Modeling Approaches: Compare logistic regression with decision trees, random forests, or gradient boosting to evaluate improvements in predictive accuracy.
- Feature Engineering: Add interaction terms or create composite health scores to better capture lifestyle effects.
- Cross-Validation & Robustness Checks: Perform k-fold cross-validation to confirm model stability.
- External Validation: Test the model on other datasets to confirm generalizability.
- Time-Series or Longitudinal Analysis: If temporal data is available, explore how risk factors evolve over time.

