# DataCamp | Hypothesis Testing with Men's and Women's Soccer Matches

This project is part of the **Associate Data Scientist in Python** career track on DataCamp. The primary objective is to conduct a hypothesis test to determine whether the mean number of goals scored in women's international soccer matches is significantly greater than in men's matches at a significance level of 0.1.

The sample data was clearly not drawn from a normal distribution, as confirmed by performing a normality test. Consequently, we employed the Mann-Whitney U test, a non-parametric alternative to the t-test, which does not require the assumption of normality.

Furthermore, since the sample size is sufficiently large, we assumed that the test statistic is asymptotically distributed as standard normal. However, the results from the parametric approximation differed notably from the exact Mann-Whitney U test results. To obtain a more robust conclusion, we relied on the exact result provided by the Mann-Whitney U test.

## Environment

- Python 3.12.7
- pandas 2.2.2
- numpy 1.26.4
- seaborn 0.13.2
- matplotlib 3.9.2
- scipy 1.14.1
- pingouin 0.5.5
