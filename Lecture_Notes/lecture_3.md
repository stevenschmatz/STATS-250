# Lecture 3: Numerical Summaries

 Notation for describing a set of data:
 
 $$x_1, x_2, x_3, \dots, x_n$$
 
 where \\(n\\) is the size of your data set.
 
 ## Describing the Center Location
 
 ##### Mean
 
Mean of the data set: the average of all elements.

$$\bar{x} = \frac{x_1 + x_2 + x_3 + \dots + x_n}{n}$$

The mean is *sensitive* to extreme observations.

If a distribution is fairly symmetric, we tend to use the **mean** to describe the center.

##### Median

Median of the data set: the middle element, *when the elements are sorted in increasing order!* If the number of data points is even, then the median is the average of the two innermost data points.

The median is *resistant* (robust) to extreme observations.

If a distribution is skewed, we tend to use the **median**.
 
### Skewness

If the distribution is *symmetric*, the mean and the median will be equal.

Otherwise:
* If the distribution is **right skewed**, then the median is *greater than* the mean.
* If the distribution is **left skewed**, then the median is *less than* the mean.

## Describing Variability

Range:
* A spread over 100% of data.
* Maximum - Minimum

Percentiles can also be used. The \\(p^{\text{th}}\\) percentile is a value such that \\(p\\) percent of the observations fall at or below that value:
* Median: \\(50^{\text{th}}\\) percentile
* First quartile: \\(25^{text{th}}\\) percentile
* Third quartile: \\(75^{\text{th}}\\) percentile

Another measure is *interquartile range*.

