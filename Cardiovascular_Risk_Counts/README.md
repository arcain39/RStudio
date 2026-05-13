## Objectives
- Model the count of non-idea cardiovascular risk factors using Poisson and negative binomial regression
- Evaluate predictor significance using Type III ANOVA
- Estimate incident rate ratios (IRRs) and confidence intervals
- Compare Poisson and negative binomial model fit
- Visualize predicted counts across insurance x education groups

## Methods
- Poisson regression (glm, family = 'poisson)
- Negative binomial regression(MASS::glm.nb)
- Type III ANOVA for global significance
- IRR estimation with 95% CIs
- Predicted count generation for insurance x HS graduation combinations
- Dispersion assessment (mean vs. variance)
- Visualization using ggplot2

## Summary
This project explored whether age, health insurance status, and high school education could help estimate the number of controllable risk factors for stroke. The analysis showed that age was the only significant predictor: for every one year increase in age, the expected count of controllable risk factors increased by about 1%. Insurance status and education showed small diffrences, but these effects were not strong enough to be considered meaningful. Two types of statistical models were used, the Poisson regression and the negative binomial regression. The Poisson model assumes that the mean and variance of the outcome are equal, but the data showed underdispersion, with the variance smaller than the mean. Because the negative binomial model is designed to adjust for overdispersion, it converged to the same results as the Poisson model in this case. Overall, the main takeaway is that age is linked to the number of controllable risk factors, while insurance and education did not play a significant role in this dataset.
