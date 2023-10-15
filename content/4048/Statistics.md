---
title: Statistics
topic: "4048"
---
# Measures of central tendency
## Mean
For a set of $n$ elements $\{x_1, x_2, \dots, x_n\}$, the mean $\bar{x}$ is given by
$$
\bar{x} = \frac{x_1+x_2+\cdots+x_n}{n} = \frac{\sum\limits^{n}_{i=1}x_i}{n}
$$

For a frequency distribution,
$$
\bar{x} = \frac{\sum fx}{\sum f}
$$
where $x$ is the mid-value of the class interval.
## Median
For a set of data sorted in **ascending** or **descending order**, the median is
- the middle value if there is an odd number of data;
- the average of the two middle values if there is an even number of data.

## Mode
The mode of a set of data is the value which occurs most **frequently**.
The modal class is the class interval with the highest frequency.

---
# Quartiles
In a set of data arranged in **ascending order**, for example,

$$
\{3, 5, 6, 10, 13, 14, 22, 24, 29, 31, 35\}
$$

The **lower quartile**, denoted $Q_1$, is the middle value of the **lower half** of the data set. 25% of the data is less than or equal to this value. With reference to the above set of data, $Q_1 =6$.
The **median**, denoted $Q_2$, is the value of the data in the **middle position**. 50% of the data is less than or equal to this value. Here, $Q_2 = 14$.
The **upper quartile**, denoted $Q_3$ is the middle value of the **upper half** of the data. 75% of the data is less than or equal to this value. Here, $Q_3 = 29$.
Note that the number of values in the data set above is **odd**. For even-numbered data sets, the median and the quartiles are taken to be the average of their respective middle values.
## Interquartile range
The **interquartile range** is obtained by taking the difference between the **upper quartile**, $Q_3$, and the **lower quartile**, $Q_1$.
$$
\text{interquartile range} = Q_3 - Q_1
$$
The interquartile range is a better measure of spread of the data than the range because it gives an indication of how the middle 50% of the data is distributed.
A smaller interquartile range indicates that the data clusters closely around the median, whereas a larger interquartile range indicates that the data is spread across a large range of values.
## Box-and-whisker plots
A box-and-whisker plot is a graph that shows the range of a set of data, together with the quartiles.
![[Pasted image 20231009225924.png|650]]
Box-and-whisker plots can be drawn either horizontally or vertically.

---
# Cumulative frequency graph
The **cumulative frequency** refers to the number of observations that is **less than or equal to** that value. The value of the last cumulative frequency for a distribution is the **maximum** value of the distribution.
![[Pasted image 20231009230058.png|500]]

---
# Standard deviation
For a set of ungrouped data, where $n$ is the number of data points, the standard deviation, $\text{SD}$, is given by
$$
\text{SD} = \sqrt{\frac{\sum{x^2}}{n}-\left(\frac{\sum{x}}{n}\right)^2}
$$
where $\frac{\sum{x^2}}{n}$ refers to the mean of all ${x_i}^2$, and $\left(\frac{\sum{x}}{n}\right)^2$ refers to the square of the mean.
For a set of grouped data represented in a frequency, the standard deviation is given by
$$
\text{SD} = \sqrt{\frac{\sum{fx^2}}{\sum{f}}-\left(\frac{\sum{fx}}{\sum{f}}\right)^2}
$$
where $\frac{\sum{fx^2}}{\sum{f}}$ refers to the mean of all $fx^2$, and $\left(\frac{\sum{fx}}{\sum{f}}\right)^2$ refers to the square of the mean. We take the mid-value of each class to represent the value of each item in a class interval.
A larger standard deviation means a wider spread of data (less consistent data), and a smaller standard deviation means a smaller spread of data (more consistent data).