#statistics 
The z-distribution, or standard normal distribution, is a foundational concept in statistics, central to understanding various statistical tests, including z-tests. This special distribution has a mean of 0 and a standard deviation of 1, making it a pivotal tool for assessing the statistical significance of test results. Here are detailed notes on the z-distribution, with an emphasis on z-tests:

### Definition
The z-distribution is a normalized form of any [[Normal Distribution]]. It converts any normal distribution to a standard form with a mean ($\mu$) of 0 and a standard deviation ($\sigma$) of 1.

### Z-Score
A z-score represents the distance of a data point from the mean, measured in terms of standard deviations. It's calculated using:
$$z = \frac{X - \mu}{\sigma}$$
where $X$ is a value from the original distribution, $\mu$ is the mean of that distribution, and $\sigma$ is its standard deviation.

### Properties of the Z-Distribution
- **Symmetry**: It is symmetrically bell-shaped around a mean of 0.
- **Mean**: The mean is 0.
- **Standard Deviation**: The standard deviation is 1.
- **Total Area**: The total area under the curve equals 1, representing the total probability.

### Z-Tests
[[Z-test|Z-tests]] are statistical tests that use the z-distribution to determine whether there is a significant difference between sample observations and the population, or between two sample means, assuming the variances are known and the sample size is large (typically n > 30).

### Applications of Z-Tests
Z-tests are used to:
- Test hypotheses about population means when the population variance is known.
- Determine if two populations differ significantly on some single characteristic, assuming known variances.
- Calculate the confidence intervals for population mean differences.

### Limitations of Z-Tests
Z-tests assume that:
- The data follows a normal distribution, especially for smaller sample sizes.
- The population standard deviation is known, which is rare in practice.
- Samples are independently drawn and identically distributed.

For real-world applications where the population standard deviation is unknown or the sample size is small, the t-test is often more appropriate.

### Summary
Understanding the z-distribution and its application in z-tests is crucial for conducting statistical analyses in research. These tests provide a method for making inferences about population parameters, assessing the significance of observed differences, and guiding decision-making in the presence of uncertainty.