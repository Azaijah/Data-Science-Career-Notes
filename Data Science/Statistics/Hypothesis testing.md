#statistics 
Hypothesis testing is a fundamental aspect of statistical analysis used to determine the likelihood that a given hypothesis about a population parameter is true, based on sample data. It is a methodological approach for making decisions or inferences about population parameters. Here's a detailed overview:

### Key Concepts

- **Null Hypothesis ($H_0$)**: A statement of no effect or no difference, serving as the default or starting assumption. It is the hypothesis that is directly tested and is often a statement of equality (e.g., $\mu = \mu_0$).
- **Alternative Hypothesis ($H_a$ or $H_1$)**: Represents what the researcher is trying to prove. It is a statement that indicates the presence of an effect or a difference. Depending on the test, it can be non-directional (not specifying the direction of the difference) or directional (specifying greater than or less than).
- **Type I Error ($\alpha$)**: Occurs when the null hypothesis is wrongly rejected. It is the probability of a false positive, and the significance level ($\alpha$) is set by the researcher before conducting the test.
- **Type II Error ($\beta$)**: Occurs when the null hypothesis is wrongly accepted. It is the probability of a false negative.
- **Power of the Test**: The probability of correctly rejecting the null hypothesis when it is false ($1 - \beta$). Higher power means a greater chance of detecting an effect when there is one.

### Steps in Hypothesis Testing

1. **State the Hypotheses**: Formulate the null and alternative hypotheses.
2. **Choose the Significance Level ($\alpha$)**: Common values are 0.05, 0.01, and 0.10.
3. **Select the Appropriate Test**: Based on the type of data and the research question, choose the statistical test (e.g., t-test, chi-square test).
4. **Calculate the Test Statistic**: Using sample data, compute a value that reflects the difference between the observed sample statistic and the null hypothesis value.
5. **Determine the p-Value or Critical Value**: The p-value is the probability of observing a test statistic as extreme as, or more extreme than, the observed value, under the assumption that the null hypothesis is true. Alternatively, compare the test statistic to a critical value based on the significance level.
6. **Make a Decision**: Reject or fail to reject the null hypothesis based on the comparison of the p-value and the significance level or the comparison of the test statistic and the critical value.

### Types of Tests

- **Z-Tests**: Appropriate for comparing a sample mean to a population mean or comparing the means of two populations, when the population variances are known and the sample size is large ($n > 30$). Also used for comparing proportions. Works with [[Normal Distribution|normal distributions]]

- **t-Tests**: Suitable for comparing means between two groups (independent or paired samples) or comparing a single group mean to a population mean, especially when the sample size is small ($n \leq 30$) and the population variance is unknown. Works with [[T-Distribution|t-distributions]]

- **ANOVA (Analysis of Variance)**: Used to compare means across three or more groups to determine if there's a significant difference. It's ideal when you're examining the effect of one or more categorical independent variables on a continuous dependent variable.

- **Chi-Square Tests**: Applied to categorical data to assess the likelihood of observed differences occurring by chance. It's useful for comparing observed frequencies to expected frequencies in nominal or categorical data.

- **Regression Analysis**: Examines the relationship between variables. Linear regression tests for linear relationships between two continuous variables, while multiple regression includes multiple independent variables to analyze complex relationships.


### Making Inferences

After testing, results are interpreted in the context of the research question. Rejecting the null hypothesis suggests that there is sufficient evidence to support the alternative hypothesis. Failing to reject the null hypothesis suggests that there is not enough evidence to support the alternative hypothesis. However, it does not prove the null hypothesis true.






[[Null & Alternative Hypothesis]]
[[Hypothesis Testing Procedure]]
[[Testing for normality]]
