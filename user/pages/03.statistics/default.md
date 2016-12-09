---
title: Statistics
---

# Statistics

Notes from ud827 - [Intro to Descriptive Statistics](https://www.udacity.com/course/intro-to-descriptive-statistics--ud827) and ud201 - [Intro to Inferential Statistics](https://www.udacity.com/course/intro-to-inferential-statistics--ud201)

## Definitions

Constructs require an operational definition


## Measures of Central Tendency

A measure of central tendency is a central or typical value for a probability distribution.

### Mean

The *arithmetic mean* is the sum of the sampled values divided by the number of items in the sample.

Population mean: $ \mu = \sum{\frac{x_i}{N}} $

Sample mean: $ \bar{x} = \sum{\frac{x_i}{n}} $

### Mode
The *mode* is the value that appears most often in a set of data.

### Median
The *median* is the value separating the higher half of a data sample from the lower half.

## Measures of Variability

Variability denotes how stretched or squeezed a distribution is.

### Standard Deviation

Population standard deviation: $ \sigma = \sqrt{ \frac{1}{N} \sum{(x_i - \bar{x})^2}} $

Sample standard deviation: $ s = \sqrt{ \frac{1}{n} \sum{(x_i - \bar{x})^2}} $

Bessel's correction is the use of $ n − 1 $ instead of n in the formula for the sample variance and sample standard deviation, where n is the number of observations in a sample. This method corrects the bias in the estimation of the population variance: $ \sigma \approx \sqrt{ \frac{1}{n-1} \sum{(x_i - \bar{x})^2}} $

### Minimum, Maximum and Interquartile Range (IQR)

$$
IQR = Q_3 - Q_1
$$

A value is considered an outlier if it's less than $ Q_1 - 1.5 \times IQR $ or more than $ Q_3 + 1.5 \times IQR $

## Measures of Shape

Kurtosis and skewness measure the "tailed-ness" and asymmetry, respectively, of a distribution.

### Kurtosis

Kurtosis is a measure of the "tailedness" of the distribution.

The kurtosis is the fourth standardized moment.

Distributions with zero excess kurtosis are called mesokurtic, a distribution with positive excess kurtosis is called leptokurtic (and has a "fat tail"), and a distribution with negative excess kurtosis is called platykurtic (and has a "thin tail").

### Skewness

Skewness is a measure of the asymmetry of the distribution about its mean. 

The kurtosis is the third standardized moment.

Negative skew indicates that the tail on the left side of the probability density function is longer or fatter than the right side.

## Z-score

Z is the number of standard deviations away from the mean: $ Z = \frac{x - \mu}{\sigma} $

The Standard Normal Distribution has a mean of 0 and a standard deviation of 1.

When knowing the Z-score, it is possible to determine the area under the probability curve by using the [Z-table](https://s3.amazonaws.com/udacity-hosted-downloads/ZTable.jpg).

## Sampling Distribution

The sampling distribution is the distribution of sample means.  The standard error (SE) is the standard deviation of the sampling distribution. 

According to the Central Limit Theorem, the sampling distribution is normal and the standard error is:

$$
SE = \frac{ \sigma }{ \sqrt{n} }
$$

## Degrees of Freedom

$$
dF = n - 1
$$

## Standard Error of Mean

$$
SEM = \frac{S}{\sqrt{n}}
$$

## Standard t-test

$$
t = \frac{\bar{X} - \mu}{SEM}
$$

## Confidence Interval

$$
CI = \bar{X} \pm \text{margin of error}
$$
where the margin of error is $ t_{critical} \times SEM $

## Cohen's d

$$
d = \frac{\bar{X}-\mu}{S}
$$

## r sqared

$$
r^2 = \frac{t^2}{t^2 + dF}
$$