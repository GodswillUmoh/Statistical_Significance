# Statistical_Significance
> Statistical significance is a concept in statistics used to determine whether the results of an analysis or experiment are unlikely to have occurred by chance. It helps researchers decide if there is enough evidence to support a hypothesis or if observed differences or relationships are meaningful.

## Explaining with Coin
Explaining Statistical Significance with a Fair Coin (𝐻0) and Unfair Coin (𝐻1) Concept
> Imagine you are conducting an experiment to determine whether a coin is fair (has an equal chance of landing heads or tails). Here's how the null and alternative hypotheses work in this scenario:
> Hypotheses:
> + Null Hypothesis (𝐻0): The coin is fair. Probability of heads (𝑃(𝐻)) = 0.5.
> + Alternative Hypothesis (𝐻1): The coin is not fair. Probability of heads (𝑃(𝐻)) ≠ 0.5.

## Key Notes:
> + Null Hypothesis (𝐻0): Assumes no effect or no difference (e.g., the coin is fair).

> + Alternative Hypothesis (𝐻1): Suggests a deviation from the null (e.g., the coin is unfair).

> + Statistical Test: Determines if observed results (e.g., 60 heads in 100 tosses) are significantly different from expected results under 𝐻0

> + P-Value: Quantifies the likelihood of observing the data if 𝐻0 is true.

> + Decision: Compare p-value to 𝛼 to accept or reject 𝐻0​

_This process demonstrates the concept of statistical significance in testing whether a coin is fair._

## Experiment
Assuming you live in the world that says H0 is fair coin, you tossed a coin six times and got 1 Head and 5 Tails, will you still say is a fair coin, you see the P-value goes down for every time you see tail, feel uneasy.

## What is P-value
> The p-value, or probability value, is a statistical measure used to determine the strength of evidence against the null hypothesis (𝐻0) in a hypothesis test. It quantifies how likely it is to observe the results (or more extreme ones) if the null hypothesis were true.
> 
> The p-value represents the probability of obtaining the observed data (or something more extreme) under the assumption that the null hypothesis (H0) is true.
> The p-value always lies between 0 and 1 (0≤𝑝≤1).

## Interpretation:
> + Low p-value (<α): Strong evidence against 𝐻0, reject the null hypothesis.
> + High p-value (≥𝛼): Insufficient evidence against 𝐻0, fail to reject the null hypothesis.

## Significance Level (𝛼):
> + The threshold to decide whether the p-value indicates statistical significance.
> + Common values: 𝛼 =0.05 (5%), 𝛼=0.01 (1%).

## How to Interpret P-Value
> + p<0.05: The results are statistically significant. There is strong evidence to reject 𝐻0.
> + 𝑝≥0.05: The results are not statistically significant. There is not enough evidence to reject 𝐻0.
> + e.g assume we toss a coin and got the following; For a case where we live in the H0 of Fair coin, end up getting tails all the time up to 6 times
> + 0.5
> + 0.25
> + 0.12
> + 0.06 __At this point the p-value is less than 0.05 (5%)_, hence it is statistically significant, reject the H0
> + 0.03
> + 0.01

