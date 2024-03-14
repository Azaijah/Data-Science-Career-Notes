#statistics 

Good video:
https://www.youtube.com/watch?v=pTmLQvMM-1M

### Definition and Purpose
A z-test compares sample data to a known population parameter to assess the significance of the difference. The primary purpose is to test hypotheses about population means under specific conditions. Similarly, t-tests are used to determine whether there is a significant difference between the means of two groups, which may be related in certain features or not.

### Types of Z-Tests
1. **One-Sample Z-Test**: Used to compare the mean of a single sample to a known population mean.
2. **Two-Sample Z-Test**: Used to compare the means of two independent samples, assuming the population variances are known.
3. **Proportion Z-Test**: Used to compare observed proportions, such as the proportion of success in a binary outcome.

### Types of T-Tests
- **One-Sample T-Test**: Similar to the one-sample z-test, but used when the population variance is unknown and the sample size is small.
- **Two-Sample T-Test (independent samples)**: Compares the means of two independent groups.
- **Paired T-Test**: Compares means from the same group at different times (paired observations).

### Assumptions
Z-tests and t-tests rely on several critical assumptions:
- [[Normal Distribution]]: The sampling distribution of the mean should be approximately normal. This is generally satisfied if the sample size is large (central limit theorem) or the population is normally distributed. T-tests are more tolerant of deviations from normality.
- **Known Population Variance (Z-Test)**: The population variance (or standard deviation) must be known for z-tests. For t-tests, the population variance is unknown.
- **Independent Samples**: In two-sample z-tests and independent two-sample t-tests, the samples must be independent of each other.
- **Large Sample Size (Z-Test)**: Generally, a sample size greater than 30 is considered large enough for the central limit theorem to apply, making the distribution of the sample mean approximately normal. T-tests are suitable for smaller samples.

### Single and Two-Tailed Tests
- **Single-Tailed Test**: Tests for the possibility of the relationship in one direction and completely ignores the possibility of a relationship in the other direction.
- **Two-Tailed Test**: Tests for the possibility of the relationship in both directions. It is more conservative and is used when there is no specific direction of interest.

### Formulas

#### One-Sample Z-Test
$$z = \frac{\bar{x} - \mu}{\sigma/\sqrt{n}}$$

#### Two-Sample Z-Test
$$z = \frac{\bar{x}_1 - \bar{x}_2}{\sqrt{\sigma^2_1/n_1 + \sigma^2_2/n_2}}$$

#### Proportion Z-Test
$$z = \frac{\hat{p}_1 - \hat{p}_2}{\sqrt{P(1-P)(\frac{1}{n_1} + \frac{1}{n_2})}}$$

### Conducting a Z/T-Test
1. **State the Hypotheses**: Formulate the null hypothesis (H0) and the alternative hypothesis (H1).
2. **Select the Significance Level** (α), often set at 0.05.
3. **Calculate the Statistic** using the appropriate formula for the type of test.
4. **Determine the Critical Value or p-Value**: Use tables or statistical software to find the p-value associated with the calculated statistic.
5. **Make a Decision**: Reject the null hypothesis if the p-value is less than the significance level, indicating a statistically significant difference.

### Interpretation
The outcome provides evidence regarding the null hypothesis. A low p-value suggests that the observed difference is unlikely to have occurred by chance alone, leading to the rejection of the null hypothesis in favor of the alternative hypothesis.

### Applications
Both tests are widely used in research and decision-making to assess process changes, compare average outcomes between groups, and evaluate treatment effectiveness.

### Limitations
- **Z-Test**: Requires known population variances, often not practical.
- **T-Test**: More suitable for small samples but assumes population variance is unknown.
- Both tests assume normal distribution, which may not hold for small samples or non-normally distributed data.

Z-tests and t-tests are fundamental tools in statistics for hypothesis testing, each with its specific conditions and applications.