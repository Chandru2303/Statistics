# Descriptive Statistics

Descriptive statistics is a branch of statistics that focuses on summarizing and organizing data to describe its main features. It provides simple yet insightful insights into the data set without making any inferences about a larger population.

Descriptive statistics are useful for summarizing data, identifying patterns, and providing a clear overview before diving into more complex statistical analyses.

## Mean

**Definition:** The mean is the average of a data set.

**Example:** For the dataset `{2, 4, 6, 8, 10}`, the mean = (2 + 4 + 6 + 8 + 10) / 5 = 6.

**Exercise:** Calculate the mean for `{5, 12, 8, 21, 17}`

**Answer:** 12.6

## Median

**Definition:** The median is the middle value of a data set when it is ordered from smallest to largest.

**Example:** 
- For the data set `{1, 1, 2, 5, 6, 6, 9}`, the median is 5.
- For the data set `{1, 1, 2, 6, 6, 9}`, the median is 4 (Take the mean of 2 and 6 or (2+6)/2 = 4).

**Exercise:** Find the median for `{3, 7, 8, 10, 12, 15}`

**Answer:** 9

## Mode

**Definition:** The mode is the value that appears most frequently in a data set. A data set may have one mode, more than one mode, or no mode at all if no value repeats.

**Example:** For the data set `[4, 8, 6, 5, 9, 6]`, the mode is 6 because it appears most frequently.

**Exercise:** Find the mode for `{9, 8, 8, 7, 7, 6}`

**Answer:** 7, 8

## Range

**Definition:** The range measures the difference between the highest and lowest values in a data set.

**How to Calculate:** Subtract the minimum value from the maximum value.

**Formula:** Range = Max - Min

**Example:** For the data set `[3, 7, 5, 10, 2]`, the range is 10 - 2 = 8

**Exercise:** Find the range for `{2, 3, 5, 8, 9, 12, 6}`

**Answer:** 10

## Variance

**Definition:** Variance measures the average squared deviation of each value from the mean of the data set. It quantifies the spread of the data points.

**How to Calculate:** 
1. Find the mean of the data set.
2. Subtract the mean from each data point and square the result (to get squared deviations).
3. Find the average of these squared deviations.

**Formula:** 
- Excel formula: `=VAR.P({85,90,95,100,105})` for population variance, `=VAR.S({85,90,95,100})` for sample variance.

**Population Variance:** Calculate the mean (μ) of the entire population, then find the average of the squared differences between each value and the mean.

**Sample Variance:** Calculate the mean of the sample, then find the average of the squared differences between each sample value and the sample mean. Note that the denominator is `n−1` rather than `n`.

## Example:

Consider a small population of five students' test scores: `85, 90, 95, 100, 105`.

1. **Calculate the Mean:**

   \[
   \text{Mean} = \frac{85 + 90 + 95 + 100 + 105}{5} = 93
   \]

2. **Calculate Each Squared Difference from the Mean:**

   | Score | Mean | Difference from the Mean | Squared Difference from the Mean |
   |-------|------|---------------------------|----------------------------------|
   | 85    | 93   | -8                        | 64                               |
   | 90    | 93   | -3                        | 9                                |
   | 95    | 93   | 2                         | 4                                |
   | 100   | 93   | 7                         | 49                               |
   | 105   | 93   | 12                        | 144                              |

   **Sum of Squared Differences:** 270

3. **Calculate the Population Variance:** 270 / 5 = 54

   

4. **Calculate the Sample Variance:**

   For the sample variance, divide by \( n - 1 \) (where \( n \) is the number of scores):

   270 / (5-1) = 67.5
   
## Standard Deviation

**Definition:** Standard deviation is a statistic measuring the dispersion of a dataset relative to its mean. It is calculated as the square root of the variance.

**How to Calculate:** 
1. Find the mean.
2. Calculate Variance.
3. Take the Square Root.


## Example: https://www.mathsisfun.com/data/standard-deviation.html
