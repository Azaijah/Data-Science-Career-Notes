#statistics 
Two popular tests are the **Shapiro-Wilk (SW)** test and the **Kolmogorov-Smirnov (KS)** test. These tests are crucial for deciding the appropriate statistical methods to use for analysis, as many parametric tests assume normality of the data.
### Shapiro-Wilk Test

The Shapiro-Wilk test is specifically designed to test the normality of a dataset. It works by comparing the observed distribution of data with a normal distribution. The null hypothesis $(H_0)$ of the SW test states that the sample comes from a normally distributed population. If the p-value obtained from the test is less than the chosen significance level (commonly 0.05), the null hypothesis is rejected, suggesting that the data do not follow a normal distribution.

- **Pros:** It is considered one of the most powerful tests for normality, especially for small sample sizes.
- **Cons:** Its performance may decrease as the sample size becomes very large.

### Kolmogorov-Smirnov Test

The Kolmogorov-Smirnov test is a more general non-parametric test that compares a sample with a reference probability distribution (one-sample KS test) or compares two samples (two-sample KS test). When used to test for normality, the one-sample KS test compares the empirical distribution function of the sample with the cumulative distribution function of the normal distribution. The null hypothesis $(H_0)$ is that the sample is drawn from a population that follows a specified distribution.

- **Pros:** It can be used to test for any specified distribution, not just normality.
- **Cons:** The KS test is less powerful than the Shapiro-Wilk test for testing normality, especially with small sample sizes. Furthermore, when using the one-sample KS test for normality, the parameters of the normal distribution (mean and standard deviation) must be specified in advance, which can affect the test's sensitivity if the sample's actual parameters are used.