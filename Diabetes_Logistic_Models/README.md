# Logistic, Ordinal, and Multinomial Modeling of Diabetes

This project models diabetes status using multiple regression frameworks, including binary logistic regression, ordinal logistic regression, and multinominal logistic regression. Predictors include age, weight, hypertension status (HTN), and HDL cholesterol category (hdl3cat). The analysis also evaluates whether the relationship between hypertension and diabetes varies across HDL categories.

##Objectives
- Model diabetes status using logistic, ordinal, and multinomial regression
- Evaluate global significance of predictors using Type III ANOVA
- Estimate odds ratios and confidence intervals
- Visualize predicted diabetes probabilities across HTN x HDL groups

 ## Methods
 - Logistic regression (binary, ordinal, multinomial)
 - Type III ANOVA for global significance
 - Odds ratio estimation with 95% CIs
 - Interaction modeling (HTN x HDL category)
 - Predicted probability visualization using ggplot2
 - Proportional odds testing (Brant test)

## Summary

In this project, we examined how age, weight, blood pressure status(hypertensive vs. normotensive), and HDL cholesterol levels relate to a person's likelihood of being non-diabetic, pre-diabetic, or diabetic. We compared two types of models: one that assumes these categories follow a natural order, and one that treats them as separate groups. Statistical testing showed that the model without the ordering assumption (multinomial logistic regression) fit the data better. Using this model, we found that older individuals and those with higher weight had slightly higher chances of being pre-diabetic or diabetic. High blood pressure was a strong risk factor; people with hypertension were more than three times as likely to be diabetic compared to those with normal blood pressure. HDL levels also mattered, individuals with high HDL were significantly less likely to be diabetic than those with low HDL. Overall, the results suggest that age, weight, blood pressure, and cholesterol levels all play important roles in understanding diabetes risk.
