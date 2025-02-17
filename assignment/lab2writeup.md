
# Methodology Write-Up

This analysis explores the relationship between paid leave, income inequality, and high-risk infant mortality using data on infant deaths and births. The exposure variable in the study is paid leave (categorized as "yes" or "no"), while the outcome variable is high-risk infant mortality, defined based on relative risk thresholds.
The first step involved calculating the risk of infant mortality for Black and White infants. 

Risk was determined by dividing the number of infant deaths by the total number of births within each racial group. Using these values, the relative risk was calculated as the ratio of Black infant mortality risk to White infant mortality risk. States were then categorized into "high risk" or "low risk" groups based on a relative risk threshold of 2.7, with states exceeding this threshold labeled as "high risk."
To examine the association between paid leave and high-risk infant mortality, an odds ratio was calculated. A contingency table was created to count the number of states with and without paid leave across the high-risk and low-risk categories. 

The odds ratio revealed that the odds of high-risk infant mortality are significantly lower for states with paid leave compared to those without paid leave. Specifically, the odds ratio of 0.111 indicates that states with paid leave are 89% less likely to have high-risk infant mortality compared to states without paid leave.

Finally, a Directed Acyclic Graph (DAG) was created to illustrate the potential causal relationships. The DAG showed that income inequality influences both paid leave and high-risk infant mortality, and paid leave has a direct effect on high-risk infant mortality. This suggests that paid leave may act as a confounder in the relationship between income inequality and high-risk infant mortality, as it is influenced by income inequality and independently affects the outcome.
Through this methodology, we quantified the protective effect of paid leave on infant mortality and highlighted its role in mitigating disparities driven by income inequality

