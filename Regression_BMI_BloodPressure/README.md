# Regression Modeling of Systolic Blood Pressure

This project analyzes systolic blood pressure (SBP) as a function of age, education level, and BMI category using linear regression.

## Objectives
- Build main effects and interaction models
- Evaluate predictor significance
- Identify outliers
- Visualize predicted SBP values

## Methods
- Linear regression (glm, lm)
- Type III ANOVA
- VIF for multicollinearity
- Diagnostic plots

## Summary 
From this analysis, we found that education level (whether someone graduated high school) does not change the relationship between BMI and systolic blood pressure (SBP). However, BMI does change how SBP increases with age. People with higher BMI start out with higher blood pressure when they are young, but their blood pressure rises more slowly as they age. In contrast, people with lower BMI begin with lower SBP, but their blood pressure increases more quickly over time. For example, someone with a BMI of 32 is expected to see their SBP rise by about 0.55mmHg per year, while someone with a BMI of 25 sees a slightly steeper increase of about 0.62mmHg per year. Education level has smell effect, high school graduates tend to have slightly lower SBP, but it does not interact with BMI in a meaningful way. Overall, the graph shows that although BMI groups start far apart at younger ages, the differences between them shrinks as age increases.
